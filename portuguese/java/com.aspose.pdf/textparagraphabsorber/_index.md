---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um objeto absorvedor de parágrafos de texto. Executa pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextParagraphAbsorber.TextParagraphs}."
type: docs
weight: 5220
url: /pt/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

Representa um objeto absorvedor de parágrafos de texto. Executa pesquisa de texto e fornece acesso aos resultados da pesquisa via coleção {@code TextParagraphAbsorber.TextParagraphs}.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> Inicializa uma nova instância do {@code TextParagraphAbsorber} com a coleção de retângulos. </p> |

## Métodos

| Método | Descrição |
| --- | --- |
| [getRectangles](#getRectangles--) | Obtém os retângulos que o {@code TextParagraphAbsorber} usa para pesquisar parágrafos de texto no documento PDF ou na página. |
| [getTextParagraphs](#getTextParagraphs--) | Obtém a coleção de ocorrências de pesquisa que são apresentadas com objetos {@code TextParagraph}. |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | Define os retângulos que o {@code TextParagraphAbsorber} usa para pesquisar parágrafos de texto no documento PDF ou na página. |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Define a coleção de ocorrências de pesquisa que são apresentadas com objetos {@code TextParagraph}. |
| [visit](#visit-com.aspose.pdf.Page-) | Executa a pesquisa na página especificada. |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> Inicializa uma nova instância do {@code TextParagraphAbsorber} com a coleção de retângulos. </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

Obtém os retângulos que o {@code TextParagraphAbsorber} usa para pesquisar parágrafos de texto no documento PDF ou na página.

**Returns:**
matriz de retângulos

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

Obtém a coleção de ocorrências de pesquisa que são apresentadas com objetos {@code TextParagraph}.

**Returns:**
Valor de TextParagraphCollection

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
Define os retângulos que o {@code TextParagraphAbsorber} usa para pesquisar parágrafos de texto no documento PDF ou na página.

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
Define a coleção de ocorrências de pesquisa que são apresentadas com objetos {@code TextParagraph}.

### visit {#visit-com.aspose.pdf.Page-}
Executa a pesquisa na página especificada.
