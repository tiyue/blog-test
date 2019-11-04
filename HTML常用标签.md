# HTML常用标签
## a标签的用法
### herf属性
1. `<a href="//google.com">网址</a>`
2. `<a href="a/b/c">路径</a>`
3. `<a href="./index.html">引用HTML</a>`
4. `<a href="tel:1834561237">拨打电话</a>`
5. `<a href=".mailto:xxx@qq.com">打开邮箱</a>`
6. `<a href="#xxx">ID</a>`
7. `<a href="javascript: ;">查看</a>`
### target属性
1. `<a target="_blank">在新窗口打开</a>`
2. `<a target="_self">在当前窗口打开</a>`
3. `<a target="_top">在顶层窗口打开</a>`
4. `<a target="_parent">在当前窗口的上一级打开</a>`
## table标签的用法
1. `<table>表总标签</table>`
2. `<table>表头</table>`
3. `<tbody>表中部</tbody>`
4. `<tfoot>表尾</tfoot>`
5. `<tr>行</tr>`
6. `<td>数据</td>`
7. `<th>行头</th>`
### 属性
1. `table-layout= "auto/fixed";`自动控制、等宽列距
2.` border-collapse="collapse";`控制行与行合并
3. `border-spacing=0px;`行与行之间的距离
``` <style>
      table {
        width: 600px;
        border-collapse: collapse;
        border-spacing: 0px;
        table-layout: fixed;
      }
      td,
      th {
        border: 1px solid blue;
      }
    </style>
  <body>
    <table>
      <thead>
        <tr>
          <th>种类</th>
          <th>单价</th>
          <th>数量</th>
          <th>总价</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>苹果</th>
          <td>10</td>
          <td>10</td>
          <td>30</td>
        </tr>
        <tr>
          <th>梨子</th>
          <td>5</td>
          <td>5</td>
          <td>2</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <th>累计总价</th>
          <td>10</td>
          <td></td>
          <td></td>
        </tr>
      </tfoot>
    </table>
  </body>
</html>
```
---
## img的用法
> 作用：发起GET请求，获取图片
### 标签的属性
1. src：图片的地址
2. alt：图片加载失败时的代替文字
3. height：高度
4. width：宽度
### 事件
> onload/onerror：检测图片加载失败是否成功
## form
> 发get/post请求，刷新页面
### form标签属性
1. action:请求页面的地址
2. autocomplete：自动填充
3. method：请求方式更换为POST
4. target：选择刷新的页面
### 事件
> onsubmit
## input
### 标签属性
- input type="text";
- input type="color";颜色
- input type="password";
- input type="radio";单选（同组加name属性）
- input type="checkout";多选（同组加name属性）
- input type="file";
- input type="file multiple";多个文件
- input type="hidden";js传数据
- input type="textarea";多行文本
- input type="select" ```<option value=""></option>下拉框```
### 事件
onchange/onfocus/onblur
## 感想
发觉自己不会整理笔记，老是在一些莫名其妙的东西浪费时间。
