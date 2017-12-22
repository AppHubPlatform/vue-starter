<template>
  <div class="box-container">
    <div class="box">
      <i class="fa fa-chevron-left"></i>
    </div>
    <div class="box" v-for="page in pages">
      {{page}}
    </div>
    <div class="box">
      <i class="fa fa-chevron-right"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Paginator',
  data () {
    return {
      pages: [1, 2, 3, 4, 5],
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .box-container {
    display: flex;
    flex-direction: row;
  }

  .box {
    width: 25px;
    height: 25px;
    border: 1px solid black;
    cursor: pointer;
    margin-right: 2px;
  }
</style>
