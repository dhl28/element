<template>
  <div style="margin: 20px;">
    <el-input v-model="input" placeholder="请输入内容"></el-input>
    <el-date-picker showWeekNumber v-model="value1" type="datetime" placeholder="选择日期时间"></el-date-picker>
  </div>
</template>

<script>
export default {
  data() {
    return {
      input: "Hello Element UI!"
    };
  }
};
</script>
