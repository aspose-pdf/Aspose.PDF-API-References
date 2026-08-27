---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "La classe descrive l'elenco delle azioni."
type: docs
weight: 3680
url: /it/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

La classe descrive l'elenco delle azioni.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Aggiungi l'azione all'elenco delle azioni. |
| [delete](#delete-int-) | Rimuovi l'azione per indice. |
| [get_Item](#get_Item-int-) | Ottiene l'azione per il suo indice. |
| [getCount](#getCount--) | Ottiene il conteggio delle azioni. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Metodo interno |
| [iterator](#iterator--) | Ottiene l'enumeratore. |

### add {#add-com.aspose.pdf.PdfAction-}
Aggiungi l'azione all'elenco delle azioni.

### delete {#delete-int-}
```
public void delete(int index)
```

Rimuovi l'azione per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice dell'azione da rimuovere. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Ottiene l'azione per il suo indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Valore dell'indice dell'azione. |

**Returns:**
Indice di PdfAction se trovato; altrimenti, lancia @throws IndexOutOfRangeException IndexOutOfRangeException

### getCount {#getCount--}
```
public int getCount()
```

Ottiene il conteggio delle azioni.

**Returns:**
valore int

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

Metodo interno

**Returns:**
oggetto interno.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

Ottiene l'enumeratore.

**Returns:**
enumeratore PDfAction.
