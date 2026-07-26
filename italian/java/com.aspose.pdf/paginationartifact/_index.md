---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe base astratta per gli artefatti di impaginazione in un documento."
type: docs
weight: 3460
url: /it/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

Rappresenta una classe base astratta per gli artefatti di impaginazione in un documento.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEndPage](#getEndPage--) | Ottiene o imposta il numero di pagina finale per l'artefatto. Il valore deve essere maggiore o uguale a 0. Se viene impostato un valore inferiore a 0, verrà regolato a 0. Il valore predefinito di 0 indica che non ci sono limiti di pagina finale. |
| [getStartPage](#getStartPage--) | Ottiene o imposta il numero di pagina iniziale per l'artefatto. Il valore deve essere maggiore o uguale a 1. Se viene impostato un valore inferiore a 1, verrà regolato a 1. |
| [getSubset](#getSubset--) | Ottiene o imposta il sottoinsieme di pagine a cui si applica l'artefatto (ad esempio, tutte le pagine, pagine pari, pagine dispari). |
| [setEndPage](#setEndPage-int-) | Ottiene o imposta il numero di pagina finale per l'artefatto. Il valore deve essere maggiore o uguale a 0. Se viene impostato un valore inferiore a 0, verrà regolato a 0. Il valore predefinito di 0 indica che non ci sono limiti di pagina finale. |
| [setStartPage](#setStartPage-int-) | Ottiene o imposta il numero di pagina iniziale per l'artefatto. Il valore deve essere maggiore o uguale a 1. Se viene impostato un valore inferiore a 1, verrà regolato a 1. |
| [setSubset](#setSubset-int-) | Ottiene o imposta il sottoinsieme di pagine a cui si applica l'artefatto (ad esempio, tutte le pagine, pagine pari, pagine dispari). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

Ottiene o imposta il numero di pagina finale per l'artefatto. Il valore deve essere maggiore o uguale a 0. Se viene impostato un valore inferiore a 0, verrà regolato a 0. Il valore predefinito di 0 indica che non ci sono limiti di pagina finale.

**Returns:**
valore int

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

Ottiene o imposta il numero di pagina iniziale per l'artefatto. Il valore deve essere maggiore o uguale a 1. Se viene impostato un valore inferiore a 1, verrà regolato a 1.

**Returns:**
valore int

### getSubset {#getSubset--}
```
public final int getSubset()
```

Ottiene o imposta il sottoinsieme di pagine a cui si applica l'artefatto (ad esempio, tutte le pagine, pagine pari, pagine dispari).

**Returns:**
valore int

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

Ottiene o imposta il numero di pagina finale per l'artefatto. Il valore deve essere maggiore o uguale a 0. Se viene impostato un valore inferiore a 0, verrà regolato a 0. Il valore predefinito di 0 indica che non ci sono limiti di pagina finale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

Ottiene o imposta il numero di pagina iniziale per l'artefatto. Il valore deve essere maggiore o uguale a 1. Se viene impostato un valore inferiore a 1, verrà regolato a 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

Ottiene o imposta il sottoinsieme di pagine a cui si applica l'artefatto (ad esempio, tutte le pagine, pagine pari, pagine dispari).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
