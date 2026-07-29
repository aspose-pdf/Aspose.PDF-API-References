---
title: "PageInfo"
linktitle: "PageInfo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Seiteninformationen für den pdf‑Generator dar. Stellt eine Page‑Information‑Annotation in einem PDF‑Dokument dar. Diese Annotation enthält den Dateinamen, die Seitennummer sowie Datum und Uhrzeit der Annotationserstellung. Diese Klasse wird hauptsächlich verwendet, um Metadaten zu einer bestimmten Seite im PDF‑Dokument hinzuzufügen, was für Nachverfolgungs‑ und Referenzzwecke nützlich sein kann. Beispielsweise kann sie verwendet werden, um Seiten während des Druckvorgangs zu markieren oder zusätzliche Informationen über die Seite beim Betrachten des Dokuments bereitzustellen."
type: docs
weight: 3370
url: /de/java/com.aspose.pdf/pageinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class PageInfo extends Object implements com.aspose.ms.System.ICloneable
```

Stellt die Seiteninformationen für den pdf‑Generator dar. Stellt eine Page‑Information‑Annotation in einem PDF‑Dokument dar. Diese Annotation enthält den Dateinamen, die Seitennummer sowie Datum und Uhrzeit der Annotationserstellung. Diese Klasse wird hauptsächlich verwendet, um Metadaten zu einer bestimmten Seite im PDF‑Dokument hinzuzufügen, was für Nachverfolgungs‑ und Referenzzwecke nützlich sein kann. Beispielsweise kann sie verwendet werden, um Seiten während des Druckvorgangs zu markieren oder zusätzliche Informationen über die Seite beim Betrachten des Dokuments bereitzustellen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PageInfo](#PageInfo--) | Standardkonstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | Klone Seiteninformationen. |
| [getAnyMargin](#getAnyMargin--) | Liest oder setzt den Seitenrand für jede Seite außer der ersten. |
| [getDefaultTextState](#getDefaultTextState--) | Liest die Standardschriftart. |
| [getHeight](#getHeight--) | Liest die Seitenhöhe. |
| [getMargin](#getMargin--) | Liest den Seitenrand. |
| [getPureHeight](#getPureHeight--) | Liest die reine Seitenhöhe ohne Ränder. |
| [getWidth](#getWidth--) | Liest die Seitenbreite. |
| [isLandscape](#isLandscape--) | Liest, ob die Seite im Querformat ist. |
| [setAnyMargin](#setAnyMargin-com.aspose.pdf.MarginInfo-) | Liest oder setzt den Seitenrand für jede Seite außer der ersten. |
| [setDefaultTextState](#setDefaultTextState-com.aspose.pdf.TextState-) | Setzt die Standardschriftart. |
| [setHeight](#setHeight-double-) | Setzt die Seitenhöhe. |
| [setLandscape](#setLandscape-boolean-) | Setzt, ob die Seite im Querformat ist. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Setzt den Seitenrand. |
| [setWidth](#setWidth-double-) | Setzt die Seitenbreite. |

### PageInfo {#PageInfo--}
```
public PageInfo()
```

Standardkonstruktor

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klone Seiteninformationen.

**Returns:**
Das geklonte Objekt

### getAnyMargin {#getAnyMargin--}
```
public final MarginInfo getAnyMargin()
```

Liest oder setzt den Seitenrand für jede Seite außer der ersten.

**Returns:**
MarginInfo‑Instanz

### getDefaultTextState {#getDefaultTextState--}
```
public TextState getDefaultTextState()
```

Liest die Standardschriftart.

**Returns:**
TextState-Instanz

### getHeight {#getHeight--}
```
public double getHeight()
```

Liest die Seitenhöhe.

**Returns:**
double-Wert

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Liest den Seitenrand.

**Returns:**
MarginInfo-Wert

### getPureHeight {#getPureHeight--}
```
public double getPureHeight()
```

Liest die reine Seitenhöhe ohne Ränder.

**Returns:**
double-Wert

### getWidth {#getWidth--}
```
public double getWidth()
```

Liest die Seitenbreite.

**Returns:**
double-Wert

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Liest, ob die Seite im Querformat ist.

**Returns:**
boolescher Wert

### setAnyMargin {#setAnyMargin-com.aspose.pdf.MarginInfo-}
Liest oder setzt den Seitenrand für jede Seite außer der ersten.

### setDefaultTextState {#setDefaultTextState-com.aspose.pdf.TextState-}
Setzt die Standardschriftart.

### setHeight {#setHeight-double-}
```
public final void setHeight(double value)
```

Setzt die Seitenhöhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Setzt, ob die Seite im Querformat ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Setzt den Seitenrand.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Setzt die Seitenbreite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |
