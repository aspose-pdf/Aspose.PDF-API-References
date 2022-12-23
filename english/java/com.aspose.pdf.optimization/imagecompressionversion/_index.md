---
title: ImageCompressionVersion
second_title: Aspose.PDF for Java API Reference
description: Describes versions of image compression algorithm.
type: docs
weight: 11
url: /java/com.aspose.pdf.optimization/imagecompressionversion/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ImageCompressionVersion extends System.Enum
```

Describes versions of image compression algorithm.
## Fields

| Field | Description |
| --- | --- |
| [Standard](#Standard) | Standard algorithm. |
| [Fast](#Fast) | Improved algorithm faster then standard but applicable not for all cases. |
| [Mixed](#Mixed) | Use fast algorithm when possible and standard for other cases. |
### Standard {#Standard}
```
public static final int Standard
```


Standard algorithm. Default value.

### Fast {#Fast}
```
public static final int Fast
```


Improved algorithm faster then standard but applicable not for all cases.

### Mixed {#Mixed}
```
public static final int Mixed
```


Use fast algorithm when possible and standard for other cases. May be slower then "Fast" but may produce better compression.

