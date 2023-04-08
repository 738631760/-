<!doctype html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>XP模块合集</title>
    <style type="text/css">
        a:link {
                color:#42b983;
                font-weight: bold;
        }
        a:visited {
                color:blue;
                font-weight: bold;
        }
        a:hover {
                color:red;
                font-weight: bold;
        }
        a:active {
                color:black;
                font-weight: bold;
        }
    </style>
    
    <script>
        var imgs = document.querySelectorAll('img');

        //offsetTop是元素与offsetParent的距离，循环获取直到页面顶部
        function getTop(e) {
            var T = e.offsetTop;
            while(e = e.offsetParent) {
                T += e.offsetTop;
            }
            return T;
        }

        function lazyLoad(imgs) {
            var H = document.documentElement.clientHeight;//获取可视区域高度
            var S = document.documentElement.scrollTop || document.body.scrollTop;
            for (var i = 0; i < imgs.length; i++) {
                if (H + S > getTop(imgs[i])) {
                    imgs[i].src = imgs[i].getAttribute('data-src');
                }
            }
        }

        window.onload = window.onscroll = function () { //onscroll()在滚动条滚动的时候触发
            lazyLoad(imgs);
        }
    </script>

</head>
<style>

        p{
            line-height: 30px;
        }
        .back{
            width:50px;
            height:50px;
            line-height:50px;
            background-color: #abcdef;
            color:#00f;
            text-align: center;
            position: fixed;
            right:30px;
            bottom:30px;
            border-radius: 30% 30% 30% 30%;
            font-size:30px;
            font-weight:bold;
            display:none;
        }
</style>
<body>
    <div class="top"></div>
    <main>
        <section style="padding-left: 10%; padding-top: 3%; padding-bottom: 5%; padding-right: 10%;">
            <article>
                <h3><p><font color="red">说明：资源均来自</font><a href="http://www.coolapk.com/u/462071" target="_blank" rel="noopener">Android 逆向小子</a></p></h3>
                <p>蓝奏云网盘统一密码：<mark> OJBK </mark></p>
                
                <p>【MAGISK】面具稳定版</p>
                <p>卡刷包和管理器版本号最好一致，以免出现不必要的问题。 </p>
                <p>面具卡刷包： <a href="https://nalankang.lanzouo.com/b00u7gexg" target="_blank" rel="noopener">点击查看</a></p>
                <p>面具管理器： <a href="https://nalankang.lanzouo.com/b00u7gcij" target="_blank" rel="noopener">点击查看</a></p>
                <p>【MAGISK】面具金丝雀版(Canary)</p>
                <p>稳定版发布前的测试版本 </p>
                <p>卡刷包和管理器版本号最好一致，以免出现不必要的问题。 </p>
                <p>金丝雀版管理器：<a href="https://nalankang.lanzouo.com/b00v4q5yb" target="_blank" rel="noopener">点击查看</a></p>
                <p>金丝雀版卡刷包：<a href="https://nalankang.lanzouo.com/b00v2ob6f" target="_blank" rel="noopener">点击查看</a></p>
                <p>Shamiko(隐藏MagiskHide)：<a href="https://nalankang.lanzouo.com/b00v9d09i" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【MAGISK】面具阿尔法版(alpha)</p>
                <p>作者：vvb2060，基于金丝雀版本制作，加入其它新特性 </p>
                <p>卡刷包和管理器版本号最好一致，以免出现不必要的问题。 </p>
                <p>阿尔法版管理器：<a href="https://nalankang.lanzouo.com/b00uotzpe" target="_blank" rel="noopener">点击查看</a></p>
                <p>阿尔法版卡刷包：<a href="https://nalankang.lanzouo.com/b00uotyle" target="_blank" rel="noopener">点击查看</a></p>
                <p>Shamiko(隐藏MagiskHide)：<a href="https://nalankang.lanzouo.com/b00v9d09i" target="_blank"
                        rel="noopener">点击查看</a> </p>
                <p>【MAGISK】面具lite版</p>
                <p>发布之初只作为root管理器，不提供对模块的支持。不过后面的版本作者又恢复了模块支持，白名单模式的Magisk，所有应用程序默认隐藏，只有勾选的应用程序才能获得超级用户权限</p>
                <p>lite版面具管理器：<a href="https://nalankang.lanzouo.com/b00v8k94d" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>lite版面具卡刷包：<a href="https://nalankang.lanzouo.com/b00v8kaje" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>面具自定义通道：<a href="https://magisk.topjohnwu.com/zh.html" target="_blank" rel="noopener">点击查看</a></p>
                <p>面具字体： 筑紫𝐀丸： <a href="https://nalankang.lanzouo.com/b00vsaycb" target="_blank"
                        rel="noopener">点击查看</a> </p>
                <p>面具模块合集：<a href="https://nalankang.lanzouo.com/b00u8npfc" target="_blank" rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684095580-70dde6dd-63db-4d91-bd90-c61db0369dd0.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684095580-70dde6dd-63db-4d91-bd90-c61db0369dd0.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        alt="2022-02-02_14-27-30776778.png" class="medium-zoom-image"></p>
                <p>【LSPOSED】框架-(安卓8.1-12) </p>
                <p>Riru模块： <a href="https://nalankang.lanzouo.com/b00u7gi9g" target="_blank" rel="noopener">点击查看</a></p>
                <p>LSPosed正式版：<a href="https://nalankang.lanzouo.com/b00uiewlg" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>LSPosed测试版： <a href="https://nalankang.lanzouo.com/b00u7rzoj" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>安卓8.0可用版本：<a href="https://nalankang.lanzouo.com/b00uu1hva" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684125246-56d97448-16de-4e64-bd0e-27f6f51c2080.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684125246-56d97448-16de-4e64-bd0e-27f6f51c2080.png"
                        alt="IMG_20220220_144538780.png" class="medium-zoom-image"></p>
                <p>【EDXPOSED】框架-(安卓8.0-11) </p>
                <p>EDxposed管理器(分支美化版)： <a href="https://nalankang.lanzouo.com/b00tml4pc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>EdXposed管理器(官方正式版)： <a href="https://nalankang.lanzouo.com/b00u12ibi" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>EdXposed管理器(官方先行版)：<a href="https://nalankang.lanzouo.com/b00u12i4b" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Riru模块： <a href="https://nalankang.lanzouo.com/b00u7gi9g" target="_blank" rel="noopener">点击查看</a></p>
                <p>Edxposed阿尔法(S版)： <a href="https://nalankang.lanzouo.com/b00u7gnpc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Edxposed阿尔法(Y版)： <a href="https://nalankang.lanzouo.com/b00u7gq8d" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Edxposed金丝雀(S版和Y版)： <a href="https://nalankang.lanzouo.com/b00u7h7ah" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684150054-452fb424-76a1-4b97-ad97-5a2d709448f4.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684150054-452fb424-76a1-4b97-ad97-5a2d709448f4.png"
                        alt="IMG_20220220_150153781783.png" class="medium-zoom-image"></p>
                <p>【DREAMLAND】梦境框架-(安卓7.0-12) </p>
                <p>Riru模块： <a href="https://nalankang.lanzouo.com/b00u7gi9g" target="_blank" rel="noopener">点击查看</a></p>
                <p>梦境管理器：<a href="https://nalankang.lanzouo.com/b00uicrmf" target="_blank" rel="noopener">点击查看</a></p>
                <p>magisk-dreamland：<a href="https://nalankang.lanzouo.com/b00uicrad" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684168058-e9ebdd55-0eb7-4d71-8782-67caca3fb79c.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684168058-e9ebdd55-0eb7-4d71-8782-67caca3fb79c.png"
                        alt="IMG_20220220_152839785.png" class="medium-zoom-image"></p>
                <p>免【ROOT】XPOSED框架 </p>
                <p>天鉴：(输入0000长按D，右上点造访-得到密码)：<a href="https://nalankang.lanzouo.com/b00uu09lg" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>太极：<a href="https://nalankang.lanzouo.com/b00uicmcf" target="_blank" rel="noopener">点击查看</a></p>
                <p>应用转生： <a href="https://nalankang.lanzouo.com/b00u1wq0f" target="_blank" rel="noopener">点击查看</a></p>
                <p>VirtualXposed： <a href="https://nalankang.lanzouo.com/b00u1wqgb" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>SandVXposed：<a href="https://www.coolapk.com/apk/io.virtualapp.sandvxposed64" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>神之手：<a href="https://nalankang.lanzouo.com/b00uucuad" target="_blank" rel="noopener">点击查看</a></p>
                <p>VMOS Pro(虚拟大师)：<a href="https://nalankang.lanzouo.com/b00um855g" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>SlimVXP：<a href="https://www.coolapk.com/apk/io.virtualapp.sandvxposed" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>BlackBox黑盒：<a href="https://nalankang.lanzouo.com/b00vkf9ub" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684205009-036b842b-a1c5-4b01-8f3e-e8ae337c2786.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645684205009-036b842b-a1c5-4b01-8f3e-e8ae337c2786.png"
                        alt="IMG_20220220_161114788.png" class="medium-zoom-image"></p>
                <p>【XP模块】 抖音模块</p>
                <p>抖音助手： <a href="https://nalankang.lanzouo.com/b00um3gmj" target="_blank" rel="noopener">点击查看</a></p>
                <p>抖音+： <a href="https://nalankang.lanzouo.com/b00u6mqej" target="_blank" rel="noopener">点击查看</a></p>
                <p>抖音伴侣： <a href="https://nalankang.lanzouo.com/b00t5ypuj" target="_blank" rel="noopener">点击查看</a></p>
                <p>AdAway： <a href="https://nalankang.lanzouo.com/b00tsmbgh" target="_blank" rel="noopener">点击查看</a></p>
                <p>要你命三千： <a href="https://nalankang.lanzouo.com/b00tw4jhc" target="_blank" rel="noopener">点击查看</a></p>
                <p>诺诺诺嗯： <a href="https://nalankang.lanzouo.com/b00u5t5wh" target="_blank" rel="noopener">点击查看</a></p>
                <p>HookBox：<a href="https://nalankang.lanzouo.com/b00uembsb" target="_blank" rel="noopener">点击查看</a></p>
                <p>长江七号：<a href="https://nalankang.lanzouo.com/b00tuzfsd" target="_blank" rel="noopener">点击查看</a></p>
                <p>小鸽子(视频无水印下载)：<a href="https://nalankang.lanzouo.com/b00vs6o1g" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645685134600-d6f02fdc-90d4-4bfd-ac43-1b085d8cf2eb.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645685134600-d6f02fdc-90d4-4bfd-ac43-1b085d8cf2eb.png"
                        alt="IMG_20220220_162211790.png" class="medium-zoom-image"></p>
                <p>【XP模块】 蚂蚁森林模块</p>
                <p>蚂蚁森林🌱自动浇水、收能量、喂鸡、签到… </p>
                <p>水晶版： <a href="https://nalankang.lanzouo.com/b00tsmwvi" target="_blank" rel="noopener">点击查看</a></p>
                <p>秋风版： <a href="https://nalankang.lanzouo.com/b00tphmhg" target="_blank" rel="noopener">点击查看</a></p>
                <p>蜡笔小新版：<a href="https://nalankang.lanzouo.com/b00u7fmyj" target="_blank" rel="noopener">点击查看</a></p>
                <p>雨季版：<a href="https://nalankang.lanzouo.com/b00v77tpa" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】隐藏应用列表 </p>
                <p>该模块提供了一些隐藏方式用于隐藏某些指定的软件从而不被检测到 </p>
                <p>隐藏应用列表：<a href="https://nalankang.lanzouo.com/b00ujaeti" target="_blank" rel="noopener">点击查看</a></p>
                <p>Riru-Hide My Applist：<a href="https://nalankang.lanzouo.com/b00unry9e" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>应用列表检测器：<a href="https://nalankang.lanzouo.com/b00uwpoeb" target="_blank" rel="noopener">点击查看</a></p>
                <p>隐秘空间：<a href="https://nalankang.lanzouo.com/b00vbys7c" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】 核心破解</p>
                <p>允许降级安装应用，禁用软件包管理器签名验证，禁用APK签名验证 </p>
                <p>核心破解3.8(安卓10-12)： <a href="https://nalankang.lanzouo.com/b00u2j7xc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>核心破解2.2(安卓9-10)： <a href="https://nalankang.lanzouo.com/iQS6Gjdk6zi" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>核心破解2.1(安卓8.x)： <a href="https://nalankang.lanzouo.com/iq7ZYjdk6ve" target="_blank"
                        rel="noopener">点击查看</a> </p>
                <p>核心破解2.0(安卓7.x)： <a href="https://nalankang.lanzouo.com/ic56Ljgow5g" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>核心破解1.4(安卓4.x-6.x)： <a href="https://nalankang.lanzouo.com/iaKd1jdk6pi" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【XP模块】 应用管理模块</p>
                <p>应用管理： <a href="https://nalankang.lanzouo.com/ibNpugt6sih" target="_blank" rel="noopener">点击查看</a></p>
                <p>阻止运行： <a href="https://nalankang.lanzouo.com/b00tjjhaf" target="_blank" rel="noopener">点击查看</a></p>
                <p>绿色守护： <a href="https://nalankang.lanzouo.com/b00tw4f3e" target="_blank" rel="noopener">点击查看</a></p>
                <p>应用控制器： <a href="https://nalankang.lanzouo.com/ili9Rgt6rib" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>Thanox(灭霸)： <a href="https://nalankang.lanzouo.com/b00ucbm7i" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>DeepSleep(控制应用后台唤醒)：<a href="https://nalankang.lanzouo.com/b00vsg6vi" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【XP模块】指纹支付模块 </p>
                <p>xposed版：<a href="https://nalankang.lanzouo.com/b00twbp5i" target="_blank" rel="noopener">点击查看</a></p>
                <p>面具Riru版：<a href="https://nalankang.lanzouo.com/b00utf13e" target="_blank" rel="noopener">点击查看</a></p>
                <p>面具Zygisk版：<a href="https://nalankang.lanzouo.com/b00v90psj" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>【XP模块】取消对话框 </p>
                <p>对话框取消： <a href="https://nalankang.lanzouo.com/iHJzpl4nyuh" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>对话框取消beta版： <a href="https://nalankang.lanzouo.com/iX6Cvl4nzjc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>对话框取消修复版：<a href="https://nalankang.lanzouo.com/b00vnmxqb" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>【XP模块】隐私保护模块 </p>
                <p>我的隐私：<a href="https://nalankang.lanzouo.com/iIw5Foda0sf" target="_blank" rel="noopener">点击查看</a></p>
                <p>X隐私保护： <a href="https://nalankang.lanzouo.com/b00uanape" target="_blank" rel="noopener">点击查看</a></p>
                <p>XPrivacyLua： <a href="https://nalankang.lanzouo.com/b00u9131a" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>放开我的剪贴板： <a href="https://www.coolapk.com/apk/cn.nlifew.clipmgr" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【XP模块】 应用破解模块：可以白嫖部分软件和单机游戏 </p>
                <p>vipHook： <a href="https://nalankang.lanzouo.com/b00tym8ed" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>GodVip：<a href="https://nalankang.lanzouo.com/b00uk8e4h" target="_blank" rel="noopener">点击查看</a></p>
                <p>BuyTool幸运内购： <a href="https://nalankang.lanzouo.com/b00ttwnti" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>BuyTool使用介绍：<a
                        href="https://www.coolapk.com/feed/15028248?shareKey=ODA0MjEyNzUyOTEyNjBjZGIyNGM~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.2.4-beta6"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>天帝VIP(破解应用VIP)：<a href="https://nalankang.lanzouo.com/b00usgjyd" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>道道道(破解应用VIP)：<a href="https://nalankang.lanzouo.com/b00usyqdc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Jasi破解器：<a href="https://nalankang.lanzouo.com/b00uzhq8h" target="_blank" rel="noopener">点击查看</a></p>
                <p>simpleVip：<a href="https://nalankang.lanzouo.com/b00uzhqcb" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>mHook管理器：<a href="https://nalankang.lanzouo.com/b00v4u35e" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>esXplorer(破解ES文件管理器VIP)：<a href="https://nalankang.lanzouo.com/b00v629ih" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Hook模块：<a href="https://nalankang.lanzouo.com/b00v635of" target="_blank" rel="noopener">点击查看</a></p>
                <p>KModule(破解部分软件VIP)：<a href="https://nalankang.lanzouo.com/b00usnx1g" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>WuWei(破解部分软件VIP)：<a href="https://nalankang.lanzouo.com/b00vbmg4f" target="_blank"
                        rel="noopener">点击查看</a> </p>
                <p>野草集：(破解部分小说软件VIP)<a href="https://nalankang.lanzoum.com/b00vgt8di" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>酷通hook：<a href="https://nalankang.lanzouo.com/b00vpfnej" target="_blank" rel="noopener">点击查看</a></p>
                <p>河马视频等通杀模块：<a href="https://nalankang.lanzouo.com/b00vpfnbg" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>大师兄影视模块：<a href="https://nalankang.lanzouo.com/b00vpfn6b" target="_blank" rel="noopener">点击查看</a></p>
                <p>飞瓜影视等通杀模块：<a href="https://nalankang.lanzouo.com/b00vpfn8d" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>小草视频通杀模块：<a href="https://nalankang.lanzouo.com/b00vpfn5a" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>Fuck VIP(破解部分应用VIP)：<a href="https://nalankang.lanzouo.com/b00vta7qj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Fuck光速虚拟机XP模块：<a href="https://nalankang.lanzouo.com/b00vta7cf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/jpeg/28378617/1653780186605-d5548c9e-8095-4231-adf2-1bb6fcd185d3.jpeg?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/jpeg/28378617/1653780186605-d5548c9e-8095-4231-adf2-1bb6fcd185d3.jpeg?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        alt="img" class="medium-zoom-image"></p>
                <p>酷我音乐模块</p>
                <p>酷我酷狗VIP：<a href="https://nalankang.lanzouo.com/b00ujhxza" target="_blank" rel="noopener">点击查看</a></p>
                <p>酷我增强插件：<a href="https://nalankang.lanzouo.com/b00vpfnfa" target="_blank" rel="noopener">点击查看</a></p>
                <p>酷我VIP：<a href="https://nalankang.lanzouo.com/b00vlet8j" target="_blank" rel="noopener">点击查看</a></p>
                <p>酷我增强：<a href="https://nalankang.lanzouo.com/b00vnxgqf" target="_blank" rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688562720-600a20f0-a5e3-4389-9c9d-e191cdaa562c.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688562720-600a20f0-a5e3-4389-9c9d-e191cdaa562c.png"
                        alt="20220220142547Aicy793797.png" class="medium-zoom-image"></p>
                <p>【XP模块】 微信增强模块合集 </p>
                <p>V++： <a href="https://nalankang.lanzouo.com/iFHt3n8udfe" target="_blank" rel="noopener">点击查看</a></p>
                <p>女娲石：<a href="https://nalankang.lanzouo.com/tp/iva8Uuedfli" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>微运动：<a href="https://nalankang.lanzouo.com/tp/iyGE2ghdg5c" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>微X模块 ： <a href="https://nalankang.lanzouo.com/b00tujq4j" target="_blank" rel="noopener">点击查看</a></p>
                <p>微信分组： <a href="https://nalankang.lanzouo.com/b00u7165a" target="_blank" rel="noopener">点击查看</a></p>
                <p>微信群发： <a href="https://nalankang.lanzouo.com/b00u7164j" target="_blank" rel="noopener">点击查看</a></p>
                <p>微信密友： <a href="https://nalankang.lanzouo.com/b00u716hc" target="_blank" rel="noopener">点击查看</a></p>
                <p>微信增强： <a href="https://nalankang.lanzouo.com/b00u7311i" target="_blank" rel="noopener">点击查看</a></p>
                <p>微信斗图： <a href="https://nalankang.lanzouo.com/b00u7163i" target="_blank" rel="noopener">点击查看</a></p>
                <p>畅玩微信： <a href="https://nalankang.lanzouo.com/b00u757wh" target="_blank" rel="noopener">点击查看</a></p>
                <p>企业助手： <a href="https://nalankang.lanzoui.com/b00u716mh" target="_blank" rel="noopener">点击查看</a></p>
                <p>微信学英语：<a href="https://nalankang.lanzouo.com/b00udu6vg" target="_blank" rel="noopener">点击查看</a></p>
                <p>TSBattery(省电模块)：<a href="https://nalankang.lanzouo.com/b00utqtkf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>模拟微信摇一摇：<a href="https://nalankang.lanzouo.com/ibL7Xp64jze" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>MDWechat(微信美化)： <a href="https://nalankang.lanzouo.com/b00u7166b" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>去TM的微信信息流：<a href="https://nalankang.lanzouo.com/tp/iTrToghd41g" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>我不需要确认：<a href="https://nalankang.lanzouo.com/b00v82usf" target="_blank" rel="noopener">点击查看</a></p>
                <p>QQCleaner Lite(轻量版本的瘦身模块)：<a href="https://nalankang.lanzouo.com/b00vrngib" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>QQ瘦身模块(QQ/TIM/微信缓存垃圾清理)：<a href="https://nalankang.lanzouo.com/b00tszuzi" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688580197-83842c38-780e-4037-a0e3-e2c7a32c9fa5.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688580197-83842c38-780e-4037-a0e3-e2c7a32c9fa5.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        alt="20220220194848Aicy-1798.png" class="medium-zoom-image"></p>
                <p>【XP模块】 QQ增强模块合集 </p>
                <p>QN(增强模块)： <a href="https://nalankang.lanzouo.com/b00tsdawd" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>QX(增强模块)： <a href="https://nalankang.lanzouo.com/b00u0c8md" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>绿豆(增强模块)：<a href="https://nalankang.lanzouo.com/b00u74h3c" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>QScript脚本模块： <a href="https://nalankang.lanzouo.com/b00u94zfe" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>H.entai.Q(增强模块)： <a href="https://nalankang.lanzouo.com/b00u73uof" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>ColorQQ2(主题美化)：<a href="https://nalankang.lanzouo.com/b00u9sekh" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>XAutoDaily(自动签到)：<a href="https://nalankang.lanzouo.com/b00udwffg" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>花Q： <a href="https://nalankang.lanzouo.com/b00tg274j" target="_blank" rel="noopener">点击查看</a></p>
                <p>QQ省电模块： <a href="https://nalankang.lanzouo.com/b00u9clng" target="_blank" rel="noopener">点击查看</a></p>
                <p>QQ净化：<a href="https://nalankang.lanzouo.com/id15ckb" target="_blank" rel="noopener">点击查看</a></p>
                <p>QQ瘦身(缓存清理垃圾)： <a href="https://nalankang.lanzouo.com/b00tszuzi" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>TSBattery(省电模块)：<a href="https://nalankang.lanzouo.com/b00utqtkf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>QAuxiliary(增强模块)：<a href="https://nalankang.lanzouo.com/b00vc3gha" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>QQCleaner Lite(轻量版本的瘦身模块)：<a href="https://nalankang.lanzouo.com/b00vrngib" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>QTool(QQ增强模块)：<a href="https://nalankang.lanzouo.com/b00vlucje" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【XP模块】 系统增强模块</p>
                <p>Xp快译： <a href="https://nalankang.lanzouo.com/tp/ipnxCn6pb3i" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>全局复制： <a href="https://nalankang.lanzouo.com/iNjcbh1ex8d" target="_blank" rel="noopener">点击查看</a></p>
                <p>强制截图： <a href="https://nalankang.lanzouo.com/iDOdis7llzc" target="_blank" rel="noopener">点击查看</a></p>
                <p>指纹支付： <a href="https://nalankang.lanzouo.com/b00twbp5i" target="_blank" rel="noopener">点击查看</a></p>
                <p>锁定通知： <a href="https://www.coolapk.com/apk/me.singleneuron.locknotification" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>文本自定义： <a href="https://nalankang.lanzouo.com/izfDpdcai0d" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>锤子BigBang： <a href="https://www.coolapk.com/apk/com.forfan.bigbang.coolapk" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>伪装WiFi连接： <a href="https://nalankang.lanzouo.com/b00tvgw6f" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>移除截屏延迟： <a href="https://nalankang.lanzouo.com/isXezjesckd" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>无障碍-Daemon： <a href="https://nalankang.lanzouo.com/iRz8qim5hda" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>米窗-全局小窗： <a href="https://www.coolapk.com/apk/com.sunshine.freeform" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>原生音乐通知栏： <a href="https://nalankang.lanzouo.com/b00tsmf3i" target="_blank" rel="noopener">点击查</a></p>
                <p>短信验证码提取： <a href="https://nalankang.lanzouo.com/b00uaxssf" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>导航栏扩展模块： <a href="https://www.coolapk.com/apk/com.egguncle.xposednavigationbar" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>xSuite(修改应用图标)： <a href="https://nalankang.lanzouo.com/i49dhgt6zij" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Xposed edge por(边缘手势)： <a href="https://nalankang.lanzouo.com/b00tvgqqj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>爱玩机-安装器接管：<a href="https://nalankang.lanzouo.com/b00ujhxvg" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>阻止更新：<a href="https://nalankang.lanzouo.com/iALHhqxzrzg" target="_blank" rel="noopener">点击查看</a></p>
                <p>Flat Style Bar Indicators(状态栏美化)：<a href="https://nalankang.lanzouo.com/b00ursodi" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>剪贴板过滤器：<a href="https://nalankang.lanzouo.com/b00uxukdc" target="_blank" rel="noopener">点击查看</a></p>
                <p>状态栏歌词：<a href="https://nalankang.lanzouo.com/b00uzgujg" target="_blank" rel="noopener">点击查看</a></p>
                <p>音量级别+：<a href="https://nalankang.lanzouo.com/irAP4p31ida" target="_blank" rel="noopener">点击查看</a></p>
                <p>非残(假装自己没有使用无障碍服务)：<a href="https://nalankang.lanzouo.com/b00v7ufmb" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>SkyOlin助手(分屏)：<a href="https://nalankang.lanzouo.com/b00vbffoh" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>隐秘空间：<a href="https://nalankang.lanzouo.com/b00vbys7c" target="_blank" rel="noopener">点击查看</a></p>
                <p>自由屏幕旋转：<a href="https://nalankang.lanzouo.com/b00vj5gif" target="_blank" rel="noopener">点击查看</a></p>
                <p>拒绝强制亮度：<a href="https://nalankang.lanzouo.com/b00vj5gli" target="_blank" rel="noopener">点击查看</a></p>
                <p>设置应用全屏：<a href="https://nalankang.lanzouo.com/b00vloi6b" target="_blank" rel="noopener">点击查看</a></p>
                <p>进程锁：<a href="https://nalankang.lanzouo.com/b00vtzfkb" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】伪装设备信息 </p>
                <p>应用伪装： <a href="https://nalankang.lanzouo.com/b00u9amhe" target="_blank" rel="noopener">点击查看</a></p>
                <p>应用变量： <a href="https://nalankang.lanzouo.com/iFeH6h1ehxc" target="_blank" rel="noopener">点击查看</a></p>
                <p>爱玩机-应用伪装：<a href="https://nalankang.lanzouo.com/b00uj175i" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>手机查看器：<a href="https://nalankang.lanzouo.com/b00v891id" target="_blank" rel="noopener">点击查看</a></p>
                <p>Android Faker：<a href="https://nalankang.lanzouo.com/b00v88yxa" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>设备ID更改器：<a href="https://nalankang.lanzouo.com/b00v894xg" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】 存储重定向</p>
                <p>重定向应用程序在sdcard目录下生成的文件夹和文件的路径，防止应用在sdcard目录下乱拉屎 </p>
                <p>存储重定向：<a href="https://nalankang.lanzouo.com/irdVpqq85gb" target="_blank" rel="noopener">点击查看</a></p>
                <p>XInternalSD： <a href="https://nalankang.lanzouo.com/i44wggt6jni" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>LT NoLitter重制版： <a href="https://nalankang.lanzouo.com/iP7gb03mea1g" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688605586-8c20ca94-fe9f-4104-9b96-371cc29658d8.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688605586-8c20ca94-fe9f-4104-9b96-371cc29658d8.png"
                        alt="IMG_20220221_153614822.png" class="medium-zoom-image"></p>
                <p>【XP模块】 强国助手模块</p>
                <p>模拟点击，解放双手，学生党必备的软件 积分执行、顺序执行、挑战答题、每周答题、双人对战、四人对战 </p>
                <p>霸王强国：<a href="https://nalankang.lanzouo.com/b00up7oda" target="_blank" rel="noopener">点击查看</a></p>
                <p>旺仔强国：<a href="https://nalankang.lanzouo.com/b00unbzje" target="_blank" rel="noopener">点击查看</a></p>
                <p>校雷锋强国：<a href="https://nalankang.lanzouo.com/b00umdy0f" target="_blank" rel="noopener">点击查看</a></p>
                <p>阿超强国：<a href="https://nalankang.lanzouo.com/b00umdy1g" target="_blank" rel="noopener">点击查看</a></p>
                <p>高级强国：<a href="https://nalankang.lanzouo.com/b00umdy4j" target="_blank" rel="noopener">点击查看</a></p>
                <p>学习机强国：<a href="https://nalankang.lanzouo.com/b00umdxyd" target="_blank" rel="noopener">点击查看</a></p>
                <p>自动学习强国：<a href="https://nalankang.lanzouo.com/b00upocjg" target="_blank" rel="noopener">点击查看</a></p>
                <p>时光强国：<a href="https://nalankang.lanzouo.com/b00uqe7fi" target="_blank" rel="noopener">点击查看</a></p>
                <p>学习助手：<a href="https://nalankang.lanzouo.com/b00utuj4d" target="_blank" rel="noopener">点击查看</a></p>
                <p>AI强国：<a href="https://nalankang.lanzouo.com/b00v0v3sj" target="_blank" rel="noopener">点击查看</a></p>
                <p>一键强国：<a href="https://nalankang.lanzouo.com/b00v44m8f" target="_blank" rel="noopener">点击查看</a></p>
                <p>科技强国：<a href="https://nalankang.lanzouo.com/b00v9lzsf" target="_blank" rel="noopener">点击查看</a></p>
                <p>强国能手：<a href="https://nalankang.lanzouo.com/b00ve2g7g" target="_blank" rel="noopener">点击查看</a></p>
                <p>学习一下强国：<a href="https://nalankang.lanzouo.com/b00vg2urc" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】 虚拟定位</p>
                <p>可以模拟一个虚假的地理位置 </p>
                <p>模拟位置： <a href="https://nalankang.lanzouo.com/b00tvpb1i" target="_blank" rel="noopener">点击查看</a></p>
                <p>lataclysm： <a href="https://nalankang.lanzouo.com/izZ3xljlaqh" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>X定位保护：<a href="https://nalankang.lanzouo.com/b00ut32sd" target="_blank" rel="noopener">点击查看</a></p>
                <p>对话框取消beta版： <a href="https://nalankang.lanzouo.com/iX6Cvl4nzjc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>虚拟定位：<a href="https://nalankang.lanzouo.com/b00v8fv7i" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】 翻译模块</p>
                <p>把app内的文字翻译成中文 </p>
                <p>AllTrans： <a href="https://nalankang.lanzouo.com/b00tngrof" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>AllTrans使用教程：<a
                        href="https://www.coolapk.com/feed/23531453?shareKey=M2Y0OTg1ZTRmMDk2NjE2N2QwYjY~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.2.3"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>微信学英语：<a href="https://nalankang.lanzouo.com/b00udu6vg" target="_blank" rel="noopener">点击查看</a></p>
                <p>Xp快译： <a href="https://nalankang.lanzouo.com/tp/ipnxCn6pb3i" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688642526-db7e3fde-daf3-4470-8ef6-177ee91df9df.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688642526-db7e3fde-daf3-4470-8ef6-177ee91df9df.png"
                        alt="20220221084110Aicy799.png" class="medium-zoom-image"></p>
                <p>【XP模块】 MIUI系统专用模块合集 </p>
                <p>XMiTools： <a href="https://www.coolapk.com/apk/com.tianma.tweaks.miui" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>小米净化： <a href="https://nalankang.lanzouo.com/b00tyatha" target="_blank" rel="noopener">点击查看</a></p>
                <p>MIUI全局高帧： <a href="https://nalankang.lanzouo.com/b00ud00wb" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>Miui12双排状态栏： <a href="https://www.coolapk.com/apk/com.lz.teemo" target="_blank"
                        rel="noopener">点击查看</a> </p>
                <p>解锁MIUI键盘优化： <a href="https://nalankang.lanzouo.com/b00ud00la" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>MiuiHome桌面增强模块：<a href="https://nalankang.lanzouo.com/b00v28daf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>ChiMi(MIUI增强模块)： <a href="https://nalankang.lanzouo.com/b00t6n0ti" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>CustoMIUIzer(MIUI专用)： <a href="https://nalankang.lanzouo.com/b00tyaawb" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>MIUI双开限制解除模块： <a href="https://nalankang.lanzouo.com/b00u9zola" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>移除系统相机拍照声音模块：<a href="https://nalankang.lanzouo.com/b00uhrdud" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>爱玩机-MIUI安装器：<a href="https://nalankang.lanzouo.com/b00ujhxte" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>爱玩机-MIUI高级设置：<a href="https://nalankang.lanzouo.com/b00ujhxqb" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>淘米水(MIUI去广吿模块)：<a href="https://nalankang.lanzouo.com/b00ukbeab" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>不要多管闲事(干掉无障碍十秒等待)：<a href="https://nalankang.lanzouo.com/b00ulw6ch" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>MIUI强调色：<a href="https://nalankang.lanzouo.com/b00ulw97a" target="_blank" rel="noopener">点击查看</a></p>
                <p>MIUltra(MIUI12.5扩展)：<a href="https://nalankang.lanzouo.com/b00usk4wf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>小米运动Hook：<a href="https://nalankang.lanzouo.com/b00uz62yd" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>状态栏歌词：<a href="https://nalankang.lanzouo.com/b00uzgujg" target="_blank" rel="noopener">点击查看</a></p>
                <p>小米push增强模块：<a href="https://nalankang.lanzouo.com/b00uzzc2f" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>隐藏MIUI勇者标识：<a href="https://nalankang.lanzouo.com/b00v2o9li" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>AppLock(防止特定应用被侧滑杀死或一键清理)：<a href="https://nalankang.lanzouo.com/b00v4oaej" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>MiCode(小米浏览器增强模块)：<a href="https://www.coolapk.com/apk/xyz.kymirai.micode" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>独立显秒：<a href="https://nalankang.lanzouo.com/b00v7h4ni" target="_blank" rel="noopener">点击查看</a></p>
                <p>MIUI原生通知图标：<a href="https://nalankang.lanzouo.com/b00v9rnab" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>粗粮：<a href="https://nalankang.lanzouo.com/b00v9zykf" target="_blank" rel="noopener">点击查看</a></p>
                <p>小米翻译+：<a href="https://nalankang.lanzouo.com/b00va0h4d" target="_blank" rel="noopener">点击查看</a></p>
                <p>Miui时间显秒：<a href="https://nalankang.lanzouo.com/b00vbja3a" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>解锁小米妙：<a href="https://nalankang.lanzouo.com/b00vbja1i" target="_blank" rel="noopener">点击查看</a></p>
                <p>WooBoxForMIUI(MIUI13系统扩展)：<a href="https://nalankang.lanzouo.com/b00vc2p2d" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>解锁MIUI+：<a href="https://nalankang.lanzouo.com/b00vczkba" target="_blank" rel="noopener">点击查看</a></p>
                <p>不许卡米：<a href="https://nalankang.lanzouo.com/b00vcvnha" target="_blank" rel="noopener">点击查看</a></p>
                <p>Miui主题破解：<a href="https://nalankang.lanzouo.com/b00velxyj" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>MIUI工具箱：<a href="https://nalankang.lanzouo.com/b00vg2u8d" target="_blank" rel="noopener">点击查看</a></p>
                <p>AppLock(防止应用被侧滑杀死或一键清理)：<a href="https://nalankang.lanzouo.com/b00vi88ne" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>MIUI性能救星：<a href="https://nalankang.lanzouo.com/b00vkcyng" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>MaxFreeForm(解除MIUI13多小窗限制)：<a href="https://nalankang.lanzouo.com/b00vlohgf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>MiuiMediaEditor(MIUI相册增强模块)：<a href="https://nalankang.lanzouo.com/b00vn4gfa" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>MIUI遮罩进化：<a href="https://nalankang.lanzouo.com/b00vm6mxa" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>MIUI修改原生安装器：<a href="https://nalankang.lanzouo.com/b00vqp23i" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>墨•桌：<a href="https://nalankang.lanzouo.com/b00vqp1uj" target="_blank" rel="noopener">点击查看</a></p>
                <p>AutoNFC：<a href="https://nalankang.lanzouo.com/b00vqs8wb" target="_blank" rel="noopener">点击查看</a></p>
                <p>MIUI QOL(系统增强模块)：<a href="https://nalankang.lanzouo.com/b00vu6xof" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688660960-5e8aec0f-d972-4c90-a18a-4c4625b9502e.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688660960-5e8aec0f-d972-4c90-a18a-4c4625b9502e.png"
                        alt="IMG_20220221_085858801.png" class="medium-zoom-image"></p>
                <p>【XP模块】 Flyme系统专用模块合集 </p>
                <p>FXposed： <a href="https://nalankang.lanzouo.com/b00tg28vc" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>Flyme助手： <a href="https://nalankang.lanzouo.com/b00t637bc" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>MZXPT(魅族工具箱)： <a href="https://nalankang.lanzouo.com/b00tw4g4b" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>flyme工具箱：<a href="https://nalankang.lanzouo.com/b00uyi65e" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1650627329960-aca65bfb-12c0-4fa2-9742-fafe2fb97319.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1650627329960-aca65bfb-12c0-4fa2-9742-fafe2fb97319.png"
                        alt="IMG_20220422_1925241225.png" class="medium-zoom-image"></p>
                <p>【XP模块】 ColorOS系统专用模块合集 </p>
                <p>万物： <a href="https://www.coolapk.com/apk/com.bangtu.opaod" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>一加拓展： <a href="https://www.coolapk.com/apk/com.davidking.optools" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>一加氢氧主题： <a href="https://www.coolapk.com/apk/com.jizhi.optheme" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>一加指纹拓展： <a href="https://www.coolapk.com/apk/com.davidking.xposed.opfingerprint" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>一加状态栏网速： <a href="https://www.coolapk.com/apk/me.seasonyuu.xposed.networkspeedindicator.h2os"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>ColorOSTool系统增强模块：<a href="https://nalankang.lanzouo.com/b00utw46h" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>WooBox For ColorOS：<a href="https://nalankang.lanzouo.com/b00vkrz0j" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>ColorOS通知图标增强：<a href="https://nalankang.lanzouo.com/b00vdjeeh" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688696153-dd365348-3c5a-4e6b-8151-3868755589a8.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688696153-dd365348-3c5a-4e6b-8151-3868755589a8.png"
                        alt="20220221091208Aicy804.png" class="medium-zoom-image"></p>
                <p>【XP模块】 网易云音乐模块合集 </p>
                <p>云村清洁工： <a href="https://nalankang.lanzouo.com/in7DElr49xe" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>杜比大喇叭β版： <a href="https://nalankang.lanzouo.com/b00u9dtif" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>UnblockMusic Pro： <a href="https://nalankang.lanzouo.com/b00u9dtwj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>网易云音乐插件： <a href="https://nalankang.lanzouo.com/iFEzDgt5bri" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>专辑封面禁旋转： <a href="https://nalankang.lanzouo.com/b00u9ezsh" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>网易叼毛云：<a href="https://nalankang.lanzouo.com/b00ve8qyj" target="_blank" rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688713086-526de8e7-3535-43a8-bf66-4e4e2ad8e217.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688713086-526de8e7-3535-43a8-bf66-4e4e2ad8e217.png"
                        alt="IMG_20220221_113124805.png" class="medium-zoom-image"></p>
                <p>【XP模块】 微博净化模块 </p>
                <p>微博+： <a href="https://nalankang.lanzouo.com/b00u8r25i" target="_blank" rel="noopener">点击查看</a></p>
                <p>AdAway： <a href="https://nalankang.lanzouo.com/b00tsmbgh" target="_blank" rel="noopener">点击查看</a></p>
                <p>微博助手：<a href="https://nalankang.lanzouo.com/b00ullbyd" target="_blank" rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688766260-3642e12e-1087-4a32-a019-0457d2f06874.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688766260-3642e12e-1087-4a32-a019-0457d2f06874.png"
                        alt="20220221141156Aicy809828.png" class="medium-zoom-image"></p>
                <p>【XP模块】 百度贴吧净化模块 </p>
                <p>百度贴吧伴侣： <a href="https://nalankang.lanzouo.com/b00u0l13g" target="_blank" rel="noopener">点击查看</a></p>
                <p>百度贴吧助手：<a href="https://nalankang.lanzouo.com/b00uecoyf" target="_blank" rel="noopener">点击查看</a></p>
                <p>帖吧TS(帖吧净化)： <a href="https://nalankang.lanzouo.com/b00tzwihc" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>联璧模块： <a href="https://nalankang.lanzouo.com/b00tsmwqd" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】 建行工行模块忽略ROOT检测模块 </p>
                <p>建行杀手： <a href="https://nalankang.lanzouo.com/insPchnubsj" target="_blank" rel="noopener">点击查看</a></p>
                <p>建行忽略root修复版： <a href="https://nalankang.lanzouo.com/ifQ6Chnuekj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>BankRX(工行建行)： <a href="https://nalankang.lanzouo.com/iQH4Nhpiuni" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>无间道(农行、工行、反诈中心屏蔽root检测)：<a href="https://nalankang.lanzouo.com/b00v8j57g" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688782799-953972e0-5766-494b-ab04-c4fe68aea327.png"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688782799-953972e0-5766-494b-ab04-c4fe68aea327.png"
                        alt="20220221142448Aicy812.png" class="medium-zoom-image"></p>
                <p>【XP模块】 哔哩哔哩增强模块 </p>
                <p>哔哩漫游： <a href="https://nalankang.lanzouo.com/b00ttp0kj" target="_blank" rel="noopener">点击查看</a></p>
                <p>哔哩补丁： <a href="https://nalankang.lanzouo.com/igGPQlrcepe" target="_blank" rel="noopener">点击查看</a></p>
                <p>联璧模块： <a href="https://nalankang.lanzouo.com/b00tsmwqd" target="_blank" rel="noopener">点击查看</a></p>
                <p>FuckBilibiliVote(去你妈b站视频弹窗)：<a href="https://nalankang.lanzouo.com/b00vq2xsb" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>不要竖屏：<a href="https://nalankang.lanzouo.com/b00vtzfja" target="_blank" rel="noopener">点击查看</a></p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/jpeg/28378617/1653780211920-61ed5321-f824-4c6b-9159-335049490f14.jpeg?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/jpeg/28378617/1653780211920-61ed5321-f824-4c6b-9159-335049490f14.jpeg?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        alt="img" class="medium-zoom-image"></p>
                <p>番茄小说VIP破解模块</p>
                <p>番茄vip模块：<a href="https://nalankang.lanzouo.com/b00vpo0wd" target="_blank" rel="noopener">点击查看</a></p>
                <p>番茄小说hookvip模块：<a href="https://nalankang.lanzouo.com/b00vpo0ub" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【XP模块】 运动修改模块</p>
                <p>修改步数，让你装逼不费劲！ </p>
                <p>运动修改器： <a href="https://nalankang.lanzouo.com/b00to5bpa" target="_blank" rel="noopener">点击查看</a></p>
                <p>运动加速器： <a href="https://nalankang.lanzouo.com/b00u8tp0d" target="_blank" rel="noopener">点击查看</a></p>
                <p>运动模拟器： <a href="https://nalankang.lanzouo.com/iAVp7lridyd" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>【XP模块】状态栏变色 </p>
                <p>微聚旧版： <a href="https://nalankang.lanzouo.com/iXbImrfwr7i" target="_blank" rel="noopener">点击查看</a></p>
                <p>微聚新版： <a href="https://nalankang.lanzouo.com/apk/io.ikws4.weiju" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>PerfectColorBar： <a href="https://www.lanzoui.com/irKuHgt707e" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>自动沉浸式状态栏：<a href="https://nalankang.lanzouo.com/iWnM5stybvi" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>【XP模块】 隐藏Root和xposed不被检测到 </p>
                <p>RootCloak(隐藏Root)：<a href="https://nalankang.lanzouo.com/iD7LLjks9ab" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>zuper(隐藏Xposed和Root)： <a href="https://nalankang.lanzouo.com/i2iuJgvqumf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>隐藏应用列表：<a href="https://nalankang.lanzouo.com/b00ujaeti" target="_blank" rel="noopener">点击查看</a></p>
                <p>XposedHider(隐藏Xposed)：<a href="https://nalankang.lanzouo.com/b00v4pjpa" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>SudoHide(隐藏Xposed)：<a href="https://nalankang.lanzouo.com/b00v4pjkf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【XP模块】 重力工具箱</p>
                <p>GravityBox[安卓8] ： <a href="https://nalankang.lanzouo.com/b00u9xezc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>GravityBox[安卓9] ： <a href="https://nalankang.lanzouo.com/b00u9xf7a" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>GravityBox[安卓10] ： <a href="https://nalankang.lanzouo.com/b00u9xfdg" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>GravityBox[安卓11] ： <a href="https://nalankang.lanzouo.com/b00u9xffi" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【XP模块】去广吿模块 </p>
                <p>AD快消：<a href="https://nalankang.lanzouo.com/b00u7asef" target="_blank" rel="noopener">点击查看</a></p>
                <p>大圣净化： <a href="https://nalankang.lanzouo.com/b00u8uhij" target="_blank" rel="noopener">点击查看</a></p>
                <p>大圣净化-Magisk版：<a href="https://nalankang.lanzouo.com/b00v95m8b" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>悟空加速： <a href="https://nalankang.lanzouo.com/b00u8uhja" target="_blank" rel="noopener">点击查看</a></p>
                <p>AdBlocker： <a href="https://nalankang.lanzouo.com/b00tf5ive" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>联璧模块： <a href="https://nalankang.lanzouo.com/b00tsmwqd" target="_blank" rel="noopener">点击查看</a></p>
                <p>闲鱼助手：<a href="https://nalankang.lanzouo.com/b00un0t1e" target="_blank" rel="noopener">点击查看</a></p>
                <p>电报广告拦截器：<a href="https://nalankang.lanzouo.com/b00v0v12b" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>电报去广告模块：<a href="https://nalankang.lanzoui.com/b00v0v15e" target="_blank" rel="noopener">点击查看</a></p>
                <p>推特去广告模块：<a href="https://nalankang.lanzouo.com/b00vauqdg" target="_blank" rel="noopener">点击查看</a></p>
                <p>FuckCoolapkR-酷安去广告模块：<a href="https://nalankang.lanzouo.com/b00vio87e" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>皮皮虾,我们走</p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688802737-2f5cc10f-ed7e-4c36-95e2-0eb6b542c8ae.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688802737-2f5cc10f-ed7e-4c36-95e2-0eb6b542c8ae.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        alt="IMG_20220221_143749814.png" class="medium-zoom-image"></p>
                <p>【XP模块】 皮皮虾快手模块合集 </p>
                <p>快手+： <a href="https://nalankang.lanzouo.com/b00u8r2cf" target="_blank" rel="noopener">点击查看</a></p>
                <p>AdAway： <a href="https://nalankang.lanzouo.com/b00tsmbgh" target="_blank" rel="noopener">点击查看</a></p>
                <p>诺诺诺嗯： <a href="https://nalankang.lanzouo.com/b00u5t5wh" target="_blank" rel="noopener">点击查看</a></p>
                <p>皮皮虾助手： <a href="https://nalankang.lanzouo.com/b00tvgswh" target="_blank" rel="noopener">点击查看</a></p>
                <p>要你命三千： <a href="https://nalankang.lanzouo.com/b00tw4jhc" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】小红书模块 </p>
                <p>AdAway： <a href="https://nalankang.lanzouo.com/b00tsmbgh" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>X小红书： <a href="https://nalankang.lanzouo.com/b00u9cabi" target="_blank" rel="noopener">点击查看</a> </p>
                <p>小红书+： <a href="https://nalankang.lanzouo.com/b00ucb8pc" target="_blank" rel="noopener">点击查看</a></p>
                <p>红薯猪手：<a href="https://nalankang.lanzouo.com/b00vdhfxa" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】钉钉模块</p>
                <p>钉钉打卡： <a href="https://nalankang.lanzouo.com/b00tw4j8d" target="_blank" rel="noopener">点击查看</a></p>
                <p>钉钉助手： <a href="https://nalankang.lanzouo.com/b00ty6xeh" target="_blank" rel="noopener">点击查看</a></p>
                <p>钉钉反撤回神器：<a href="https://nalankang.lanzouo.com/b00vn4gqb" target="_blank" rel="noopener">点击查看</a></p>
                <p>钉钉增强：<a href="https://nalankang.lanzouo.com/b00vs1a1c" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】telegram电报模块</p>
                <p>TMoe(电报增强模块)：<a href="https://nalankang.lanzouo.com/b00vudbyf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>电报广告拦截器：<a href="https://nalankang.lanzouo.com/b00v0v12b" target="_blank" rel="noopener">点击查看</a></p>
                <p>电报去广告模块：<a href="https://nalankang.lanzoui.com/b00v0v15e" target="_blank" rel="noopener">点击查看</a></p>
                <p>【XP模块】其他模块合集 </p>
                <p>算法助手(Hook工具)：<a href="https://nalankang.lanzouo.com/b00umtq4h" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>上帝模式：<a href="https://nalankang.lanzouo.com/b00um9gha" target="_blank" rel="noopener">点击查看</a></p>
                <p>天帝模式：<a href="https://nalankang.lanzoui.com/b00vio9qj" target="_blank" rel="noopener">点击查看</a></p>
                <p>定时清理(清理文件和文件夹)： <a href="https://nalankang.lanzouo.com/i62C4ilqksd" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>xposed黑名单(禁用Xposed)： <a href="https://nalankang.lanzouo.com/iuJe2h1efgd" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>AllTrans(应用内翻译)：<a
                        href="https://www.coolapk.com/feed/23531453?shareKey=MjE0Mjk1NTEyNDRkNjBjZGMyZDY~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.2.4-beta6"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>去伱大爷的内置浏览器： <a href="https://nalankang.lanzouo.com/iJLBYiqgs6j" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>一键分享(视频无水印)： <a href="https://nalankang.lanzouo.com/b00u71tcf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>知了(知乎增强模块)： <a href="https://nalankang.lanzouo.com/b00tt2w1e" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>交通12123屏蔽root检测 ： <a href="https://nalankang.lanzouo.com/id38v2h" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>面具hide增强模块： <a href="https://nalankang.lanzouo.com/iMmPihuq4wj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>你才长按复制访问：<a href="https://nalankang.lanzouo.com/b00tys3qb" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>导航栏扩展模块： <a href="https://www.coolapk.com/apk/com.egguncle.xposednavigationbar" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>今日头条+： <a href="https://nalankang.lanzouo.com/b00u8r28b" target="_blank" rel="noopener">点击查看</a></p>
                <p>假装分享： <a href="https://nalankang.lanzouo.com/iOJ09lmdg4b" target="_blank" rel="noopener">点击查看</a></p>
                <p>Magisk hide(面具增强模块)： <a href="https://nalankang.lanzouo.com/iMmPihuq4wj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>太极更新宝(太极阴专用)： <a href="https://nalankang.lanzouo.com/itU7Fkwxova" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>一个让你感觉卧曹卧曹的模块： <a href="https://nalankang.lanzouo.com/ii7Hzgt6zsj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>应用设置重生版： <a href="https://nalankang.lanzouo.com/b00u7e3ni" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>飞书助手： <a href="https://nalankang.lanzouo.com/b00tx61rc" target="_blank" rel="noopener">点击查看</a></p>
                <p>数据过滤： <a href="https://nalankang.lanzouo.com/b00ubhcpg" target="_blank" rel="noopener">点击查看</a></p>
                <p>阿里系Xposed反检测： <a href="https://nalankang.lanzouo.com/ikPQ5n2y3pc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>淘饭饭(自动领券)：<a href="https://nalankang.lanzouo.com/b00ue7nlg" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>拼夕夕免拼助手：<a href="https://nalankang.lanzouo.com/b00u6yczi" target="_blank" rel="noopener">点击查看</a></p>
                <p>京东历史价格：<a href="https://nalankang.lanzouo.com/irbo1pi4lve" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>陌陌群发模块：<a href="https://nalankang.lanzouo.com/b00uli2mj" target="_blank" rel="noopener">点击查看</a></p>
                <p>DDex脱壳(XP)：<a href="https://nalankang.lanzouo.com/b00vcvtla" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>DJkwaiching(破解音乐VIP)：<a href="https://nalankang.lanzouo.com/b00tytm1g" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Blued模块：<a href="https://nalankang.lanzouo.com/b00up6lzi" target="_blank" rel="noopener">点击查看</a></p>
                <p>王者人生wifi信息劫持：<a href="https://nalankang.lanzouo.com/ib4F3s4471e" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>油管模块合集： <a href="https://nalankang.lanzouo.com/b00u8om6b" target="_blank" rel="noopener">点击查看</a></p>
                <p>小草影视助手：<a href="https://nalankang.lanzouo.com/b00utv70d" target="_blank" rel="noopener">点击查看</a></p>
                <p>VCAM(虚拟摄像头)：<a href="https://nalankang.lanzouo.com/b00uud7hi" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>动漫之家增强模块：<a href="https://nalankang.lanzouo.com/b00uwt6zi" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>Xposed Tool(一键内置XP模块)：<a href="https://nalankang.lanzouo.com/b00vsay9i" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>支付宝装X模块：<a href="https://nalankang.lanzouo.com/b00v730da" target="_blank" rel="noopener">点击查看</a></p>
                <p>钱迹自动记账插件：<a href="https://nalankang.lanzouo.com/b00v7fjjc" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>AnyDebug(修改应用布局参数)：<a href="https://nalankang.lanzoui.com/b00vhv14f" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>过VPN检测：<a href="https://nalankang.lanzouo.com/b00vsaxud" target="_blank" rel="noopener">点击查看</a></p>
                <p>Fuck云注入(禁止云注入弹窗)：<a href="https://nalankang.lanzouo.com/b00vta76j" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>QDReadHook：(起点阅读增强模块)：<a href="https://nalankang.lanzouo.com/b00vu7rof" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【APP】搞机助手 </p>
                <p>搞机助手(情非得已)原创作者：<a href="https://nalankang.lanzouo.com/b00uks1sd" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>搞机重制版(快播内部工作人员)：<a href="https://nalankang.lanzouo.com/b00tugduj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>搞机助手2(抱抱猫People11)：<a href="https://nalankang.lanzouo.com/b00uks28j" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>【APP】第三方油管纯净无广吿 </p>
                <p>Vanced：<a href="https://nalankang.lanzouo.com/b00ujce7i" target="_blank" rel="noopener">点击查看</a></p>
                <p>𝐏𝐮𝐫𝐞𝐓𝐮𝐛𝐞𝐫：<a href="https://nalankang.lanzouo.com/b00usb4ba" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>LibreTube：<a href="https://nalankang.lanzouo.com/b00vsd3ta" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>【APP】文件管理器 </p>
                <p>RE文件管理器： <a href="https://nalankang.lanzouo.com/b00u85wja" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>ES文件管理器会员版： <a href="https://nalankang.lanzouo.com/b00u2b9pi" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>NP管理器： <a href="https://nalankang.lanzouo.com/b00u7565e" target="_blank" rel="noopener">点击查看</a> </p>
                <p>ES管理器美化版：<a href="https://nalankang.lanzouo.com/b00uwhrob" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>RS文件管理器：<a href="https://nalankang.lanzouo.com/b00v3lsaj" target="_blank" rel="noopener">点击查看</a></p>
                <p>SE文件管理器：<a href="https://nalankang.lanzouo.com/b00v55w4d" target="_blank" rel="noopener">点击查看</a></p>
                <p>【APP】终端模拟器 </p>
                <p>Termux：<a href="https://nalankang.lanzouo.com/b00v67ype" target="_blank" rel="noopener">点击查看</a></p>
                <p>ZeroTermux：<a href="https://cloud.189.cn/t/aqam2uZNJ7ny" target="_blank" rel="noopener">点击查看</a></p>
                <p>UTermux：<a href="https://cloud.189.cn/t/YbmqaiqYniIn" target="_blank" rel="noopener">点击查看</a></p>
                <p>终端模拟器：<a href="https://nalankang.lanzouo.com/b00v67zte" target="_blank" rel="noopener">点击查看</a></p>
                <p>Ansole：<a href="https://nalankang.lanzouo.com/b00v681pc" target="_blank" rel="noopener">点击查看</a></p>
                <p>NeoTerm：<a href="https://nalankang.lanzouo.com/b00v681xa" target="_blank" rel="noopener">点击查看</a></p>
                <p>【APP】JAVA模拟器 </p>
                <p>J2ME Loader：<a href="https://nalankang.lanzouo.com/b00vaursh" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>Retro2ME：<a href="https://nalankang.lanzouo.com/b00vaurhg" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>【APP】加固app脱壳工具 </p>
                <p>BlackDex：<a href="https://nalankang.lanzouo.com/b00um84kf" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>fdex2：<a href="https://nalankang.lanzouo.com/iBdENqkpmng" target="_blank" rel="noopener">点击查看</a></p>
                <p>微脱壳：<a href="https://nalankang.lanzouo.com/iFfamqkpmoh" target="_blank" rel="noopener">点击查看</a></p>
                <p>反射大师：<a href="https://nalankang.lanzouo.com/b00v2j5ud" target="_blank" rel="noopener">点击查看</a></p>
                <p>DDex脱壳(XP)：<a href="https://nalankang.lanzouo.com/b00vcvtla" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>DITOR-脱壳工具：<a href="https://nalankang.lanzouo.com/b00vdbu8j" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>【APP】备份工具 </p>
                <p>钛备份： <a href="https://nalankang.lanzouo.com/b00u85wmd" target="_blank" rel="noopener">点击查看</a></p>
                <p>超级备份：<a href="https://nalankang.lanzouo.com/b00v82qxg" target="_blank" rel="noopener">点击查看</a></p>
                <p>【APP】在线影视播放软件 </p>
                <p>星球视频：<a href="https://nalankang.lanzouo.com/b00v2atfi" target="_blank" rel="noopener">点击查看</a></p>
                <p>美剧鸟：<a href="https://nalankang.lanzouo.com/b00v2assf" target="_blank" rel="noopener">点击查看</a></p>
                <p>电视家3.0：<a href="https://nalankang.lanzouo.com/b00uvarti" target="_blank" rel="noopener">点击查看</a></p>
                <p>小草影视：<a href="https://nalankang.lanzouo.com/b00uvtgkh" target="_blank" rel="noopener">点击查看</a></p>
                <p>美剧星球：<a href="https://nalankang.lanzouo.com/b00uoxh3i" target="_blank" rel="noopener">点击查看</a></p>
                <p>【APP】Apk编辑工具 </p>
                <p>Apk编辑器：<a href="https://nalankang.lanzouo.com/b00u06q0d" target="_blank" rel="noopener">点击查看</a></p>
                <p>APK Editor R3：<a href="https://nalankang.lanzouo.com/b00uud6lg" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Apktool M(Apk反编译)：<a href="https://nalankang.lanzouo.com/b00uud6kf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>NP管理器：<a href="https://nalankang.lanzouo.com/b00u7565e" target="_blank" rel="noopener">点击查看</a></p>
                <p>MT管理器：<a href="https://www.coolapk.com/apk/bin.mt.plus" target="_blank" rel="noopener">点击查看</a></p>
                <p>【APP】应用冻结</p>
                <p>雹：<a href="https://nalankang.lanzouo.com/b00vjgpxa" target="_blank" rel="noopener">点击查看</a></p>
                <p>冰箱：<a href="https://nalankang.lanzouo.com/b00vjgpsf" target="_blank" rel="noopener">点击查看</a></p>
                <p>【APP】下载工具 </p>
                <p>ADM(下载工具)： <a href="https://nalankang.lanzouo.com/b00u06sid" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>IDM+(下载工具)： <a href="https://nalankang.lanzouo.com/b00u06sje" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>闪电下载： <a href="https://nalankang.lanzouo.com/b00u06tlc" target="_blank" rel="noopener">点击查看</a></p>
                <p>种子磁力播放器：<a href="https://nalankang.lanzouo.com/b00uunmef" target="_blank" rel="noopener">点击查看</a></p>
                <p>种子磁力下载器：<a href="https://nalankang.lanzouo.com/b00uunmja" target="_blank" rel="noopener">点击查看</a></p>
                <p>磁力云高级版：<a href="https://nalankang.lanzouo.com/b00ur7bhi" target="_blank" rel="noopener">点击查看</a></p>
                <p>tTorrent种子下载器：<a href="https://nalankang.lanzouo.com/b00uz3ikh" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>懒熊下载：<a href="https://nalankang.lanzouo.com/b00uz3ibi" target="_blank" rel="noopener">点击查看</a> </p>
                <p>浩克下载：<a href="https://nalankang.lanzouo.com/b00u79kob" target="_blank" rel="noopener">点击查看</a></p>
                <p>极速下载：<a href="https://nalankang.lanzouo.com/b00v2asli" target="_blank" rel="noopener">点击查看</a></p>
                <p>冰冰磁力下载器：<a href="https://nalankang.lanzouo.com/b00v2w6yb" target="_blank" rel="noopener">点击查看</a></p>
                <p>离线云：<a href="https://nalankang.lanzouo.com/b00u79khe" target="_blank" rel="noopener">点击查看</a></p>
                <p>迅雷不限速版：<a href="https://nalankang.lanzouo.com/b00v8e9zi" target="_blank" rel="noopener">点击查看</a></p>
                <p>快鸟下载：<a href="https://nalankang.lanzouo.com/b00v8mdhc" target="_blank" rel="noopener">点击查看</a></p>
                <p>全能下载：<a href="https://nalankang.lanzouo.com/b00va46tg" target="_blank" rel="noopener">点击查看</a></p>
                <p>火箭BT下载器：<a href="https://nalankang.lanzouo.com/b00vb309a" target="_blank" rel="noopener">点击查看</a></p>
                <p>游隼下载器：<a href="https://nalankang.lanzoui.com/b00vfsk6b" target="_blank" rel="noopener">点击查看</a></p>
                <p>【APP】HiShoot2i(带壳截图) </p>
                <p>HiShoot2i汉化版：<a href="https://nalankang.lanzouo.com/ihKhIu8yelc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>精选模板(蓝奏云)：<a href="https://nalankang.lanzouo.com/b00tvr6yd" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>其他模板(百度云)： <a href="https://pan.baidu.com/s/1ZmToxkG__uLjFFZfep8eeg" target="_blank"
                        rel="noopener">点击查看</a>提取码:h368 </p>
                <p>一些模板预览图：<a
                        href="https://www.coolapk.com/feed/29231338?shareKey=ZDg5NGQ3NmVhZjY3NjExOTNiOTQ~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.2.3"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>【APP】短信伪造 </p>
                <p>一键添加收发短信到本地,可以任意设置收到任何人给你发来的短信，效果跟正常短信一模一样。应用仅供娱乐！ </p>
                <p>伪造短信消息：<a href="https://nalankang.lanzouo.com/iAmMrsm3l1a" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>【APP】抓包工具 </p>
                <p>HttpCanary(小黄鸟)：<a href="https://nalankang.lanzouo.com/b00usn91c" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Wicap(安卓嗅探器)：<a href="https://nalankang.lanzouo.com/b00usn8te" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Packet Capture(免root抓包)：<a href="https://nalankang.lanzouo.com/b00usn8yj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>抓包精灵：<a href="https://nalankang.lanzouo.com/b00vb69jc" target="_blank" rel="noopener">点击查看</a> </p>
                <p>【APP】MacroDroid智能触发器 </p>
                <p>一款任务自动化配置工具，只有你想不到，没有他做不到的，功能强大，类似Tasker和xposed edge </p>
                <p>MacroDroid：<a href="https://nalankang.lanzouo.com/b00usijgh" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>辅助模块：<a href="https://nalankang.lanzouo.com/b00usiqle" target="_blank" rel="noopener">点击查看</a></p>
                <p>自动发邮件插件：<a href="https://nalankang.lanzouo.com/b00utusqj" target="_blank" rel="noopener">点击查看</a></p>
                <p>【YX】怀旧小游戏 </p>
                <p>植物大战僵尸1代合集： <a href="https://nalankang.lanzouo.com/b00uu2nsj" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>植物大战僵尸北美汉化版： <a href="https://cloud.189.cn/t/faUjeaA3Evqm" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>孤胆枪手合集：<a href="https://cloud.189.cn/t/BvmeMv3qe22e" target="_blank" rel="noopener">点击查看</a> </p>
                <p>NYA~</p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688833808-f9b29d99-7d90-429b-b410-92ca1814adc8.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645688833808-f9b29d99-7d90-429b-b410-92ca1814adc8.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        alt="IMG_20220220_152839785821.png" class="medium-zoom-image"></p>
                <p>【APP】应用分享 </p>
                <p>UC浏览器(去广吿版)：<a href="https://nalankang.lanzouo.com/b00uotlmh" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>QQ浏览器(去广吿版)：<a href="https://nalankang.lanzouo.com/b00usnkpc" target="_blank" rel="noopener">点击率就</a>
                </p>
                <p>血轮眼(禁用服务)：<a href="https://nalankang.lanzouo.com/b00ucdbhe" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>网速测试(网速测试)： <a href="https://nalankang.lanzouo.com/b00u06nch" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>温控拜拜(删除温控)： <a href="https://nalankang.lanzouo.com/i8YXOig4oob" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>镜像助手(提取、刷入REC)： <a href="https://nalankang.lanzouo.com/ilViPijcsna" target="_blank"
                        rel="noopener">点击查看</a> </p>
                <p>TWRP(下载刷入TWRP)： <a href="https://nalankang.lanzouo.com/b00u06y2d" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>Cellular-Pro(频段锁定)： <a href="https://nalankang.lanzouo.com/b00u06pna" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>APK编辑器： <a href="https://nalankang.lanzouo.com/b00u06q0d" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>微软远程桌面： <a href="https://nalankang.lanzouo.com/b00u06qib" target="_blank" rel="noopener">点击查看</a></p>
                <p>歌词适配(网易云音乐下载)：<a href="https://nalankang.lanzouo.com/b00u06rdc" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>快图浏览器(魔改版)： <a href="https://nalankang.lanzouo.com/b00u06uhe" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>联通营业厅(去广吿)： <a href="https://nalankang.lanzouo.com/b00uq36md" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>黑阈(阻止运行)： <a href="https://nalankang.lanzouo.com/b00u71uwb" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>碘酒编辑器(气泡碘酒)： <a href="https://nalankang.lanzouo.com/is0vQkt9fsb" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>云闪付(谷歌版)： <a href="https://nalankang.lanzouo.com/b00u71vte" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>Nova桌面： <a href="https://nalankang.lanzouo.com/b00u7cmgd" target="_blank" rel="noopener">点击查看</a></p>
                <p>钛备份： <a href="https://nalankang.lanzouo.com/b00u85wmd" target="_blank" rel="noopener">点击查看</a> </p>
                <p>山寨版谷歌应用商店： <a href="https://nalankang.lanzouo.com/b00u7hyze" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>Aptoide开源应用商店：<a href="https://nalankang.lanzouo.com/b00uuddhe" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>第三方油管(无广吿)：<a href="https://nalankang.lanzouo.com/b00ujce7i" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>照片编辑器：<a href="https://nalankang.lanzouo.com/b00uo1fkb" target="_blank" rel="noopener">点击查看</a></p>
                <p>虚拟相机(可以用相册里面的照片假装拍照)：<a href="https://nalankang.lanzouo.com/b00up86ej" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>飞聊(中文版电报)：<a href="https://nalankang.lanzouo.com/b00upq0bi" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>𝐓𝐞𝐥𝐞𝐠𝐫𝐚𝐦(电报魔法版自带踢子)：<a href="https://nalankang.lanzouo.com/b00v8earg" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>NekogramX(第三方电报自带踢子)：<a href="https://nalankang.lanzoum.com/b00vcrn1a" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>王者特权获取：<a href="https://nalankang.lanzouo.com/iDWRSs44eni" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>SD女佣高级版：<a href="https://nalankang.lanzouo.com/b00ur7bgh" target="_blank" rel="noopener">点击查看</a></p>
                <p>傲软抠图会员版：<a href="https://nalankang.lanzouo.com/b00ur7bja" target="_blank" rel="noopener">点击查看</a></p>
                <p>神仙自动救砖：<a href="https://nalankang.lanzouo.com/b00urjnza" target="_blank" rel="noopener">点击查看</a></p>
                <p>MX_Player视频播放器：<a href="https://nalankang.lanzouo.com/b00ursr2f" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>蓝云(第三方蓝奏云)：<a href="https://nalankang.lanzouo.com/b083z1nsj" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>迅游手游加速器(会员版)：<a href="https://nalankang.lanzouo.com/b00usp1kf" target="_blank"
                        rel="noopener">点击查看</a> </p>
                <p>腾讯手游加速器(魔改版)：<a href="https://nalankang.lanzouo.com/b00v8m6zi" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>See第三方微博：<a href="https://nalankang.lanzouo.com/b00uumzmf" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>HiGo谷歌框架安装器：<a href="https://nalankang.lanzouo.com/b00uuxmbc" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>状态栏歌词-高级版：<a href="https://nalankang.lanzouo.com/b00uwt8xi" target="_blank" rel="noopener">点击率就</a>
                </p>
                <p>李跳跳(自动跳过广告)：<a href="https://nalankang.lanzouo.com/b00v0m18d" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>一指禅(自动跳过广告)：<a href="https://nalankang.lanzouo.com/b00v8ktla" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>AetherSX2(PS2游戏模拟器)：<a href="https://nalankang.lanzouo.com/b00v3iwqb" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>幸运破解器：<a href="https://nalankang.lanzouo.com/b00u06nfa" target="_blank" rel="noopener">点击查看</a> </p>
                <p>Andronix(手机上安装Linux系统)：<a href="https://nalankang.lanzouo.com/b00v6275c" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>屏幕翻译：<a href="https://nalankang.lanzouo.com/b00v75tyh" target="_blank" rel="noopener">点击查看</a></p>
                <p>MIUI下载器：<a href="https://nalankang.lanzouo.com/b00v7ef5i" target="_blank" rel="noopener">点击查看</a></p>
                <p>两仪(安卓容器)：<a href="https://cloud.189.cn/t/7BvEJ32qINNr" target="_blank" rel="noopener">点击查看</a></p>
                <p>𝐓𝐢𝐤𝐓𝐨𝐤(抖音国际版)：<a href="https://nalankang.lanzoum.com/b00vcpf8h" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>风车动漫魔改版：<a href="https://nalankang.lanzouo.com/b00v9ce9g" target="_blank" rel="noopener">点击查看</a></p>
                <p>蓝云(蓝奏云第三方客户端)：<a href="https://nalankang.lanzouo.com/b00v9m5dg" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>面具root权限开关：<a href="https://nalankang.lanzouo.com/b00vaasbg" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>爱美化(手机主题制作)：<a href="https://nalankang.lanzouo.com/b00vauqib" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>甲壳虫ADB助手：<a href="https://nalankang.lanzouo.com/b00vd9rde" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>AccubatteryPro-精准电量：<a href="https://nalankang.lanzouo.com/b00vdbnwb" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>清浊(垃圾清理)：<a href="https://nalankang.lanzouo.com/b00vgt4hi" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>绿去广告(自动跳过开屏广告)：<a href="https://nalankang.lanzouo.com/b00vijqoj" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>酷安去广告版：<a href="https://nalankang.lanzouo.com/b00vjm8ja" target="_blank" rel="noopener">点击查看</a></p>
                <p>Momo(检测工具)：<a href="https://nalankang.lanzouo.com/b00vno8mj" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>【WX】微X主题 </p>
                <p>微信主题美化，主题功能需要打赏才能开通 </p>
                <p>微X主题〈带土与琳〉：<a
                        href="https://www.coolapk.com/feed/24107117?shareKey=YzMwOGQ2YjljNTM4NjAwMWFkOWY~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.0-rc2"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>微X主题〈Q版蜘蛛侠〉： <a
                        href="https://www.coolapk.com/feed/24230601?shareKey=YzBiYjhjMGQzMDgyNjAwMWFkOWQ~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.0-rc2"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>微X主题〈漫〉： <a
                        href="https://www.coolapk.com/feed/24081843?shareKey=MTMwNTdjMjI0ZmQ5NjAwMWFkYzA~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.0-rc2"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>微X主题〈无题〉： <a
                        href="https://www.coolapk.com/feed/22527630?shareKey=NTJiZTYyN2IzZmIwNjAwMWFlYTY~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.0-rc2"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>【WJ】玩机技巧 </p>
                <p>手机端制作卡刷包线刷包教程： <a
                        href="https://www.coolapk.com/feed/22941669?shareKey=NTVmMWViYjgwMzE0NWZiMTQ3M2E~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.0-beta2"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>魅族16T纯手机端解锁教程：<a
                        href="https://www.coolapk.com/feed/22941669?shareKey=NGFmMDkxYTVjZWZhNjAyOWU3Zjg~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.0.1"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>防止手机文件误删教程： <a
                        href="https://www.coolapk.com/feed/21508157?shareKey=MzU5ZTE1ZmRmNmIyNWY3YWM3NGU~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_10.5.3"
                        target="_blank" rel="noopener">点击查看</a> </p>
                <p>魅族手机原厂线刷包： <a
                        href="https://www.coolapk.com/feed/21349572?shareKey=Zjg0ZWY1ZTc2YTA4NWZjOGMwNTY~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.0-beta2"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>自定义应用名称教程： <a
                        href="https://www.coolapk.com/feed/15346519?shareKey=N2VhYWJjZDU5ZThmNWY3YWM3ZGQ~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_10.5.3"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>UC浏览器去除启动页广告教程： <a
                        href="https://www.coolapk.com/feed/21502013?shareKey=MzUxNGMyN2NhMDU3NWY3YWM3NGU~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_10.5.3"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>SELinux未处于严格模式的解决方法：<a
                        href="https://www.coolapk.com/feed/24620582?shareKey=NGVmMmIzNWU1ZTg3NjA0NWM5NmU~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.0.3-beta1"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>禁用App启动页广告教程：<a
                        href="https://www.coolapk.com/feed/27731488?shareKey=ZTZhYzFiZTEwODVmNjBjNzFjMjY~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.2"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>把英文软件翻译成中文：<a
                        href="https://www.coolapk.com/feed/23531453?shareKey=M2Y0OTg1ZTRmMDk2NjE2N2QwYjY~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.2.3"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>修补boot安装面具教程：<a
                        href="https://www.coolapk.com/feed/32152531?shareKey=ODdjZGFlMzAzNTliNjFiYThkNDk~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.2.3"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>面具开启Zygisk后隐藏root教程：<a
                        href="https://www.coolapk.com/feed/33457333?shareKey=MjNiOGZlZDI2MzNjNjIwNTQxOTY~&amp;shareUid=462071&amp;shareFrom=com.coolapk.market_11.2.3"
                        target="_blank" rel="noopener">点击查看</a></p>
                <p>米</p>
                <p><img src="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645692639120-3984d35a-e077-4954-a112-5eaa3b5a4cba.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        data-origin="https://cdn.nlark.com/yuque/0/2022/png/26257373/1645692639120-3984d35a-e077-4954-a112-5eaa3b5a4cba.png?x-oss-process=image%2Fresize%2Cw_750%2Climit_0"
                        alt="2022_0114_124720-1820.png" class="medium-zoom-image"></p>
                <p>【PC】端搞机工具合集 </p>
                <p>秋之盒： <a href="https://nalankang.lanzouo.com/b00u8myid" target="_blank" rel="noopener">点击查看</a></p>
                <p>ADB工具： <a href="https://nalankang.lanzouo.com/b00u8mv1i" target="_blank" rel="noopener">点击查看</a></p>
                <p>高通全系列驱动：<a href="https://nalankang.lanzouo.com/iPzC9lgltwj" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>ADB&amp;FastBoot驱动：<a href="https://nalankang.lanzouo.com/iIk1Xlgltsf" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>搞机工具箱：<a href="https://nalankang.lanzouo.com/b00u8nnqb" target="_blank" rel="noopener">点击查看</a></p>
                <p>搞机助手PC版： <a href="https://nalankang.lanzouo.com/b00u8muij" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>搞机助手CMD命令版：<a href="https://nalankang.lanzouo.com/b00uugykb" target="_blank" rel="noopener">点击查看</a>
                </p>
                <p>小米线刷工具售后版： <a href="https://cloud.189.cn/t/e6Vra2jAfuae" target="_blank" rel="noopener">点击查看</a></p>
                <p>高通9008线刷工具：<a href="https://nalankang.lanzouo.com/iPvjYp8qw2d" target="_blank"
                        rel="noopener">点击查看</a></p>
                <p>百度云不限速下载工具：<a href="https://nalankang.lanzouo.com/iD2Ldxkw51g" target="_blank"
                        rel="noopener">点击查看</a></p>
            </article>
        </section>
    </main>
    
    <div class="back">
        ↑
    </div>
</body>
<script type="text/javascript">
        // 只要滚动条发生滚动了，就判断滚动过多少距离，如果大于等于300了，就应该让顶部出现了
        // 滚动事件
        
        // 获取回到顶部
        var b = document.querySelector(".back");
        window.onscroll=function(){
            // console.log(123);
            // 获取滚动过距离
            var t = document.documentElement.scrollTop || document.body.scrollTop;
            // console.log(t);
            // 判断这个距离是否大于等于300
            // 获取顶部元素
            var up = document.querySelector(".top");
            if(t>=300){
                // 如果大于等于300了，就让顶部出现
                // 让顶部出现就是让他的display变成block
                // up.style.display = "block"
                up.style.height = "80px"
            }else{ // 上面的时候消失
                // up.style.display = "none"
                up.style.height=0;
                // console.log(up);
            }
        
            // 回到顶部
            if(t>=400){
                b.style.display="block"
            }else{
                b.style.display="none"
            }
        
            // 判断滚动条是否回到了0的位置
            if(t<=0){
                // 清除定时器
                // 局部定义的变量，在另一个局部没法使用
                clearInterval(timer);
            }
        }
        var timer; // 必须变成全局的变量，两个局部中才都能使用
        // console.log(b);
        // 给回到顶部绑定单击事件
        b.onclick=function(){
            // 让滚动过的距离变成0 - 滚动过的距离可以获取，也可以设置
            // document.documentElement.scrollTop = 0
            // document.body.scrollTop = 0
            // 这种回到顶部是瞬间回去的 - 慢慢回去
            // 用到每个一会就 让滚动过的距离减小一点 - 定时器
            timer = setInterval(function(){
                // 先获取到滚动过的距离，
                var t = document.documentElement.scrollTop || document.body.scrollTop;
                // 然后减小一点
                var t1 = t-600;
                // 然后将减小的值 赋值 给 滚动过的距离
                document.documentElement.scrollTop = t1
                document.body.scrollTop = t1
                console.log(123);
            },20);
        }
</script>
</html>
