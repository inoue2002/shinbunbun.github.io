<template>
  <div>
    <MyHeader />
    <Nuxt />
    <MyFooter />
  </div>
</template>

<style lang="scss">
  // Default options
$defaultDuration: .3s;
$primaryColour: #ececec;
$secondaryColour: #666;
$shadowColour: rgba(0, 0, 0, .6);

@media screen and (min-width: 768px) {
  .card {
    transition-duration: $defaultDuration;
    transition-property: transform;

    //@include hideTapHighlightColor();
    //@include hardwareAccel();
    //@include improveAntiAlias();

    &:hover {
      transform: scale(1.1);
    }
  }
}

</style>

<style>
html {
  /*font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;*/
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

:root {
  --nuxt-green: #00c58e;
  --background-color: #F0F5F5;
  --fot-color: #4D4D4D;
  --card-color: #FAFCFC;
  --card-shadow-color: #BABFBF;
}

body{
  background-color: var(--background-color);
  color: #4D4D4D !important;
}
</style>
