<template>
  <div class="user">
    <!-- <h1>This is {{ $route.params.username }}'s page</h1> -->
    <!-- без props былобы так как выше-->
    <h1>This is {{ username }}'s page</h1>
  </div>
</template>

<script>
export default {
  props: ['username']
}
</script>
