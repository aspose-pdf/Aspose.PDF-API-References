---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un formato di numero di pagina che include un indice, il numero totale di pagine e un delimitatore."
type: docs
weight: 150
url: /it/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Rappresenta un formato di numero di pagina che include un indice, il numero totale di pagine e un delimitatore.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Ottiene o imposta il delimitatore usato nel formato del numero di pagina. La stringa formattata verrà aggiornata in base al delimitatore specificato. |
| [getIndex](#getIndex--) | Ottiene o imposta il componente indice di pagina del formato del numero di pagina. La stringa formattata includerà un segnaposto per l'indice di pagina. |
| [getOffset](#getOffset--) | Ottiene o imposta l'offset da aggiungere all'indice di pagina. |
| [getPageNumberString](#getPageNumberString-int-int-) | Restituisce una stringa formattata che rappresenta il numero di pagina in base alle impostazioni correnti. |
| [getTotalNum](#getTotalNum--) | Ottiene o imposta il componente del numero totale di pagine del formato del numero di pagina. La stringa formattata includerà un segnaposto per il numero totale di pagine. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Ottiene o imposta il delimitatore usato nel formato del numero di pagina. La stringa formattata verrà aggiornata in base al delimitatore specificato. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Ottiene o imposta il componente indice di pagina del formato del numero di pagina. |
| [setOffset](#setOffset-int-) | Ottiene o imposta l'offset da aggiungere all'indice di pagina. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Ottiene o imposta il componente del numero totale di pagine del formato del numero di pagina. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Ottiene o imposta il delimitatore usato nel formato del numero di pagina. La stringa formattata verrà aggiornata in base al delimitatore specificato.

**Returns:**
valore String

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Ottiene o imposta il componente indice di pagina del formato del numero di pagina. La stringa formattata includerà un segnaposto per l'indice di pagina.

**Returns:**
istanza PageIndex

### getOffset {#getOffset--}
```
public final int getOffset()
```

Ottiene o imposta l'offset da aggiungere all'indice di pagina.

**Returns:**
valore int

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Restituisce una stringa formattata che rappresenta il numero di pagina in base alle impostazioni correnti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber |  | Il numero di pagina corrente. |
| conteggio |  | Il numero totale di pagine. |

**Returns:**
Una stringa di numero di pagina formattata.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Ottiene o imposta il componente del numero totale di pagine del formato del numero di pagina. La stringa formattata includerà un segnaposto per il numero totale di pagine.

**Returns:**
istanza PageTotalNum

### setDelimiter {#setDelimiter-java.lang.String-}
Ottiene o imposta il delimitatore usato nel formato del numero di pagina. La stringa formattata verrà aggiornata in base al delimitatore specificato.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Ottiene o imposta il componente indice di pagina del formato del numero di pagina.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Ottiene o imposta l'offset da aggiungere all'indice di pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Ottiene o imposta il componente del numero totale di pagine del formato del numero di pagina.
