---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Optionsklasse für das Extrahieren von Vektorgrafiken aus der PDF‑Dokumentseite dar."
type: docs
weight: 30
url: /de/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

Stellt eine Optionsklasse für das Extrahieren von Vektorgrafiken aus der PDF‑Dokumentseite dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | Erstellt eine Instanz der SvgExtractionOptions-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Ruft die Option ab und setzt sie, um Unterpfade automatisch zu Bildern zu gruppieren. Diese Option schließt die {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)})-Option aus. |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | Ruft die Option ab und legt sie fest, um jeden Unterpfad aus einem PDF-Dokument in separate SVG‑Bilder zu extrahieren. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | Ruft das Begrenzungsrechteck ab und legt es fest, das den Extraktionsbereich für die SVG‑Extraktion definiert. |
| [getGroupStrength](#getGroupStrength--) | Ruft die Option ab und legt sie fest. Die Stärke der Gruppierung von Unterpfaden zu Bildern. Ermöglicht die Konfiguration des Gruppierungsgrades von Unterpfaden. Der Wertebereich liegt zwischen 0 und 1. Ein Wert von 0 entspricht der {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)})‑Option. Ein Wert von 1 erzeugt ein einzelnes Bild für alle Vektorpfade auf der Seite. Die Option hat Wirkung, wenn {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) false ist. Der Standardwert ist {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Ruft die minimale Strichbreite ab und legt sie fest, die im resultierenden SVG verwendet wird. Wenn das PDF eine dünnere Strichbreite verwendet, wird sie durch diese Breite ersetzt. Der Standardwert ist 0,5. Der Wert wird in transformierten Benutzerausrag‑Einheiten der konvertierten PDF‑Seite angegeben. Standardmäßig entspricht 1 Benutzerausrag‑Einheit 1/72 Zoll (0,35 mm), kann jedoch vom PDF‑Dokument überschrieben werden. Transformationen können die tatsächliche minimale Breite im erzeugten SVG beeinflussen. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Ruft die Option ab und legt sie fest, um streng zu prüfen, ob Unterpfade innerhalb des angegebenen Rechtecks in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) liegen. Wenn sie auf false gesetzt ist, werden Unterpfade, die nicht vollständig in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) enthalten sind, extrahiert. Der Standardwert ist {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Ruft das Flag ab und legt es fest, das bestimmt, ob XFrom‑Elemente, die auf Seiten gefunden werden, entpackt werden sollen oder nicht. XFrom‑Elemente können in verschiedenen SVG‑Dateien landen. Nur XForms, die durch Do‑Anweisungen aus dem Seiteninhalt gerendert werden, werden entpackt. Verschachtelte XForms werden nicht entpackt. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Ruft die Option ab und legt sie fest, nur das XForm zu entpacken, das dem angegebenen Prädikat entspricht. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Ruft die Option ab und setzt sie, um Unterpfade automatisch zu Bildern zu gruppieren. Diese Option schließt die {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)})-Option aus. |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | Ruft die Option ab und legt sie fest, um jeden Unterpfad aus einem PDF-Dokument in separate SVG‑Bilder zu extrahieren. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | Ruft das Begrenzungsrechteck ab und legt es fest, das den Extraktionsbereich für die SVG‑Extraktion definiert. |
| [setGroupStrength](#setGroupStrength-double-) | Ruft die Option ab und legt sie fest. Die Stärke der Gruppierung von Unterpfaden zu Bildern. Ermöglicht die Konfiguration des Gruppierungsgrades von Unterpfaden. Der Wertebereich liegt zwischen 0 und 1. Ein Wert von 0 entspricht der {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)})‑Option. Ein Wert von 1 erzeugt ein einzelnes Bild für alle Vektorpfade auf der Seite. Die Option hat Wirkung, wenn {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) false ist. Der Standardwert ist {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Ruft die minimale Strichbreite ab und legt sie fest, die im resultierenden SVG verwendet wird. Wenn das PDF eine dünnere Strichbreite verwendet, wird sie durch diese Breite ersetzt. Der Standardwert ist 0,5. Der Wert wird in transformierten Benutzerausrag‑Einheiten der konvertierten PDF‑Seite angegeben. Standardmäßig entspricht 1 Benutzerausrag‑Einheit 1/72 Zoll (0,35 mm), kann jedoch vom PDF‑Dokument überschrieben werden. Transformationen können die tatsächliche minimale Breite im erzeugten SVG beeinflussen. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Ruft die Option ab und legt sie fest, um streng zu prüfen, ob Unterpfade innerhalb des angegebenen Rechtecks in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) liegen. Wenn sie auf false gesetzt ist, werden Unterpfade, die nicht vollständig in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) enthalten sind, extrahiert. Der Standardwert ist {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Ruft das Flag ab und legt es fest, das bestimmt, ob XFrom‑Elemente, die auf Seiten gefunden werden, entpackt werden sollen oder nicht. XFrom‑Elemente können in verschiedenen SVG‑Dateien landen. Nur XForms, die durch Do‑Anweisungen aus dem Seiteninhalt gerendert werden, werden entpackt. Verschachtelte XForms werden nicht entpackt. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Ruft die Option ab und legt sie fest, nur das XForm zu entpacken, das dem angegebenen Prädikat entspricht. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

Erstellt eine Instanz der SvgExtractionOptions-Klasse.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Ruft die Option ab und setzt sie, um Unterpfade automatisch zu Bildern zu gruppieren. Diese Option schließt die {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)})-Option aus.

**Returns:**
boolescher Wert

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

Ruft die Option ab und legt sie fest, um jeden Unterpfad aus einem PDF-Dokument in separate SVG‑Bilder zu extrahieren.

**Returns:**
boolescher Wert

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

Ruft das Begrenzungsrechteck ab und legt es fest, das den Extraktionsbereich für die SVG‑Extraktion definiert.

**Returns:**
Rechteck-Instanz

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Ruft die Option ab und legt sie fest. Die Stärke der Gruppierung von Unterpfaden zu Bildern. Ermöglicht die Konfiguration des Gruppierungsgrades von Unterpfaden. Der Wertebereich liegt zwischen 0 und 1. Ein Wert von 0 entspricht der {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)})‑Option. Ein Wert von 1 erzeugt ein einzelnes Bild für alle Vektorpfade auf der Seite. Die Option hat Wirkung, wenn {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) false ist. Der Standardwert ist {@code 0.8}.

**Returns:**
double-Wert

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Ruft die minimale Strichbreite ab und legt sie fest, die im resultierenden SVG verwendet wird. Wenn das PDF eine dünnere Strichbreite verwendet, wird sie durch diese Breite ersetzt. Der Standardwert ist 0,5. Der Wert wird in transformierten Benutzerausrag‑Einheiten der konvertierten PDF‑Seite angegeben. Standardmäßig entspricht 1 Benutzerausrag‑Einheit 1/72 Zoll (0,35 mm), kann jedoch vom PDF‑Dokument überschrieben werden. Transformationen können die tatsächliche minimale Breite im erzeugten SVG beeinflussen.

**Returns:**
double-Wert

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Ruft die Option ab und legt sie fest, um streng zu prüfen, ob Unterpfade innerhalb des angegebenen Rechtecks in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) liegen. Wenn sie auf false gesetzt ist, werden Unterpfade, die nicht vollständig in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) enthalten sind, extrahiert. Der Standardwert ist {@code True}.

**Returns:**
boolescher Wert

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Ruft das Flag ab und legt es fest, das bestimmt, ob XFrom‑Elemente, die auf Seiten gefunden werden, entpackt werden sollen oder nicht. XFrom‑Elemente können in verschiedenen SVG‑Dateien landen. Nur XForms, die durch Do‑Anweisungen aus dem Seiteninhalt gerendert werden, werden entpackt. Verschachtelte XForms werden nicht entpackt.

**Returns:**
boolescher Wert

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Ruft die Option ab und legt sie fest, nur das XForm zu entpacken, das dem angegebenen Prädikat entspricht.

**Returns:**
interne Predicate‑Instanz der XFormPlacement‑Instanz

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Ruft die Option ab und setzt sie, um Unterpfade automatisch zu Bildern zu gruppieren. Diese Option schließt die {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)})-Option aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

Ruft die Option ab und legt sie fest, um jeden Unterpfad aus einem PDF-Dokument in separate SVG‑Bilder zu extrahieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
Ruft das Begrenzungsrechteck ab und legt es fest, das den Extraktionsbereich für die SVG‑Extraktion definiert.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Ruft die Option ab und legt sie fest. Die Stärke der Gruppierung von Unterpfaden zu Bildern. Ermöglicht die Konfiguration des Gruppierungsgrades von Unterpfaden. Der Wertebereich liegt zwischen 0 und 1. Ein Wert von 0 entspricht der {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)})‑Option. Ein Wert von 1 erzeugt ein einzelnes Bild für alle Vektorpfade auf der Seite. Die Option hat Wirkung, wenn {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) false ist. Der Standardwert ist {@code 0.8}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Ruft die minimale Strichbreite ab und legt sie fest, die im resultierenden SVG verwendet wird. Wenn das PDF eine dünnere Strichbreite verwendet, wird sie durch diese Breite ersetzt. Der Standardwert ist 0,5. Der Wert wird in transformierten Benutzerausrag‑Einheiten der konvertierten PDF‑Seite angegeben. Standardmäßig entspricht 1 Benutzerausrag‑Einheit 1/72 Zoll (0,35 mm), kann jedoch vom PDF‑Dokument überschrieben werden. Transformationen können die tatsächliche minimale Breite im erzeugten SVG beeinflussen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Ruft die Option ab und legt sie fest, um streng zu prüfen, ob Unterpfade innerhalb des angegebenen Rechtecks in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) liegen. Wenn sie auf false gesetzt ist, werden Unterpfade, die nicht vollständig in {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) enthalten sind, extrahiert. Der Standardwert ist {@code True}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Ruft das Flag ab und legt es fest, das bestimmt, ob XFrom‑Elemente, die auf Seiten gefunden werden, entpackt werden sollen oder nicht. XFrom‑Elemente können in verschiedenen SVG‑Dateien landen. Nur XForms, die durch Do‑Anweisungen aus dem Seiteninhalt gerendert werden, werden entpackt. Verschachtelte XForms werden nicht entpackt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Ruft die Option ab und legt sie fest, nur das XForm zu entpacken, das dem angegebenen Prädikat entspricht.
