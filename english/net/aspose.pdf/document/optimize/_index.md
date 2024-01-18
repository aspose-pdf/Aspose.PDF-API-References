---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Document method. Linearize the document in order to  open the first page as quickly as possible  display next page or follow by link to the next page as quickly as possible  display the page incrementally as it arrives when data for a page is delivered over a slow channel display the most useful data first  permit user interaction such as following a link to be performed even before the entire page has been received and displayed. Invoking this method doesnt actually saves the document. On the contrary the document only is prepared to have optimized structure call then Save to get optimized document
type: docs
weight: 720
url: /net/aspose.pdf/document/optimize/
---
## Document.Optimize method

Linearize the document in order to - open the first page as quickly as possible; - display next page or follow by link to the next page as quickly as possible; - display the page incrementally as it arrives when data for a page is delivered over a slow channel (display the most useful data first); - permit user interaction, such as following a link, to be performed even before the entire page has been received and displayed. Invoking this method doesn't actually saves the document. On the contrary the document only is prepared to have optimized structure, call then Save to get optimized document.

```csharp
public void Optimize()
```

### Examples

The following example shows how to optimize a PDF document for the web.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimize for web
	pdfDocument.Optimize();

	// Save output document
	pdfDocument.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
	
    ' Open document
    Using pdfDocument As Document = New Document(pdfFilePath)

        ' Optimize for web
        pdfDocument.Optimize()

        ' Save output document
        pdfDocument.Save(pdfFilePath)
    End Using
```

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


