
<!-- 安装插件 vetur -->
<template>
    <div>
        <h3>学生姓名:{{name}}</h3>
        <h3>学生性别:{{sex}}</h3>
    </div>
</template>

<script>
    //创建组件
    export default {
        name: "Student",
        data() {
            return { 
                name: "小小鱼",
                sex:"男"
            }
        }
    }
</script>

<style></style>
