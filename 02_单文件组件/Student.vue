<template>
    <div>
        <h3>学生名字：{{ name }}</h3>
        <h3>学校年龄：{{ age }}</h3>
    </div>
</template>

<script>

    export default {
        name: "School",
        data() {
            return {
                name: "小小鱼",
                age: 20
            }
        },
    }
</script>