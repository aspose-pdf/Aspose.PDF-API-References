---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Aspose.PDF för Java API-referens"
description: "Inkapslar resultatet av en operation som försöker extrahera osignerat innehåll från ett PDF-dokument. Denna klass tillhandahåller information om operationens framgång, detaljer om."
type: docs
weight: 40
url: /sv/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Inkapslar resultatet av en operation som försöker extrahera osignerat innehåll från ett PDF-dokument. Denna klass tillhandahåller information om operationens framgång, detaljer om det osignerade innehållet, ett meddelande som beskriver resultatet samt täckningsstatusen för dokumentets signaturer.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCoverage](#getCoverage--) | Hämtar ett värde som indikerar i vilken grad dokumentet är täckt av giltiga digitala signaturer. |
| [getMessage](#getMessage--) | Hämtar ett meddelande som beskriver resultatet av operationen. |
| [getSuccess](#getSuccess--) | Hämtar ett värde som indikerar om operationen för att hämta osignerat innehåll från dokumentet lyckades. |
| [getUnsignedContent](#getUnsignedContent--) | Hämtar ett osignerat innehåll. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Hämtar ett värde som indikerar i vilken grad dokumentet är täckt av giltiga digitala signaturer.

**Returns:**
ett värde som indikerar i vilken grad dokumentet är täckt av giltiga digitala signaturer.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Hämtar ett meddelande som beskriver resultatet av operationen.

**Returns:**
ett meddelande som beskriver resultatet av operationen.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Hämtar ett värde som indikerar om operationen för att hämta osignerat innehåll från dokumentet lyckades.

**Returns:**
ett värde som indikerar om operationen för att hämta osignerat innehåll från dokumentet lyckades.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

Hämtar ett osignerat innehåll.

**Returns:**
ett osignerat innehåll.
