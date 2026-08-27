---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe descrive le regole che possono essere utilizzate per risolvere l'errore di Adobe Preflight \\\"Text cannot be mapped to Unicode\\\"."
type: docs
weight: 5380
url: /it/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

Questa classe descrive le regole che possono essere usate per risolvere l'errore Adobe Preflight "Il testo non può essere mappato su Unicode".

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | Inizializza una nuova istanza della classe {@link ToUnicodeProcessingRules}. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | Inizializza una nuova istanza della classe {@link ToUnicodeProcessingRules} con l'opzione specificata per rimuovere gli spazi dai nomi CMap. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | Inizializza una nuova istanza della classe {@link ToUnicodeProcessingRules} con le opzioni specificate. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | Alcuni font non forniscono informazioni sugli Unicode per alcuni simboli di testo. Questa mancanza di informazioni genera l'errore \"Text cannot be mapped to Unicode\". Usa questa opzione per mappare i simboli non collegati sul carattere Unicode \"space\" (codice 32). |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | Alcuni font hanno mappe di codici carattere ToUnicode con spazi nei nomi. Questi spazi potrebbero generare errori nella mappatura del testo Unicode. Questa opzione indica di rimuovere gli spazi dai nomi delle mappe di codici carattere ToUnicode. Per impostazione predefinita false. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | Alcuni font non forniscono informazioni sugli Unicode per alcuni simboli di testo. Questa mancanza di informazioni genera l'errore \"Text cannot be mapped to Unicode\". Usa questa opzione per mappare i simboli non collegati sul carattere Unicode \"space\" (codice 32). |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | Alcuni font hanno mappe di codici carattere ToUnicode con spazi nei nomi. Questi spazi potrebbero generare errori nella mappatura del testo Unicode. Questa opzione indica di rimuovere gli spazi dai nomi delle mappe di codici carattere ToUnicode. Per impostazione predefinita false. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

Inizializza una nuova istanza della classe {@link ToUnicodeProcessingRules}.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

Inizializza una nuova istanza della classe {@link ToUnicodeProcessingRules} con l'opzione specificata per rimuovere gli spazi dai nomi CMap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| removeSpaces |  | Valore booleano che indica se rimuovere gli spazi dai nomi CMap. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

Inizializza una nuova istanza della classe {@link ToUnicodeProcessingRules} con le opzioni specificate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| removeSpaces |  | Indica se gli spazi devono essere rimossi dai nomi CMap. |
| mapNonLinkedUnicodesOnSpace |  | Indica se i simboli Unicode non collegati devono essere mappati su spazi. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

Alcuni font non forniscono informazioni sugli Unicode per alcuni simboli di testo. Questa mancanza di informazioni genera l'errore \"Text cannot be mapped to Unicode\". Usa questa opzione per mappare i simboli non collegati sul carattere Unicode \"space\" (codice 32).

**Returns:**
valore booleano

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

Alcuni font hanno mappe di codici carattere ToUnicode con spazi nei nomi. Questi spazi potrebbero generare errori nella mappatura del testo Unicode. Questa opzione indica di rimuovere gli spazi dai nomi delle mappe di codici carattere ToUnicode. Per impostazione predefinita false.

**Returns:**
valore booleano

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

Alcuni font non forniscono informazioni sugli Unicode per alcuni simboli di testo. Questa mancanza di informazioni genera l'errore \"Text cannot be mapped to Unicode\". Usa questa opzione per mappare i simboli non collegati sul carattere Unicode \"space\" (codice 32).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

Alcuni font hanno mappe di codici carattere ToUnicode con spazi nei nomi. Questi spazi potrebbero generare errori nella mappatura del testo Unicode. Questa opzione indica di rimuovere gli spazi dai nomi delle mappe di codici carattere ToUnicode. Per impostazione predefinita false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
