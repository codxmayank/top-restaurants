<template>
  <div>
    <slot name="header" />
    <div>
      <img
        src="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
        alt=""
      />
    </div>
    <slot name="redirectElement" />
  </div>
</template>

<style scoped>
  img {
    width: 10rem;
  }
</style>
