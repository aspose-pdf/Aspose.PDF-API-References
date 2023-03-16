---
title: PositioningMode
second_title: Aspose.PDF for Java API Reference
description: Defines positioning mode.
type: docs
weight: 50
url: /java/com.aspose.pdf.facades/positioningmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PositioningMode extends System.Enum
```

Defines positioning mode. Possible values include Legacy (backward compatibility) and Current (updated text position calculation method)
## Fields

| Field | Description |
| --- | --- |
| [Legacy](#Legacy) | Legacy text positioning |
| [ModernLineSpacing](#ModernLineSpacing) | Updated line spacing, vertical position calculation is done by the old rules (i.e. text is positioned relative to bottom-left corner of the specified rectangle) |
| [Current](#Current) | Updated line spacing and vertical position calculation is done based on left-top corner rather than left-bottom. |
### Legacy {#Legacy}
```
public static final int Legacy
```


Legacy text positioning

### ModernLineSpacing {#ModernLineSpacing}
```
public static final int ModernLineSpacing
```


Updated line spacing, vertical position calculation is done by the old rules (i.e. text is positioned relative to bottom-left corner of the specified rectangle)

### Current {#Current}
```
public static final int Current
```


Updated line spacing and vertical position calculation is done based on left-top corner rather than left-bottom.

