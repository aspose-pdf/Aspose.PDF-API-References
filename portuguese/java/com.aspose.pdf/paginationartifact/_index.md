---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe base abstrata para artefatos de paginação em um documento."
type: docs
weight: 3460
url: /pt/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

Representa uma classe base abstrata para artefatos de paginação em um documento.

## Métodos

| Método | Descrição |
| --- | --- |
| [getEndPage](#getEndPage--) | Obtém ou define o número da página final para o artefato. O valor deve ser maior ou igual a 0. Se um valor menor que 0 for definido, ele será ajustado para 0. O valor padrão de 0 significa que não há limites de página final. |
| [getStartPage](#getStartPage--) | Obtém ou define o número da página inicial para o artefato. O valor deve ser maior ou igual a 1. Se um valor menor que 1 for definido, ele será ajustado para 1. |
| [getSubset](#getSubset--) | Obtém ou define o subconjunto de páginas ao qual o artefato se aplica (por exemplo, todas as páginas, páginas pares, páginas ímpares). |
| [setEndPage](#setEndPage-int-) | Obtém ou define o número da página final para o artefato. O valor deve ser maior ou igual a 0. Se um valor menor que 0 for definido, ele será ajustado para 0. O valor padrão de 0 significa que não há limites de página final. |
| [setStartPage](#setStartPage-int-) | Obtém ou define o número da página inicial para o artefato. O valor deve ser maior ou igual a 1. Se um valor menor que 1 for definido, ele será ajustado para 1. |
| [setSubset](#setSubset-int-) | Obtém ou define o subconjunto de páginas ao qual o artefato se aplica (por exemplo, todas as páginas, páginas pares, páginas ímpares). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

Obtém ou define o número da página final para o artefato. O valor deve ser maior ou igual a 0. Se um valor menor que 0 for definido, ele será ajustado para 0. O valor padrão de 0 significa que não há limites de página final.

**Returns:**
valor int

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

Obtém ou define o número da página inicial para o artefato. O valor deve ser maior ou igual a 1. Se um valor menor que 1 for definido, ele será ajustado para 1.

**Returns:**
valor int

### getSubset {#getSubset--}
```
public final int getSubset()
```

Obtém ou define o subconjunto de páginas ao qual o artefato se aplica (por exemplo, todas as páginas, páginas pares, páginas ímpares).

**Returns:**
valor int

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

Obtém ou define o número da página final para o artefato. O valor deve ser maior ou igual a 0. Se um valor menor que 0 for definido, ele será ajustado para 0. O valor padrão de 0 significa que não há limites de página final.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

Obtém ou define o número da página inicial para o artefato. O valor deve ser maior ou igual a 1. Se um valor menor que 1 for definido, ele será ajustado para 1.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

Obtém ou define o subconjunto de páginas ao qual o artefato se aplica (por exemplo, todas as páginas, páginas pares, páginas ímpares).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
