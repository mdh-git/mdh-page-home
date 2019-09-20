<template>
  <div>
    <el-link class="link">
      GitHub
      <i
        class="el-icon-view el-icon--right"
        href="https://github.com/mdh-git"
        target="_blank"
      ></i>
    </el-link>
    <h1>{{ msg }}</h1>
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

<style scoped>
h1 {
  color: rgb(0, 255, 255);
  text-align: center;
  font-family: STKaiti;
  font-weight: normal;
  font-size: 50px;
}
.link {
  color: #19f;
  float: right;
  font-size: 20px;
}
</style>
