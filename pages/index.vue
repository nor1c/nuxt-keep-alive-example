<template>
  <div>
    {{ count }}
    <button @click="count++">increase</button>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    -> current scroll position here (this scroll position will be retained) <-
    <br>
    
    <nuxt-link :to="'another'">go to another page</nuxt-link>
  </div>
</template>

<script>

export default {
  data() {
    return {
      count: 0
    };
  }
}
</script>
