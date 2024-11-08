<template>
  <div>
    <Post/>
    <Post/>
    <Post/>

  </div>
</template>

<script>
import Post from "@/components/Post.vue"
export default {
    name : "ContainerComponent",
    components : {
        Post,
    }
}
</script>

<style>

</style>