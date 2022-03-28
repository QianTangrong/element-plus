<template>
  <el-pagination
    :page-size="20"
    :pager-count="11"
    layout="prev, pager, next"
    :total="1000"
    :page-sizes="[10, 20, 30, 40]"
  />
</template>
