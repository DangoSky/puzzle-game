<template>
  <div>
    <p class="select">请选择碎片的数量</p>
    <!-- <ul>
      <li v-for="item in options">
        {{item}}
      </li>
    </ul> -->
  </div>
</template>

<script>
  export default {
    // props: ['options']
  }
</script>

<style lang="less" scoped>
  .select {
    background: rgb(216, 202, 202) url('../image//arrow.png') no-repeat calc(100% - 10px) center;
    border-radius: 10px;
    /* color: white; */
    /* border: 1px solid red; */
    display: inline-block;
    padding: 5px 40px 5px 5px;
  }
</style>
