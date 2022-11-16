---
title: ParagraphAbsorber
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示页面结构对象（例如节和段落）的吸收器对象。
type: docs
weight: 269
url: /zh/java/com.aspose.pdf/paragraphabsorber/
---
**遗产：**
java.lang.Object
```
public class ParagraphAbsorber
```

表示页面结构对象（例如节和段落）的吸收器对象。执行文本部分和段落的搜索，并提供对在文本坐标空间中描述它的矩形和多边形的访问。还执行文本段搜索，并通过按结构元素分组的 TextFragments 集合提供对搜索结果的访问。

--------------------

该示例演示了如何在第一个 PDF 文档页面上找到每个段落的第一个文本段并将其突出显示。 // 打开文档 Document doc = new Document("input.pdf"); // 创建 ParagraphAbsorber 对象 ParagraphAbsorber absorber = new ParagraphAbsorber(); // 接受第一页的吸收器 absorber.visit(doc.getPages.get\ _项目（1））； // 获取第一页的标记对象 PageMarkup markup = absorber.getPageMarkups().get(0); // 遍历页面文本的结构元素以找到每个段落的第一个文本片段 for (MarkupSection section : markup.getSections())\ for (MarkupParagraph paragraph : section.getParagraphs())\{ TextFragment 片段 = paragraph.getFragments().get\ _项目（0）； // 更新文本属性 fragment.getTextState().setBackgroundColor (Color.getLightBlue());\ }\} // 保存文档 doc.save(GetOutputPath("output.pdf"));

--------------------

搜索完成后，ParagraphAbsorber.PageMarkups 集合将包含 PageMarkup 对象，该对象通过 MarkupSection 和 MarkupParagraph 的集合表示页面结构。 TextFragment 对象提供对搜索出现文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字体大小、颜色等）。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ParagraphAbsorber()](#ParagraphAbsorber--) | 初始化 ParagraphAbsorber 的新实例，该实例执行对文档或页面的部分/段落的搜索。 |
| [ParagraphAbsorber(int sectionsSearchDepth)](#ParagraphAbsorber-int-) | 初始化 ParagraphAbsorber 的新实例，该实例执行对文档或页面的部分/段落的搜索。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageMarkups()](#getPageMarkups--) | 获取已吸收的 PageMarkup 集合。 |
| [getSectionsSearchDepth()](#getSectionsSearchDepth--) | 获取或设置一个值，该值指示对结构的更精细元素执行顺序搜索的次数。 |
| [hashCode()](#hashCode--) |  |
| [isMulticolumnParagraphsAllowed()](#isMulticolumnParagraphsAllowed--) | 获取或设置一个值，该值指示是否可以将下一节的起始文本行视为上一节最后一段的延续。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMulticolumnParagraphsAllowed(boolean value)](#setMulticolumnParagraphsAllowed-boolean-) | 获取或设置一个值，该值指示是否可以将下一节的起始文本行视为上一节最后一段的延续。 |
| [setSectionsSearchDepth(int value)](#setSectionsSearchDepth-int-) | 获取或设置一个值，该值指示对结构的更精细元素执行顺序搜索的次数。 |
| [toString()](#toString--) |  |
| [visit(Document doc)](#visit-com.aspose.pdf.Document-) | 对指定的部分和段落执行搜索[Document](../../com.aspose.pdf/document). |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | 在指定的 Page 上执行搜索。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ParagraphAbsorber() {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```


初始化 ParagraphAbsorber 的新实例，该实例执行对文档或页面的部分/段落的搜索。

### ParagraphAbsorber(int sectionsSearchDepth) {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```


初始化 ParagraphAbsorber 的新实例，该实例执行对文档或页面的部分/段落的搜索。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sectionsSearchDepth | int | 将执行的对更精细结构元素的顺序搜索数。

--------------------

有关该参数的更多提示，请参阅 ParagraphAbsorber.SectionsSearchDepth 属性。

 ----------------------|

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getPageMarkups() {#getPageMarkups--}
```
public List<PageMarkup> getPageMarkups()
```


获取已吸收的 PageMarkup 集合。

**退货：**
java.util.List<com.aspose.pdf.PageMarkup> - PageMarkup 实例列表
### getSectionsSearchDepth() {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```


获取或设置一个值，该值指示对结构的更精细元素执行顺序搜索的次数。默认搜索深度为 3。这意味着对水平划分的部分（标题、段落等）进行三次搜索，对垂直划分的部分（列）进行三次搜索。

--------------------

增加此值可能会导致性能轻微下降，而搜索结果没有明显变化。减小该值可能会导致章节中的段落判断错误。如果您不想只获得页面结构的“粗略”元素，我们不建议将值设置为小于默认值。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isMulticolumnParagraphsAllowed() {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```


获取或设置一个值，该值指示是否可以将下一节的起始文本行视为上一节最后一段的延续。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMulticolumnParagraphsAllowed(boolean value) {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```


获取或设置一个值，该值指示是否可以将下一节的起始文本行视为上一节最后一段的延续。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSectionsSearchDepth(int value) {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```


获取或设置一个值，该值指示对结构的更精细元素执行顺序搜索的次数。默认搜索深度为 3。这意味着对水平划分的部分（标题、段落等）进行三次搜索，对垂直划分的部分（列）进行三次搜索。

--------------------

增加此值可能会导致性能轻微下降，而搜索结果没有明显变化。减小该值可能会导致章节中的段落判断错误。如果您不想只获得页面结构的“粗略”元素，我们不建议将值设置为小于默认值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### visit(Document doc) {#visit-com.aspose.pdf.Document-}
```
public void visit(Document doc)
```


对指定的部分和段落执行搜索[Document](../../com.aspose.pdf/document).

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| doc | [Document](../../com.aspose.pdf/document) | Pdf 文档对象。 |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


在指定的 Page 上执行搜索。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf 文档页面对象。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
