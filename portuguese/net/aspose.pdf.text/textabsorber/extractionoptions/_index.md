---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextAbsorber. Obtém ou define opções de extração de texto
type: docs
weight: 30
url: /pt/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## Propriedade TextAbsorber.ExtractionOptions

Obtém ou define opções de extração de texto.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Observações

Permite definir o modo de formatação de texto [`TextExtractionOptions`](../../textextractionoptions/) durante a extração. O modo padrão é Puro

## Exemplos

O exemplo demonstra como definir o modo de formatação de texto Puro e realizar a extração de texto.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

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