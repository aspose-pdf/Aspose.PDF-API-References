---
title: "Klass XslFoLoadOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.XslFoLoadOptions-klass. Representerar alternativ för att ladda/importera XSLFO-fil till pdf-dokument"
type: docs
weight: 11720
url: /sv/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

Representerar alternativ för att läsa in/importera XSL-FO‑fil till pdf‑dokument.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Skapar `XslFoLoadOptions`-objekt utan xsl-data. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Skapar `XslFoLoadOptions`-objekt med xsl-data. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Skapar `XslFoLoadOptions`-objekt med xsl-data. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Basvägen/url som relativa sökvägar till externa resurser (om några) som refereras i den inlästa SVG-filen söks från. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller anger en flagga för att inaktivera alla licensrestriktioner för alla teckensnitt vid inläsning av filen. När `true` tillåts operationer med ett teckensnitt som är förbjudet av dess licens, till exempel att bädda in ett teckensnitt i ett PDF‑dokument även om licensreglerna förbjuder inbäddning av detta teckensnitt. Standardvärdet är `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformat som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återuppringning för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Hämtar xsl-data för att konvertera xml till pdf-dokument. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList för att infoga värden i befintliga xls-parametrar  XLS-filen har parametern 'animal' utan värde: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); nu antar konverteraren att det finns en 'animal'-parameter med värdet 'cat' i XLS-filen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Källdokumentet XSLFO kan innehålla formateringsfel. Denna enum listar möjliga strategier för hantering av dessa fel. |

## Exempel

Följande exempel visar hur man konverterar XSL-FO-fil till PDF-fil

```csharp
[C#]
// Sökvägen till dokumentkatalogen.
string dataDir = @"YOUR_DATA_DIRECTORY";

// Sökvägen till din XSL-FO-fil.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// Sökvägen till utdata‑PDF‑filen.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initiera XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Spara PDF‑fil
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Se även

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


