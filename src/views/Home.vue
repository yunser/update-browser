<template>
    <my-page title="升级浏览器">
        <!-- <div class="tip"></div> -->
        <!-- <a class="download" href="http://rj.baidu.com/soft/detail/14744.html" target="_blank">下载谷歌浏览器</a> -->
        <ui-article>
            <p>你的浏览器版本太旧，影响了网站的正常使用。建议升级浏览器，以获得更好的体验。</p>
            <p>建议使用「谷歌浏览器」。</p>
            <ul>
                <li>
                    <a href="https://www.google.cn/chrome/" target="_blank">官方下载地址</a>
                </li>
                <li>
                    <a href="https://pc.qq.com/search.html#!keyword=%E8%B0%B7%E6%AD%8C%E6%B5%8F%E8%A7%88%E5%99%A8" target="_blank">腾讯软件中心</a>
                </li>
            </ul>
        </ui-article>
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
