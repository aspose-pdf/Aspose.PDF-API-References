---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Aspose.PDF for Java API 参考"
description: "表示将字体替换为系统字体的字体替换策略类。"
type: docs
weight: 110
url: /zh/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

表示将字体替换为系统字体的字体替换策略类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | 初始化 {@code SystemFontsSubstitution} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | 获取或设置默认的替换字体。当未找到其他有效替换且初始字体属于目标替换类别 ({@code FontCategories}) 时使用该字体。 |
| [getFontCategories](#getFontCategories--) | 获取或设置应使用系统字体进行替换的字体类别。 |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | 获取或设置默认的替换字体。当未找到其他有效替换且初始字体属于目标替换类别 ({@code FontCategories}) 时使用该字体。 |
| [setFontCategories](#setFontCategories-int-) | 获取或设置应使用系统字体进行替换的字体类别。 |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

初始化 {@code SystemFontsSubstitution} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontCategories |  | 目标字体类别，以使用系统字体进行替换 |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

获取或设置默认的替换字体。当未找到其他有效替换且初始字体属于目标替换类别 ({@code FontCategories}) 时使用该字体。

**Returns:**
Font 对象

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

获取或设置应使用系统字体进行替换的字体类别。

**Returns:**
SubstitutionFontCategories 元素 @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
获取或设置默认的替换字体。当未找到其他有效替换且初始字体属于目标替换类别 ({@code FontCategories}) 时使用该字体。

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

获取或设置应使用系统字体进行替换的字体类别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | SubstitutionFontCategories 元素 @see SubstitutionFontCategories |
