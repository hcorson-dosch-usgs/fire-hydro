<template>
  <div
    id="resources-section"
  >
    <h2><a /><span class="lowlight">Resources</span></h2>
    <div class="usa-accordion usa-accordion--bordered">
      <div>
        <h3 class="usa-accordion__heading">
          <button
            class="usa-accordion__button"
          >
            Resource 1
          </button>
        </h3>
        <div
          class="usa-accordion__content usa-prose gage-target"
        >
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Tellus pellentesque eu tincidunt tortor. Blandit massa enim nec dui nunc mattis enim. Non arcu risus quis varius. Tellus mauris a diam maecenas sed enim ut sem. Nulla facilisi cras fermentum odio eu feugiat pretium nibh. Fringilla urna porttitor rhoncus dolor purus non enim. Fusce id velit ut tortor pretium viverra suspendisse potenti nullam.</p>
        </div>
      </div>
      <div>
        <h3 class="usa-accordion__heading">
          <button
            class="usa-accordion__button"
          >
            Resource 2
          </button>
        </h3>
        <div
          class="usa-accordion__content usa-prose"
        >
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Tellus pellentesque eu tincidunt tortor. Blandit massa enim nec dui nunc mattis enim. Non arcu risus quis varius. Tellus mauris a diam maecenas sed enim ut sem. Nulla facilisi cras fermentum odio eu feugiat pretium nibh. Fringilla urna porttitor rhoncus dolor purus non enim. Fusce id velit ut tortor pretium viverra suspendisse potenti nullam.</p>
        </div>
      </div>
      <div>
        <h3 class="usa-accordion__heading">
          <button
            class="usa-accordion__button"
          >
            Resource 3
          </button>
        </h3>
        <div
          class="usa-accordion__content usa-prose"
        >
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Tellus pellentesque eu tincidunt tortor. Blandit massa enim nec dui nunc mattis enim. Non arcu risus quis varius. Tellus mauris a diam maecenas sed enim ut sem. Nulla facilisi cras fermentum odio eu feugiat pretium nibh. Fringilla urna porttitor rhoncus dolor purus non enim. Fusce id velit ut tortor pretium viverra suspendisse potenti nullam.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: 'Resources'
    }
</script>

<style lang="scss" scoped>
$chevronLeft: '~@/assets/images/chevron-left.png';
$chevronDown: '~@/assets/images/chevron-down.png';

// Import Colors
  $white: rgb(255,255,255);
  $black: rgb(0,0,0);  
  $lightGray:rgb(237,237,237);
  $mediumGray: rgb(100,100,100);
  $darkGray: rgb(51,51,51);
  $usgsGreen: rgb(51,120,53);
  $usgsBlue: rgb(0,38,76);
  $fireRed: rgb(163,54,48);
  $fireRedlight: rgba(163,54,48,0.8);
  $fireYellow: rgb(249,178,68);
  $fireYellowlight: rgba(249,178,68,0.8);


  h2{
    margin-bottom: 10px;
  }
  button:not([disabled]):focus{
    outline: none;
  }
  .usa-accordion__button{
    background-image: url($chevronDown);
    background-size: 15px 10px;
    background-color: $fireRed;
    color: $white;
  }
  .usa-accordion__button[aria-expanded=false]{
    background-image: url($chevronLeft);
    background-size: 10px 15px;
    background-color: $white;
    color: $fireRed;
  }

#app h2.usa-accordion__heading {
  margin: 0;
}
</style>