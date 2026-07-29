---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar användningsläge för marginalområde under konvertering (som HTML, EPUB etc), definierar behandling av instruktioner för importerat format relaterade till användning av marginaler."
type: docs
weight: 2800
url: /sv/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

Representerar användningsläge för marginalområde under konvertering (som HTML, EPUB etc), definierar behandling av instruktioner för importerat format relaterade till användning av marginaler.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | Det här läget förbjuder strikt användning av marginalområdet, så konverteraren kommer aldrig att använda marginalernas område för rendering, även om CSS eller formatet på källdokumentet tillåter eller kräver det. |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | I detta läge följer konverteraren formatet på det importerade dokumentet (t.ex. CSS för importerad HTML) vid användning av marginalområdet. Så om formatet på det importerade dokumentet kräver användning av marginalområdet för rendering, kommer konverteraren att tillåta det. |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

Det här läget förbjuder strikt användning av marginalområdet, så konverteraren kommer aldrig att använda marginalernas område för rendering, även om CSS eller formatet på källdokumentet tillåter eller kräver det.

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

I detta läge följer konverteraren formatet på det importerade dokumentet (t.ex. CSS för importerad HTML) vid användning av marginalområdet. Så om formatet på det importerade dokumentet kräver användning av marginalområdet för rendering, kommer konverteraren att tillåta det.
