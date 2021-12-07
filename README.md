# miaoPhoenix
consumer experience analyst
这是带有 ~~删除线~~ 的文字
【语法】 在段落中填写 [TOC] （toc小写也可以）以显示各标题为结构的目录（大纲）导航。



## H1~H3(#的个数)[博客园只支持H1~3]
```
# H1
## H2
### H3
```
[TOC] 
# H1
## H2
### H3

## 斜体(一个\*斜体)，加粗(两个\*粗体)，删除线（两个\~）
```
**加粗内容** 其他内容 *斜体内容* ~~删除内容~~
```
**加粗内容** 其他内容 *斜体内容* ~~删除内容~~

## 引用(> or >>)、代码块(\```开头结尾)、分隔符(\---)、换行(空一行 或者 br标签 )、转义( \\ )
引用：
```
>引用 | 块注释
>从前有座山，山里有座庙
>>里面再来个引用
```
>引用 | 块注释
>从前有座山，山里有座庙
>>里面再来个引用
代码块：
以\```(反引号)开头
以\```(～下面的符合)结尾
如果要语法高亮就在\```后面加小写语言名,eg:html,css,javascript,python,cs(csharp)等等
```python
print("以 ```python开头，```结尾")
```

var infos_list = new List<object>() { "C#", "JavaScript" };

```csharp
var infos_list = new List<object>() { "C#", "JavaScript" };
```
分隔符：
```
---
```
---

换行：
```
<br/>
<br/>
<br/>
```
<br/>
<br/>
<br/>

转义字符
```
\<br/>
```
\<br/>

## HTML代码
直接写HTML就可以解析：
```html
<div>
    <code>
        print("mmd")
    </code>
</div>
```
<div>
    <code>
        print("mmd")
    </code>
</div>

## 超链接、图片、锚点跳转
超链接：
```
页面内打开：[超链接文字](url)
写法1：
汇总系列：[链接](https://www.cnblogs.com/dunitian/p/4822808.html#ai)
写法2：
汇总系列：<https://www.cnblogs.com/dunitian/p/4822808.html#ai>
```
