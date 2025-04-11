---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXLoadOptions-Klasse. Stellt Optionen zum Laden/Importieren von TeX-Dateien in ein PDF-Dokument dar
type: docs
weight: 10370
url: /de/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions-Klasse

Stellt Optionen zum Laden/Importieren von TeX-Dateien in ein PDF-Dokument dar.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Ruft einen bestimmten Wert für Datums-/Zeitprimitive wie Jahr, Monat, Tag und Uhrzeit ab oder legt ihn fest. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft ein Flag ab oder legt es fest, um Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, z. B. das Einbetten einer Schriftart in ein PDF-Dokument, selbst wenn die Lizenzregeln das Einbetten dieser Schriftart deaktivieren. Standardmäßig `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Ruft das TeX-Eingangsverzeichnis ab oder legt es fest. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Ruft den Namen des Jobs ab oder legt ihn fest. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Ruft ein Flag ab oder legt es fest, das Ligaturen in allen Schriftarten deaktiviert. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Ruft das TeX-Ausgangsverzeichnis ab oder legt es fest. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Ruft ein Flag ab oder legt es fest, das das Rasterisieren von mathematischen Formeln erlaubt. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Ruft das Flag ab oder legt es fest, das angibt, ob der TeX-Job zweimal ausgeführt werden muss, falls beispielsweise Verweise in den Eingabe-TeX-Dateien vorhanden sind. Im Allgemeinen ist dieses Verhalten nützlich, wenn die Engine während des Satzprozesses einige Daten sammelt und in einer Hilfsdatei speichert, alles beim ersten Durchlauf. Und beim zweiten Durchlauf verwendet die Engine diese Daten irgendwie. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Ruft das TeX erforderliche Eingangsverzeichnis ab oder legt es fest. Erforderliche Eingaben sind die Dateien, die irgendwie in die Haupt-.tex-Datei aufgenommen werden, z. B. Pakete, für die es keine integrierte Unterstützung gibt. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Ruft ein Flag ab oder legt es fest, das angibt, ob die Terminalausgabe auf der Konsole angezeigt werden soll. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Ruft ein Flag ab oder legt es fest, das angibt, ob Schriftarten in der Ausgabedatei unterteilt werden sollen oder nicht. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und die Ladeoperation wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte die Ladeoperation eingestellt werden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Ruft das Ergebnis für das Laden und Kompilieren von TeX ab - ob alles reibungslos verlief oder ob es Kommentare/Fehler gab. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine TeX-Datei in eine PDF-Datei konvertiert

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)