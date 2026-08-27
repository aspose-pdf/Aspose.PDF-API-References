---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den Dokumentenoptimierungsalgorithmus beschreibt. Eine Instanz dieser Klasse kann als Parameter der Methode OptimizeResources() verwendet werden. @deprecated Diese Klasse ist veraltet. Bitte."
type: docs
weight: 1110
url: /de/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Klasse, die den Dokumentoptimierungsalgorithmus beschreibt. Eine Instanz dieser Klasse kann als Parameter der Methode OptimizeResources() verwendet werden. @deprecated Diese Klasse ist veraltet. Bitte verwenden Sie stattdessen com.aspose.pdf.optimization.OptimizationOptions.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Veraltet. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [all](#all--) | Erstellt eine Optimierungsstrategie mit allen aktivierten Optionen. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Gibt die maximale Bilddimension an. Wenn die Breite oder Höhe des vorhandenen Bildes größer als dieser Wert ist, wird die Bildgröße proportional reduziert. |
| [getResolution](#getResolution--) | Gibt die neue Bild-DPI an, wenn das CompressIamges-Flag verwendet wird. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Gibt die maximale Bilddimension an. Wenn die Breite oder Höhe des vorhandenen Bildes größer als dieser Wert ist, wird die Bildgröße proportional reduziert. |
| [setResolution](#setResolution-int-) | Gibt die neue Bild-DPI an, wenn das CompressIamges-Flag verwendet wird. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Veraltet.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Erstellt eine Optimierungsstrategie mit allen aktivierten Optionen.

**Returns:**
OptimizationOptions-Objekt.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Gibt die maximale Bilddimension an. Wenn die Breite oder Höhe des vorhandenen Bildes größer als dieser Wert ist, wird die Bildgröße proportional reduziert.

**Returns:**
maximale Bilddimension

### getResolution {#getResolution--}
```
public int getResolution()
```

Gibt die neue Bild-DPI an, wenn das CompressIamges-Flag verwendet wird.

**Returns:**
Bildauflösung

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Gibt die maximale Bilddimension an. Wenn die Breite oder Höhe des vorhandenen Bildes größer als dieser Wert ist, wird die Bildgröße proportional reduziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dimension |  | maximale Bilddimension |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

Gibt die neue Bild-DPI an, wenn das CompressIamges-Flag verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpi |  | Bildauflösung |
