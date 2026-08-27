---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Aspose.PDF for Java API 参考"
description: "表示文档中分页工件的抽象基类。"
type: docs
weight: 3460
url: /zh/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

表示文档中分页工件的抽象基类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEndPage](#getEndPage--) | 获取或设置工件的结束页码。该值必须大于或等于 0。如果设置的值小于 0，将会被调整为 0。默认值 0 表示没有结束页边界。 |
| [getStartPage](#getStartPage--) | 获取或设置工件的起始页码。该值必须大于或等于 1。如果设置的值小于 1，将会被调整为 1。 |
| [getSubset](#getSubset--) | 获取或设置工件适用的页面子集（例如，所有页面、偶数页、奇数页）。 |
| [setEndPage](#setEndPage-int-) | 获取或设置工件的结束页码。该值必须大于或等于 0。如果设置的值小于 0，将会被调整为 0。默认值 0 表示没有结束页边界。 |
| [setStartPage](#setStartPage-int-) | 获取或设置工件的起始页码。该值必须大于或等于 1。如果设置的值小于 1，将会被调整为 1。 |
| [setSubset](#setSubset-int-) | 获取或设置工件适用的页面子集（例如，所有页面、偶数页、奇数页）。 |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

获取或设置工件的结束页码。该值必须大于或等于 0。如果设置的值小于 0，将会被调整为 0。默认值 0 表示没有结束页边界。

**Returns:**
int 值

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

获取或设置工件的起始页码。该值必须大于或等于 1。如果设置的值小于 1，将会被调整为 1。

**Returns:**
int 值

### getSubset {#getSubset--}
```
public final int getSubset()
```

获取或设置工件适用的页面子集（例如，所有页面、偶数页、奇数页）。

**Returns:**
int 值

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

获取或设置工件的结束页码。该值必须大于或等于 0。如果设置的值小于 0，将会被调整为 0。默认值 0 表示没有结束页边界。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

获取或设置工件的起始页码。该值必须大于或等于 1。如果设置的值小于 1，将会被调整为 1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

获取或设置工件适用的页面子集（例如，所有页面、偶数页、奇数页）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
