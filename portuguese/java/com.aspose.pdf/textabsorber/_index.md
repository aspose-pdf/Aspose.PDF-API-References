---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa um objeto absorvedor de texto. Executa extração de texto e fornece acesso ao resultado via {@code TextAbsorber.Text} objeto. </p> <hr> <pre> O exemplo."
type: docs
weight: 4900
url: /pt/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> Representa um objeto absorvedor de texto. Executa a extração de texto e fornece acesso ao resultado via {@code TextAbsorber.Text} objeto. </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. // abrir documento Document doc = new Document(inFile); // criar objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceitar o absorvedor para a primeira página doc.getPages().get(1).accept(absorber); // obter o texto extraído String extractedText = absorber.getText(); </pre> <hr> <p> O objeto {@code TextAbsorber} é usado para extrair texto de um documento Pdf ou da página do documento. </p>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> Inicializa uma nova instância do {@code TextAbsorber}. </p> <hr> <pre> O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Executa extração de texto e fornece acesso ao texto extraído via {@code TextAbsorber.Text} objeto. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> Inicializa uma nova instância do {@code TextAbsorber}. </p> <hr> <pre> O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Executa extração de texto e fornece acesso ao texto extraído via {@code TextAbsorber.Text} objeto. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa uma nova instância do {@code TextAbsorber}. </p> <hr> <pre> O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Executa extração de texto e fornece acesso ao texto extraído via {@code TextAbsorber.Text} objeto. </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa uma nova instância do {@code TextAbsorber}. </p> <hr> <pre> O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Executa extração de texto e fornece acesso ao texto extraído via {@code TextAbsorber.Text} objeto. </p> |

## Métodos

| Método | Descrição |
| --- | --- |
| [getErrors](#getErrors--) | Lista de objetos {@code TextExtractionError}. Contém informações sobre erros encontrados durante a extração de texto. A busca por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho. |
| [getExtractionOptions](#getExtractionOptions--) | <p> Obtém opções de extração de texto. </p> <hr> <pre> O exemplo demonstra como definir o modo de formatação de texto puro e executar a extração de texto. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permite definir o modo de formatação de texto {@code TextExtractionOptions} durante a extração. O modo padrão é {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [getText](#getText--) | <p> Obtém o texto extraído que o {@code TextAbsorber} extrai no documento PDF ou página. </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | Obtém opções de pesquisa de texto. Permite definir um retângulo que delimita o texto extraído. Por padrão, o retângulo está vazio. Isso significa que apenas os limites da página definem a região de extração de texto. |
| [hasErrors](#hasErrors--) | O valor indica se erros foram encontrados durante a extração de texto. A pesquisa por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho. |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> Define opções de extração de texto. </p> <hr> <pre> O exemplo demonstra como definir o modo de formatação de texto puro e executar a extração de texto. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permite definir o modo de formatação de texto {@code TextExtractionOptions} durante a extração. O modo padrão é {@code TextExtractionOptions.TextFormattingMode.Pure} </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Define opções de pesquisa de texto. Permite definir um retângulo que delimita o texto extraído. Por padrão, o retângulo está vazio. Isso significa que apenas os limites da página definem a região de extração de texto. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extrai texto no documento especificado </p> <hr> <pre> O exemplo demonstra como extrair texto em um documento PDF. // abrir documento Document doc = new Document(inFile); // criar objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceitar o absorvedor em todas as páginas do documento absorber.visit(doc); // obter o texto extraído String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extrai texto na página especificada </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. // abrir documento Document doc = new Document(inFile); // criar objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceitar o absorvedor em todas as páginas do documento absorber.visit(doc.getPages(1)); // obter o texto extraído String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> Extrai texto no XForm especificado. </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. // abrir documento Document doc = new Document(inFile); // criar objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceitar o absorvedor em todas as páginas do documento absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // obter o texto extraído String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> Inicializa uma nova instância do {@code TextAbsorber}. </p> <hr> <pre> O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Executa extração de texto e fornece acesso ao texto extraído via {@code TextAbsorber.Text} objeto. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> Inicializa uma nova instância do {@code TextAbsorber}. </p> <hr> <pre> O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Executa extração de texto e fornece acesso ao texto extraído via {@code TextAbsorber.Text} objeto. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa uma nova instância do {@code TextAbsorber}. </p> <hr> <pre> O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Executa extração de texto e fornece acesso ao texto extraído via {@code TextAbsorber.Text} objeto. </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa uma nova instância do {@code TextAbsorber}. </p> <hr> <pre> O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Executa extração de texto e fornece acesso ao texto extraído via {@code TextAbsorber.Text} objeto. </p>

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

Lista de objetos {@code TextExtractionError}. Contém informações sobre erros encontrados durante a extração de texto. A busca por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho.

**Returns:**
Lista de objetos TextExtractionError

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> Obtém opções de extração de texto. </p> <hr> <pre> O exemplo demonstra como definir o modo de formatação de texto puro e executar a extração de texto. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permite definir o modo de formatação de texto {@code TextExtractionOptions} durante a extração. O modo padrão é {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

**Returns:**
Valor de TextExtractionOptions

### getText {#getText--}
```
public String getText()
```

<p> Obtém o texto extraído que o {@code TextAbsorber} extrai no documento PDF ou página. </p>

**Returns:**
String value <hr> <pre> O exemplo demonstra como extrair texto de todas as páginas do documento PDF. // abrir documento Document doc = new Document(inFile); // criar objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceitar o absorvedor em todas as páginas do documento doc.getPages().accept(absorber); // obter o texto extraído String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Obtém opções de pesquisa de texto. Permite definir um retângulo que delimita o texto extraído. Por padrão, o retângulo está vazio. Isso significa que apenas os limites da página definem a região de extração de texto.

**Returns:**
Valor de TextSearchOptions

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

O valor indica se erros foram encontrados durante a extração de texto. A pesquisa por erros será realizada somente se TextSearchOptions.LogTextExtractionErrors = true; e pode diminuir o desempenho.

**Returns:**
valor booleano

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> Define opções de extração de texto. </p> <hr> <pre> O exemplo demonstra como definir o modo de formatação de texto puro e executar a extração de texto. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Permite definir o modo de formatação de texto {@code TextExtractionOptions} durante a extração. O modo padrão é {@code TextExtractionOptions.TextFormattingMode.Pure} </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Define opções de pesquisa de texto. Permite definir um retângulo que delimita o texto extraído. Por padrão, o retângulo está vazio. Isso significa que apenas os limites da página definem a região de extração de texto.

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extrai texto no documento especificado </p> <hr> <pre> O exemplo demonstra como extrair texto em um documento PDF. // abrir documento Document doc = new Document(inFile); // criar objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceitar o absorvedor em todas as páginas do documento absorber.visit(doc); // obter o texto extraído String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extrai texto na página especificada </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. // abrir documento Document doc = new Document(inFile); // criar objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceitar o absorvedor em todas as páginas do documento absorber.visit(doc.getPages(1)); // obter o texto extraído String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> Extrai texto no XForm especificado. </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. // abrir documento Document doc = new Document(inFile); // criar objeto TextAbsorber para extrair texto TextAbsorber absorber = new TextAbsorber(); // aceitar o absorvedor em todas as páginas do documento absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // obter o texto extraído String extractedText = absorber.getText(); </pre>
