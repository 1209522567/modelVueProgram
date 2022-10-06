<template>
  <div>
    <h1>This is an iframe Page</h1>
    <button @click="parentChangePage">父级跳转页面</button>
  </div>
</template>

<script>
export default {
  methods:{
    parentChangePage(){
      window.parent.location.href = ''
    }
  }
}
</script>

<style>

</style>