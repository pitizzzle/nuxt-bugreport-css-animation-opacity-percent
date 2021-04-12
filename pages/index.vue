<template>
  <main>
    <div id="test" class="animation-active"></div>
  </main>
</template>

<style>
#test {
  width: 100px;
  height: 100px;
  background: red;
}
#test.animation-active {
  animation: test-animation 2s;
}
@keyframes test-animation {
  from { opacity: 0%; }
  to { opacity: 95%; }
}
</style>
