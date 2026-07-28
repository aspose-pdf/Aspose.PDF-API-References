---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Aspose.PDF för Java API-referens"
description: "När en PDF‑fil (som vanligtvis har fast layout) konverteras försöker konverteringsmotorn utföra gruppering och flernivåanalys för att återställa det ursprungliga dokumentet."
type: docs
weight: 1250
url: /sv/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

När en PDF-fil (som vanligtvis har fast layout) konverteras försöker konverteringsmotorn utföra gruppering och flernivåanalys för att återställa den ursprungliga författarens avsikt och producera resultat i flödeslayout. Denna egenskap finjusterar den konverteringen för den önskade metoden för innehållsigenkänning.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Fixed](#Fixed) | Detta läge är snabbt och bra för att maximalt bevara de ursprungliga sidornas utseende, men tyvärr stödjer många EPUB‑läsare inte xhtml med fast layout. |
| [Flow](#Flow) | Fullständigt igenkänningsläge, motorn försöker utföra gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och producera xhtml i flödeslayout. |
| [PdfFlow](#PdfFlow) | Huvudidén med denna konvertering är baserad på att spara den "naturliga" ordningen för innehållsrendering som bildas under bearbetning av pdf-dokument. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

Detta läge är snabbt och bra för att maximalt bevara de ursprungliga sidornas utseende, men tyvärr stödjer många EPUB‑läsare inte xhtml med fast layout.

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Fullständigt igenkänningsläge, motorn försöker utföra gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och producera xhtml i flödeslayout.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

Huvudidén med denna konvertering är baserad på att spara den "naturliga" ordningen för innehållsrendering som bildas under bearbetning av pdf-dokument.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
