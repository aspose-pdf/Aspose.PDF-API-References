---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一个基于字体大小处理标题级别的类。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

表示一个基于字体大小处理标题级别的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | 创建 HeadingLevels 类的新实例。 |
| [HeadingLevels](#HeadingLevels-double-) | 创建 HeadingLevels 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | 添加标题级别。 |
| [estimateLevel](#estimateLevel-double-) | 估计可能的标题级别。如果在级别列表中未找到 fontSize，则返回最接近该字体大小值的级别。如果 fontSize 超出指定的最小和最大标题级别范围，方法将返回 false。 |
| [findLevel](#findLevel-double-int:A-) | 查找对应 fontSize 的级别。寻找精确匹配。 |
| [getAllLevels](#getAllLevels--) | 获取所有标题级别。 |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

创建 HeadingLevels 类的新实例。

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

创建 HeadingLevels 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold |  | 用于比较字体大小的阈值。在阈值范围内，标题级别相同。阈值的默认值为 0.01。 |

### addLevels {#addLevels-java.lang.Iterable-}
添加标题级别。

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

估计可能的标题级别。如果在级别列表中未找到 fontSize，则返回最接近该字体大小值的级别。如果 fontSize 超出指定的最小和最大标题级别范围，方法将返回 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontSize |  | 字体大小。 |

**Returns:**
标题级别。

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

查找对应 fontSize 的级别。寻找精确匹配。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontSize |  | 字体大小。 |
| level |  | 给定字体大小对应的标题级别。 |

**Returns:**
如果 fontSize 不在指定范围内，则返回 False。

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

获取所有标题级别。

**Returns:**
IEnumerable 的 Double
