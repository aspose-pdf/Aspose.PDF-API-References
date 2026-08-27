---
title: "Klass ApsLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.ApsLoadOptions‑klass. Klassen beskriver APS‑inläsningsalternativ."
type: docs
weight: 2850
url: /sv/net/aspose.pdf/apsloadoptions/
---
## ApsLoadOptions class

Klassen beskriver APS-inläsningsalternativ.

```csharp
public class ApsLoadOptions : LoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ApsLoadOptions](apsloadoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |

## Exempel

Följande exempel visar hur man konverterar en APS‑fil till en PDF‑fil

```csharp
[C#]
	// Sökvägen till dokumentkatalogen.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Sökvägen till din APS‑fil.
	string apsFile = Path.Combine(dataDir, "APS-to-PDF.aps");

	// Sökvägen till utdata‑PDF‑filen.
	string pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf");

	// Initiera ApsLoadOptions \t
	ApsLoadOptions apsLoadOptions = new ApsLoadOptions();

	// Initiera Document med ApsLoadOptions     
	using (Document pdfDocument = new Document(apsFile, apsLoadOptions))
	{
	 
		// Spara PDF‑fil
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your APS File.
    Dim apsFile = Path.Combine(dataDir, "APS-to-PDF.aps")
	
    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf")
 
    ' Initialize ApsLoadOptions    
    Dim apsLoadOptions As ApsLoadOptions = New ApsLoadOptions()
 
	' Initialize Document wiht ApsLoadOptions
    Using pdfDocument As Document = New Document(apsFile, apsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Se även

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


