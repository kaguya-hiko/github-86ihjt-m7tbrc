<template>
  <div>
    <h1>HOME</h1>
    {{ title }}
    <p>{{ counter.count }}</p>
  </div>
</template>

<script>
export default {
  setup() {
    const title = ref('ヤッホぉ');
    const counter = useCounter();
    return {
      title,
      counter,
    };
  },
};
</script>
