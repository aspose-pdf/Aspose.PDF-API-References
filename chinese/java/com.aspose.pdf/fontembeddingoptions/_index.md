---
title: "FontEmbeddingOptions"
linktitle: "FontEmbeddingOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "PDF/A 标准要求所有字体必须嵌入文档。此类包含在某些字体无法嵌入（因为该字体缺失）时的标志。"
type: docs
weight: 1680
url: /zh/java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

PDF/A 标准要求所有字体必须嵌入文档中。此类包含在某些字体因目标电脑上缺失而无法嵌入的情况下使用的标志。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | 初始化 {@link FontEmbeddingOptions} 类的新实例。此构造函数将 {@code UseDefaultSubstitution}（{@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}）属性的默认值设置为 {@code }。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | 指示是否使用默认字体替代策略来替换非嵌入式字体。默认值为 false； |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | 指示是否使用默认字体替代策略来替换非嵌入式字体。默认值为 false； |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

初始化 {@link FontEmbeddingOptions} 类的新实例。此构造函数将 {@code UseDefaultSubstitution}（{@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}）属性的默认值设置为 {@code }。

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

指示是否使用默认字体替代策略来替换非嵌入式字体。默认值为 false；

**Returns:**
布尔值

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

指示是否使用默认字体替代策略来替换非嵌入式字体。默认值为 false；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
