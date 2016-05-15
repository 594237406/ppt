title: 测试页面
speaker: 李宏吉
url: https://github.com/594237406/ppt
files: /css/ppt.css

[slide style="background-image:url('/img/bg1.png')"]
# 这是个有背景的家伙
## 我是副标题

[slide]
# 主标题样式
## 副标题样式
----
```
nodeppt是基于nodejs写的支持 **Markdown!** 语法的网页PPT

nodeppt：https://github.com/ksky521/nodePPT
```

[slide]
<div class='div'>
    <p>这是html</p>
</div>
<p id="css-demo">这是css样式</p>
<p>具体看下项目中 ppts/demo.md 代码</p>
<script>
function testScriptTag(){}
console.log(typeof testScriptTag);
</script>
<style>
#css-demo{
color: red;
}
</style>

[slide]
### 市面上主要的css预处理器：lesssassstylus
 ---
|less| sass | stylus
:-------|:------:|-------:|--------
环境 |js/nodejs | Ruby | nodejs
扩展名 | .less | .sass/.scss | .styl
特点 | 老牌，用户多，支持js解析 | 功能全，有成型框架，发展快 | 语法多样，小众
案例/框架 | [Bootstrap](http://getbootstrap.com/) | [compass](http://compass-style.org) [bourbon](http://bourbon.io) |

[slide]
<iframe data-src="http://www.baidu.com" src="about:blank;" style='height:100vh;' ></iframe>