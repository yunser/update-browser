<template>
    <my-page title="请升级浏览器">
        <div class="tip">你的浏览器版本太旧，影响了网站的正常使用。建议升级浏览器，以获得更好的体验。</div>
        <a class="download" href="http://rj.baidu.com/soft/detail/14744.html" target="_blank">下载谷歌浏览器</a>
    </my-page>
</template>

<script>
    export default {
        data () {
            return {
                page: {
                    menu: [
                        {
                            type: 'icon',
                            icon: 'help',
                            to: '/help'
                        }
                    ]
                }
            }
        }
    }
</script>

<style scoped>
.tip {
    margin-bottom: 16px;
    font-size: 16px;
}
.download {
}
</style>
