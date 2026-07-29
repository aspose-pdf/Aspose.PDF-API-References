---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本搜索选项"
type: docs
weight: 5290
url: /zh/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

表示文本搜索选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | 初始化 {@code TextSearchOptions} 对象的新实例。指定正则表达式使用模式。 |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | 初始化 TextSearchOptions 对象的新实例。指定限定搜索文本的矩形。 |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | 初始化 TextSearchOptions 对象的新实例。指定限定搜索文本的矩形以及正则表达式使用模式。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | 获取或设置其边界排除搜索文本的矩形。 |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | 获取或设置一个指示，指示文本（片段）吸收器是否忽略因缺少字体而产生的错误。true - 表示将忽略缺少字体的错误。引用了不正确资源的文本段将在处理期间被跳过。false（默认） - 缺少字体错误将通过抛出异常终止处理。 |
| [getLimitToPageBounds](#getLimitToPageBounds--) | 获取指示，指示文本是否在页面边界内进行搜索。 |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | 获取或设置一个指示，指示文本提取（解码）错误是否会记录在文本（片段）吸收器中。true - 表示会记录文本提取（解码）错误，这可能会降低性能。false（默认） - 不记录错误。 |
| [getRectangle](#getRectangle--) | 获取限定搜索文本的矩形。如果需要限定文本提取或文本替换区域，可使用此属性。 |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | 获取或设置一个值，允许在文本搜索期间搜索与文本相关的图形（下划线、背景等）。true - 将执行对文本相关图形的搜索（默认值）。false - 将忽略源文档中可能出现的图形元素。若出现性能问题或不需要处理下划线、背景或裁剪，可将其设为 false。 |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | 获取限制在页面上搜索指定数量的文本相关图形（下划线、背景等）的值。默认值为 250。若出现性能问题，可设置较小的值；若未找到某些图形元素，可尝试更大的值。 |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | 获取指示，指示文本是否使用字体引擎编码进行搜索。true - 表示将使用字体引擎编码（如果文本搜索因文档编码不完整而失败，可尝试此方式）。false - 表示将使用文档字体编码（默认值）。 |
| [isDotallMode](#isDotallMode--) | <p> 在 dotall 模式下，表达式 <tt>.</tt> 匹配任何字符，包括换行符。默认情况下，此表达式不匹配换行符。 |
| [isIgnoreShadowText](#isIgnoreShadowText--) | 获取或设置指示，指示搜索时是否忽略表示普通文本阴影的文本片段。true - 表示不会找到阴影文本（如果文本搜索在相近位置返回重复片段，可尝试此方式）。false - 表示阴影文本将与普通文本一起被找到（默认值）。 |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | 指示是否使用正则表达式 |
| [isSearchInAnnotations](#isSearchInAnnotations--) | 获取或设置一个值，允许在批注中搜索文本。true - 将在批注中搜索文本。false - 文本片段吸收器将不会解析批注中的文本。 |
| [setDotallMode](#setDotallMode-boolean-) | 启用 dotall 模式。<p> 在 dotall 模式下，表达式 <tt>.</tt> 匹配任何字符，包括换行符。默认情况下，此表达式不匹配换行符。 |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | 获取或设置其边界排除搜索文本的矩形。 |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | 获取或设置一个指示，指示文本（片段）吸收器是否忽略因缺少字体而产生的错误。true - 表示将忽略缺少字体的错误。引用了不正确资源的文本段将在处理期间被跳过。false（默认） - 缺少字体错误将通过抛出异常终止处理。 |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | 获取或设置指示，指示搜索时是否忽略表示普通文本阴影的文本片段。true - 表示不会找到阴影文本（如果文本搜索在相近位置返回重复片段，可尝试此方式）。false - 表示阴影文本将与普通文本一起被找到（默认值）。 |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | 设置指示，指示文本是否在页面边界内进行搜索。 |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | 获取或设置一个指示，指示文本提取（解码）错误是否会记录在文本（片段）吸收器中。true - 表示会记录文本提取（解码）错误，这可能会降低性能。false（默认） - 不记录错误。 |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | 设置限定搜索文本的矩形。如果需要限定文本提取或文本替换区域，可使用此属性。 |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | 指示是否使用正则表达式 |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | 获取或设置一个值，允许在文本搜索期间搜索与文本相关的图形（下划线、背景等）。true - 将执行对文本相关图形的搜索（默认值）。false - 将忽略源文档中可能出现的图形元素。若出现性能问题或不需要处理下划线、背景或裁剪，可将其设为 false。 |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | 获取或设置一个值，允许在批注中搜索文本。true - 将在批注中搜索文本。false - 文本片段吸收器将不会解析批注中的文本。 |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | 设置限制在页面上搜索指定数量的文本相关图形（下划线、背景等）的值。默认值为 250。若出现性能问题，可设置较小的值；若未找到某些图形元素，可尝试更大的值。 |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | 设置指示，指示文本是否使用字体引擎编码进行搜索。true - 表示将使用字体引擎编码（如果文本搜索因文档编码不完整而失败，可尝试此方式）。false - 表示将使用文档字体编码（默认值）。 |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

初始化 {@code TextSearchOptions} 对象的新实例。指定正则表达式使用模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isRegularExpressionUsed |  | 指示已使用正则表达式的值。 |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
初始化 TextSearchOptions 对象的新实例。指定限定搜索文本的矩形。

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
初始化 TextSearchOptions 对象的新实例。指定限定搜索文本的矩形以及正则表达式使用模式。

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

获取或设置其边界排除搜索文本的矩形。

**Returns:**
Rectangle 实例数组

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

获取或设置一个指示，指示文本（片段）吸收器是否忽略因缺少字体而产生的错误。true - 表示将忽略缺少字体的错误。引用了不正确资源的文本段将在处理期间被跳过。false（默认） - 缺少字体错误将通过抛出异常终止处理。

**Returns:**
布尔值

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

获取指示，指示文本是否在页面边界内进行搜索。

**Returns:**
布尔值

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

获取或设置一个指示，指示文本提取（解码）错误是否会记录在文本（片段）吸收器中。true - 表示会记录文本提取（解码）错误，这可能会降低性能。false（默认） - 不记录错误。

**Returns:**
布尔值

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取限定搜索文本的矩形。如果需要限定文本提取或文本替换区域，可使用此属性。

**Returns:**
矩形值

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

获取或设置一个值，允许在文本搜索期间搜索与文本相关的图形（下划线、背景等）。true - 将执行对文本相关图形的搜索（默认值）。false - 将忽略源文档中可能出现的图形元素。若出现性能问题或不需要处理下划线、背景或裁剪，可将其设为 false。

**Returns:**
布尔值

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

获取限制在页面上搜索指定数量的文本相关图形（下划线、背景等）的值。默认值为 250。若出现性能问题，可设置较小的值；若未找到某些图形元素，可尝试更大的值。

**Returns:**
int 值

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

获取指示，指示文本是否使用字体引擎编码进行搜索。true - 表示将使用字体引擎编码（如果文本搜索因文档编码不完整而失败，可尝试此方式）。false - 表示将使用文档字体编码（默认值）。

**Returns:**
布尔值

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> 在 dotall 模式下，表达式 <tt>.</tt> 匹配任何字符，包括换行符。默认情况下，此表达式不匹配换行符。

**Returns:**
布尔值

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

获取或设置指示，指示搜索时是否忽略表示普通文本阴影的文本片段。true - 表示不会找到阴影文本（如果文本搜索在相近位置返回重复片段，可尝试此方式）。false - 表示阴影文本将与普通文本一起被找到（默认值）。

**Returns:**
布尔值

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

指示是否使用正则表达式

**Returns:**
布尔值

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

获取或设置一个值，允许在批注中搜索文本。true - 将在批注中搜索文本。false - 文本片段吸收器将不会解析批注中的文本。

**Returns:**
布尔值

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

启用 dotall 模式。<p> 在 dotall 模式下，表达式 <tt>.</tt> 匹配任何字符，包括换行符。默认情况下，此表达式不匹配换行符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dotallMode |  | 布尔值 |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
获取或设置其边界排除搜索文本的矩形。

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

获取或设置一个指示，指示文本（片段）吸收器是否忽略因缺少字体而产生的错误。true - 表示将忽略缺少字体的错误。引用了不正确资源的文本段将在处理期间被跳过。false（默认） - 缺少字体错误将通过抛出异常终止处理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

获取或设置指示，指示搜索时是否忽略表示普通文本阴影的文本片段。true - 表示不会找到阴影文本（如果文本搜索在相近位置返回重复片段，可尝试此方式）。false - 表示阴影文本将与普通文本一起被找到（默认值）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

设置指示，指示文本是否在页面边界内进行搜索。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

获取或设置一个指示，指示文本提取（解码）错误是否会记录在文本（片段）吸收器中。true - 表示会记录文本提取（解码）错误，这可能会降低性能。false（默认） - 不记录错误。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
设置限定搜索文本的矩形。如果需要限定文本提取或文本替换区域，可使用此属性。

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

指示是否使用正则表达式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

获取或设置一个值，允许在文本搜索期间搜索与文本相关的图形（下划线、背景等）。true - 将执行对文本相关图形的搜索（默认值）。false - 将忽略源文档中可能出现的图形元素。若出现性能问题或不需要处理下划线、背景或裁剪，可将其设为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

获取或设置一个值，允许在批注中搜索文本。true - 将在批注中搜索文本。false - 文本片段吸收器将不会解析批注中的文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

设置限制在页面上搜索指定数量的文本相关图形（下划线、背景等）的值。默认值为 250。若出现性能问题，可设置较小的值；若未找到某些图形元素，可尝试更大的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

设置指示，指示文本是否使用字体引擎编码进行搜索。true - 表示将使用字体引擎编码（如果文本搜索因文档编码不完整而失败，可尝试此方式）。false - 表示将使用文档字体编码（默认值）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
