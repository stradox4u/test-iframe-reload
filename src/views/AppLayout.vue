<template>
  <div>
    <main>
      <slot name="bodySlot"></slot>
      <!-- If the iframe is inside of the Routerview component, it reloads when we navigate -->
      <!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/RBYJTop1e-g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
    </main>
  </div>
</template>