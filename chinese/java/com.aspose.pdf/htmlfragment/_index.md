---
title: HtmlFragment
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 html 片段。
type: docs
weight: 157
url: /zh/java/com.aspose.pdf/htmlfragment/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.FormattedFragment](../../com.aspose.pdf/formattedfragment)
```
public final class HtmlFragment extends FormattedFragment
```

表示 html 片段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlFragment(String text)](#HtmlFragment-java.lang.String-) | 初始化 HtmlFragment 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆 html 片段。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取段落的水平对齐方式 |
| [getHtmlLoadOptions()](#getHtmlLoadOptions--) | 获取将用于将 HTML 加载（和呈现）到该类实例中的 HtmlLoadOptions。 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getRectangle()](#getRectangle--) | 获取 HtmlFragment 的矩形 |
| [getTextState()](#getTextState--) | 获取或设置字体 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取段落的垂直对齐方式 |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [hashCode()](#hashCode--) |  |
| [isBreakWords()](#isBreakWords--) | 获取或设置分词 |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [isParagraphHasMargin()](#isParagraphHasMargin--) | 获取或设置段落是否有默认边距，否则边距为 0 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBreakWords(boolean value)](#setBreakWords-boolean-) | 获取或设置分词 |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置段落的水平对齐方式 |
| [setHtmlLoadOptions(HtmlLoadOptions value)](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | 设置将用于将 HTML 加载（和呈现）到该类实例中的 HtmlLoadOptions。 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置超链接（用于 pdf 生成器）。 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setParagraphHasMargin(boolean value)](#setParagraphHasMargin-boolean-) | 获取或设置段落是否有默认边距，否则边距为 0 |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | 获取或设置字体 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置段落的垂直对齐方式 |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlFragment(String text) {#HtmlFragment-java.lang.String-}
```
public HtmlFragment(String text)
```


初始化 HtmlFragment 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 片段文字 |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆 html 片段。

**退货：**
java.lang.Object - 克隆的 html 片段对象。
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
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取段落的水平对齐方式

**退货：**
int - HorizontalAlignment 值
### getHtmlLoadOptions() {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```


获取将用于将 HTML 加载（和呈现）到该类实例中的 HtmlLoadOptions。请在需要为这个或那个实例使用特定设置导入 HTML 时使用它（当这个或那个实例应该使用特定的 BasePath 导入 HTML 或应该使用特定的外部资源加载器时）如果参数是默认值（null），那么将使用标准的 HTML 加载选项。

**退货：**
[HtmlLoadOptions](../../com.aspose.pdf/htmlloadoptions) - HtmlLoadOptions 值
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


获取片段超链接（用于 pdf 生成器）。

**退货：**
[Hyperlink](../../com.aspose.pdf/hyperlink) - 片段超链接（用于 pdf 生成器）。
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取段落的外边距（用于生成 pdf）

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```


获取 HtmlFragment 的矩形

**退货：**
java.awt.geom.Rectangle2D.Float - java.awt.geom.Rectangle2D.Float 实例
### getTextState() {#getTextState--}
```
public TextState getTextState()
```


获取或设置字体

**退货：**
[TextState](../../com.aspose.pdf/textstate) 文本状态对象
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取段落的垂直对齐方式

**退货：**
int - VerticalAlignment 元素
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


获取一个 int 值，该值指示图形的 Z 顺序。具有较大 ZIndex 的图形将被放置在具有较小 ZIndex 的图形之上。 ZIndex 可以是负数。具有负 ZIndex 的图形将放置在页面中文本的后面。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isBreakWords() {#isBreakWords--}
```
public final boolean isBreakWords()
```


获取或设置分词

**退货：**
boolean - 布尔值
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


获取一个段落是内联的。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


获取强制此段落在新页面生成的 bool 值。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isParagraphHasMargin() {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```


获取或设置段落是否有默认边距，否则边距为 0

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




### setBreakWords(boolean value) {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```


获取或设置分词

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置段落的水平对齐方式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setHtmlLoadOptions(HtmlLoadOptions value) {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
```
public void setHtmlLoadOptions(HtmlLoadOptions value)
```


设置将用于将 HTML 加载（和呈现）到该类实例中的 HtmlLoadOptions。请在需要为这个或那个实例使用特定设置导入 HTML 时使用它（当这个或那个实例应该使用特定的 BasePath 导入 HTML 或应该使用特定的外部资源加载器时）如果参数是默认值（null），那么将使用标准的 HTML 加载选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [HtmlLoadOptions](../../com.aspose.pdf/htmlloadoptions) | HtmlLoadOptions 值 |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


设置超链接（用于 pdf 生成器）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | 超链接（用于 pdf 生成器）。 |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


设置一个段落是内联的。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


设置一个布尔值，强制此段落在新页面生成。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置段落的外边距（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setParagraphHasMargin(boolean value) {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```


获取或设置段落是否有默认边距，否则边距为 0

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public void setTextState(TextState value)
```


获取或设置字体

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态对象 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


设置段落的垂直对齐方式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


设置一个指示图形 Z 顺序的 int 值。具有较大 ZIndex 的图形将被放置在具有较小 ZIndex 的图形之上。 ZIndex 可以是负数。具有负 ZIndex 的图形将放置在页面中文本的后面。

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
