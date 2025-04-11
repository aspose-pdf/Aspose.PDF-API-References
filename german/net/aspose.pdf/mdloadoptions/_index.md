---
title: Class MdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MdLoadOptions-Klasse. Ladeoptionen für die Konvertierung im Markdown-Format
type: docs
weight: 6940
url: /de/net/aspose.pdf/mdloadoptions/
---
## MdLoadOptions-Klasse

Ladeoptionen für die Konvertierung im Markdown-Format.

```csharp
public class MdLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MdLoadOptions](mdloadoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft ein Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel erlaubt es, eine Schriftart in ein PDF-Dokument einzubetten, auch wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Standardmäßig `false`. |
| [IsPriorityCssPageRule](../../aspose.pdf/mdloadoptions/isprioritycsspagerule/) { get; set; } | Ruft ein Flag ab oder legt es fest, das angibt, dass @page-Regeln, die in CSS definiert sind, die in PageInfo definierten Werte überschreiben. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [PageInfo](../../aspose.pdf/mdloadoptions/pageinfo/) { get; set; } | Ruft die Seiteninformationen des Dokuments ab oder legt sie fest. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und die Ladeoperation wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte die Ladeoperation eingestellt werden. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine MD-Datei in eine PDF-Datei konvertiert.

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

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)