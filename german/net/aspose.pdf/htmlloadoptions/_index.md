---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlLoadOptions-Klasse. Stellt Optionen zum Laden/Importieren einer HTML-Datei in ein PDF-Dokument dar
type: docs
weight: 5530
url: /de/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions-Klasse

Stellt Optionen zum Laden/Importieren einer HTML-Datei in ein PDF-Dokument dar.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Erstellt Ladeoptionen zum Konvertieren von HTML in ein PDF-Dokument mit leerem Basis-Pfad. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Erstellt Ladeoptionen zum Konvertieren von HTML in ein PDF-Dokument mit definiertem Basis-Pfad. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Der Basis-Pfad/URL für die HTML-Datei. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ruft den Wert ab oder legt fest, ob die Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei deaktiviert werden sollen. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF-Dokument, auch wenn die Lizenzregeln das Einbetten dieser Schriftart deaktivieren. Standardmäßig `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Ruft den Wert ab oder legt fest, welche Medientypen während des Renderns verwendet werden. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Ruft den Wert ab oder legt das Attribut fest, das die beim Parsen dieses Dokuments verwendete Kodierung angibt. Wenn dieses Attribut null ist, wird die Kodierung aus dem Zeichensatzattribut des Dokuments bestimmt. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Ruft den Wert ab oder legt fest, ob Schriftarten in das Ergebnisdokument eingebettet werden. |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Ruft den Wert ab oder legt das Flag fest, das angibt, dass @page-Regeln, die in CSS definiert sind, die in PageInfo definierten Werte überschreiben. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Ruft den Wert ab oder legt fest, ob das gesamte Dokument auf einer einzelnen Seite gerendert werden soll. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Stellt das Dateiformat dar, das von [`LoadOptions`](../loadoptions/) beschrieben wird. |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Ruft den Wert ab oder legt die Seiteninformationen des Dokuments fest. |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Ruft den Wert ab oder legt die Layoutoption fest. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein Element des ReturnAction-Enums zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Ladevorgang eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Manchmal ist es notwendig, die Verwendung des internen Ladeprogramms für externe Ressourcen (wie Bilder oder CSS) zu vermeiden und eine benutzerdefinierte Methode bereitzustellen, die die angeforderten Ressourcen von irgendwoher abruft. Zum Beispiel ist bei der Verwendung von Aspose.PDF in der Cloud der direkte Zugriff auf referenzierte Dateien unmöglich: In diesem Fall sollte benutzerdefinierter Code in eine spezielle Methode eingefügt werden, und ein Delegat, der auf diese Methode verweist, sollte diesem Attribut zugewiesen werden. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Wenn das Laden von externen Daten, die in HTML referenziert sind, Anmeldeinformationen erfordert, können Sie diese in dieses Parameter einfügen - sie werden beim Laden der externen Ressourcen verwendet. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine HTML-Datei in eine PDF-Datei konvertiert.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Siehe auch

* Klasse [LoadOptions](../loadoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)