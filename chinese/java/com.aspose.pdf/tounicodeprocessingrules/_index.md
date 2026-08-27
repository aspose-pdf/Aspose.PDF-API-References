---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF for Java API 参考"
description: "此类描述了可用于解决 Adobe Preflight 错误 \"Text cannot be mapped to Unicode\" 的规则。"
type: docs
weight: 5380
url: /zh/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

此类描述可用于解决 Adobe Preflight 错误 "Text cannot be mapped to Unicode" 的规则。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | 初始化 {@link ToUnicodeProcessingRules} 类的新实例。 |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | 使用指定的移除 CMap 名称中空格的选项，初始化 {@link ToUnicodeProcessingRules} 类的新实例。 |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | 使用指定的选项，初始化 {@link ToUnicodeProcessingRules} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | 某些字体未提供某些文本符号的 Unicode 信息。这种信息缺失会导致错误 "Text cannot be mapped to Unicode"。使用此标志可将未链接的符号映射为 Unicode "空格"(代码 32)。 |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | 某些字体的 ToUnicode 字符码映射名称中包含空格。这些空格可能导致 Unicode 文本映射错误。此标志用于从 ToUnicode 字符码映射名称中移除空格。默认值为 false。 |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | 某些字体未提供某些文本符号的 Unicode 信息。这种信息缺失会导致错误 "Text cannot be mapped to Unicode"。使用此标志可将未链接的符号映射为 Unicode "空格"(代码 32)。 |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | 某些字体的 ToUnicode 字符码映射名称中包含空格。这些空格可能导致 Unicode 文本映射错误。此标志用于从 ToUnicode 字符码映射名称中移除空格。默认值为 false。 |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

初始化 {@link ToUnicodeProcessingRules} 类的新实例。

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

使用指定的移除 CMap 名称中空格的选项，初始化 {@link ToUnicodeProcessingRules} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| removeSpaces |  | 一个布尔值，指示是否从 CMap 名称中移除空格。 |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

使用指定的选项，初始化 {@link ToUnicodeProcessingRules} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| removeSpaces |  | 指示是否应从 CMap 名称中移除空格。 |
| mapNonLinkedUnicodesOnSpace |  | 指示是否应将未链接的 Unicode 符号映射为空格。 |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

某些字体未提供某些文本符号的 Unicode 信息。这种信息缺失会导致错误 "Text cannot be mapped to Unicode"。使用此标志可将未链接的符号映射为 Unicode "空格"(代码 32)。

**Returns:**
布尔值

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

某些字体的 ToUnicode 字符码映射名称中包含空格。这些空格可能导致 Unicode 文本映射错误。此标志用于从 ToUnicode 字符码映射名称中移除空格。默认值为 false。

**Returns:**
布尔值

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

某些字体未提供某些文本符号的 Unicode 信息。这种信息缺失会导致错误 "Text cannot be mapped to Unicode"。使用此标志可将未链接的符号映射为 Unicode "空格"(代码 32)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

某些字体的 ToUnicode 字符码映射名称中包含空格。这些空格可能导致 Unicode 文本映射错误。此标志用于从 ToUnicode 字符码映射名称中移除空格。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
