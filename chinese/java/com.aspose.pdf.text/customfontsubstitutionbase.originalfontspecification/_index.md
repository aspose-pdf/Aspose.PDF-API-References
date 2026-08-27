---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示原始字体规范。 </p> <hr> <p> 提供与原始字体相关的信息，例如，标志。还提供有助于检查是否会进行替换的标志。 </p>"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> 表示原始字体规范。 </p> <hr> <p> 提供与原始字体相关的信息，例如，标志。还提供一个标志，帮助检查是否会对该字体进行替换，并且用户可以覆盖默认的替换逻辑。 </p>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | 初始化新的 OriginalFontSpecification 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | 获取原始字体名称。 |
| [isEmbedded](#isEmbedded--) | 获取指示字体是否已嵌入的值。 |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> 获取指示替换是不可避免的值。 </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
初始化新的 OriginalFontSpecification 对象。

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

获取原始字体名称。

**Returns:**
字符串值

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

获取指示字体是否已嵌入的值。

**Returns:**
布尔值

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> 获取指示替换是不可避免的值。 </p>

**Returns:**
boolean value <hr> <p> 如果因为原始字体缺失或原始字体在某些任务上下文中无法使用而请求替换，则返回 true。如果用户忽略此标志并且未替换字体，则执行默认的字体替换过程。但这为用户提供了更改标准字体替换过程并为系统设置更好字体的机会。如果原始字体存在且有效，但允许用户替换，则返回 false。 </p>
