---
title: Class MhtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MhtLoadOptions-Klasse. Stellt Optionen für das Laden/Importieren von .mht-Dateien in ein PDF-Dokument dar
type: docs
weight: 6970
url: /de/net/aspose.pdf/mhtloadoptions/
---
## MhtLoadOptions-Klasse

Stellt Optionen für das Laden/Importieren von .mht-Dateien in ein PDF-Dokument dar.

```csharp
public sealed class MhtLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MhtLoadOptions](mhtloadoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft das Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF-Dokument, auch wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Standardmäßig `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | Ruft die Seiteninformationen des Dokuments ab oder legt sie fest |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Ladevorgang eingestellt werden. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine MHT-Datei in eine PDF-Datei konvertiert

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MHT File.
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// Initialize MhtLoadOptions	
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MHT File.
    Dim mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf")
 
    ' Initialize MhtLoadOptions
    Dim mhtLoadOptions As MhtLoadOptions = New MhtLoadOptions()
 
    Using pdfDocument As Document = New Document(mhtFile, mhtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```
	
### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)