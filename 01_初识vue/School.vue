
<!-- 安装插件 vetur -->
<template>
    <div>
        <h3>学校名称:{{name}}</h3>
        <h3>学校地址:{{address}}</h3>
    </div>
</template>

<script>
    //创建组件
    export default {
        name: "School",
        data() {
            return { 
                name: "尚硅谷",
                address:"北京昌平" 
            }
        }
    }
</script>

<style></style>
