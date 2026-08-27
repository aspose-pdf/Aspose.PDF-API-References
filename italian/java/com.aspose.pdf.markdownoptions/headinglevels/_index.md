---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per lavorare con i livelli di intestazione basati sulla dimensione del carattere."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Rappresenta una classe per lavorare con i livelli di intestazione basati sulla dimensione del carattere.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | Crea una nuova istanza della classe HeadingLevels. |
| [HeadingLevels](#HeadingLevels-double-) | Crea una nuova istanza della classe HeadingLevels. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Aggiunge livelli di intestazione. |
| [estimateLevel](#estimateLevel-double-) | Stima il livello di intestazione possibile. Se fontSize non è trovato nell'elenco dei livelli, verrà restituito il livello più vicino a questo valore di fontSize. Se fontSize è al di fuori dei livelli di intestazione minimo e massimo specificati, il metodo restituirà false. |
| [findLevel](#findLevel-double-int:A-) | Trova il livello per la corrispondente fontSize. Cerca una corrispondenza esatta. |
| [getAllLevels](#getAllLevels--) | Ottiene tutti i livelli di intestazione. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

Crea una nuova istanza della classe HeadingLevels.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

Crea una nuova istanza della classe HeadingLevels.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold |  | Il valore di soglia per confrontare le dimensioni dei caratteri. All'interno della soglia, i livelli di intestazione sono gli stessi. Il valore predefinito della soglia è 0.01. |

### addLevels {#addLevels-java.lang.Iterable-}
Aggiunge livelli di intestazione.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Stima il livello di intestazione possibile. Se fontSize non è trovato nell'elenco dei livelli, verrà restituito il livello più vicino a questo valore di fontSize. Se fontSize è al di fuori dei livelli di intestazione minimo e massimo specificati, il metodo restituirà false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontSize |  | La dimensione del carattere. |

**Returns:**
Livello di intestazione.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

Trova il livello per la corrispondente fontSize. Cerca una corrispondenza esatta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontSize |  | La dimensione del carattere. |
| level |  | Il livello di intestazione corrispondente per la fontSize fornita. |

**Returns:**
False se la fontSize non è entro l'intervallo specificato.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Ottiene tutti i livelli di intestazione.

**Returns:**
IEnumerable of Double
