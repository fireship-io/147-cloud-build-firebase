<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <iframe src="https://giphy.com/embed/BofJb4WxJnz7jFfxeD" width="480" height="270" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/topgear-bbc-top-gear-BofJb4WxJnz7jFfxeD">via GIPHY</a></p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
