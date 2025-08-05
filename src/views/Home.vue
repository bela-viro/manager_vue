<template>
  <div>
    <el-button>Default</el-button>
    <el-button type="primary">青哥哥</el-button>
    <el-button type="primary">青哥哥</el-button>
    <el-button type="primary">青哥哥</el-button>
    <el-button type="primary">青哥哥</el-button>
    <el-button type="success">小武哥哥</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="info">Info</el-button>
    <el-button type="warning">Warning</el-button>
    <el-button type="danger">Danger</el-button>


    <div style="padding: 50px">
      <el-icon size="25" color="green"><ChatDotRound /></el-icon>
      <el-button type="primary" icon="Search">按钮</el-button>

      <el-input placeholder="placeholder" :suffix-icon="Calendar" :prefix-icon="Search"></el-input>
      

    </div>
  </div>
</template>

<script setup>
import {Calendar, Search} from "@element-plus/icons-vue";
</script>