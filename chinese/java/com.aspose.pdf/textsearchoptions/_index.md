---
title: TextSearchOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文本搜索选项
type: docs
weight: 385
url: /zh/java/com.aspose.pdf/textsearchoptions/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextSearchOptions extends TextOptions
```

表示文本搜索选项
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextSearchOptions(boolean isRegularExpressionUsed)](#TextSearchOptions-boolean-) | 初始化 TextSearchOptions 对象的新实例。 |
| [TextSearchOptions(Rectangle rectangle)](#TextSearchOptions-com.aspose.pdf.Rectangle-) | 初始化 TextSearchOptions 对象的新实例。 |
| [TextSearchOptions(Rectangle rectangle, boolean isRegularExpressionUsed)](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | 初始化 TextSearchOptions 对象的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIgnoreResourceFontErrors()](#getIgnoreResourceFontErrors--) | 获取或设置与字体缺失相关的错误将被文本（片段）吸收器忽略的指示。 |
| [getLimitToPageBounds()](#getLimitToPageBounds--) | 获取在页面边界内搜索文本的指示。 |
| [getLogTextExtractionErrors()](#getLogTextExtractionErrors--) | 获取或设置文本提取（解码）错误将记录在文本（片段）吸收器中的指示。 true - 表示将记录文本提取（解码）错误。 |
| [getRectangle()](#getRectangle--) | 获取限定搜索文本的矩形。 |
| [getSearchForTextRelatedGraphics()](#getSearchForTextRelatedGraphics--) | 获取或设置允许在文本搜索期间搜索与文本相关的图形（下划线、背景等）的值。 |
| [getStoredGraphicElementsMaxCount()](#getStoredGraphicElementsMaxCount--) | 获取限制在页面上搜索指定数量元素的文本相关图形（下划线、背景等）的值。 |
| [getUseFontEngineEncoding()](#getUseFontEngineEncoding--) | 获取将使用字体引擎编码搜索文本的指示。 true - 表示将使用字体引擎编码（如果文本搜索因文档中的编码不完善而失败，请尝试此操作） false - 表示将使用文档字体编码（默认值） |
| [hashCode()](#hashCode--) |  |
| [isDotallMode()](#isDotallMode--) | 在 dotall 模式下，表达式 .匹配任何字符，包括行终止符。 |
| [isIgnoreShadowText()](#isIgnoreShadowText--) | 获取或设置表示普通文本阴影的文本片段在搜索期间将被忽略的指示。 true - 表示不会找到阴影文本（如果文本搜索在关闭位置返回重复的片段，请尝试此操作） false - 表示将找到阴影文本以及普通文本（默认值） |
| [isRegularExpressionUsed()](#isRegularExpressionUsed--) | 表示是否使用正则表达式 |
| [isSearchInAnnotations()](#isSearchInAnnotations--) | 获取或设置允许在 Annotations 中搜索文本的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDotallMode(boolean dotallMode)](#setDotallMode-boolean-) | 启用 dotall 模式。 |
| [setIgnoreResourceFontErrors(boolean value)](#setIgnoreResourceFontErrors-boolean-) | 获取或设置与字体缺失相关的错误将被文本（片段）吸收器忽略的指示。 |
| [setIgnoreShadowText(boolean value)](#setIgnoreShadowText-boolean-) | 获取或设置表示普通文本阴影的文本片段在搜索期间将被忽略的指示。 true - 表示不会找到阴影文本（如果文本搜索在关闭位置返回重复的片段，请尝试此操作） false - 表示将找到阴影文本以及普通文本（默认值） |
| [setLimitToPageBounds(boolean value)](#setLimitToPageBounds-boolean-) | 设置在页面边界内搜索文本的指示。 |
| [setLogTextExtractionErrors(boolean value)](#setLogTextExtractionErrors-boolean-) | 获取或设置文本提取（解码）错误将记录在文本（片段）吸收器中的指示。 true - 表示将记录文本提取（解码）错误。 |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | 设置限定搜索文本的矩形。 |
| [setRegularExpressionUsed(boolean value)](#setRegularExpressionUsed-boolean-) | 表示是否使用正则表达式 |
| [setSearchForTextRelatedGraphics(boolean value)](#setSearchForTextRelatedGraphics-boolean-) | 获取或设置允许在文本搜索期间搜索与文本相关的图形（下划线、背景等）的值。 |
| [setSearchInAnnotations(boolean value)](#setSearchInAnnotations-boolean-) | 获取或设置允许在 Annotations 中搜索文本的值。 |
| [setStoredGraphicElementsMaxCount(int value)](#setStoredGraphicElementsMaxCount-int-) | 设置限制在页面上搜索指定数量元素的文本相关图形（下划线、背景等）的值。 |
| [setUseFontEngineEncoding(boolean value)](#setUseFontEngineEncoding-boolean-) | 设置将使用字体引擎编码搜索文本的指示。 true - 表示将使用字体引擎编码（如果文本搜索因文档中的编码不完善而失败，请尝试此操作） false - 表示将使用文档字体编码（默认值） |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextSearchOptions(boolean isRegularExpressionUsed) {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```


初始化 TextSearchOptions 对象的新实例。指定正则表达式使用模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| isRegularExpressionUsed | boolean | 指示使用正则表达式的值。 |

### TextSearchOptions(Rectangle rectangle) {#TextSearchOptions-com.aspose.pdf.Rectangle-}
```
public TextSearchOptions(Rectangle rectangle)
```


初始化 TextSearchOptions 对象的新实例。指定分隔搜索文本的矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | 包含提取文本的矩形。 |

### TextSearchOptions(Rectangle rectangle, boolean isRegularExpressionUsed) {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
```
public TextSearchOptions(Rectangle rectangle, boolean isRegularExpressionUsed)
```


初始化 TextSearchOptions 对象的新实例。指定分隔搜索文本和正则表达式使用模式的矩形。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | 包含提取文本的矩形。 |
| isRegularExpressionUsed | boolean | 指示使用正则表达式的值。 |

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
### getIgnoreResourceFontErrors() {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```


获取或设置与字体缺失相关的错误将被文本（片段）吸收器忽略的指示。 true - 表示将忽略缺少字体的错误。引用不正确资源的文本段将在处理过程中被跳过。 false（默认）- 没有字体错误将通过抛出异常来终止处理。

**退货：**
boolean - 布尔值
### getLimitToPageBounds() {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```


获取在页面边界内搜索文本的指示。

**退货：**
boolean - 布尔值
### getLogTextExtractionErrors() {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```


获取或设置文本提取（解码）错误将记录在文本（片段）吸收器中的指示。 true - 表示将记录文本提取（解码）错误。它可能会降低性能。 false（默认）- 没有错误记录。

**退货：**
boolean - 布尔值
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取限定搜索文本的矩形。如果需要分隔文本提取或文本替换区域，则可以使用该属性。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) 矩形值
### getSearchForTextRelatedGraphics() {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```


获取或设置允许在文本搜索期间搜索与文本相关的图形（下划线、背景等）的值。 true - 将执行搜索与文本相关的图形（默认值）。 false - 源文档中可能出现的图形元素将被忽略。在出现性能问题或不需要处理下划线、背景或裁剪时设置此项。

**退货：**
boolean - 布尔值
### getStoredGraphicElementsMaxCount() {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```


获取限制在页面上搜索指定数量元素的文本相关图形（下划线、背景等）的值。默认值为 250。在性能问题的情况下设置较小的值，在找不到某些图形元素的情况下尝试较大的值。

**退货：**
int - 整数值
### getUseFontEngineEncoding() {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```


获取将使用字体引擎编码搜索文本的指示。 true - 表示将使用字体引擎编码（如果文本搜索因文档中的编码不完善而失败，请尝试此操作） false - 表示将使用文档字体编码（默认值）

**退货：**
boolean - 布尔值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isDotallMode() {#isDotallMode--}
```
public static boolean isDotallMode()
```


在 dotall 模式下，表达式 .匹配任何字符，包括行终止符。默认情况下，此表达式不匹配行终止符。

**退货：**
boolean - 布尔值
### isIgnoreShadowText() {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```


获取或设置表示普通文本阴影的文本片段在搜索期间将被忽略的指示。 true - 表示不会找到阴影文本（如果文本搜索在关闭位置返回重复的片段，请尝试此操作） false - 表示将找到阴影文本以及普通文本（默认值）

**退货：**
boolean - 布尔值
### isRegularExpressionUsed() {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```


表示是否使用正则表达式

**退货：**
boolean - 布尔值
### isSearchInAnnotations() {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```


获取或设置允许在 Annotations 中搜索文本的值。 true - 将在注释中搜索文本。 false - Annotations 中的文本不会被 TextFragmentAbsorber 解析。

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




### setDotallMode(boolean dotallMode) {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```


启用 dotall 模式。

在 dotall 模式下，表达式 .匹配任何字符，包括行终止符。默认情况下，此表达式不匹配行终止符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| dotallMode | boolean | 布尔值 |

### setIgnoreResourceFontErrors(boolean value) {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```


获取或设置与字体缺失相关的错误将被文本（片段）吸收器忽略的指示。 true - 表示将忽略缺少字体的错误。引用不正确资源的文本段将在处理过程中被跳过。 false（默认）- 没有字体错误将通过抛出异常来终止处理。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setIgnoreShadowText(boolean value) {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```


获取或设置表示普通文本阴影的文本片段在搜索期间将被忽略的指示。 true - 表示不会找到阴影文本（如果文本搜索在关闭位置返回重复的片段，请尝试此操作） false - 表示将找到阴影文本以及普通文本（默认值）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLimitToPageBounds(boolean value) {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```


设置在页面边界内搜索文本的指示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLogTextExtractionErrors(boolean value) {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```


获取或设置文本提取（解码）错误将记录在文本（片段）吸收器中的指示。 true - 表示将记录文本提取（解码）错误。它可能会降低性能。 false（默认）- 没有错误记录。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


设置限定搜索文本的矩形。如果需要分隔文本提取或文本替换区域，则可以使用该属性。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### setRegularExpressionUsed(boolean value) {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```


表示是否使用正则表达式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSearchForTextRelatedGraphics(boolean value) {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```


获取或设置允许在文本搜索期间搜索与文本相关的图形（下划线、背景等）的值。 true - 将执行搜索与文本相关的图形（默认值）。 false - 源文档中可能出现的图形元素将被忽略。在出现性能问题或不需要处理下划线、背景或裁剪时设置此项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSearchInAnnotations(boolean value) {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```


获取或设置允许在 Annotations 中搜索文本的值。 true - 将在注释中搜索文本。 false - Annotations 中的文本不会被 TextFragmentAbsorber 解析。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setStoredGraphicElementsMaxCount(int value) {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```


设置限制在页面上搜索指定数量元素的文本相关图形（下划线、背景等）的值。默认值为 250。在性能问题的情况下设置较小的值，在找不到某些图形元素的情况下尝试较大的值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setUseFontEngineEncoding(boolean value) {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```


设置将使用字体引擎编码搜索文本的指示。 true - 表示将使用字体引擎编码（如果文本搜索因文档中的编码不完善而失败，请尝试此操作） false - 表示将使用文档字体编码（默认值）

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
