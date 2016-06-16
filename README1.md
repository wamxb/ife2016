[TOC]

# html5 标签列表

## 章节

| Element     | Description                         |
| ----------- | ----------------------------------- |
| `<section>` | 定义文档中的一个章节                          |
| `<article>` | 定义可以独立于内容其余部分的完整独立内容块               |
| `<aside>`   | 定义和页面内容联度比较低的内容——如果被删除，剩下的内容任然很合理   |
| `<header>`  | 定义页面或章节的头部，经常包含 logo,页面标题和导航性的目录    |
| `<footer>`  | 定义页面或章节的尾部。经常宝航版权信息，法律信息链接和反馈建议用的地址 |
| `<address>` | 定义包含联系信息的一个章节                       |
| `<main>`    | 定义文档中主要或重要的内容                       |

## 组织内容

| Element            | Description         |
| ------------------ | ------------------- |
| `<blockquote>`     | 代表引用其他来源的内容         |
| `<dl>`             | 定义一个定义列表（一系列术语和其定义） |
| `<dt>`             | 代表一个由下一个`<dd>`定义的术语 |
| `<dd>`             | 代表出现在它之前术语的定义       |
| **`<figure>`**     | 代表一个和文档有关的图例        |
| **`<figcaption>`** | 代表一个图例的说明           |

## 文字形式

| Element    | Description                             |
| ---------- | --------------------------------------- |
| `<em>`     | 代表 *强调*文字                               |
| `<strong>` | 代表 **特别重要**文字                           |
| `<small>`  | 代表 注释，如免责声明，版权声明等，对理解文档不重要              |
| `<s>`      | 代表 不准确或不相关的内容                           |
| `<cite>`   | 代表 作品标题                                 |
| `<q>`      | 代表 内联的引用                                |
| `<abbr>`   | 代表 *省略*或*缩写*， 其完整内容在 `title` 属性中        |
| `<time>`   | 代表 *日期*和*时间*；机器可读的等价形式通过 `datetime`属性定义 |
| `<i>`      | 代表一段*不同性质*的文字，如技术术语，外文短语等               |
| `<b>`      | 代表 一段*需要被关注*的文字                         |
| `<u>`      | 代表 一段需要*下划线呈现*的文本注释，如标记处拼写错误的文字等        |
| `<mark>`   | 代表一段需要被高亮的*引用*文字                        |

## 嵌入内容

| Element    | Description                   |
| ---------- | ----------------------------- |
| `<embed>`  | 代表一个*嵌入*的外部资源，如应用程序或交互内容      |
| `<object>` | 代表一个 *外部资源* ，如图片、HTML 子文档、插件等 |
| `<param>`  | 代表 `<object>` 元素所指定的插件的 *参数*  |
| `<map>`    | 与 `<area>` 元素共同定义 *图像映射* 区域   |
| `<area>`   | 与 `<map>` 元素共同定义 *图像映射* 区域    |
| `<math>`   | 定义一段 *数学公式*                   |

## 表格

| Element      | Description     |
| ------------ | --------------- |
| `<caption>`  | 代表 *表格的标题*      |
| `<colgroup>` | 代表表格中一组 *单列或多列* |
| `<col>`      | 代表表格中的 *列*      |

## 表单

| Element      | Description               |
| ------------ | ------------------------- |
| `<fieldset>` | 代表 *控件组*                  |
| `<legend>`   | 代表 `<fieldset>` 控件组的 *标题* |
| `<optgroup>` | 代表一个 *选项分组*               |
| `<output>`   | 代表 *计算值*                  |
| `<progress>` | 代表 *进度条*                 |
| `<meter>`    | 代表 *滑动条*                  |

## 交互元素

| Element      | Description                    |
| ------------ | ------------------------------ |
| `<details> ` | 代表一个用户可以(点击)获取额外信息或控件的 *小部件*   |
| `<summary>`  | 代表 `<details>` 元素的 *综述* 或 *标题* |
| `<menuitem>` | 代表一个用户可以点击的菜单项                 |
| `<menu>`     | 代表菜单                           |

```html

<style type="text/css">
    table {
        border-collapse: collapse;
        border-spacing: 0;
        width: 100%;
    }
    .column1 { width: 10%; border: 1px solid red; }
    .column2 { width: 90%; border: 1px solid darkcyan; }
</style>
<table>
    <colgroup>
        <col class="column1">
        <col class="column2">
    </colgroup>
    <thead>
    <tr>
        <th>first name</th>
        <th>last name</th>
    </tr>
    </thead>
    <tbody>
    <tr>
        <td>John</td>
        <td>Doe</td>
    </tr>
    <tr>
        <td>Jane</td>
        <td>Doe</td>
    </tr>
    </tbody>
</table>

<form oninput="result.value=parseInt(a.value)+parseInt(b.value)">
    <input type="range" name="b" value="50"/> +
    <input type="number" name="a" value="10"/> =
    <output name="result"></output>
</form>

<!--设置high,颜色变红-->
<p>He got a <meter low="69" high="80" min="0" max="100" value="10">B</meter> on the exam.</p>
```

https://developer.mozilla.org/zh-CN/docs/Web/Guide/HTML/HTML5/HTML5_element_list
