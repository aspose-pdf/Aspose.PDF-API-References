---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Referência da API Aspose.PDF para Java"
description: "Marcação de página representada por coleções de {@code MarkupSection} e {@code MarkupParagraph}."
type: docs
weight: 3420
url: /pt/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

Marcação de página representada por coleções de {@code MarkupSection} e {@code MarkupParagraph}.

## Métodos

| Método | Descrição |
| --- | --- |
| [getNumber](#getNumber--) | Obtém o número da página processada. |
| [getParagraphs](#getParagraphs--) | Obtém a coleção de {@code MarkupParagraph} que foi encontrada na página. |
| [getRectangle](#getRectangle--) | Obtém o retângulo da página processada. |
| [getSections](#getSections--) | Obtém a coleção de {@code MarkupSection} que foi encontrada na página. |
| [getTextFragments](#getTextFragments--) | <p> Obtém a coleção de {@code TextFragment} que foi encontrada na página. </p><hr> O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de pesquisa, às propriedades do texto e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc). |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Obtém ou define o valor que indica se as linhas de texto iniciais de uma próxima seção podem ser tratadas como continuação do último parágrafo de uma seção anterior. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Obtém ou define o valor que indica se as linhas de texto iniciais de uma próxima seção podem ser tratadas como continuação do último parágrafo de uma seção anterior. |

### getNumber {#getNumber--}
```
public int getNumber()
```

Obtém o número da página processada.

**Returns:**
valor int

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Obtém a coleção de {@code MarkupParagraph} que foi encontrada na página.

**Returns:**
Lista de instâncias de MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo da página processada.

**Returns:**
objeto Rectangle

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

Obtém a coleção de {@code MarkupSection} que foi encontrada na página.

**Returns:**
Lista de instâncias de MarkupSection

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> Obtém a coleção de {@code TextFragment} que foi encontrada na página. </p><hr> O objeto {@code TextFragment} fornece acesso ao texto da ocorrência de pesquisa, às propriedades do texto e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc).

**Returns:**
Lista de instâncias de TextFragment

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Obtém ou define o valor que indica se as linhas de texto iniciais de uma próxima seção podem ser tratadas como continuação do último parágrafo de uma seção anterior.

**Returns:**
valor booleano

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Obtém ou define o valor que indica se as linhas de texto iniciais de uma próxima seção podem ser tratadas como continuação do último parágrafo de uma seção anterior.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
