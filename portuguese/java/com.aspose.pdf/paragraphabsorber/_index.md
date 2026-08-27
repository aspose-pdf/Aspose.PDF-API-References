---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa um objeto absorvedor de objetos de estrutura de página, como seções e parágrafos. Executa busca por seções e parágrafos de texto e fornece acesso para.</p>"
type: docs
weight: 3470
url: /pt/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> Representa um objeto absorvedor de objetos de estrutura de página, como seções e parágrafos. Executa busca por seções e parágrafos de texto e fornece acesso a retângulos e polígonos que os descrevem no espaço de coordenadas de texto. Também executa busca de segmentos de texto e fornece acesso aos resultados da busca via coleções {@code TextFragments} agrupadas por elementos de estrutura. </p> O exemplo demonstra como encontrar o primeiro segmento de texto de cada parágrafo na primeira página do documento PDF e destacá‑lo. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Quando a busca for concluída, a coleção {@code ParagraphAbsorber.PageMarkups} conterá objetos {@code PageMarkup} que representam a estrutura da página por coleções de {@code MarkupSection} e {@code MarkupParagraph}. O objeto {@code TextFragment} fornece acesso ao texto da ocorrência da busca, às propriedades do texto e permite editar o texto e alterar o estado do texto (fonte, tamanho da fonte, cor etc).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | Inicializa uma nova instância do {@code ParagraphAbsorber} que executa busca por seções/parágrafos do documento ou página. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> Inicializa uma nova instância do {@code ParagraphAbsorber} que executa busca por seções/parágrafos do documento ou página. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | Inicializa uma nova instância do {@code ParagraphAbsorber} que executa busca por seções/parágrafos do documento ou página. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | Inicializa uma nova instância do {@code ParagraphAbsorber} que executa busca por seções/parágrafos do documento ou página. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | Obtém a coleção de {@code PageMarkup} que foram absorvidos. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | Obtém o ParagraphAbsorberOptions. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> Obtém ou define o valor que indica quantas vezes buscas sequenciais por elementos mais finos da estrutura serão realizadas. A profundidade de busca padrão é 3. Isso significa três buscas por seções divididas horizontalmente (cabeçalhos, parágrafos etc.) e três buscas por seções divididas verticalmente (colunas). </p><hr> Aumentar esse valor pode levar a uma leve diminuição de desempenho sem alterações visíveis nos resultados da busca. Diminuir esse valor pode levar a uma determinação incorreta de parágrafos em seções. Não recomendamos definir um valor menor que o padrão se você não deseja obter apenas elementos 'grossos' da estrutura da página. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Obtém ou define o TextReplaceOptions. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Obtém ou define o valor que indica se as linhas de texto iniciais de uma próxima seção podem ser tratadas como continuação do último parágrafo de uma seção anterior. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Obtém ou define o valor que indica se as linhas de texto iniciais de uma próxima seção podem ser tratadas como continuação do último parágrafo de uma seção anterior. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | Define o ParagraphAbsorberOptions. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> Obtém ou define o valor que indica quantas vezes buscas sequenciais por elementos mais finos da estrutura serão realizadas. A profundidade de busca padrão é 3. Isso significa três buscas por seções divididas horizontalmente (cabeçalhos, parágrafos etc.) e três buscas por seções divididas verticalmente (colunas). </p><hr> Aumentar esse valor pode levar a uma leve diminuição de desempenho sem alterações visíveis nos resultados da busca. Diminuir esse valor pode levar a uma determinação incorreta de parágrafos em seções. Não recomendamos definir um valor menor que o padrão se você não deseja obter apenas elementos 'grossos' da estrutura da página. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Obtém ou define o TextReplaceOptions. |
| [visit](#visit-com.aspose.pdf.Document-) | Executa busca por seções e parágrafos no {@link Document} especificado. |
| [visit](#visit-com.aspose.pdf.Page-) | Executa busca na {@code Page} especificada. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

Inicializa uma nova instância do {@code ParagraphAbsorber} que executa busca por seções/parágrafos do documento ou página.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> Inicializa uma nova instância do {@code ParagraphAbsorber} que executa busca por seções/parágrafos do documento ou página. </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sectionsSearchDepth |  | Número de buscas sequenciais para elementos de estrutura mais finos que serão realizadas. <hr> Veja a propriedade {@code ParagraphAbsorber.SectionsSearchDepth} para mais dicas sobre o parâmetro. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
Inicializa uma nova instância do {@code ParagraphAbsorber} que executa busca por seções/parágrafos do documento ou página.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
Inicializa uma nova instância do {@code ParagraphAbsorber} que executa busca por seções/parágrafos do documento ou página.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

Obtém a coleção de {@code PageMarkup} que foram absorvidos.

**Returns:**
Lista de instâncias de PageMarkup

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

Obtém o ParagraphAbsorberOptions.

**Returns:**
Instância de ParagraphAbsorberOptions

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> Obtém ou define o valor que indica quantas vezes buscas sequenciais por elementos mais finos da estrutura serão realizadas. A profundidade de busca padrão é 3. Isso significa três buscas por seções divididas horizontalmente (cabeçalhos, parágrafos etc.) e três buscas por seções divididas verticalmente (colunas). </p><hr> Aumentar esse valor pode levar a uma leve diminuição de desempenho sem alterações visíveis nos resultados da busca. Diminuir esse valor pode levar a uma determinação incorreta de parágrafos em seções. Não recomendamos definir um valor menor que o padrão se você não deseja obter apenas elementos 'grossos' da estrutura da página.

**Returns:**
valor int

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

Obtém ou define o TextReplaceOptions.

**Returns:**
Instância de TextReplaceOptions

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

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
Define o ParagraphAbsorberOptions.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> Obtém ou define o valor que indica quantas vezes buscas sequenciais por elementos mais finos da estrutura serão realizadas. A profundidade de busca padrão é 3. Isso significa três buscas por seções divididas horizontalmente (cabeçalhos, parágrafos etc.) e três buscas por seções divididas verticalmente (colunas). </p><hr> Aumentar esse valor pode levar a uma leve diminuição de desempenho sem alterações visíveis nos resultados da busca. Diminuir esse valor pode levar a uma determinação incorreta de parágrafos em seções. Não recomendamos definir um valor menor que o padrão se você não deseja obter apenas elementos 'grossos' da estrutura da página.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Obtém ou define o TextReplaceOptions.

### visit {#visit-com.aspose.pdf.Document-}
Executa busca por seções e parágrafos no {@link Document} especificado.

### visit {#visit-com.aspose.pdf.Page-}
Executa busca na {@code Page} especificada.
