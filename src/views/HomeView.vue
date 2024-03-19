<script setup lang="ts">
</script>

<template>
    <div class="common-layout">
        <el-container style="width: 100%;height: 100%">
            <el-aside width="140px">
                left
            </el-aside>
            <el-container>
                <el-header height="4%">
                    top
                </el-header>
                <el-main>
                    mid
                </el-main>
                <el-footer height="4%">
                    Fot
                </el-footer>
            </el-container>
        </el-container>
    </div>
</template>

<style scoped>
.common-layout {
    width: 100%;
    height: 100%;
}
</style>
