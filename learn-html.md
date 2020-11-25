# Note of HTML
## Brief introduction
HTML (HyperText Markup Language) 超文本标记语言--一种用于创建网页的标准标记语言

## Tags
### Basic file 基础文档
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Web title</title>
    </head>
    <body>
        file body
    </body>
</html>
```
### Basic tags of file 基础标签
```html
<!--注释-->
<h1>biggest title</h1>
<h2> . . . </h2>
<h3> . . . </h3>
<h4> . . . </h4>
<h5> . . . </h5>
<h6>smallest title</h6>

<p>这是一个段落。</p>
<br> （换行）
<hr> （水平线）
```
### Formatting 文件格式化
```html
<b>粗体文本</b>
<code>计算机代码</code>
<em>强调文本</em>
<i>斜体文本</i>
<kbd>键盘输入</kbd> 
<pre>预格式化文本</pre>
<small>更小的文本</small>
<strong>重要的文本</strong>
 
<abbr> （缩写）
<address> （联系信息）
<bdo> （文字方向）
<blockquote> （从另一个源引用的部分）
<cite> （工作的名称）
<del> （删除的文本）
<ins> （插入的文本）
<sub> （下标文本）
<sup> （上标文本）
```
实例见：https://www.runoob.com/html/html-formatting.html

### Links 链接
```html
<!--普通链接-->
<a href="https://sharlylv.github.io/learn-web/learn-markdown">链接文本</a>
<!--图像链接-->
<a href="https://sharlylv.github.io/learn-web/learn-markdown">
    <img src="URL" alt="替换文本">
</a>
<!--邮件链接-->
<a href="mailto:webmaster@example.com">发送e-mail</a>
<!--书签-->
<a id="tips">提示部分</a>
<a href="#tips">跳到提示部分</a>
```
### Images 图像
```html
<img loading="lazy" src="URL" alt="替换文本" height="42" width="42">
```

### styles/sections 样式、区块
```html
<style type="text/css">
    h1 {color:red;}
    p {color:blue;}
</style>

<div>文档中的块级元素</div>
<span>文档中的内联元素</span>
```
### unordered list 无序列表
```html
<ul>
    <li>项目</li>
    <li>项目</li>
</ul>
```
### ordered list 有序列表
```html
<ol>
    <li>第一项</li>
    <li>第二项</li>
</ol>
```
### define list 自定义列表
```html
<dl>
  <dt>项目 1</dt>
    <dd>描述项目 1</dd>
  <dt>项目 2</dt>
    <dd>描述项目 2</dd>
</dl>
```
### Table 表格
```html
<table border="1">
  <tr>
    <th>表格标题</th>
    <th>表格标题</th>
  </tr>
  <tr>
    <td>表格数据</td>
    <td>表格数据</td>
  </tr>
</table>
```
### Iframe 框架
```html
<iframe src="demo_iframe.htm"></iframe>
```
https://www.runoob.com/html/html-iframes.html

### Forms 表单
表单用于记录用户的输入
```html
<form action="demo_form.php" method="post/get">
    <input type="text" name="email" size="40" maxlength="50">
    <input type="password">
    <input type="checkbox" checked="checked">
    <input type="radio" checked="checked">
    <input type="submit" value="Send">
    <input type="reset">
    <input type="hidden">

<select>
    <option>苹果</option>
    <option selected="selected">香蕉</option>
    <option>樱桃</option>
</select>

<textarea name="comment" rows="60" cols="20"></textarea>
 
</form>
```
实例见： https://www.runoob.com/html/html-forms.html
### Entities 实体
```html
&lt; <!--小于号-->
&gt; <!--大于号-->
&#169; <!--©-->
```