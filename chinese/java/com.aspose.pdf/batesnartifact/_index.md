---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Aspose.PDF for Java API 参考"
description: "类描述 Bates 编号工件。"
type: docs
weight: 290
url: /zh/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

类描述 Bates 编号工件。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | 初始化 {@link BatesNArtifact} 类的新实例。此构造函数是内部的，并使用默认值创建一个页眉工件实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | 获取或设置 Bates 编号的位数。该值必须在 3 到 15（含）之间。如果设置的值小于 3，将调整为 3。如果设置的值大于 15，将调整为 15。默认值为 6。 |
| [getPrefix](#getPrefix--) | 获取或设置要添加到 Bates 编号的前缀。 |
| [getStartNumber](#getStartNumber--) | 获取或设置 Bates 编号的起始数字。该值必须大于或等于 1。如果设置的值小于 1，将调整为 1。 |
| [getSuffix](#getSuffix--) | 获取或设置要添加到 Bates 编号的后缀。 |
| [setNumberOfDigits](#setNumberOfDigits-int-) | 获取或设置 Bates 编号的位数。该值必须在 3 到 15（含）之间。如果设置的值小于 3，将调整为 3。如果设置的值大于 15，将调整为 15。默认值为 6。 |
| [setPrefix](#setPrefix-java.lang.String-) | 获取或设置要添加到 Bates 编号的前缀。 |
| [setStartNumber](#setStartNumber-int-) | 获取或设置 Bates 编号的起始数字。该值必须大于或等于 1。如果设置的值小于 1，将调整为 1。 |
| [setSuffix](#setSuffix-java.lang.String-) | 获取或设置要添加到 Bates 编号的后缀。 |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

初始化 {@link BatesNArtifact} 类的新实例。此构造函数是内部的，并使用默认值创建一个页眉工件实例。

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

获取或设置 Bates 编号的位数。该值必须在 3 到 15（含）之间。如果设置的值小于 3，将调整为 3。如果设置的值大于 15，将调整为 15。默认值为 6。

**Returns:**
int 值

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

获取或设置要添加到 Bates 编号的前缀。

**Returns:**
字符串值

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

获取或设置 Bates 编号的起始数字。该值必须大于或等于 1。如果设置的值小于 1，将调整为 1。

**Returns:**
int 值

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

获取或设置要添加到 Bates 编号的后缀。

**Returns:**
字符串值

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

获取或设置 Bates 编号的位数。该值必须在 3 到 15（含）之间。如果设置的值小于 3，将调整为 3。如果设置的值大于 15，将调整为 15。默认值为 6。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPrefix {#setPrefix-java.lang.String-}
获取或设置要添加到 Bates 编号的前缀。

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

获取或设置 Bates 编号的起始数字。该值必须大于或等于 1。如果设置的值小于 1，将调整为 1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setSuffix {#setSuffix-java.lang.String-}
获取或设置要添加到 Bates 编号的后缀。
