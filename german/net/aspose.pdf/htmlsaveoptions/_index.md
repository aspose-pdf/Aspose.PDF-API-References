---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptions-Klasse. Speicheroptionen für den Export in das Html-Format
type: docs
weight: 5560
url: /de/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions-Klasse

Speicheroptionen für den Export in das Html-Format

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | Initialisiert eine neue Instanz der `HtmlSaveOptions`-Klasse. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | Initialisiert eine neue Instanz der `HtmlSaveOptions`-Klasse. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | Initialisiert eine neue Instanz der `HtmlSaveOptions`-Klasse. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | Initialisiert eine neue Instanz der `HtmlSaveOptions`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Definiert die Batchgröße, wenn die gestapelte Konvertierung auf das Quell- und Zielformatpaar anwendbar ist. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ruft den booleschen Wert ab oder legt ihn fest, der angibt, ob Schriftglykene während der Vorbereitung von APS-Seiten zwischengespeichert werden. Verbessert die Leistung der Konvertierung von PDF in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ruft den booleschen Wert ab oder legt ihn fest, der angibt, ob das Response-Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Ruft das Flag ab oder legt es fest, das angibt, ob gefundene SVG-Grafiken (falls vorhanden) während des Speicherns in das SVGZ-Format komprimiert (zipped) werden. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Wenn das Attribut ConvertMarkedContentToLayers auf true gesetzt ist, werden alle Elemente innerhalb eines PDF-markierten Inhalts (Schicht) in ein HTML-Div mit dem Attribut "data-pdflayer" eingefügt, das den Schichtnamen angibt. Dieser Schichtname wird aus den optionalen Eigenschaften des PDF-markierten Inhalts extrahiert. Wenn dieses Attribut false (standardmäßig) ist, werden keine Schichten aus dem PDF-markierten Inhalt erstellt. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Gibt den Namen einer installierten Schriftart an, die verwendet wird, um jede Dokumentenschriftart zu ersetzen, die nicht eingebettet und nicht im System installiert ist. Wenn null, wird die Standardschriftart verwendet. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Ruft den [`HtmlDocumentType`](../htmldocumenttype/) ab oder legt ihn fest. |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Mit dieser Eigenschaft können Sie explizit definieren, welche Seiten des Dokuments konvertiert werden sollen. Seiten in dieser Liste müssen 1-basierte Nummern haben. Das heißt, gültige Seitenzahlen müssen aus dem Bereich (1...[NumberOfPagesInConvertedDocument]) entnommen werden. Die Reihenfolge der Seiten in dieser Liste hat keinen Einfluss auf ihre Reihenfolge in der Ergebnis-HTML-Seite(n) - in den Ergebnisseiten werden sie immer in der Reihenfolge angezeigt, in der sie im Quell-PDF vorhanden sind. Wenn diese Liste null ist (wie standardmäßig), werden alle Seiten konvertiert. Wenn eine Seitenzahl dieser Liste außerhalb des Bereichs der vorhandenen Seiten (1-[amountOfPagesInDocument]) liegt, wird eine Ausnahme ausgelöst. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Dieses Attribut aktiviert die Funktionalität zum Extrahieren von Bildern oder Texten für PDF-Dokumente mit OCR-Unterlayer. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob das HTML als festes Layout erstellt wird. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Dieses Attribut gibt den vollständigen Breitentext für den Flussmodus an, FixedLayout = false. |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Schriftquellen von vorab gespeicherten Schriftarten. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Text mit der angegebenen Größe oder kleiner wird während der Konvertierung ignoriert. Wir entfernen diesen Text nicht, wir ignorieren ihn und übertragen ihn nicht in die Ausgabedatei. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, dass Fehler im Zusammenhang mit der Abwesenheit von Schriftarten ignoriert werden. true - bedeutet, dass Fehler aufgrund fehlender Schriftarten ignoriert werden. Textsegmente, die auf falsche Ressourcen verweisen, werden während der Verarbeitung übersprungen. false ist standardmäßig. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Ruft die Auflösung für die Bilddarstellung ab oder legt sie fest. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Dieses Attribut legt die minimale Breite der grafischen Pfadlinie fest. Wenn die Dicke der Linie weniger als 1px beträgt, rundet Adobe Acrobat sie auf diesen Wert. Dieses Attribut kann verwendet werden, um dieses Verhalten für HTML-Browser zu emulieren. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Dieses Attribut schaltet den Modus ein, in dem Textglykene nicht in Wörter und Zeichenfolgen gruppiert werden. Dieser Modus ermöglicht es, die maximale Präzision bei der Positionierung von Glyphe auf der Seite beizubehalten, und kann für die Konvertierung von Dokumenten mit Musiknoten oder Glyphen verwendet werden, die separat platziert werden sollten. Dieser Parameter wird nur angewendet, wenn der Wert des FixedLayout-Attributs true ist. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Wenn das Attribut RenderTextAsImage auf true gesetzt ist, wird der Text aus der Quelle zu einem Bild in HTML. Kann nützlich sein, um Text nicht auswählbar zu machen oder wenn HTML-Text nicht richtig gerendert wird. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format der Datenspeicherung. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Gibt an, dass die vollständige Schriftart gespeichert wird, unterstützt nur True Type Fonts. Standardmäßig ist SaveFullFont = false und der Konverter speichert die Teilmenge der ursprünglichen Schriftart, die benötigt wird, um den Text des Dokuments anzuzeigen. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Dieses Attribut gibt eine sequenzielle Gruppierung von Glyphen und Wörtern in Zeichenfolgen an. Zum Beispiel haben Tags und Wörter eine andere Reihenfolge im konvertierten HTML und Sie möchten, dass sie übereinstimmen. Dieser Parameter wird nur angewendet, wenn der Wert des FixedLayout-Attributs true ist. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Wenn der Mehrseitenmodus ausgewählt ist (d.h. 'SplitIntoPages' ist 'true'), definiert dieses Attribut, ob für jede Ergebnis-HTML-Seite eine separate CSS-Datei erstellt werden soll. Standardmäßig ist dieses Attribut false, sodass eine große gemeinsame CSS für alle erstellten Seiten erstellt wird. Die Gesamtgröße aller in diesem Modus generierten CSS (eine CSS pro Seite) ist normalerweise viel größer als die Größe einer großen CSS-Datei, da in diesem Fall CSS-Klassen in mehreren CSS-Dateien für jede Seite dupliziert werden. Daher sollte diese Einstellung nur verwendet werden, wenn Sie an einer zukünftigen Verarbeitung jeder HTML-Seite unabhängig interessiert sind, und daher die Größe der CSS jeder einzelnen Seite das kritischste Problem ist. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Ruft das Flag ab oder legt es fest, das angibt, ob jede Seite des Quelldokuments in ihr eigenes Ziel-HTML-Dokument konvertiert wird, d.h. ob das Ergebnis-HTML in mehrere HTML-Seiten aufgeteilt wird. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Ruft den Titel der HTML-Seite ab oder legt ihn fest. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Das Flag zum Kombinieren von Bildfragmenten zu einem Bild. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Wenn das Attribut UseZOrder auf true gesetzt ist, werden Grafiken und Text entsprechend der Z-Reihenfolge im ursprünglichen PDF-Dokument zum resultierenden HTML-Dokument hinzugefügt. Wenn dieses Attribut false ist, wird alle Grafiken als einzelne Schicht platziert, was einige unerwünschte Effekte für überlappende Objekte verursachen kann. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback zur Behandlung von Warnungen, die generiert werden. Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speicherprozess wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, in diesem Fall sollte der Speicherprozess eingestellt werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Dieses Parameter definiert erforderliche Antialiasing-Maßnahmen während der Konvertierung von zusammengesetzten Hintergrundbildern von PDF nach HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Wenn der PDFtoHTML-Konverter die Ergebnis-CSS generiert, werden CSS-Klassennamen (etwas wie ".stl_01 {}" ... ".stl_NN {}") generiert und im Ergebnis-CSS verwendet. Diese Eigenschaft ermöglicht es, den Klassennamen-Präfix zwangsweise festzulegen. Wenn Sie möchten, dass alle Klassennamen mit 'my_prefix_' beginnen (d.h. etwas wie 'my_prefix_1' ... 'my_prefix_NNN'), weisen Sie einfach 'my_prefix_' dieser Eigenschaft vor der Konvertierung zu. Wenn diese Eigenschaft unberührt bleibt (d.h. null als Wert belassen wird), generiert der Konverter die Klassennamen selbst (es wird etwas wie ".stl_01 {}" ... ".stl_NN {}" sein). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Dieses Feld kann eine Speicherstrategie enthalten, die während der Konvertierung von PDF nach HTML verwendet werden muss (sofern vorhanden), um das Speichern von CSS, das mit dem erstellten HTML-Dokument als Ganzes oder mit seinen Seiten (wenn mehrere HTML-Seiten generiert werden) verbunden ist, zu behandeln. Wenn Sie die CSS-Datei auf eine bestimmte Weise behandeln möchten, erstellen Sie einfach die entsprechende Methode und weisen Sie den daraus erstellten Delegaten dieser Eigenschaft zu. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Das Ergebnis der Konvertierung kann eine oder mehrere HTML-Seiten enthalten. Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung einer HTML-Seite implementiert (genauer gesagt - Markup-HTML, ohne extern verlinkte Dateien, falls vorhanden), die während der Konvertierung erstellt wurde. In diesem Fall kann die Verarbeitung (wie das Speichern des HTML der Seite im Stream oder auf der Festplatte) in diesem benutzerdefinierten Code erfolgen. In diesem Fall müssen alle notwendigen Schritte zum Speichern der HTML-Seite im Code der bereitgestellten Methode unternommen werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Wenn die Verarbeitung aus irgendeinem Grund vom Code des Konverters selbst und nicht im benutzerdefinierten Code durchgeführt werden muss, setzen Sie im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen 'htmlSavingInfo': es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst auf die gleiche Weise durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code zur Verarbeitung gäbe. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Dieser Handler kann verwendet werden, um Ereignisse zum Fortschritt der Konvertierung zu behandeln, z.B. kann er verwendet werden, um einen Fortschrittsbalken oder Nachrichten über die aktuelle Anzahl der verarbeiteten Seiten anzuzeigen. Ein Beispiel für den Code des Handlers, der den Fortschritt in der Konsole anzeigt, ist: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Dieses Feld kann eine Speicherstrategie enthalten, die während der Konvertierung für die benutzerdefinierte Behandlung der erstellten referenzierten Ressourcen-Dateien (wie Bilder und Schriftarten), die mit den Knoten des gespeicherten HTML verbunden sind, verwendet werden muss. Diese Strategie muss Ressourcen verarbeiten und einen String zurückgeben, der die wünschenswerte URL der gespeicherten Ressource im generierten HTML darstellt. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Dieses Feld kann eine benutzerdefinierte Methode enthalten, die die URL (oder URL-Vorlage, wenn die Mehrseitengenerierung aktiviert ist - siehe Details unten) des betreffenden CSS zurückgibt, wie sie im generierten Ergebnis-HTML eingefügt werden sollte. Wenn Sie möchten, dass der Konverter eine bestimmte URL anstelle des Standard-CSS-Dateinamens in das generierte CSS einfügt, erstellen Sie einfach die Methode, die die gewünschte URL generiert, und fügen Sie sie in diese Eigenschaft ein. Wenn das Flag 'SplitCssIntoPages' gesetzt ist, muss diese benutzerdefinierte Strategie (sofern vorhanden) nicht die genaue URL des CSS zurückgeben, sondern vielmehr eine Vorlagenzeichenfolge, die (nach der Ersetzung des Platzhalters mit der Seitennummer mit der string.Format()-Funktion im Konverter) in die URL für das CSS dieser oder jener Seite aufgelöst werden kann. Beispiele für erwartete Rückgabestrings in diesem Fall sind: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Liste der in PDF eingebetteten Schriftartnamen, die nicht in HTML eingebettet werden. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Definiert eine spezielle Regel zur Kodierung, um die PDF-Dekodierung für das aktuelle Dokument anzupassen. |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Definiert den Schriftartspeichermodus, der während des Speicherns von PDF in das gewünschte Format verwendet wird. |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Manchmal sind spezifische Anforderungen an die Generierung von HTML-Markup vorhanden. Dieses Parameter definiert die HTML-Vorbereitungsmodi, die während der Konvertierung von PDF in HTML verwendet werden können, um solche spezifischen Anforderungen zu erfüllen. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Verarbeitet Seiten in mehreren Threads. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Legt den Modus der Positionierung von Buchstaben in Wörtern im Ergebnis-HTML fest. |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Dieses Attribut stellt eine Reihe von Einstellungen dar, die zum Zeichnen eines Rahmens (falls vorhanden) im Ergebnis-HTML-Dokument um den Bereich verwendet werden, der die Quell-PDF-Seite darstellt. Im Wesentlichen betrifft es die Anzeige der Papierkanten der Seite, nicht den Seitenrahmen, der in der PDF-Seite selbst referenziert wird. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Dieses Attribut stellt eine Reihe von zusätzlichen Seitenrändern (falls vorhanden) im Ergebnis-HTML-Dokument um den Bereich dar, der die Quell-PDF-Seite darstellt. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Wenn das Attribut 'SplitOnPages=false' ist, wird das gesamte HTML, das alle Eingabe-PDF-Seiten darstellt, in eine große Ergebnis-HTML-Datei eingefügt. Dieses Flag definiert, ob das Ergebnis-HTML so generiert wird, dass der Fluss der Bereiche, die PDF-Seiten im Ergebnis-HTML darstellen, von der Bildschirmauflösung des Betrachters abhängt. Angenommen, die Breite des Bildschirms auf der Seite des Betrachters ist groß genug, um 2 oder mehr Seiten nebeneinander in horizontaler Richtung anzuzeigen. Wenn dieses Flag auf true gesetzt ist, wird diese Möglichkeit genutzt (so viele Seiten wie möglich werden in horizontaler Richtung nebeneinander angezeigt, dann wird die nächste horizontale Gruppe von Seiten unter der ersten angezeigt). Andernfalls fließen die Seiten so: die nächste Seite geht immer unter die vorherige. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Es definiert, ob referenzierte Dateien (HTML, Schriftarten, Bilder, CSS) in die Haupt-HTML-Datei eingebettet oder als separate binäre Entitäten generiert werden. |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | Konvertierte PDFs können Rasterbilder enthalten. Dieses Parameter definiert, wie sie während der Konvertierung von PDF nach HTML behandelt werden sollen. |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Definiert, ob im erstellten HTML der obere und untere leere Bereich ohne Inhalt (falls vorhanden) entfernt werden. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDFs können Texte enthalten, die von anderen Elementen (z.B. von Bildern) beschattet werden, aber in Acrobat Reader in die Zwischenablage ausgewählt werden können (normalerweise geschieht dies, wenn das Dokument Bilder und OCR-Text enthält, die daraus extrahiert wurden). Diese Einstellung sagt dem Konverter, ob wir solche Texte als transparente auswählbare Texte im Ergebnis-HTML speichern müssen, um das Verhalten von Acrobat Reader nachzuahmen (ansonsten werden solche Texte normalerweise als verborgen gespeichert, nicht verfügbar zum Kopieren in die Zwischenablage). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDFs können transparente Texte enthalten, die in die Zwischenablage ausgewählt werden können (normalerweise geschieht dies, wenn das Dokument Bilder und OCR-Text enthält, die daraus extrahiert wurden). Diese Einstellung sagt dem Konverter, ob wir solche Texte als transparente auswählbare Texte im Ergebnis-HTML speichern müssen. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Ruft den Pfad zum Verzeichnis ab oder legt ihn fest, in dem alle Bilder gespeichert werden müssen, wenn sie während des Speicherns des Dokuments als HTML gefunden werden. Wenn das Parameter leer oder null ist, werden Bilddateien (falls vorhanden) zusammen mit anderen Dateien, die mit HTML verknüpft sind, gespeichert. Es hat keinen Einfluss, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die relevante Bilddatei zu verarbeiten. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Ruft den Pfad zum Verzeichnis ab oder legt ihn fest, in dem nur SVG-Bilder gespeichert werden müssen, wenn sie während des Speicherns des Dokuments als HTML gefunden werden. Wenn das Parameter leer oder null ist, werden SVG-Dateien (falls vorhanden) zusammen mit anderen Bilddateien (nahe der Ausgabedatei) oder in einem speziellen Ordner für Bilder gespeichert (wenn dies in der Option SpecialImagesFolderIfAny angegeben ist). Es hat keinen Einfluss, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die relevante Bilddatei zu verarbeiten. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen), die aus mehreren gleichen Kachel-Hintergrundbildern bestehen, die nebeneinander platziert sind. In diesem Fall erzeugen Renderer der Zielformate (z.B. MsWord für DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen der Hintergrundbilder, da ihre Techniken zur Glättung der Bildkanten (Antialiasing) sich von denen von Acrobat Reader unterscheiden. Wenn es so aussieht, als ob das exportierte Dokument sichtbare Grenzen zwischen Teilen derselben Hintergrundbilder enthält, versuchen Sie bitte, diese Einstellung zu verwenden, um diesen unerwünschten Effekt loszuwerden. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, verwenden Sie diese Option also bitte nur, wenn es wirklich notwendig ist. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF selbst enthält keine Unterstreichungsmarkierungen für Texte. Es wird mit einer Linie unter dem Text emuliert. Diese Option ermöglicht es dem Konverter, zu erraten, dass diese oder jene Linie eine Textunterstreichung ist und diese Information in CSS anstelle der grafischen Darstellung der Unterstreichung zu setzen. |

## Beispiele

Das folgende Beispiel zeigt, wie man eine PDF-Datei in eine HTML-Datei konvertiert.

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### Siehe auch

* Klasse [UnifiedSaveOptions](../unifiedsaveoptions/)
* Schnittstelle [IPageSetOptions](../ipagesetoptions/)
* Schnittstelle [IPipelineOptions](../ipipelineoptions/)
* Namensraum [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)