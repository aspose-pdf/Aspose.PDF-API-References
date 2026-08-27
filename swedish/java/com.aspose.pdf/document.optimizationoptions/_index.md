---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som beskriver dokumentoptimeringsalgoritmen. En instans av denna klass kan användas som parameter till metoden OptimizeResources(). @deprecated Denna klass är föråldrad. Vänligen."
type: docs
weight: 1110
url: /sv/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Klass som beskriver dokumentoptimeringsalgoritm. En instans av denna klass kan användas som parameter till metoden OptimizeResources(). @deprecated Denna klass är föråldrad. Använd com.aspose.pdf.optimization.OptimizationOptions istället.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Föråldrad. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [all](#all--) | Skapar optimeringsstrategi med alla alternativ aktiverade. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Anger maximal bilddimension. Om bildens bredd eller höjd på den befintliga bilden är större än detta värde – bildens storlek kommer att reduceras proportionellt. |
| [getResolution](#getResolution--) | Anger ny bild-dpi när flaggan CompressIamges används. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Anger maximal bilddimension. Om bildens bredd eller höjd på den befintliga bilden är större än detta värde – bildens storlek kommer att reduceras proportionellt. |
| [setResolution](#setResolution-int-) | Anger ny bild-dpi när flaggan CompressIamges används. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Föråldrad.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Skapar optimeringsstrategi med alla alternativ aktiverade.

**Returns:**
OptimizationOptions‑objekt.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Anger maximal bilddimension. Om bildens bredd eller höjd på den befintliga bilden är större än detta värde – bildens storlek kommer att reduceras proportionellt.

**Returns:**
maximal bilddimension

### getResolution {#getResolution--}
```
public int getResolution()
```

Anger ny bild-dpi när flaggan CompressIamges används.

**Returns:**
bildupplösning

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Anger maximal bilddimension. Om bildens bredd eller höjd på den befintliga bilden är större än detta värde – bildens storlek kommer att reduceras proportionellt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dimension |  | maximal bilddimension |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

Anger ny bild-dpi när flaggan CompressIamges används.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpi |  | bildupplösning |
