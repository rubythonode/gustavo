<!--<template lang="html">
  <div>
    <h1>
      {{ post.meta.title }}
    </h1>
    <p><date>{{ post.meta.date | moment("MMM D YYYY") }}</date></p>
    <div v-html="post.content">
    </div>
  </div>
</template>-->

<script>
export default {

  // render () {
  //   return this.content;
  // },
  template () {
    return this.content;
  },

  props: [
    'content',
  ],
}
</script>
