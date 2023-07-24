<template>
<div class="home-container">
    <Github githubLink="https://github.com/gyg15534771322"></Github>
    <h1>这是首页</h1>
</div>
</template>

<script>
    import Github from 'components/Github/index'
    export default {
        name: 'home',
        components: { Github },
        mounted () {}
    }
</script>


<style lang="less" scoped>
    h1 {
        text-align: center;
        margin-top: 50px;
    }
</style>
