---
title: Class TxtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TxtLoadOptions klass. Laddningsalternativ för TXT till PDF-konvertering
type: docs
weight: 11130
url: /sv/net/aspose.pdf/txtloadoptions/
---
## TxtLoadOptions klass

Laddningsalternativ för TXT till PDF-konvertering.

```csharp
public class TxtLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TxtLoadOptions](txtloadoptions/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller sätter en flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformatet som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och laddningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall laddningsoperationen ska upphöra. |

## Exempel

Följande exempel visar hur man konverterar en TXT-fil till en PDF-fil

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TXT File.
	string txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf");

	// Initialize TxtLoadOptions	
	TxtLoadOptions txtLoadOptions = new TxtLoadOptions();
		
	using (Document pdfDocument = new Document(txtFile, txtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TXT File.
    Dim txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf")
 
    ' Initialize TxtLoadOptions
    Dim txtLoadOptions As TxtLoadOptions = New TxtLoadOptions()
 
    Using pdfDocument As Document = New Document(txtFile, txtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)