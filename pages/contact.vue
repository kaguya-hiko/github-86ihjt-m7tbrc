<template>
  <div>
    <h1>CONTACT</h1>
    composables: {{ counter.count }}
    <button @click="clickHandler">increment</button>
  </div>
</template>

<script>
export default {
  setup() {
    definePageMeta({
      layout: 'custom',
    });
    const counter = useCounter();
    const clickHandler = () => {
      counter.increment();
    };
    return {
      counter,
      clickHandler,
    };
  },
};
</script>
