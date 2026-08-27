---
title: "Document.Optimize"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document‑metod. Lineariserar dokumentet för att öppna den första sidan så snabbt som möjligt visa nästa sida eller följa en länk till nästa sida så snabbt som möjligt visa sidan stegvis när den anländer när data för en sida levereras över en långsam kanal visa den mest användbara datan först möjliggöra användarinteraktion såsom att följa en länk innan hela sidan har mottagits och visats. Att anropa denna metod sparar faktiskt inte dokumentet. Tvärtom förbereds dokumentet bara för att ha en optimerad struktur; anropa sedan Save för att få ett optimerat dokument"
type: docs
weight: 770
url: /sv/net/aspose.pdf/document/optimize/
---
## Document.Optimize method

Lineariserar document för att - öppna den första sidan så snabbt som möjligt; - visa nästa sida eller följa en länk till nästa sida så snabbt som möjligt; - visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal (visa den mest användbara datan först); - tillåta användarinteraktion, såsom att följa en länk, att utföras även innan hela sidan har mottagits och visats. Att anropa denna metod sparar faktiskt inte document. Tvärtom förbereds document bara för att ha en optimerad struktur, anropa sedan Save för att få ett optimerat document.

```csharp
public void Optimize()
```

### Exempel

Följande exempel visar hur man optimerar ett PDF-dokument för webben.

```csharp
[C#]
	// Sökvägen till din PDF‑fil.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Öppna dokument
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimera för webben
	pdfDocument.Optimize();

	// Spara utdata-dokument
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

### Se även

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


