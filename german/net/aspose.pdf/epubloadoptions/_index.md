---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubLoadOptions-Klasse. Enthält Optionen zum Laden/Importieren einer EPUB-Datei in ein PDF-Dokument
type: docs
weight: 4050
url: /de/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions-Klasse

Enthält Optionen zum Laden/Importieren einer EPUB-Datei in ein PDF-Dokument.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Erstellt Standardladeoptionen zum Konvertieren einer EPUB-Datei in ein PDF-Dokument. Standard-PDF-Seitengröße - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Erstellt Ladeoptionen mit der angegebenen Seitengröße. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Ruft das benutzerdefinierte CSS ab oder legt es fest, das beim Öffnen des Epub-Dokuments angewendet werden soll. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft ein Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF-Dokument, auch wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Standardmäßig `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Ruft eine Referenz auf ein Objekt ab, das die Randinformationen darstellt. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Ruft die Ausgabeseitengröße für den Import ab oder legt sie fest. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und die Ladeoperation wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte die Ladeoperation eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Stellt den Modus der Nutzung des Randbereichs dar - definiert die Behandlung von Anweisungen (falls vorhanden) des CSS des importierten Dokuments in Bezug auf die Nutzung von Rändern. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ACHTUNG! Die Funktion ist implementiert, wurde jedoch noch nicht in die öffentliche API aufgenommen, da ein Blockierungsproblem in der OSHARED-Schicht für das Beispiel-Dokument aufgetreten ist. Stellt den Modus der Nutzung der Seitengröße während der Konvertierung dar. Formate (wie HTML, EPUB usw.) haben normalerweise ein schwebendes Design, sodass sie die erforderliche Seitengröße anpassen können. Manchmal hat der Inhalt jedoch bestimmte horizontale Positionen oder Größen, die es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu bringen. In diesem Fall können wir definieren, was in diesem Fall zu tun ist (d.h. wenn die Größe des Inhalts nicht in die erforderliche ursprüngliche Seitengröße des resultierenden PDF-Dokuments passt). |

## Beispiele

Das folgende Beispiel zeigt, wie man eine EPUB-Datei in eine PDF-Datei konvertiert

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)