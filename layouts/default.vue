<template>
  <Nuxt />
</template>

<script>
export default {

}
</script>

<style lang="scss">
:root{
  // Background colors
  --c-bg-primary: #121212;
  --c-bg-secondary: rgb(0, 0, 0);

  // Text colors
  --c-txt-primary: #fff;
  --c-txt-secondary: #ffffff4b;

  // Accent colors
  --c-accent-primary: #4ae373;
  --c-accent-secondary: #4abae3;

  // Fonts
  --f-normal-type: 'Roboto', monospace;
  --f-normal-weight: 100;
  --f-highlight-type: 'Segoe UI', 'Tahoma', 'Geneva', 'Verdana', sans-serif;
  --f-highlight-weight: 300;




  font-family: var(--f-normal-type);
  font-weight: var(--f-normal-weight);
}


@media (prefers-color-scheme: light){
  :root{
    // Background colors
    --c-bg-primary: #ebebeb;
    --c-bg-secondary: rgb(0, 0, 0);
    // Text colors
    --c-txt-primary: #fff;
    --c-txt-secondary: #ffffff4b;

    // Accent colors
    --c-accent-primary: #3b6edb;
    --c-accent-secondary: #24e62e;
  }

}
h1, h2, h3{
  font-family: var(--f-highlight-type);
  font-weight: var(--f-highlight-weight);
}
</style>
