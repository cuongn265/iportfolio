<template>
  <el-row type="flex" :gutter="10">
    <el-col :span="6">
      <div class="grid-content bg-purple">
        <left-side/>
      </div>
    </el-col>
    <el-col :span="18">
      <right-side/>
    </el-col>
  </el-row>
</template>

<script>
import LeftSide from "~/components/LeftSide"
import RightSide from "~/components/RightSide"

export default {

  components: {
    LeftSide,
    RightSide
  }
}
</script>
