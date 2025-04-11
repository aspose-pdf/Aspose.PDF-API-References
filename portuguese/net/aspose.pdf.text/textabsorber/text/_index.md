---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: Propriedade TextAbsorber. Obtém o texto extraído que o TextAbsorber extrai do documento ou página PDF
type: docs
weight: 50
url: /pt/net/aspose.pdf.text/textabsorber/text/
---
## Propriedade TextAbsorber.Text

Obtém o texto extraído que o [`TextAbsorber`](../) extrai do documento ou página PDF.

```csharp
public virtual string Text { get; }
```

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