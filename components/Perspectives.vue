<template>
  <div class="perspectives" aria-hidden="true">
    <span v-for="n in 5" :key="n" :class="`lens lens-${n}`" />
  </div>
</template>
