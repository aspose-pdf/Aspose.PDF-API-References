---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber property. Gets extracted text that the TextAbsorber extracts on the PDF document or page
type: docs
weight: 50
url: /net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

Gets extracted text that the [`TextAbsorber`](../) extracts on the PDF document or page.

```csharp
public virtual string Text { get; }
```

## Examples

The example demonstrates how to extract text from all pages of the PDF document.

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

### See Also

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


