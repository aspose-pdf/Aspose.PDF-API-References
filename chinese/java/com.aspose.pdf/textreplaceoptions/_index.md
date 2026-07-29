---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文本替换选项"
type: docs
weight: 5250
url: /zh/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

表示文本替换选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | 初始化 {@code TextReplaceOptions} 对象的新实例，使用默认的调整和范围：ReplaceAdjustment.None 和 Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | 初始化 {@code TextReplaceOptions} 对象的新实例，以用于指定的替换后操作。 |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | 初始化 {@code TextReplaceOptions} 对象的新实例，使用默认的调整和范围：ReplaceAdjustment.None 和 Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | 初始化 {@code TextReplaceOptions} 对象的新实例，使用默认的调整和范围：ReplaceAdjustment.None 和 Scope.REPLACE_FIRST |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | 获取或设置行间距的值，当强制进行替换调整以创建新文本行时使用。该值应为被替换文本字体大小的倍数。默认值为 1.2。 |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | 获取或设置用于调整字体大小以适应 {@code TextReplaceOptions.Rectangle} 定义的边界的策略（{@link #getRectangle}/{@link #setRectangle(Rectangle)}）。 |
| [getLeftAdjustment](#getLeftAdjustment--) | 获取使用 TextReplaceOptions 时替换文本的左侧位置调整：- ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | 获取或设置用于容纳替换后文本的矩形。 |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | 获取在文本片段替换后将执行的操作，使其更短。 |
| [getReplaceScope](#getReplaceScope--) | 获取应用替换文本操作的范围。 |
| [getRightAdjustment](#getRightAdjustment--) | 设置或获取使用 TextReplaceOptions 时替换文本的右侧位置调整：- ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | 获取或设置一个值，指示在文本替换后调整页面文本时是否忽略不同的段落。 |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | 获取或设置行间距的值，当强制进行替换调整以创建新文本行时使用。该值应为被替换文本字体大小的倍数。默认值为 1.2。 |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | 获取或设置用于调整字体大小以适应 TextReplaceOptions.Rectangle 定义的边界的策略（getRectangle() / setRectangle(Rectangle)）。 |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | 获取或设置一个值，指示在文本替换后调整页面文本时是否忽略不同的段落。 |
| [setLeftAdjustment](#setLeftAdjustment-double-) | 设置或获取使用 TextReplaceOptions 时替换文本的左侧位置调整：- ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | 获取或设置用于容纳替换后文本的矩形。 |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | 设置在文本片段替换后将执行的操作，以使其更短。 |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | 设置应用替换文本操作的范围。 |
| [setRightAdjustment](#setRightAdjustment-double-) | 设置使用 TextReplaceOptions 时替换文本的右侧位置调整：- ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

初始化 {@code TextReplaceOptions} 对象的新实例，使用默认的调整和范围：ReplaceAdjustment.None 和 Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

初始化 {@code TextReplaceOptions} 对象的新实例，以用于指定的替换后操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 调整 |  | ReplaceAdjustment 对象。 @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
初始化 {@code TextReplaceOptions} 对象的新实例，使用默认的调整和范围：ReplaceAdjustment.None 和 Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
初始化 {@code TextReplaceOptions} 对象的新实例，使用默认的调整和范围：ReplaceAdjustment.None 和 Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

获取或设置行间距的值，当强制进行替换调整以创建新文本行时使用。该值应为被替换文本字体大小的倍数。默认值为 1.2。

**Returns:**
double 值

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

获取或设置用于调整字体大小以适应 {@code TextReplaceOptions.Rectangle} 定义的边界的策略（{@link #getRectangle}/{@link #setRectangle(Rectangle)}）。

**Returns:**
FontSizeAdjustment 元素

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

获取使用 TextReplaceOptions 时替换文本的左侧位置调整：- ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double 值

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

获取或设置用于容纳替换后文本的矩形。

**Returns:**
Rectangle 实例

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

获取在文本片段替换后将执行的操作，使其更短。

**Returns:**
ReplaceAdjustment 元素 @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

获取应用替换文本操作的范围。

**Returns:**
int 值 @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

设置或获取使用 TextReplaceOptions 时替换文本的右侧位置调整：- ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double 值

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

获取或设置一个值，指示在文本替换后调整页面文本时是否忽略不同的段落。

**Returns:**
boolean 值

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

获取或设置行间距的值，当强制进行替换调整以创建新文本行时使用。该值应为被替换文本字体大小的倍数。默认值为 1.2。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
获取或设置用于调整字体大小以适应 TextReplaceOptions.Rectangle 定义的边界的策略（getRectangle() / setRectangle(Rectangle)）。

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

获取或设置一个值，指示在文本替换后调整页面文本时是否忽略不同的段落。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

设置或获取使用 TextReplaceOptions 时替换文本的左侧位置调整：- ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
获取或设置用于容纳替换后文本的矩形。

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

设置在文本片段替换后将执行的操作，以使其更短。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | ReplaceAdjustment 元素 @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
设置应用替换文本操作的范围。

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

设置使用 TextReplaceOptions 时替换文本的右侧位置调整：- ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值 |
