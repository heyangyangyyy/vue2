<template>
    <div>
        <!-- 这里是分类页 -->
        <myHeader></myHeader>
        <myContent></myContent>
    </div>
</template>

<script>
    import myHeader from './list_header.vue'
    import myContent from './content/index.vue'
    export default {
        components:{
            myHeader:myHeader,
            myContent:myContent
        }
    }
</script>

<style scoped>

</style>