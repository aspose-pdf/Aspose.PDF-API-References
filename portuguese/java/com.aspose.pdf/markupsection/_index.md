---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma seção de marcação – a região retangular de uma página que contém texto e pode ser visualmente separada de outros blocos de texto."
type: docs
weight: 2890
url: /pt/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

Representa uma seção de marcação – a região retangular de uma página que contém texto e pode ser visualmente separada de outros blocos de texto.

## Métodos

| Método | Descrição |
| --- | --- |
| [getFragments](#getFragments--) | <p> Coleção de objetos {@code TextFragment} não vazios que estão dentro da seção. </p><hr> O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de pesquisa, propriedades do texto, e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc). |
| [getParagraphs](#getParagraphs--) | Coleção de objetos {@code MarkupParagraph} que estão dentro da seção. |
| [getRectangle](#getRectangle--) | Retângulo da seção |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Coleção de objetos {@code TextFragment} não vazios que estão dentro da seção. </p><hr> O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de pesquisa, propriedades do texto, e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc).

**Returns:**
lista de instâncias de TextFragment

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Coleção de objetos {@code MarkupParagraph} que estão dentro da seção.

**Returns:**
lista de instâncias de MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Retângulo da seção

**Returns:**
Instância de Rectangle
