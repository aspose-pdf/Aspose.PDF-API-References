---
title: PaginationArtifact
second_title: Aspose.PDF for Java API Reference
description: Represents an abstract base class for pagination artifacts in a document.
type: docs
weight: 3460
url: /java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

Represents an abstract base class for pagination artifacts in a document.

## Methods

| Method | Description |
| --- | --- |
| [getEndPage](#getEndPage--) | Gets or sets the ending page number for the artifact. The value must be greater than or equal to 0. If a value less than 0 is set, it will be adjusted to 0. The default value of 0 means there are no end page boundaries. |
| [getStartPage](#getStartPage--) | Gets or sets the starting page number for the artifact. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1. |
| [getSubset](#getSubset--) | Gets or sets the subset of pages to which the artifact applies (e.g., all pages, even pages, odd pages). |
| [setEndPage](#setEndPage-int-) | Gets or sets the ending page number for the artifact. The value must be greater than or equal to 0. If a value less than 0 is set, it will be adjusted to 0. The default value of 0 means there are no end page boundaries. |
| [setStartPage](#setStartPage-int-) | Gets or sets the starting page number for the artifact. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1. |
| [setSubset](#setSubset-int-) | Gets or sets the subset of pages to which the artifact applies (e.g., all pages, even pages, odd pages). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

Gets or sets the ending page number for the artifact. The value must be greater than or equal to 0. If a value less than 0 is set, it will be adjusted to 0. The default value of 0 means there are no end page boundaries.

**Returns:**
int value

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

Gets or sets the starting page number for the artifact. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1.

**Returns:**
int value

### getSubset {#getSubset--}
```
public final int getSubset()
```

Gets or sets the subset of pages to which the artifact applies (e.g., all pages, even pages, odd pages).

**Returns:**
int value

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

Gets or sets the ending page number for the artifact. The value must be greater than or equal to 0. If a value less than 0 is set, it will be adjusted to 0. The default value of 0 means there are no end page boundaries.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

Gets or sets the starting page number for the artifact. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

Gets or sets the subset of pages to which the artifact applies (e.g., all pages, even pages, odd pages).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
