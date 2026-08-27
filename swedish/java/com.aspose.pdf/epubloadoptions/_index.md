---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Innehåller alternativ för inläsning/import av EPUB-fil till PDF-dokument."
type: docs
weight: 1220
url: /sv/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

Innehåller alternativ för inläsning/import av EPUB-fil till PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | Skapar standardladdningsalternativ för att konvertera EPUB‑fil till PDF‑dokument. Standard PDF‑sidstorlek – A4 300 dpi 2480 × 3508. |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Skapar standardladdningsalternativ för att konvertera EPUB‑fil till PDF‑dokument. Standard PDF‑sidstorlek – A4 300 dpi 2480 × 3508. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCustomCss](#getCustomCss--) | Hämtar eller anger den anpassade CSS som ska tillämpas när EPUB‑dokumentet öppnas. |
| [getEngineType](#getEngineType--) | Välj motortyp för konvertering från EPUB till PDF. Standard är EngineType.NEW |
| [getMargin](#getMargin--) | Hämtar referens till objekt som representerar marginalinformation. |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | Representerar läge för användning av marginalområdet – definierar behandling av instruktioner (om några) i CSS för importerat dokument relaterade till användning av marginaler. |
| [getPageSize](#getPageSize--) | Hämtar utsidans storlek för import. |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | OBS! Funktionen är implementerad men har ännu inte lagts till i det offentliga API:t på grund av ett blockerande problem i OSHARED‑lagret som upptäcktes för exempel­dokumentet. Representerar läge för användning av sidstorlek under konvertering. Format (som HTML, EPUB etc.) har vanligtvis flytande design, så den tillåter att anpassa till önskad sidstorlek. Men ibland har innehållet specificerade horisontella positioner eller storlek som inte tillåter att placera innehållet i den önskade sidstorleken. I sådana fall kan vi definiera vad som ska göras (dvs. när innehållets storlek inte passar den initiala sidstorleken för det resulterande PDF‑dokumentet). |
| [setCustomCss](#setCustomCss-java.lang.String-) | Hämtar eller anger den anpassade CSS som ska tillämpas när EPUB‑dokumentet öppnas. |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | Välj motortyp för konvertering från EPUB till PDF. Standard är EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Hämtar referens till objekt som representerar marginalinformation. |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | Representerar läge för användning av marginalområdet – definierar behandling av instruktioner (om några) i CSS för importerat dokument relaterade till användning av marginaler. |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | OBS! Funktionen är implementerad men har ännu inte lagts till i det offentliga API:t på grund av ett blockerande problem i OSHARED‑lagret som upptäcktes för exempel­dokumentet. Representerar läge för användning av sidstorlek under konvertering. Format (som HTML, EPUB etc.) har vanligtvis flytande design, så den tillåter att anpassa till önskad sidstorlek. Men ibland har innehållet specificerade horisontella positioner eller storlek som inte tillåter att placera innehållet i den önskade sidstorleken. I sådana fall kan vi definiera vad som ska göras (dvs. när innehållets storlek inte passar den initiala sidstorleken för det resulterande PDF‑dokumentet). |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

Skapar standardladdningsalternativ för att konvertera EPUB‑fil till PDF‑dokument. Standard PDF‑sidstorlek – A4 300 dpi 2480 × 3508.

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
Skapar standardladdningsalternativ för att konvertera EPUB‑fil till PDF‑dokument. Standard PDF‑sidstorlek – A4 300 dpi 2480 × 3508.

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

Hämtar eller anger den anpassade CSS som ska tillämpas när EPUB‑dokumentet öppnas.

**Returns:**
String värde

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

Välj motortyp för konvertering från EPUB till PDF. Standard är EngineType.NEW

**Returns:**
EngineType‑element

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Hämtar referens till objekt som representerar marginalinformation.

**Returns:**
MarginInfo‑objekt

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

Representerar läge för användning av marginalområdet – definierar behandling av instruktioner (om några) i CSS för importerat dokument relaterade till användning av marginaler.

**Returns:**
MarginsAreaUsageModes‑värde @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Hämtar utsidans storlek för import.

**Returns:**
Dimension2D‑objekt

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

OBS! Funktionen är implementerad men har ännu inte lagts till i det offentliga API:t på grund av ett blockerande problem i OSHARED‑lagret som upptäcktes för exempel­dokumentet. Representerar läge för användning av sidstorlek under konvertering. Format (som HTML, EPUB etc.) har vanligtvis flytande design, så den tillåter att anpassa till önskad sidstorlek. Men ibland har innehållet specificerade horisontella positioner eller storlek som inte tillåter att placera innehållet i den önskade sidstorleken. I sådana fall kan vi definiera vad som ska göras (dvs. när innehållets storlek inte passar den initiala sidstorleken för det resulterande PDF‑dokumentet).

**Returns:**
PageSizeAdjustmentModes‑värde @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
Hämtar eller anger den anpassade CSS som ska tillämpas när EPUB‑dokumentet öppnas.

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
Välj motortyp för konvertering från EPUB till PDF. Standard är EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Hämtar referens till objekt som representerar marginalinformation.

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

Representerar läge för användning av marginalområdet – definierar behandling av instruktioner (om några) i CSS för importerat dokument relaterade till användning av marginaler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| marginsAreaUsageMode |  | MarginsAreaUsageModes‑värde @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

OBS! Funktionen är implementerad men har ännu inte lagts till i det offentliga API:t på grund av ett blockerande problem i OSHARED‑lagret som upptäcktes för exempel­dokumentet. Representerar läge för användning av sidstorlek under konvertering. Format (som HTML, EPUB etc.) har vanligtvis flytande design, så den tillåter att anpassa till önskad sidstorlek. Men ibland har innehållet specificerade horisontella positioner eller storlek som inte tillåter att placera innehållet i den önskade sidstorleken. I sådana fall kan vi definiera vad som ska göras (dvs. när innehållets storlek inte passar den initiala sidstorleken för det resulterande PDF‑dokumentet).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | PageSizeAdjustmentModes‑värde @see PageSizeAdjustmentModes |
