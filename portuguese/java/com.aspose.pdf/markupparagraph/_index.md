---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um parágrafo."
type: docs
weight: 2880
url: /pt/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

Representa um parágrafo.

## Métodos

| Método | Descrição |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | Lista de números de página nos quais o parágrafo é continuado. Ela corresponderá à página onde o parágrafo começou se ele continuar na próxima coluna na mesma página. |
| [getFragments](#getFragments--) | <p> Coleção de objetos {@code TextFragment} não vazios do parágrafo. </p><hr> O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de pesquisa, propriedades do texto, e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc). |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> Linhas do parágrafo. Cada linha é representada por uma lista de fragmentos de texto. </p><hr> O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de pesquisa, propriedades do texto, e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc). |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | Pontos do polígono que descreve o parágrafo. O ponto inicial é o canto inferior esquerdo do parágrafo. E os pontos seguintes estão em sequência anti-horária. |
| [getSecondaryPoints](#getSecondaryPoints--) | Pontos do polígono secundário que descreve a continuação do parágrafo. Não será nulo se o parágrafo for continuado na próxima coluna ou página. O ponto inicial é o canto inferior esquerdo do parágrafo. E os pontos seguintes estão em sequência anti-horária. |
| [getText](#getText--) | Obtém o objeto de texto {@code string} que o objeto {@code MarkupParagraph} representa. |
| [setText](#setText-java.lang.String-) | Obtém ou define o texto do parágrafo. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

Lista de números de página nos quais o parágrafo é continuado. Ela corresponderá à página onde o parágrafo começou se ele continuar na próxima coluna na mesma página.

**Returns:**
lista de Integer

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Coleção de objetos {@code TextFragment} não vazios do parágrafo. </p><hr> O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de pesquisa, propriedades do texto, e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc).

**Returns:**
lista de instâncias de TextFragment

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> Linhas do parágrafo. Cada linha é representada por uma lista de fragmentos de texto. </p><hr> O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de pesquisa, propriedades do texto, e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc).

**Returns:**
lista de instâncias de TextFragment

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Pontos do polígono que descreve o parágrafo. O ponto inicial é o canto inferior esquerdo do parágrafo. E os pontos seguintes estão em sequência anti-horária.

**Returns:**
array de instâncias de Point

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

Pontos do polígono secundário que descreve a continuação do parágrafo. Não será nulo se o parágrafo for continuado na próxima coluna ou página. O ponto inicial é o canto inferior esquerdo do parágrafo. E os pontos seguintes estão em sequência anti-horária.

**Returns:**
lista de Point[]

### getText {#getText--}
```
public String getText()
```

Obtém o objeto de texto {@code string} que o objeto {@code MarkupParagraph} representa.

**Returns:**
valor String

### setText {#setText-java.lang.String-}
Obtém ou define o texto do parágrafo.
