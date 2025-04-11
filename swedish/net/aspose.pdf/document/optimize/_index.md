---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmetod. Linjärisera dokumentet för att öppna den första sidan så snabbt som möjligt, visa nästa sida eller följ en länk till nästa sida så snabbt som möjligt, visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal, visa den mest användbara informationen först, tillåta användarinteraktion såsom att följa en länk att utföras även innan hela sidan har mottagits och visats. Att anropa denna metod sparar faktiskt inte dokumentet. Tvärtom är dokumentet endast förberett för att ha en optimerad struktur, anropa sedan Spara för att få det optimerade dokumentet.
type: docs
weight: 750
url: /sv/net/aspose.pdf/document/optimize/
---
## Document.Optimize metod

Linjärisera dokumentet för att - öppna den första sidan så snabbt som möjligt; - visa nästa sida eller följ en länk till nästa sida så snabbt som möjligt; - visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal (visa den mest användbara informationen först); - tillåta användarinteraktion, såsom att följa en länk, att utföras även innan hela sidan har mottagits och visats. Att anropa denna metod sparar faktiskt inte dokumentet. Tvärtom är dokumentet endast förberett för att ha en optimerad struktur, anropa sedan Spara för att få det optimerade dokumentet.

```csharp
public void Optimize()
```

### Exempel

Följande exempel visar hur man optimerar ett PDF-dokument för webben.

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

### Se Även

* klass [Document](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)