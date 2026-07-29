---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Enthält Optionen zum Laden/Importieren einer EPUB-Datei in ein PDF-Dokument."
type: docs
weight: 1220
url: /de/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

Enthält Optionen zum Laden/Importieren einer EPUB-Datei in ein PDF-Dokument.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | Erstellt Standard-Ladeoptionen für die Konvertierung einer EPUB-Datei in ein PDF-Dokument. Standard-PDF-Seitengröße – A4 300 dpi 2480 × 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Erstellt Standard-Ladeoptionen für die Konvertierung einer EPUB-Datei in ein PDF-Dokument. Standard-PDF-Seitengröße – A4 300 dpi 2480 × 3508. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Liest oder setzt das benutzerdefinierte CSS, das beim Öffnen des EPUB-Dokuments angewendet wird. |
| [getEngineType](#getEngineType--) | Wählen Sie den Engine-Typ für die Konvertierung von EPUB zu PDF. Standard ist EngineType.NEW |
| [getMargin](#getMargin--) | Liest die Referenz auf das Objekt, das Randinformationen darstellt. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | Stellt den Modus der Nutzung des Randbereichs dar – definiert die Behandlung von Anweisungen (falls vorhanden) des CSS des importierten Dokuments in Bezug auf die Nutzung der Ränder. |
| [getPageSize](#getPageSize--) | Liest die Ausgabeseitengröße für den Import. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | ACHTUNG! Die Funktion ist implementiert, wurde jedoch noch nicht in die öffentliche API aufgenommen, da ein Blocker‑Problem in der OSHARED‑Schicht für ein Beispieldokument aufgetreten ist. Stellt den Modus der Nutzung der Seitengröße während der Konvertierung dar. Formate (wie HTML, EPUB usw.) haben normalerweise ein fließendes Layout, sodass die erforderliche Seitengröße angepasst werden kann. Manchmal enthält der Inhalt jedoch festgelegte horizontale Positionen oder Größen, die es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu passen. In einem solchen Fall kann definiert werden, was in diesem Fall geschehen soll (z. B. wenn die Größe des Inhalts nicht in die erforderliche Anfangsseitengröße des resultierenden PDF-Dokuments passt). |
| [setCustomCss](#setCustomCss-java.lang.String-) | Liest oder setzt das benutzerdefinierte CSS, das beim Öffnen des EPUB-Dokuments angewendet wird. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | Wählen Sie den Engine-Typ für die Konvertierung von EPUB zu PDF. Standard ist EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Liest die Referenz auf das Objekt, das Randinformationen darstellt. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | Stellt den Modus der Nutzung des Randbereichs dar – definiert die Behandlung von Anweisungen (falls vorhanden) des CSS des importierten Dokuments in Bezug auf die Nutzung der Ränder. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | ACHTUNG! Die Funktion ist implementiert, wurde jedoch noch nicht in die öffentliche API aufgenommen, da ein Blocker‑Problem in der OSHARED‑Schicht für ein Beispieldokument aufgetreten ist. Stellt den Modus der Nutzung der Seitengröße während der Konvertierung dar. Formate (wie HTML, EPUB usw.) haben normalerweise ein fließendes Layout, sodass die erforderliche Seitengröße angepasst werden kann. Manchmal enthält der Inhalt jedoch festgelegte horizontale Positionen oder Größen, die es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu passen. In einem solchen Fall kann definiert werden, was in diesem Fall geschehen soll (z. B. wenn die Größe des Inhalts nicht in die erforderliche Anfangsseitengröße des resultierenden PDF-Dokuments passt). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

Erstellt Standard-Ladeoptionen für die Konvertierung einer EPUB-Datei in ein PDF-Dokument. Standard-PDF-Seitengröße – A4 300 dpi 2480 × 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
Erstellt Standard-Ladeoptionen für die Konvertierung einer EPUB-Datei in ein PDF-Dokument. Standard-PDF-Seitengröße – A4 300 dpi 2480 × 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Liest oder setzt das benutzerdefinierte CSS, das beim Öffnen des EPUB-Dokuments angewendet wird.

**Returns:**
String Wert

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

Wählen Sie den Engine-Typ für die Konvertierung von EPUB zu PDF. Standard ist EngineType.NEW

**Returns:**
EngineType‑Element

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Liest die Referenz auf das Objekt, das Randinformationen darstellt.

**Returns:**
MarginInfo‑Objekt

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

Stellt den Modus der Nutzung des Randbereichs dar – definiert die Behandlung von Anweisungen (falls vorhanden) des CSS des importierten Dokuments in Bezug auf die Nutzung der Ränder.

**Returns:**
MarginsAreaUsageModes-Wert @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Liest die Ausgabeseitengröße für den Import.

**Returns:**
Dimension2D‑Objekt

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

ACHTUNG! Die Funktion ist implementiert, wurde jedoch noch nicht in die öffentliche API aufgenommen, da ein Blocker‑Problem in der OSHARED‑Schicht für ein Beispieldokument aufgetreten ist. Stellt den Modus der Nutzung der Seitengröße während der Konvertierung dar. Formate (wie HTML, EPUB usw.) haben normalerweise ein fließendes Layout, sodass die erforderliche Seitengröße angepasst werden kann. Manchmal enthält der Inhalt jedoch festgelegte horizontale Positionen oder Größen, die es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu passen. In einem solchen Fall kann definiert werden, was in diesem Fall geschehen soll (z. B. wenn die Größe des Inhalts nicht in die erforderliche Anfangsseitengröße des resultierenden PDF-Dokuments passt).

**Returns:**
PageSizeAdjustmentModes-Wert @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Liest oder setzt das benutzerdefinierte CSS, das beim Öffnen des EPUB-Dokuments angewendet wird.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
Wählen Sie den Engine-Typ für die Konvertierung von EPUB zu PDF. Standard ist EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Liest die Referenz auf das Objekt, das Randinformationen darstellt.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

Stellt den Modus der Nutzung des Randbereichs dar – definiert die Behandlung von Anweisungen (falls vorhanden) des CSS des importierten Dokuments in Bezug auf die Nutzung der Ränder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| marginsAreaUsageMode |  | MarginsAreaUsageModes-Wert @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

ACHTUNG! Die Funktion ist implementiert, wurde jedoch noch nicht in die öffentliche API aufgenommen, da ein Blocker‑Problem in der OSHARED‑Schicht für ein Beispieldokument aufgetreten ist. Stellt den Modus der Nutzung der Seitengröße während der Konvertierung dar. Formate (wie HTML, EPUB usw.) haben normalerweise ein fließendes Layout, sodass die erforderliche Seitengröße angepasst werden kann. Manchmal enthält der Inhalt jedoch festgelegte horizontale Positionen oder Größen, die es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu passen. In einem solchen Fall kann definiert werden, was in diesem Fall geschehen soll (z. B. wenn die Größe des Inhalts nicht in die erforderliche Anfangsseitengröße des resultierenden PDF-Dokuments passt).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | PageSizeAdjustmentModes-Wert @see PageSizeAdjustmentModes |
