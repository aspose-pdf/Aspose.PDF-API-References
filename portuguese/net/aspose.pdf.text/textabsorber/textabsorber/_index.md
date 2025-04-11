---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Construtor do TextAbsorber. Inicializa uma nova instância do TextAbsorber
type: docs
weight: 10
url: /pt/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Inicializa uma nova instância do [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Observações

Realiza a extração de texto e fornece acesso ao texto extraído através do objeto [`Text`](../text/).

## Exemplos

O exemplo demonstra como extrair texto de todas as páginas do documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Veja Também

* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Inicializa uma nova instância do [`TextAbsorber`](../) com opções de extração.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opções de extração de texto |

## Observações

Realiza a extração de texto e fornece acesso ao texto extraído através do objeto [`Text`](../text/).

## Exemplos

O exemplo demonstra como extrair texto de todas as páginas do documento PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Veja Também

* classe [TextExtractionOptions](../../textextractionoptions/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Inicializa uma nova instância do [`TextAbsorber`](../) com opções de extração e pesquisa de texto.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opções de extração de texto |
| textSearchOptions | TextSearchOptions | Opções de pesquisa de texto |

## Observações

Realiza a extração de texto e fornece acesso ao texto extraído através do objeto [`Text`](../text/).

### Veja Também

* classe [TextExtractionOptions](../../textextractionoptions/)
* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Inicializa uma nova instância do [`TextAbsorber`](../) com opções de pesquisa de texto.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Opções de pesquisa de texto |

## Observações

Realiza a extração de texto e fornece acesso ao texto extraído através do objeto [`Text`](../text/).

### Veja Também

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)