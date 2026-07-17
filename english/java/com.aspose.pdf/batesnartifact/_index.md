---
title: BatesNArtifact
linktitle: BatesNArtifact
second_title: Aspose.PDF for Java API Reference
description: Class describes Bates Numbering artifact.
type: docs
weight: 290
url: /java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

Class describes Bates Numbering artifact.

## Constructors

| Constructor | Description |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Initializes a new instance of the {@link BatesNArtifact} class. This constructor is internal and creates a header artifact instance with default values. |

## Methods

| Method | Description |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Gets or sets the number of digits for Bates numbering. The value must be between 3 and 15 inclusive. If a value less than 3 is set, it will be adjusted to 3. If a value greater than 15 is set, it will be adjusted to 15. The default value is 6. |
| [getPrefix](#getPrefix--) | Gets or sets the prefix to be added to the Bates number. |
| [getStartNumber](#getStartNumber--) | Gets or sets the starting number for Bates numbering. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1. |
| [getSuffix](#getSuffix--) | Gets or sets the suffix to be added to the Bates number. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Gets or sets the number of digits for Bates numbering. The value must be between 3 and 15 inclusive. If a value less than 3 is set, it will be adjusted to 3. If a value greater than 15 is set, it will be adjusted to 15. The default value is 6. |
| [setPrefix](#setPrefix-java.lang.String-) | Gets or sets the prefix to be added to the Bates number. |
| [setStartNumber](#setStartNumber-int-) | Gets or sets the starting number for Bates numbering. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1. |
| [setSuffix](#setSuffix-java.lang.String-) | Gets or sets the suffix to be added to the Bates number. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Initializes a new instance of the {@link BatesNArtifact} class. This constructor is internal and creates a header artifact instance with default values.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Gets or sets the number of digits for Bates numbering. The value must be between 3 and 15 inclusive. If a value less than 3 is set, it will be adjusted to 3. If a value greater than 15 is set, it will be adjusted to 15. The default value is 6.

**Returns:**
int value

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Gets or sets the prefix to be added to the Bates number.

**Returns:**
String value

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Gets or sets the starting number for Bates numbering. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1.

**Returns:**
int value

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Gets or sets the suffix to be added to the Bates number.

**Returns:**
String value

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Gets or sets the number of digits for Bates numbering. The value must be between 3 and 15 inclusive. If a value less than 3 is set, it will be adjusted to 3. If a value greater than 15 is set, it will be adjusted to 15. The default value is 6.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPrefix {#setPrefix-java.lang.String-}
Gets or sets the prefix to be added to the Bates number.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Gets or sets the starting number for Bates numbering. The value must be greater than or equal to 1. If a value less than 1 is set, it will be adjusted to 1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setSuffix {#setSuffix-java.lang.String-}
Gets or sets the suffix to be added to the Bates number.
