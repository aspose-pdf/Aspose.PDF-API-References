---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 html 片段。"
type: docs
weight: 1950
url: /zh/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

表示 html 片段。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | 初始化 HtmlFragment 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆 html 片段。 |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | 获取 HtmlLoadOptions，该选项将用于将 HTML 加载（并呈现）到此类实例中。当需要为此或该实例的 HTML 导入使用特定设置时请使用它（例如，当此或该实例应为导入的 HTML 使用特定 BasePath 或应使用特定的外部资源加载器）。如果参数为默认值（null），则使用标准的 HTML 加载选项。 |
| [getRectangle](#getRectangle--) | 获取 HtmlFragment 的矩形 |
| [getTextState](#getTextState--) | 获取或设置字体 |
| [isBreakWords](#isBreakWords--) | 获取或设置单词换行 |
| [isParagraphHasMargin](#isParagraphHasMargin--) | 获取或设置段落是否具有默认边距，否则边距为 0 |
| [setBreakWords](#setBreakWords-boolean-) | 获取或设置单词换行 |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | 设置将用于将 HTML 加载（并呈现）到此类实例中的 HtmlLoadOptions。当需要为此或该实例的 HTML 导入使用特定设置时请使用它（例如，当此或该实例应为导入的 HTML 使用特定 BasePath 或应使用特定的外部资源加载器）。如果参数为默认值（null），则使用标准的 HTML 加载选项。 |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | 获取或设置段落是否具有默认边距，否则边距为 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | 获取或设置字体 |

### HtmlFragment {#HtmlFragment-java.lang.String-}
初始化 HtmlFragment 类的新实例。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆 html 片段。

**Returns:**
已克隆 html 片段对象。

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

获取 HtmlLoadOptions，该选项将用于将 HTML 加载（并呈现）到此类实例中。当需要为此或该实例的 HTML 导入使用特定设置时请使用它（例如，当此或该实例应为导入的 HTML 使用特定 BasePath 或应使用特定的外部资源加载器）。如果参数为默认值（null），则使用标准的 HTML 加载选项。

**Returns:**
HtmlLoadOptions 值

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

获取 HtmlFragment 的矩形

**Returns:**
java.awt.geom.Rectangle2D.Float 实例

### getTextState {#getTextState--}
```
public TextState getTextState()
```

获取或设置字体

**Returns:**
TextState 对象

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

获取或设置单词换行

**Returns:**
布尔值

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

获取或设置段落是否具有默认边距，否则边距为 0

**Returns:**
布尔值

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

获取或设置单词换行

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
设置将用于将 HTML 加载（并呈现）到此类实例中的 HtmlLoadOptions。当需要为此或该实例的 HTML 导入使用特定设置时请使用它（例如，当此或该实例应为导入的 HTML 使用特定 BasePath 或应使用特定的外部资源加载器）。如果参数为默认值（null），则使用标准的 HTML 加载选项。

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

获取或设置段落是否具有默认边距，否则边距为 0

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
获取或设置字体
