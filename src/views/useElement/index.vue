<template>
    <div id="useElement">
        <h2>这是使用Element-ui测试页面</h2>
        <h3>这是使用Element-ui中的按钮</h3>
        <el-row>
            <el-button round>圆角按钮</el-button>
            <el-button type="primary" round>主要按钮</el-button>
            <el-button type="success" round>成功按钮</el-button>
            <el-button type="info" round>信息按钮</el-button>
            <el-button type="warning" round>警告按钮</el-button>
            <el-button type="danger" round>危险按钮</el-button>
        </el-row>
        <h3>这是使用Element-ui中的开关</h3>
        <el-switch
            v-model="value"
            active-color="#13ce66"
            inactive-color="#ff4949">
        </el-switch>
        <br>
        <el-switch
            v-model="value1"
            active-text="按月付费"
            inactive-text="按年付费">
        </el-switch>
        <el-switch
            style="display: block"
            v-model="value2"
            active-color="#13ce66"
            inactive-color="#ff4949"
            active-text="按月付费"
            inactive-text="按年付费">
        </el-switch>
    </div>
</template>
<script>
export default {
  data () {
    return {
      value: true,
      value1: true,
      value2: true
    }
  }
}
</script>
