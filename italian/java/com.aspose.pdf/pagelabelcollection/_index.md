---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta la raccolta di page label."
type: docs
weight: 3400
url: /it/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

Classe che rappresenta la raccolta di page label.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLabel](#getLabel-int-) | Ottiene l'etichetta di pagina per indice di pagina (l'indice di pagina parte da 0). |
| [getPages](#getPages--) | Ottiene gli indici di pagina nella collezione. |
| [removeLabel](#removeLabel-int-) | Rimuove l'etichetta per indice di pagina (l'indice di pagina parte da 0). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | Aggiorna l'etichetta per l'indice di pagina fornito (l'indice di pagina parte da 0). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

Ottiene l'etichetta di pagina per indice di pagina (l'indice di pagina parte da 0).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageIndex |  | Indice della pagina. |

**Returns:**
Etichetta di pagina per l'indice di pagina specificato o null se l'etichetta di pagina non esiste.

### getPages {#getPages--}
```
public int[] getPages()
```

Ottiene gli indici di pagina nella collezione.

**Returns:**
Array di interi che contiene gli indici delle pagine.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

Rimuove l'etichetta per indice di pagina (l'indice di pagina parte da 0).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageIndex |  | Indice della pagina dove l'etichetta deve essere eliminata. |

**Returns:**
true se l'operazione è stata eseguita con successo.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
Aggiorna l'etichetta per l'indice di pagina fornito (l'indice di pagina parte da 0).
