<template>
  <div id="firstcomponent">
    <h1>I am a component.</h1>
    <a> written by {{ author }} </a>
  </div>
</template>

<script type="text/javascript">
export default {
  data () {
    return {
      author: "Jinkey"
    }
  }
}
</script>

<style>

</style>
