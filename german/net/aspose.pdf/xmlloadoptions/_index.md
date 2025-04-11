---
title: Class XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmlLoadOptions-Klasse. Stellt Optionen zum Laden/Importieren einer XML-Datei in ein PDF-Dokument dar
type: docs
weight: 11390
url: /de/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions-Klasse

Stellt Optionen zum Laden/Importieren einer XML-Datei in ein PDF-Dokument dar.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | Erstellt ein `XmlLoadOptions`-Objekt ohne XSL-Daten. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | Erstellt ein `XmlLoadOptions`-Objekt mit XSL-Daten. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | Erstellt ein `XmlLoadOptions`-Objekt mit XSL-Daten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft das Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF-Dokument, selbst wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Standardmäßig `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Ladevorgang eingestellt werden. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Ruft die XSL-Daten zum Konvertieren von XML in ein PDF-Dokument ab. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine XML-Datei in eine PDF-Datei konvertiert

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XML File.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialize XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)