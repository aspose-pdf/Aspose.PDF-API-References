---
title: Class PclLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PclLoadOptions-Klasse. Stellt Optionen zum Laden (Importieren) einer PCL-Datei in ein PDF-Dokument dar
type: docs
weight: 8300
url: /de/net/aspose.pdf/pclloadoptions/
---
## PclLoadOptions-Klasse

Stellt Optionen zum Laden (Importieren) einer PCL-Datei in ein PDF-Dokument dar.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | Definiert die Batchgröße, wenn die batchweise Konvertierung für das Quell- und Zielformatpaar anwendbar ist. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft ein Flag ab oder setzt es, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF-Dokument, selbst wenn die Lizenzregeln das Einbetten dieser Schriftart deaktivieren. Standardmäßig `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und die Ladeoperation wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte die Ladeoperation eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | Definiert die Konvertierungsengine, die für die Konvertierung verwendet wird |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | Liste der Konvertierungsfehler. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | Ruft einen booleschen Wert ab oder setzt ihn, der angibt, ob PCL-Konvertierungsfehler unterdrückt werden sollen. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PCL-Datei in eine PDF-Datei konvertiert

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PCL File.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Schnittstelle [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)