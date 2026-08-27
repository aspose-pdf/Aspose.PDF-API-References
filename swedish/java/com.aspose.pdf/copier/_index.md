---
title: "Copier"
linktitle: "Copier"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass för kopiering av objekt."
type: docs
weight: 850
url: /sv/java/com.aspose.pdf/copier/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Copier

```
public class Copier extends Object
```

Klass för kopiering av objekt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Copier](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | Skapar en instans av Copier-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | Duplicerar IPdfPrimitive |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | Skapar en kopia av objektet med alla beroende objekt. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | hämta Tillåt återanvändning av sidinnehåll |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | hämta Ignorera korrupta objekt |
| [getRestrictedKeys](#getRestrictedKeys--) | hämta Begränsade nycklar |
| [getReuseStreams](#getReuseStreams--) | hämta Återanvänd strömmar |
| [getUseStubs](#getUseStubs--) | Indikerar om stubbar ska användas under dupliceringsprocessen. Om alternativet är aktiverat kommer strömmarna att kopieras, annars kommer en länk till källströmmen att användas. Detta tillåter dig inte att stänga det kopierade dokumentet, men sparar på kopieringsprocessen och minnet. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | sätt Tillåt återanvändning av sidinnehåll |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Sätt Ignorera korrupta objekt |
| [setRestrictedKeys](#setRestrictedKeys-java.lang.String:A-) | sätt Begränsade nycklar |
| [setReuseStreams](#setReuseStreams-boolean-) | sätt Återanvänd strömmar |
| [setUseStubs](#setUseStubs-boolean-) | Indikerar om stubbar ska användas under dupliceringsprocessen. Om alternativet är aktiverat kommer strömmarna att kopieras, annars kommer en länk till källströmmen att användas. Detta tillåter dig inte att stänga det kopierade dokumentet, men sparar på kopieringsprocessen och minnet. |

### Copier {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
Skapar en instans av Copier-klassen.

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
Duplicerar IPdfPrimitive

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
Skapar en kopia av objektet med alla beroende objekt.

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

hämta Tillåt återanvändning av sidinnehåll

**Returns:**
booleskt värde

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

hämta Ignorera korrupta objekt

**Returns:**
booleskt värde

### getRestrictedKeys {#getRestrictedKeys--}
```
public String [] getRestrictedKeys()
```

hämta Begränsade nycklar

**Returns:**
String[] array

### getReuseStreams {#getReuseStreams--}
```
public boolean getReuseStreams()
```

hämta Återanvänd strömmar

**Returns:**
booleskt värde

### getUseStubs {#getUseStubs--}
```
public boolean getUseStubs()
```

Indikerar om stubbar ska användas under dupliceringsprocessen. Om alternativet är aktiverat kommer strömmarna att kopieras, annars kommer en länk till källströmmen att användas. Detta tillåter dig inte att stänga det kopierade dokumentet, men sparar på kopieringsprocessen och minnet.

**Returns:**
booleskt värde

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

sätt Tillåt återanvändning av sidinnehåll

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Sätt Ignorera korrupta objekt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRestrictedKeys {#setRestrictedKeys-java.lang.String:A-}
sätt Begränsade nycklar

### setReuseStreams {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```

sätt Återanvänd strömmar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseStubs {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```

Indikerar om stubbar ska användas under dupliceringsprocessen. Om alternativet är aktiverat kommer strömmarna att kopieras, annars kommer en länk till källströmmen att användas. Detta tillåter dig inte att stänga det kopierade dokumentet, men sparar på kopieringsprocessen och minnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
