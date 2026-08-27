---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse zum Festlegen von Seitenänderungsparametern. Ermöglicht das Setzen der folgenden Parameter: Größe der Ergebnisseite (Breite, Höhe) in Standard‑Raumeinheiten oder in Prozent der ursprünglichen Seiten."
type: docs
weight: 300
url: /de/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Klasse zum Festlegen von Seiten­größen‑Anpassungsparametern. Ermöglicht das Setzen der folgenden Parameter: Größe der Ergebnisseite (Breite, Höhe) in Standard‑Raumeinheiten oder in Prozent der ursprünglichen Seitengröße; linke, obere, untere und rechte Ränder in Standard‑Raumeinheiten oder in Prozent der ursprünglichen Seitengröße; Einige Werte können für die automatische Berechnung auf null belassen werden. Diese Werte werden aus dem verbleibenden Seiteninhalt berechnet, nachdem explizit angegebene Werte berücksichtigt wurden. Beispiel: Wenn die Seitenbreite = 100 und die neue Seitenbreite auf 60 Einheiten festgelegt ist, werden die linken und rechten Ränder automatisch berechnet: (100 - 60) / 2 = 15. Diese Klasse wird in der Methode ResizeContents verwendet.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Erstellt Änderungsparameter, bei denen alle Werte auf \"auto\" gesetzt sind. Später können bei Bedarf Ränder und Inhaltsgröße angegeben werden. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Erstellt Änderungsparameter, bei denen alle Werte auf \"auto\" gesetzt sind. Später können bei Bedarf Ränder und Inhaltsgröße angegeben werden. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Erstellt Änderungsparameter mit angegebener Inhaltsgröße. |
| [contentSizePercent](#contentSizePercent-double-double-) | Erstellt Änderungsparameter mit angegebener Inhaltsgröße in Prozent der ursprünglichen Seitengröße. Ränder werden automatisch berechnet. |
| [getBottomMargin](#getBottomMargin--) | Liest oder legt den unteren Rand auf der Ergebnisseite fest. |
| [getContentsHeight](#getContentsHeight--) | Liest oder legt die Höhe des Inhalts der Quellseite auf der Ergebnisseite fest. |
| [getContentsWidth](#getContentsWidth--) | Liest oder legt die Breite des Inhalts der Quellseite auf der Ergebnisseite fest. |
| [getLeftMargin](#getLeftMargin--) | Liest oder legt den linken Rand auf der Ergebnisseite fest. |
| [getRightMargin](#getRightMargin--) | Liest oder legt den rechten Rand auf der Ergebnisseite fest. |
| [getTopMargin](#getTopMargin--) | Liest oder legt den oberen Rand auf der Ergebnisseite fest. |
| [isChangeMediaBox](#isChangeMediaBox--) | Ermittelt, ob die MediaBox einer PDF‑Seite während des Größenänderungsvorgangs angepasst werden soll. Der Standardwert ist {@code false}. Das Setzen dieses Parameters ermöglicht das Anpassen der MediaBox an den CropBox‑Wert während der Größenänderung. |
| [margins](#margins-double-double-double-double-) | Erstellt Änderungsparameter mit angegebenem Randwert. Die Inhaltsgröße wird automatisch berechnet. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Erstellt Resize-Parameter. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. |
| [pageResize](#pageResize-double-double-) | Erstellt Resize-Parameter für die Seitengröße. |
| [pageResizePct](#pageResizePct-double-double-) | Erstellt Resize-Parameter für die Seitengröße. Neue Größen werden in Prozent angegeben. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Liest oder legt den unteren Rand auf der Ergebnisseite fest. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | Legt fest, ob die MediaBox einer PDF-Seite während des Resize-Vorgangs angepasst werden soll. Der Standardwert ist {@code false}. Das Setzen dieses Parameters ermöglicht das Anpassen der MediaBox an den CropBox-Wert während des Resizings. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Liest oder legt die Höhe des Inhalts der Quellseite auf der Ergebnisseite fest. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Liest oder legt die Breite des Inhalts der Quellseite auf der Ergebnisseite fest. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Liest oder legt den linken Rand auf der Ergebnisseite fest. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Liest oder legt den rechten Rand auf der Ergebnisseite fest. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Liest oder legt den oberen Rand auf der Ergebnisseite fest. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Erstellt Änderungsparameter, bei denen alle Werte auf \"auto\" gesetzt sind. Später können bei Bedarf Ränder und Inhaltsgröße angegeben werden.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Erstellt Änderungsparameter, bei denen alle Werte auf \"auto\" gesetzt sind. Später können bei Bedarf Ränder und Inhaltsgröße angegeben werden.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Erstellt Änderungsparameter mit angegebener Inhaltsgröße.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Neue Breite des Inhalts. |
| Höhe |  | Neue Höhe des Inhalts. |

**Returns:**
Gibt neue Resize-Parameter zurück.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

Erstellt Änderungsparameter mit angegebener Inhaltsgröße in Prozent der ursprünglichen Seitengröße. Ränder werden automatisch berechnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Neue Inhaltsbreite in Prozent. |
| Höhe |  | Neue Inhalts­höhe in Prozent. |

**Returns:**
Neue Resize-Parameter.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Liest oder legt den unteren Rand auf der Ergebnisseite fest.

**Returns:**
ContentsResizeValue-Objekt

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Liest oder legt die Höhe des Inhalts der Quellseite auf der Ergebnisseite fest.

**Returns:**
ContentsResizeValue-Objekt

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Liest oder legt die Breite des Inhalts der Quellseite auf der Ergebnisseite fest.

**Returns:**
ContentsResizeValue-Objekt

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Liest oder legt den linken Rand auf der Ergebnisseite fest.

**Returns:**
ContentsResizeValue-Objekt

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Liest oder legt den rechten Rand auf der Ergebnisseite fest.

**Returns:**
ContentsResizeValue-Objekt

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Liest oder legt den oberen Rand auf der Ergebnisseite fest.

**Returns:**
ContentsResizeValue-Objekt

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Ermittelt, ob die MediaBox einer PDF‑Seite während des Größenänderungsvorgangs angepasst werden soll. Der Standardwert ist {@code false}. Das Setzen dieses Parameters ermöglicht das Anpassen der MediaBox an den CropBox‑Wert während der Größenänderung.

**Returns:**
ob die MediaBox einer PDF-Seite während des Resize-Vorgangs angepasst werden soll.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Erstellt Änderungsparameter mit angegebenem Randwert. Die Inhaltsgröße wird automatisch berechnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links |  | Linker Rand. |
| rechts |  | Rechter Rand. |
| oben |  | Oberer Rand. |
| unten |  | Unterer Rand. |

**Returns:**
Erstellte Resize-Parameter.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Erstellt Resize-Parameter. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| links |  | Linker Rand (in Prozent der Seitenbreite). |
| rechts |  | Rechter Rand (in Prozent der Seitenhöhe). |
| oben |  | Oberer Rand (in Prozent der Seitenhöhe). |
| unten |  | Unterer Rand (in Prozent der Seitenhöhe). |

**Returns:**
Gibt neue Resize-Parameter zurück.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Erstellt Resize-Parameter für die Seitengröße.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Neue Seitenbreite in Einheiten. |
| Höhe |  | Neue Seitenhöhe in Einheiten. |

**Returns:**
Neue Resize-Parameter.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Erstellt Resize-Parameter für die Seitengröße. Neue Größen werden in Prozent angegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| widthPct |  | Neue Seitenbreite in Prozent. |
| heightPct |  | Neue Seitenhöhe in Prozent. |

**Returns:**
Neue Resize-Parameter.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Liest oder legt den unteren Rand auf der Ergebnisseite fest.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

Legt fest, ob die MediaBox einer PDF-Seite während des Resize-Vorgangs angepasst werden soll. Der Standardwert ist {@code false}. Das Setzen dieses Parameters ermöglicht das Anpassen der MediaBox an den CropBox-Wert während des Resizings.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ob die MediaBox einer PDF-Seite während des Resize-Vorgangs angepasst werden soll. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Liest oder legt die Höhe des Inhalts der Quellseite auf der Ergebnisseite fest.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Liest oder legt die Breite des Inhalts der Quellseite auf der Ergebnisseite fest.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Liest oder legt den linken Rand auf der Ergebnisseite fest.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Liest oder legt den rechten Rand auf der Ergebnisseite fest.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Liest oder legt den oberen Rand auf der Ergebnisseite fest.
