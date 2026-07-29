---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "描述文本编辑操作的选项。"
type: docs
weight: 4970
url: /zh/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

描述文本编辑操作的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | 使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * 初始化 {@code TextEditOptions} 对象的新实例，以用于指定的文本重新排列模式。 / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | 使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | 使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | 使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | 使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | 获取允许在添加或编辑文本时使用语言转换的值。true - 如有必要，将应用语言转换（默认值）。false - 将不应用语言转换。 |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | 获取编辑文本的裁剪路径处理模式。 |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | 获取定义字体替换场景行为的模式。 |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | 获取定义语言转换场景行为的模式。 |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | 获取在字体不包含所需字符时定义行为的模式。 |
| [getReplacementFont](#getReplacementFont--) | 获取或设置在用户字体不包含所需字符时用于替换的字体 |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> 获取或设置允许在源文档页面上搜索文本下划线的值。 <p> （已弃用）请改用 TextSearchOptions.SearchForTextRelatedGraphics。 </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | 设置允许在添加或编辑文本时使用语言转换的值。true - 如有必要将应用语言转换（默认值）。false - 将不应用语言转换。 |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | 获取编辑文本的裁剪路径处理模式。 |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | 设置定义字体替换场景行为的模式。 |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | 设置定义语言转换场景行为的模式。 |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | 设置在字体不包含所请求字符时的行为模式。 |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | 获取或设置在用户字体不包含所需字符时用于替换的字体 |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> 获取或设置允许在源文档页面上搜索文本下划线的值。 <p> （已弃用）请改用 TextSearchOptions.SearchForTextRelatedGraphics。 </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * 初始化 {@code TextEditOptions} 对象的新实例，以用于指定的文本重新排列模式。 / * / *

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
使用默认选项初始化 {@code TextEditOptions} 对象的新实例。NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

获取允许在添加或编辑文本时使用语言转换的值。true - 如有必要，将应用语言转换（默认值）。false - 将不应用语言转换。

**Returns:**
布尔值

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

获取编辑文本的裁剪路径处理模式。

**Returns:**
ClippingPathsProcessingMode 元素

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

获取定义字体替换场景行为的模式。

**Returns:**
FontReplace 值 @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

获取定义语言转换场景行为的模式。

**Returns:**
LanguageTransformation 值 @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

获取在字体不包含所需字符时定义行为的模式。

**Returns:**
NoCharacterAction 值 @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

获取或设置在用户字体不包含所需字符时用于替换的字体

**Returns:**
字体实例

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> 获取或设置允许在源文档页面上搜索文本下划线的值。 <p> （已弃用）请改用 TextSearchOptions.SearchForTextRelatedGraphics。 </p>

**Returns:**
布尔值

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

设置允许在添加或编辑文本时使用语言转换的值。true - 如有必要将应用语言转换（默认值）。false - 将不应用语言转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
获取编辑文本的裁剪路径处理模式。

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
设置定义字体替换场景行为的模式。

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
设置定义语言转换场景行为的模式。

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
设置在字体不包含所请求字符时的行为模式。

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
获取或设置在用户字体不包含所需字符时用于替换的字体

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> 获取或设置允许在源文档页面上搜索文本下划线的值。 <p> （已弃用）请改用 TextSearchOptions.SearchForTextRelatedGraphics。 </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
