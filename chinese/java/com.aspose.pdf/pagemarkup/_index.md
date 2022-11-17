---
title: PageMarkup
second_title: 用于 Java API 参考的 Aspose.PDF
description: 由 MarkupSection 和 MarkupParagraph 的集合表示的页面标记。
type: docs
weight: 265
url: /zh/java/com.aspose.pdf/pagemarkup/
---
**遗产：**
java.lang.Object
```
public final class PageMarkup
```

由 MarkupSection 和 MarkupParagraph 的集合表示的页面标记。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNumber()](#getNumber--) | 获取处理后的页码。 |
| [getParagraphs()](#getParagraphs--) | 获取在页面上找到的 MarkupParagraph 的集合。 |
| [getRectangle()](#getRectangle--) | 获取处理后的页面矩形。 |
| [getSections()](#getSections--) | 获取在页面上找到的 MarkupSection 的集合。 |
| [getTextFragments()](#getTextFragments--) | 获取在页面上找到的 TextFragment 的集合。 |
| [hashCode()](#hashCode--) |  |
| [isMulticolumnParagraphsAllowed()](#isMulticolumnParagraphsAllowed--) | 获取或设置一个值，该值指示是否可以将下一节的起始文本行视为上一节最后一段的延续。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMulticolumnParagraphsAllowed(boolean value)](#setMulticolumnParagraphsAllowed-boolean-) | 获取或设置一个值，该值指示是否可以将下一节的起始文本行视为上一节最后一段的延续。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getNumber() {#getNumber--}
```
public int getNumber()
```


获取处理后的页码。

**退货：**
int - 整数值
### getParagraphs() {#getParagraphs--}
```
public List<MarkupParagraph> getParagraphs()
```


获取在页面上找到的 MarkupParagraph 的集合。

**退货：**
java.util.List<com.aspose.pdf.MarkupParagraph> - MarkupParagraph 实例列表
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取处理后的页面矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getSections() {#getSections--}
```
public List<MarkupSection> getSections()
```


获取在页面上找到的 MarkupSection 的集合。

**退货：**
java.util.List<com.aspose.pdf.MarkupSection> - MarkupSection 实例列表
### getTextFragments() {#getTextFragments--}
```
public List<TextFragment> getTextFragments()
```


获取在页面上找到的 TextFragment 的集合。

--------------------

TextFragment 对象提供对搜索出现文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字体大小、颜色等）。

**退货：**
java.util.List<com.aspose.pdf.TextFragment> - TextFragment 实例列表
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

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
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
