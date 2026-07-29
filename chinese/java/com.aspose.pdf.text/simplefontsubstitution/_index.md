---
title: "SimpleFontSubstitution"
linktitle: "SimpleFontSubstitution"
second_title: "Aspose.PDF for Java API 参考"
description: "表示简单字体替换策略的类。"
type: docs
weight: 90
url: /zh/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

表示简单字体替换策略的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | 初始化 {@code SimpleFontSubstitution} 类的新实例。 |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | 初始化 {@code SimpleFontSubstitution} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | 获取应使用 {@code SubstitutionFontName} 替换的原始字体名称 |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | 返回 unicode 替换 |
| [getSubstitutionFontName](#getSubstitutionFontName--) | 获取应替换 {@code OriginalFontName} 的字体名称 |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
初始化 {@code SimpleFontSubstitution} 类的新实例。

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
初始化 {@code SimpleFontSubstitution} 类的新实例。

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

获取应使用 {@code SubstitutionFontName} 替换的原始字体名称

**Returns:**
字符串值

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

返回 unicode 替换

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unicode |  | char 值 |

**Returns:**
char 值

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

获取应替换 {@code OriginalFontName} 的字体名称

**Returns:**
字符串值
