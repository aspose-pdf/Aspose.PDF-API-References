---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di TextAbsorber. Ottiene il testo estratto che il TextAbsorber estrae dal documento o dalla pagina PDF
type: docs
weight: 50
url: /it/net/aspose.pdf.text/textabsorber/text/
---
## Proprietà TextAbsorber.Text

Ottiene il testo estratto che il [`TextAbsorber`](../) estrae dal documento o dalla pagina PDF.

```csharp
public virtual string Text { get; }
```

## Esempi

L'esempio dimostra come estrarre testo da tutte le pagine del documento PDF.

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

### Vedi Anche

* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)