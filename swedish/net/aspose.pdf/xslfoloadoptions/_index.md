---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptions klass. Representerar alternativ för att ladda/importera XSLFO-fil till pdf-dokument
type: docs
weight: 11530
url: /sv/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions klass

Representerar alternativ för att ladda/importera XSL-FO-fil till pdf-dokument.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Skapar `XslFoLoadOptions` objekt utan xsl-data. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Skapar `XslFoLoadOptions` objekt med xsl-data. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Skapar `XslFoLoadOptions` objekt med xsl-data. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Basvägen/url från vilken relativa vägar till externa resurser (om några) som refereras i den laddade SVG-filen söks. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Hämtar eller ställer in flagga för att inaktivera eventuella licensbegränsningar för alla typsnitt vid inläsning av filen. När `true`, tillåter att utföra operationer med typsnitt som är förbjudna av en licens för detta typsnitt, till exempel tillåter att bädda in ett typsnitt i ett PDF-dokument även om licensreglerna inaktiverar inbäddning för detta typsnitt. Som standard `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representerar filformatet som [`LoadOptions`](../loadoptions/) beskriver. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Återkoppling för att hantera eventuella varningar som genereras. WarningHandler returnerar ReturnAction enum-element som specificerar antingen Fortsätt eller Avbryt. Fortsätt är standardåtgärden och inläsningsoperationen fortsätter, men användaren kan också returnera Avbryt, i vilket fall inläsningsoperationen ska upphöra. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Hämtar xsl-data för att konvertera xml till pdf-dokument. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList för att infoga värden i befintliga xls-parametrar. XLS-filen har parameter 'animal' utan värde: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); nu antar konverteraren att det finns en 'animal' parameter med värdet 'cat' i XLS-filen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Källan XSLFO-dokumentet kan innehålla formateringsfel. Denna enum uppräknar möjliga strategier för hantering av dessa fel. |

## Exempel

Följande exempel visar hur man konverterar XSL-FO-fil till PDF-fil

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
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

### Se Även

* klass [XmlLoadOptions](../xmlloadoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)