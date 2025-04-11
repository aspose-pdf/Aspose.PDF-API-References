---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber-Eigenschaft. Erhält den extrahierten Text, den der TextAbsorber aus dem PDF-Dokument oder der Seite extrahiert
type: docs
weight: 50
url: /de/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text-Eigenschaft

Erhält den extrahierten Text, den der [`TextAbsorber`](../) aus dem PDF-Dokument oder der Seite extrahiert.

```csharp
public virtual string Text { get; }
```

## Beispiele

Das Beispiel zeigt, wie man Text aus allen Seiten des PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [TextAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)