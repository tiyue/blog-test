
## HTML的起源
> HTML的首个公开描述出现于一个名为“HTML标签”的文件中，由蒂姆·伯纳斯-李于1991年底提及。它描述18个元素，包括HTML初始的、相对简单的设计。除了超链接标签外，其他设计都深受CERN内部一个以标准通用标记语言（SGML）为基础的文件格式SGMLguid的影响。这些元素在HTML 4中仍有11个存在。[HTML](https://zh.wikipedia.org/zh-cn/HTML)
---
##HTML的起手
```HTML
<!DOCTYPE html>
<html lang="Zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
---
## 常用的章节标签
1. 标题h1~h6    ```<h1></h1>```表标题的等级和大小
2.  章节section
3.  "article"表示文档、页面、应用或网站中的独立结构，其意在成为可独立分配的或可复用的结构
4. 段落p
5. 头部header
6. 脚部footer
7. 主要内容main
8. 旁支内容aside
9.  划分div
---
## 全局属性
1. class 规定元素的一个或多个类名（引用样式表中的类）
2. contenteditable 使属性可编辑
3.  hidden 使元素不可见
4. id 区分不同的内容和结构，唯一性
5. style  规定元素的行内 CSS 样式
6. tabindex  使元素处于Tab键可选状态
7.  title 规定有关元素的额外信息
---
## 常用标签
1.  ol+ li 无序列表
2. ul+ li 有序列表
3. dl+ dt+ dd   
```
<dl>
         <dt>描述的对象</dt>
         <dd>描述的内容</dd>
</dl>
```
4. pre  保留标签内的空格和换行
5. hr  分割线
6. br 换行
7. a 超链接
8. em 强调语气
9. strong 强调事物
10. code  等宽字体，和pre共同使用
11. quote  引用
12. blockquote 引用换行
---
