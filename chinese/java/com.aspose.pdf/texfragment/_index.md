---
title: TeXFragment
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 LaTeX 片段。
type: docs
weight: 356
url: /zh/java/com.aspose.pdf/texfragment/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.FormattedFragment](../../com.aspose.pdf/formattedfragment)
```
public class TeXFragment extends FormattedFragment
```

表示 LaTeX 片段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TeXFragment(String text)](#TeXFragment-java.lang.String-) | 初始化 HtmlFragment 类的新实例。 |
| [TeXFragment(String text, boolean removeIndents)](#TeXFragment-java.lang.String-boolean-) | 初始化 HtmlFragment 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆片段。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取段落的水平对齐方式 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getLatexLoadOptionsOfInstance()](#getLatexLoadOptionsOfInstance--) | 获取或设置将用于将 LaTeX 加载（和呈现）到该类实例中的 TeXLoadOptions。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getTeXLoadOptionsOfInstance()](#getTeXLoadOptionsOfInstance--) | 获取或设置将用于将 LaTeX 加载（和呈现）到该类实例中的 TeXLoadOptions。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取段落的垂直对齐方式 |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [hashCode()](#hashCode--) |  |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置段落的水平对齐方式 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置超链接（用于 pdf 生成器）。 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setLatexLoadOptionsOfInstance(TeXLoadOptions value)](#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | 获取或设置将用于将 LaTeX 加载（和呈现）到该类实例中的 TeXLoadOptions。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setTeXLoadOptionsOfInstance(TeXLoadOptions value)](#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-) | 获取或设置将用于将 LaTeX 加载（和呈现）到该类实例中的 LatexLoadOptions。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置段落的垂直对齐方式 |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TeXFragment(String text) {#TeXFragment-java.lang.String-}
```
public TeXFragment(String text)
```


初始化 HtmlFragment 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 片段文字 |

### TeXFragment(String text, boolean removeIndents) {#TeXFragment-java.lang.String-boolean-}
```
public TeXFragment(String text, boolean removeIndents)
```


初始化 HtmlFragment 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 片段文字 |
| removeIndents | boolean | 确定在排版 LaTeX 片段时是否不缩进 |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆片段。

**退货：**
java.lang.Object - 克隆片段。
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
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


获取片段超链接（用于 pdf 生成器）。

**退货：**
[Hyperlink](../../com.aspose.pdf/hyperlink) - 片段超链接（用于 pdf 生成器）。
### getLatexLoadOptionsOfInstance() {#getLatexLoadOptionsOfInstance--}
```
public final TeXLoadOptions getLatexLoadOptionsOfInstance()
```


获取或设置将用于将 LaTeX 加载（和呈现）到该类实例中的 TeXLoadOptions。请在需要为这个或那个实例使用特定设置导入 LaTeX 时使用它（当这个或那个实例应该为导入的 LaTeX 使用特定的 BasePath 或应该使用外部资源的特定加载程序时）如果参数是默认值（null），那么将使用标准的 LaTeX 加载选项。

**退货：**
[TeXLoadOptions](../../com.aspose.pdf/texloadoptions) - TeXLoadOptions 实例
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取段落的外边距（用于生成 pdf）

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getTeXLoadOptionsOfInstance() {#getTeXLoadOptionsOfInstance--}
```
public TeXLoadOptions getTeXLoadOptionsOfInstance()
```


获取或设置将用于将 LaTeX 加载（和呈现）到该类实例中的 TeXLoadOptions。请在需要为这个或那个实例使用特定设置导入 LaTeX 时使用它（当这个或那个实例应该为导入的 LaTeX 使用特定的 BasePath 或应该使用外部资源的特定加载程序时）如果参数是默认值（null），那么将使用标准的 LaTeX 加载选项。

**退货：**
[TeXLoadOptions](../../com.aspose.pdf/texloadoptions) - TeXLoadOptions 实例
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### setLatexLoadOptionsOfInstance(TeXLoadOptions value) {#setLatexLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
```
public final void setLatexLoadOptionsOfInstance(TeXLoadOptions value)
```


获取或设置将用于将 LaTeX 加载（和呈现）到该类实例中的 TeXLoadOptions。请在需要为这个或那个实例使用特定设置导入 LaTeX 时使用它（当这个或那个实例应该为导入的 LaTeX 使用特定的 BasePath 或应该使用外部资源的特定加载程序时）如果参数是默认值（null），那么将使用标准的 LaTeX 加载选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TeXLoadOptions](../../com.aspose.pdf/texloadoptions) | TeXLoadOptions 实例 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置段落的外边距（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setTeXLoadOptionsOfInstance(TeXLoadOptions value) {#setTeXLoadOptionsOfInstance-com.aspose.pdf.TeXLoadOptions-}
```
public void setTeXLoadOptionsOfInstance(TeXLoadOptions value)
```


获取或设置将用于将 LaTeX 加载（和呈现）到该类实例中的 LatexLoadOptions。请在需要为这个或那个实例使用特定设置导入 LaTeX 时使用它（当这个或那个实例应该为导入的 LaTeX 使用特定的 BasePath 或应该使用外部资源的特定加载程序时）如果参数是默认值（null），那么将使用标准的 LaTeX 加载选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TeXLoadOptions](../../com.aspose.pdf/texloadoptions) | TeXLoadOptions 实例 |

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
