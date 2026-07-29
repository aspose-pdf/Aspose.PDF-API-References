---
title: "CollectionItem"
linktitle: "CollectionItem"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för ett samlingsobjekt. Samlingsobjektet innehåller de data som beskrivs av samlingens schema."
type: docs
weight: 640
url: /sv/java/com.aspose.pdf/collectionitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CollectionItem

```
public class CollectionItem extends Object
```

Representerar en klass för ett samlingsobjekt. Samlingsobjektet innehåller de data som beskrivs av samlingens schema.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAllNames](#getAllNames--) | Hämtar en samling av alla namn på värden i samlingsobjektet. |
| [hasName](#hasName-java.lang.String-) | Kontrollerar om det angivna namnet finns i samlingsobjektet. |
| [isEmpty](#isEmpty--) | Hämtar ett värde som indikerar om samlingsobjektet är tomt. |
| [tryGetDateTimeValue](#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Försöker hämta värdet av typen DateTime från samlingsobjektet med det angivna namnet. |
| [tryGetDoubleValue](#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Försöker hämta dubbelvärdet för det angivna namnet från samlingsobjektet. |
| [tryGetIntValue](#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Försöker hämta heltalsvärdet för ett angivet namn från samlingsobjektet. |
| [tryGetTextValue](#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-) | Försöker hämta textvärdet med det angivna namnet från samlingsobjektet. |

### getAllNames {#getAllNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllNames()
```

Hämtar en samling av alla namn på värden i samlingsobjektet.

**Returns:**
lista med String

### hasName {#hasName-java.lang.String-}
Kontrollerar om det angivna namnet finns i samlingsobjektet.

### isEmpty {#isEmpty--}
```
public final boolean isEmpty()
```

Hämtar ett värde som indikerar om samlingsobjektet är tomt.

**Returns:**
true om samlingsobjektet är tomt; annars false. Denna egenskap returnerar true om samlingsobjektet inte innehåller några värden, inklusive strängvärden, dubbelvärden, heltalsvärden och datumvärden. Om någon av dessa värdetyper finns i samlingsobjektet, returnerar egenskapen false.

### tryGetDateTimeValue {#tryGetDateTimeValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Försöker hämta värdet av typen DateTime från samlingsobjektet med det angivna namnet.

### tryGetDoubleValue {#tryGetDoubleValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Försöker hämta dubbelvärdet för det angivna namnet från samlingsobjektet.

### tryGetIntValue {#tryGetIntValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Försöker hämta heltalsvärdet för ett angivet namn från samlingsobjektet.

### tryGetTextValue {#tryGetTextValue-java.lang.String-com.aspose.pdf.CollectionItem.Value:A-}
Försöker hämta textvärdet med det angivna namnet från samlingsobjektet.
