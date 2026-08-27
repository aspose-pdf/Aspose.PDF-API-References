---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF för Java API-referens"
description: "Tillåter att kontrollera hur ett PDF-dokument konverteras till ett ordbehandlingsdokument. Använd läget RecognitionMode.Textbox när det resulterande dokumentet inte kommer att vara kraftigt."
type: docs
weight: 1050
url: /sv/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Tillåter att styra hur ett PDF-dokument konverteras till ett ordbehandlingsdokument. Använd läget RecognitionMode.Textbox när det resulterande dokumentet inte kommer att redigeras kraftigt vidare. Textboxar är enkla att modifiera när det inte finns mycket att göra. Använd läget RecognitionMode.Flow när utdata-dokumentet kräver ytterligare redigering. Stycken och textrader i flödesläget möjliggör enkel modifiering av text, men ej stödjade formateringsobjekt kommer att se sämre ut än i läget RecognitionMode.Textbox.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | Ett alternativt Flow-läge som stödjer igenkänning av tabeller. |
| [Flow](#Flow) | Fullständigt igenkänningsläge, motorn utför gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och skapa ett maximalt redigerbart dokument. |
| [Textbox](#Textbox) | Detta läge är snabbt och bra för att maximalt bevara PDF-filens ursprungliga utseende, men redigerbarheten i det resulterande dokumentet kan vara begränsad. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

Ett alternativt Flow-läge som stödjer igenkänning av tabeller.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Fullständigt igenkänningsläge, motorn utför gruppering och flernivåanalys för att återställa den ursprungliga dokumentförfattarens avsikt och skapa ett maximalt redigerbart dokument.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

Detta läge är snabbt och bra för att maximalt bevara PDF-filens ursprungliga utseende, men redigerbarheten i det resulterande dokumentet kan vara begränsad.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
