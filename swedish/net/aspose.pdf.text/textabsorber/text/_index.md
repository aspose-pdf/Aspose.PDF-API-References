---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber-egenskap. Hämtar extraherad text som TextAbsorber extraherar från PDF-dokumentet eller sidan
type: docs
weight: 50
url: /sv/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text-egenskap

Hämtar extraherad text som [`TextAbsorber`](../) extraherar från PDF-dokumentet eller sidan.

```csharp
public virtual string Text { get; }
```

## Exempel

Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet.

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

### Se Även

* klass [TextAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* sammansättning [Aspose.PDF](../../../)