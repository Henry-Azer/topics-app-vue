<template>
  <section>
    <h2>{{ topicTitle ? topicTitle : "Topic Picker" }}</h2>
    <p>{{ text ? text : "You can choose a topic form topics grid to display it here, It's created to implement passing and emitting elements through more than component using provide, inject." }}</p>
  </section>
</template>

<script>
export default {
  props: ['topicTitle', 'text'],
};
</script>