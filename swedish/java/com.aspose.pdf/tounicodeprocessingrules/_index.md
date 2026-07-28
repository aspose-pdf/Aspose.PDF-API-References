---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass beskriver regler som kan användas för att lösa Adobe Preflight-felet \"Text cannot be mapped to Unicode\"."
type: docs
weight: 5380
url: /sv/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

Denna klass beskriver regler som kan användas för att lösa Adobe Preflight‑felet "Text cannot be mapped to Unicode".

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | Initierar en ny instans av klassen {@link ToUnicodeProcessingRules}. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | Initierar en ny instans av klassen {@link ToUnicodeProcessingRules} med det angivna alternativet för att ta bort mellanslag från CMap‑namn. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | Initierar en ny instans av klassen {@link ToUnicodeProcessingRules} med angivna alternativ. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | Vissa teckensnitt tillhandahåller inte information om Unicode för vissa textsymboler. Denna brist på information ger felet "Text cannot be mapped to Unicode". Använd detta flagg för att mappa icke‑länkade symboler till Unicode‑"space" (kod 32). |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | Vissa teckensnitt har ToUnicode‑teckenkodskartor med mellanslag i namn. Dessa mellanslag kan orsaka fel vid Unicode‑textmappning. Detta flagg anger att mellanslag ska tas bort från namn på ToUnicode‑teckenkodskartor. Standardvärdet är falskt. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | Vissa teckensnitt tillhandahåller inte information om Unicode för vissa textsymboler. Denna brist på information ger felet "Text cannot be mapped to Unicode". Använd detta flagg för att mappa icke‑länkade symboler till Unicode‑"space" (kod 32). |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | Vissa teckensnitt har ToUnicode‑teckenkodskartor med mellanslag i namn. Dessa mellanslag kan orsaka fel vid Unicode‑textmappning. Detta flagg anger att mellanslag ska tas bort från namn på ToUnicode‑teckenkodskartor. Standardvärdet är falskt. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

Initierar en ny instans av klassen {@link ToUnicodeProcessingRules}.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

Initierar en ny instans av klassen {@link ToUnicodeProcessingRules} med det angivna alternativet för att ta bort mellanslag från CMap‑namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| removeSpaces |  | Ett booleskt värde som anger om mellanslag ska tas bort från CMap‑namn. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

Initierar en ny instans av klassen {@link ToUnicodeProcessingRules} med angivna alternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| removeSpaces |  | Anger om mellanslag ska tas bort från CMap‑namn. |
| mapNonLinkedUnicodesOnSpace |  | Anger om icke‑länkade Unicode‑symboler ska mappas till mellanslag. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

Vissa teckensnitt tillhandahåller inte information om Unicode för vissa textsymboler. Denna brist på information ger felet "Text cannot be mapped to Unicode". Använd detta flagg för att mappa icke‑länkade symboler till Unicode‑"space" (kod 32).

**Returns:**
booleskt värde

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

Vissa teckensnitt har ToUnicode‑teckenkodskartor med mellanslag i namn. Dessa mellanslag kan orsaka fel vid Unicode‑textmappning. Detta flagg anger att mellanslag ska tas bort från namn på ToUnicode‑teckenkodskartor. Standardvärdet är falskt.

**Returns:**
booleskt värde

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

Vissa teckensnitt tillhandahåller inte information om Unicode för vissa textsymboler. Denna brist på information ger felet "Text cannot be mapped to Unicode". Använd detta flagg för att mappa icke‑länkade symboler till Unicode‑"space" (kod 32).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

Vissa teckensnitt har ToUnicode‑teckenkodskartor med mellanslag i namn. Dessa mellanslag kan orsaka fel vid Unicode‑textmappning. Detta flagg anger att mellanslag ska tas bort från namn på ToUnicode‑teckenkodskartor. Standardvärdet är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
