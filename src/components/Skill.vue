<template>
  <div>
    <div class="topcn" style="font:20px/18px 'microsoft yahei'; color:#0FF;text-align:center;">
      <p style="font-size: 30px;">技能</p>
      <el-col>
        <el-col :span="4">
          <div>Java</div>
        </el-col>
        <el-col :span="4">
          <div>Spring</div>
        </el-col>
        <el-col :span="4">
          <div>MyBatis</div>
        </el-col>
        <el-col :span="4">
          <div>mysql</div>
        </el-col>
        <el-col :span="4">
          <div>vue</div>
        </el-col>
        <el-col :span="4">
          <div>python</div>
        </el-col>
      </el-col>
      <p>&nbsp;</p>
      <el-col>
        <el-col :span="4">
          <div>
            <el-progress type="circle" :percentage="70"></el-progress>
          </div>
        </el-col>
        <el-col :span="4">
          <div>
            <el-progress type="circle" :percentage="60"></el-progress>
          </div>
        </el-col>
        <el-col :span="4">
          <div>
            <el-progress type="circle" :percentage="70"></el-progress>
          </div>
        </el-col>
        <el-col :span="4">
          <div>
            <el-progress type="circle" :percentage="60"></el-progress>
          </div>
        </el-col>
        <el-col :span="4">
          <div>
            <el-progress type="circle" :percentage="40"></el-progress>
          </div>
        </el-col>
        <el-col :span="4">
          <div>
            <el-progress type="circle" :percentage="15"></el-progress>
          </div>
        </el-col>
      </el-col>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Skill'
}
</script>

<style scoped>
</style>
