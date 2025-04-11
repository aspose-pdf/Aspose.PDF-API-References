---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptions-Klasse. Stellt Optionen zum Laden/Importieren einer XSLFO-Datei in ein PDF-Dokument dar
type: docs
weight: 11530
url: /de/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions-Klasse

Stellt Optionen zum Laden/Importieren einer XSL-FO-Datei in ein PDF-Dokument dar.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Erstellt ein `XslFoLoadOptions`-Objekt ohne XSL-Daten. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Erstellt ein `XslFoLoadOptions`-Objekt mit XSL-Daten. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Erstellt ein `XslFoLoadOptions`-Objekt mit XSL-Daten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | Der Basis-Pfad/URL, von dem aus relative Pfade zu externen Ressourcen (sofern vorhanden) gesucht werden, die in der geladenen SVG-Datei referenziert sind. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft den Wert ab oder legt den Wert fest, um Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF-Dokument, selbst wenn die Lizenzregeln das Einbetten dieser Schriftart deaktivieren. Standardmäßig `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und die Ladeoperation wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte die Ladeoperation eingestellt werden. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Ruft die XSL-Daten zum Konvertieren von XML in ein PDF-Dokument ab. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList zum Einfügen von Werten in vorhandene XLS-Parameter. Die XLS-Datei hat den Parameter 'animal' ohne Wert: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); jetzt geht der Konverter davon aus, dass es einen 'animal'-Parameter mit dem Wert 'cat' in der XLS-Datei gibt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Das Quell-XSLFO-Dokument kann Formatierungsfehler enthalten. Dieses Enum enumeriert mögliche Strategien zur Handhabung dieser Fehler. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine XSL-FO-Datei in eine PDF-Datei konvertiert.

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

### Siehe auch

* Klasse [XmlLoadOptions](../xmlloadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)