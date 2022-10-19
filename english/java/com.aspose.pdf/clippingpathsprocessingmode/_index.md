---
title: TextEditOptions.ClippingPathsProcessingMode
second_title: Aspose.PDF for Java API Reference
description: Clipping path processing modes
type: docs
weight: 10
url: /java/com.aspose.pdf/texteditoptions.clippingpathsprocessingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class TextEditOptions.ClippingPathsProcessingMode extends System.Enum
```

Clipping path processing modes
## Fields

| Field | Description |
| --- | --- |
| [KeepIntact](#KeepIntact) | Keeps clipping paths of the original page layout. |
| [Expand](#Expand) | Original clipping path will be expanded in the case edited text requires more space. |
| [Remove](#Remove) | Original clipping path will be removed in the case edited text requires more space. |
### KeepIntact {#KeepIntact}
```
public static final int KeepIntact
```


Keeps clipping paths of the original page layout. (Default)

### Expand {#Expand}
```
public static final int Expand
```


Original clipping path will be expanded in the case edited text requires more space.

### Remove {#Remove}
```
public static final int Remove
```


Original clipping path will be removed in the case edited text requires more space. Caution: Because of clipping paths may interact with each other removing of it may lead to unexpected result on the page layout.

