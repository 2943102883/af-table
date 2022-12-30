<template>
  <div>
    <d-breadcrumb class="bg-white"></d-breadcrumb>
    <d-curd-table
      ref="table"
      :fullModal="true"
      :auto="false"
    ></d-curd-table>
  </div>
</template>

<script>
import { ref, onMounted, reactive, computed } from 'vue'
import { model } from './def'

export default {

  setup() {
    return {
      model
    }
  },
}
</script>

<style scoped>
</style>
