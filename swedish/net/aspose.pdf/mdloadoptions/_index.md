---
title: Class MdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MdLoadOptions klass. Laddningsalternativ för konvertering av Markdown-format
type: docs
weight: 6940
url: /sv/net/aspose.pdf/mdloadoptions/
---
## MdLoadOptions klass

Laddningsalternativ för konvertering av Markdown-format.

```csharp
public class MdLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MdLoadOptions](mdloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller ställer in flaggan för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [IsPriorityCssPageRule](../../aspose.pdf/mdloadoptions/isprioritycsspagerule/) { get; set; } | Hämtar eller ställer in flaggan som specificerar att @page-regler definierade i css kommer att åsidosätta värden som definieras i PageInfo. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformatet som [`LoadOptions`](../loadoptions/) beskriver. |
| [PageInfo](../../aspose.pdf/mdloadoptions/pageinfo/) { get; set; } | Hämtar eller ställer in dokumentets sidinformation |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-elementet som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och inläsningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall inläsningsoperationen ska upphöra. |

## Exempel

Följande exempel visar hur man konverterar en MD-fil till en PDF-fil

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MD File.
	string mdFile = Path.Combine(dataDir, "MD-to-PDF.md");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf");

	// Initialize MdLoadOptions	
	MdLoadOptions mdLoadOptions = new MdLoadOptions();
		
	using (Document pdfDocument = new Document(mdFile, mdLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MD File.
    Dim mdFile = Path.Combine(dataDir, "MD-to-PDF.md")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf")
 
    ' Initialize MdLoadOptions  
    Dim mdLoadOptions As MdLoadOptions = New MdLoadOptions()
 
    Using pdfDocument As Document = New Document(mdFile, mdLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Se Även

* klass [LoadOptions](../loadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)