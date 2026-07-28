---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase base abstracta para artefactos de paginación en un documento."
type: docs
weight: 3460
url: /es/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

Representa una clase base abstracta para artefactos de paginación en un documento.

## Métodos

| Método | Descripción |
| --- | --- |
| [getEndPage](#getEndPage--) | Obtiene o establece el número de página final para el artefacto. El valor debe ser mayor o igual a 0. Si se establece un valor menor que 0, se ajustará a 0. El valor predeterminado de 0 significa que no hay límites de página final. |
| [getStartPage](#getStartPage--) | Obtiene o establece el número de página inicial para el artefacto. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1. |
| [getSubset](#getSubset--) | Obtiene o establece el subconjunto de páginas al que se aplica el artefacto (p. ej., todas las páginas, páginas pares, páginas impares). |
| [setEndPage](#setEndPage-int-) | Obtiene o establece el número de página final para el artefacto. El valor debe ser mayor o igual a 0. Si se establece un valor menor que 0, se ajustará a 0. El valor predeterminado de 0 significa que no hay límites de página final. |
| [setStartPage](#setStartPage-int-) | Obtiene o establece el número de página inicial para el artefacto. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1. |
| [setSubset](#setSubset-int-) | Obtiene o establece el subconjunto de páginas al que se aplica el artefacto (p. ej., todas las páginas, páginas pares, páginas impares). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

Obtiene o establece el número de página final para el artefacto. El valor debe ser mayor o igual a 0. Si se establece un valor menor que 0, se ajustará a 0. El valor predeterminado de 0 significa que no hay límites de página final.

**Returns:**
valor int

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

Obtiene o establece el número de página inicial para el artefacto. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1.

**Returns:**
valor int

### getSubset {#getSubset--}
```
public final int getSubset()
```

Obtiene o establece el subconjunto de páginas al que se aplica el artefacto (p. ej., todas las páginas, páginas pares, páginas impares).

**Returns:**
valor int

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

Obtiene o establece el número de página final para el artefacto. El valor debe ser mayor o igual a 0. Si se establece un valor menor que 0, se ajustará a 0. El valor predeterminado de 0 significa que no hay límites de página final.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

Obtiene o establece el número de página inicial para el artefacto. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

Obtiene o establece el subconjunto de páginas al que se aplica el artefacto (p. ej., todas las páginas, páginas pares, páginas impares).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
