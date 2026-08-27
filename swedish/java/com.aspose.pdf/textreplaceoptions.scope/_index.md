---
title: "TextReplaceOptions.Scope"
linktitle: "TextReplaceOptions.Scope"
second_title: "Aspose.PDF för Java API-referens"
description: "Omfattning där ersättningsoperationen för text tillämpas REPLACE_FIRST som standard. Detta föråldrade alternativ behölls för kompatibilitet. Det påverkar PdfContentEditor och har ingen effekt på."
type: docs
weight: 5280
url: /sv/java/com.aspose.pdf/textreplaceoptions.scope/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextReplaceOptions.Scope > com.aspose.pdf.TextReplaceOptions.Scope, java.lang.Enum < TextReplaceOptions.Scope >, com.aspose.pdf.TextReplaceOptions.Scope

**All Implemented Interfaces:**
Serializable, Comparable < TextReplaceOptions.Scope >

```
public static enum TextReplaceOptions.Scope extends Enum < TextReplaceOptions.Scope >
```

Omfattning där ersättning av textoperationen tillämpas REPLACE_FIRST som standard. Detta föråldrade alternativ behölls för kompatibilitet. Det påverkar PdfContentEditor och har ingen effekt på TextFragmentAbsorber.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [REPLACE_ALL](#REPLACE_ALL) | Ersätt alla textförekomster på alla påverkade sidor |
| [REPLACE_FIRST](#REPLACE_FIRST) | Ersätt endast den första förekomsten av texten på varje påverkad sida |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### REPLACE_ALL {#REPLACE_ALL}
```
public static final TextReplaceOptions.Scope REPLACE_ALL
```

Ersätt alla textförekomster på alla påverkade sidor

### REPLACE_FIRST {#REPLACE_FIRST}
```
public static final TextReplaceOptions.Scope REPLACE_FIRST
```

Ersätt endast den första förekomsten av texten på varje påverkad sida

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static TextReplaceOptions.Scope [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
