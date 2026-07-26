---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Speicheroptionen für den Export ins HTML‑Format"
type: docs
weight: 1990
url: /de/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

Speicheroptionen für den Export ins HTML‑Format

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | Initialisiert eine neue Instanz der HtmlSaveOptions‑Klasse. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | Initialisiert eine neue Instanz der {@code HtmlSaveOptions}‑Klasse. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | Initialisiert eine neue Instanz der HtmlSaveOptions‑Klasse. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | Initialisiert eine neue Instanz der HtmlSaveOptions‑Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | Wenn das Attribut 'SplitOnPages=false' gesetzt ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, nicht in einzelne HTML‑Seiten aufgeteilt, sondern in einer großen Ergebnis‑HTML‑Datei zusammengefasst. Jede Quell‑PDF‑Seite wird jedoch in HTML mit ihrem eigenen rechteckigen Bereich dargestellt (falls nötig können diese Bereiche mit dem speziellen Attribut 'PageBorderIfAny' begrenzt werden, um die Kanten des Seitenpapiers zu zeigen). Dieser Parameter definiert die Breite des Randes, der zwingend um die ausgegebenen HTML‑Bereiche, die die Seiten des Quell‑PDF‑Dokuments repräsentieren, gelassen wird. Im Wesentlichen definiert er das garantierte Intervall zwischen den HTML‑Darstellungen von PDF‑„Papier“‑Seiten bei dieser Art der Konvertierung. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | Dieser Parameter definiert die erforderlichen Antialiasing‑Maßnahmen während der Konvertierung zusammengesetzter Hintergrundbilder von PDF nach HTML. |
| [getBatchSize](#getBatchSize--) | Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | Wenn der PDFtoHTML-Konverter Ergebnis‑CSS-Dateien erzeugt, werden CSS‑Klassennamen (etwa \".stl_01 {}\" ... \".stl_NN {}\") generiert und im Ergebnis‑CSS verwendet. Diese Eigenschaft ermöglicht das Erzwingen eines Klassennamen‑Präfixes. Zum Beispiel, wenn Sie möchten, dass alle Klassennamen mit 'my_prefix_' beginnen (d. h. etwa 'my_prefix_1' ... 'my_prefix_NNN'), dann weisen Sie dieser Eigenschaft vor der Konvertierung einfach 'my_prefix_' zu. Bleibt diese Eigenschaft unverändert (d. h. null bleibt als Wert), erzeugt der Konverter die Klassennamen selbst (es wird etwas wie \".stl_01 {}\" ... \".stl_NN {}\" sein). |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | Dieses Feld kann eine Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung von PDF zu HTML verwendet werden muss, um das Speichern von CSS‑Dateien zu handhaben, die sich auf das erstellte HTML‑Dokument als Ganzes oder auf dessen Seiten beziehen (falls mehrere HTML‑Seiten erzeugt werden). Wenn Sie die CSS‑Datei auf eine bestimmte Weise behandeln möchten, erstellen Sie bitte die entsprechende Methode und weisen Sie dieser Eigenschaft das daraus erstellte Delegat zu. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | Das Ergebnis der Konvertierung kann eine oder mehrere HTML‑Seiten enthalten. Sie können dieser Eigenschaft ein Delegat zuweisen, das aus einer benutzerdefinierten Methode erstellt wurde, welche die Verarbeitung einer HTML‑Seite (genauer gesagt – Markup‑HTML, ohne externe verknüpfte Dateien, falls vorhanden) implementiert, die während der Konvertierung erzeugt wurde. In einem solchen Fall kann die Verarbeitung (wie das Speichern des Seiten‑HTMLs in einen Stream oder auf die Festplatte) in diesem benutzerdefinierten Code durchgeführt werden. Dabei müssen alle erforderlichen Aktionen zum Speichern der HTML‑Seite im Code der bereitgestellten Methode vorgenommen werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Sollte die Verarbeitung aus irgendeinem Grund vom Code des Konverters selbst und nicht vom benutzerdefinierten Code durchgeführt werden müssen, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'htmlSavingInfo': Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, so wie es wäre, wenn kein externes benutzerdefiniertes Code‑Verfahren vorhanden wäre. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Dieser Handler kann verwendet werden, um Fortschrittsereignisse der Konvertierung zu behandeln, z. B. um eine Fortschrittsleiste oder Meldungen über die aktuelle Anzahl verarbeiteter Seiten anzuzeigen. Ein Beispiel für den Code des Handlers, der den Fortschritt in der Konsole anzeigt, ist : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | Dieses Feld kann die zu verwendende Speicherstrategie enthalten (falls vorhanden), die während der Konvertierung für die benutzerdefinierte Verarbeitung der erstellten referenzierten Ressourcendateien (wie Bilder und Schriftarten) in Bezug auf die Knoten des gespeicherten HTML verwendet wird. Diese Strategie muss Ressourcen verarbeiten und einen String zurückgeben, der die gewünschte URL der gespeicherten Ressource im erzeugten HTML darstellt. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | Dieses Feld kann eine benutzerdefinierte Methode enthalten, die die URL (oder URL‑Vorlage, wenn die Mehrseitengenerierung aktiviert ist – siehe Details unten) des betreffenden CSS zurückgibt, wie sie in das erzeugte Ergebnis‑HTML eingefügt werden soll. Zum Beispiel, wenn Sie möchten, dass der Konverter eine bestimmte URL anstelle des Standard‑CSS‑Dateinamens in das erzeugte CSS einfügt, sollten Sie einfach eine Methode erstellen und in diese Eigenschaft einfügen, die die gewünschte URL erzeugt. Ist das Flag „SplitCssIntoPages“ gesetzt, muss diese benutzerdefinierte Strategie (falls vorhanden) nicht die exakte URL des CSS, sondern eine Vorlagenzeichenkette zurückgeben, die (nach dem Ersetzen des Platzhalters durch die Seitennummer mit der String.Format‑Funktion im Konverter) in die URL für das CSS der jeweiligen Seite aufgelöst werden kann. Beispiele für erwartete Rückgabe‑Zeichenketten in einem solchen Fall sind: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' ) |
| [getDefaultFontName](#getDefaultFontName--) | Gibt den Namen einer installierten Schriftart an, die verwendet wird, um jede Dokumentschriftart zu ersetzen, die nicht eingebettet und nicht im System installiert ist. Ist der Wert null, wird die Standardschriftart für die Ersetzung verwendet. |
| [getDocumentType](#getDocumentType--) | Liefert den {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | Liste der in PDF eingebetteten Schriftartnamen, die nicht in HTML eingebettet werden. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | Mit dieser Eigenschaft können Sie explizit festlegen, welche Seiten des Dokuments konvertiert werden sollen. Seiten in dieser Liste müssen 1‑basierte Nummern haben. D.h. gültige Seitennummern müssen aus dem Bereich (1...[NumberOfPagesInConvertedDocument]) stammen. Die Reihenfolge des Auftretens der Seiten in dieser Liste beeinflusst nicht ihre Reihenfolge in den resultierenden HTML‑Seite(n) – in den Ergebnisseiten werden sie stets in der Reihenfolge angezeigt, in der sie im Quell‑PDF vorkommen. Ist diese Liste null (wie standardmäßig), werden alle Seiten konvertiert. Wenn eine Seitennummer dieser Liste außerhalb des Bereichs der vorhandenen Seiten (1-[amountOfPagesInDocument]) liegt, wird eine Ausnahme ausgelöst. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | Dieses Attribut gibt den Absatztext in voller Breite für den Flow‑Modus an, FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | Definiert eine spezielle Kodierungsregel, um die PDF‑Dekodierung für das aktuelle Dokument anzupassen |
| [getFontSavingMode](#getFontSavingMode--) | Definiert den Schriftart‑Speichermodus, der beim Speichern von PDF in das gewünschte Format verwendet wird |
| [getFontSources](#getFontSources--) | <p> Schriftquellen von vorab gespeicherten Schriftarten. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | Manchmal liegen spezifische Anforderungen an die Erzeugung von HTML‑Markup vor. Dieser Parameter definiert HTML‑Vorbereitungsmodi, die bei der Konvertierung von PDF zu HTML verwendet werden können, um solchen spezifischen Anforderungen gerecht zu werden. |
| [getImageResolution](#getImageResolution--) | Liefert oder setzt die Auflösung für die Bilddarstellung. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | Setzt den Modus der Buchstabenpositionierung in Wörtern im resultierenden HTML. |
| [getMinimalLineWidth](#getMinimalLineWidth--) | Dieses Attribut legt die minimale Breite einer Grafikpfad‑Linie fest. Ist die Linienstärke kleiner als 1 px, rundet Adobe Acrobat sie auf diesen Wert. Dieses Attribut kann also verwendet werden, um dieses Verhalten für HTML‑Browser zu emulieren. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | Dieses Attribut repräsentiert eine Gruppe von Einstellungen, die zum Zeichnen eines Rahmens (falls vorhanden) im resultierenden HTML‑Dokument um den Bereich verwendet werden, der die Quell‑PDF‑Seite darstellt. Im Wesentlichen betrifft es die Anzeige der Papierkanten der Seite, nicht den Seitenrand, der im PDF selbst referenziert wird. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | Dieses Attribut repräsentiert eine Gruppe zusätzlicher Seitenränder (falls vorhanden) im resultierenden HTML‑Dokument um den Bereich, der die Quell‑PDF‑Seite darstellt. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | Es definiert, ob referenzierte Dateien (HTML, Schriftarten, Bilder, CSS‑Dateien) in die Haupt‑HTML‑Datei eingebettet oder als separate Binär‑Entitäten erzeugt werden. |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | Konvertierte PDFs können Rasterbilder enthalten. Dieser Parameter definiert, wie sie bei der Konvertierung von PDF zu HTML behandelt werden sollen. |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | Liefert oder setzt den Pfad zu dem Verzeichnis, in dem alle Bilder gespeichert werden müssen, die beim Speichern des Dokuments als HTML auftreten. Ist der Parameter leer oder null, werden Bilddateien (falls vorhanden) zusammen mit den anderen an HTML gebundenen Dateien gespeichert. Dies hat keine Auswirkung, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die betreffende Bilddatei zu verarbeiten. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | Liefert oder setzt den Pfad zu dem Verzeichnis, in dem ausschließlich SVG‑Bilder gespeichert werden müssen, wenn sie beim Speichern des Dokuments als HTML auftreten. Ist der Parameter leer oder null, werden SVG‑Dateien (falls vorhanden) zusammen mit den anderen Bilddateien (in der Nähe der Ausgabedatei) oder in einem speziellen Bildordner (wenn im Parameter SpecialImagesFolderIfAny angegeben) gespeichert. Dies hat keine Auswirkung, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die betreffende Bilddatei zu verarbeiten. |
| [getTitle](#getTitle--) | Liefert oder setzt den HTML‑Seitentitel. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | Gibt das Flag zurück, das angibt, ob gefundene SVG-Grafiken (falls vorhanden) beim Speichern in das SVGZ-Format komprimiert (gezippt) werden. Wert: Der {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | Wenn das Attribut ConvertMarkedContentToLayers auf true gesetzt ist, werden alle Elemente innerhalb eines PDF-markierten Inhalts (Layer) in ein HTML‑div mit dem Attribut "data-pdflayer" eingefügt, das einen Layer‑Namen angibt. Dieser Layer‑Name wird aus optionalen Eigenschaften des PDF-markierten Inhalts extrahiert. Wenn dieses Attribut false ist (standardmäßig), werden keine Layer aus dem PDF-markierten Inhalt erstellt. |
| [isFixedLayout](#isFixedLayout--) | Gibt einen Wert zurück, der angibt, ob das HTML als Fixed‑Layout erstellt wird. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | Liest oder setzt die Angabe, dass Fehler im Zusammenhang mit fehlenden Schriftarten ignoriert werden. true – bedeutet, dass Fehler wegen fehlender Schriftarten ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false ist standardmäßig. |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | Wenn das Attribut 'SplitOnPages=false' ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, in einer großen Ergebnis‑HTML‑Datei zusammengefasst. Dieses Flag bestimmt, ob das Ergebnis‑HTML so erzeugt wird, dass der Fluss der Bereiche, die PDF‑Seiten im Ergebnis‑HTML repräsentieren, von der Bildschirmauflösung des Betrachters abhängt. Angenommen, die Breite des Bildschirms beim Betrachter ist groß genug, um zwei oder mehr Seiten nebeneinander horizontal anzuzeigen. Wenn dieses Flag auf true gesetzt ist, wird diese Möglichkeit genutzt (so viele Seiten wie möglich werden horizontal nebeneinander angezeigt, dann wird die nächste horizontale Gruppe von Seiten unter der ersten angezeigt). Andernfalls fließen die Seiten so: Die nächste Seite wird immer unter der vorherigen angezeigt. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | Dieses Attribut schaltet den Modus ein, in dem Textglyphen nicht zu Wörtern und Zeichenketten gruppiert werden. Dieser Modus ermöglicht maximale Präzision bei der Positionierung von Glyphen auf der Seite und kann für die Konvertierung von Dokumenten mit Noten oder Glyphen verwendet werden, die einzeln voneinander platziert werden sollen. Dieser Parameter wird nur auf das Dokument angewendet, wenn der Wert des FixedLayout‑Attributs true ist. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | Definiert, ob im erzeugten HTML der obere und untere leere Bereich ohne Inhalt (falls vorhanden) entfernt wird. |
| [isRenderTextAsImage](#isRenderTextAsImage--) | Wenn das Attribut RenderTextAsImage auf true gesetzt ist, wird der Text aus der Quelle im HTML zu einem Bild. Dies kann nützlich sein, um Text nicht auswählbar zu machen oder wenn HTML‑Text nicht korrekt gerendert wird. |
| [isSaveFullFont](#isSaveFullFont--) | Gibt an, dass die vollständige Schriftart gespeichert wird; unterstützt nur True‑Type‑Fonts. Standardmäßig ist SaveFullFont = false und der Konverter speichert das Teilset der ursprünglichen Schriftart, das zum Anzeigen des Textes im Dokument benötigt wird. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | PDF kann Texte enthalten, die von anderen Elementen (z. B. Bildern) überlagert werden, aber im Acrobat Reader in die Zwischenablage kopiert werden können (dies geschieht häufig, wenn das Dokument Bilder und daraus extrahierte OCR‑Texte enthält). Diese Einstellung teilt dem Konverter mit, ob solche Texte als transparente, auswählbare Texte im Ergebnis‑HTML gespeichert werden sollen, um das Verhalten des Acrobat Readers nachzuahmen (andernfalls werden solche Texte normalerweise als versteckt gespeichert und können nicht in die Zwischenablage kopiert werden). |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | Pdf kann transparente Texte enthalten, die in die Zwischenablage kopiert werden können (normalerweise passiert das, wenn das Dokument Bilder und daraus extrahierte OCR‑Texte enthält). Diese Einstellung teilt dem Konverter mit, ob wir solche Texte als transparente auswählbare Texte im Ergebnis‑HTML speichern müssen. |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | Dieses Attribut gibt eine sequentielle Gruppierung von Glyphen und Wörtern zu Zeichenketten an. Zum Beispiel haben Tags und Wörter in konvertiertem HTML unterschiedliche Reihenfolge und Sie möchten, dass sie übereinstimmen. Dieser Parameter wird nur auf das Dokument angewendet, wenn der Wert des FixedLayout‑Attributs true ist. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | Wenn der Mehrseitigen‑Modus ausgewählt ist (d. h. 'SplitIntoPages' ist 'true'), definiert dieses Attribut, ob für jede Ergebnis‑HTML‑Seite eine separate CSS‑Datei erstellt werden soll. Standardmäßig ist dieses Attribut false, sodass ein großes gemeinsames CSS für alle erstellten Seiten erzeugt wird. Die Gesamtsumme der in diesem Modus (ein CSS pro Seite) erzeugten CSS‑Dateien ist in der Regel viel größer als die Größe einer einzigen großen CSS‑Datei, weil in dem ersten Fall CSS‑Klassen in mehreren CSS‑Dateien für jede Seite dupliziert werden. Daher sollte diese Einstellung nur verwendet werden, wenn Sie an einer späteren Verarbeitung jeder HTML‑Seite unabhängig voneinander interessiert sind und daher die Größe des CSS jeder einzelnen Seite das kritischste Problem darstellt. |
| [isSplitIntoPages](#isSplitIntoPages--) | Gibt das Flag zurück, das angibt, ob jede Seite des Quelldokuments in ein eigenes Ziel‑HTML‑Dokument konvertiert wird, d. h. ob das Ergebnis‑HTML in mehrere HTML‑Seiten aufgeteilt wird. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | PDF selbst enthält keine Unterstreichungs‑Marker für Texte. Sie werden durch eine Linie unter dem Text simuliert. Diese Option ermöglicht es dem Konverter, zu versuchen zu erraten, dass diese oder jene Linie eine Textunterstreichung ist, und diese Information in CSS zu hinterlegen, anstatt die Unterstreichung grafisch zu zeichnen. |
| [isUseZOrder](#isUseZOrder--) | Wenn das Attribut UseZORder auf true gesetzt ist, werden Grafiken und Text dem resultierenden HTML‑Dokument entsprechend der Z‑Reihenfolge im ursprünglichen PDF‑Dokument hinzugefügt. Ist dieses Attribut false, werden alle Grafiken als einzelne Ebene eingefügt, was bei überlappenden Objekten zu unnötigen Effekten führen kann. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | Wenn das Attribut 'SplitOnPages=false' gesetzt ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, nicht in einzelne HTML‑Seiten aufgeteilt, sondern in einer großen Ergebnis‑HTML‑Datei zusammengefasst. Jede Quell‑PDF‑Seite wird jedoch in HTML mit ihrem eigenen rechteckigen Bereich dargestellt (falls nötig können diese Bereiche mit dem speziellen Attribut 'PageBorderIfAny' begrenzt werden, um die Kanten des Seitenpapiers zu zeigen). Dieser Parameter definiert die Breite des Randes, der zwingend um die ausgegebenen HTML‑Bereiche, die die Seiten des Quell‑PDF‑Dokuments repräsentieren, gelassen wird. Im Wesentlichen definiert er das garantierte Intervall zwischen den HTML‑Darstellungen von PDF‑„Papier“‑Seiten bei dieser Art der Konvertierung. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | Dieser Parameter definiert die erforderlichen Antialiasing‑Maßnahmen während der Konvertierung zusammengesetzter Hintergrundbilder von PDF nach HTML. |
| [setBatchSize](#setBatchSize-int-) | Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | Setzt das Flag, das angibt, ob gefundene SVG‑Grafiken (falls vorhanden) beim Speichern in das SVGZ‑Format komprimiert (gezippt) werden. Wert: {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | Wenn das Attribut ConvertMarkedContentToLayers auf true gesetzt ist, werden alle Elemente innerhalb eines PDF-markierten Inhalts (Layer) in ein HTML‑div mit dem Attribut "data-pdflayer" eingefügt, das einen Layer‑Namen angibt. Dieser Layer‑Name wird aus optionalen Eigenschaften des PDF-markierten Inhalts extrahiert. Wenn dieses Attribut false ist (standardmäßig), werden keine Layer aus dem PDF-markierten Inhalt erstellt. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | Wenn der PDFtoHTML-Konverter Ergebnis‑CSS-Dateien erzeugt, werden CSS‑Klassennamen (etwa \".stl_01 {}\" ... \".stl_NN {}\") generiert und im Ergebnis‑CSS verwendet. Diese Eigenschaft ermöglicht das Erzwingen eines Klassennamen‑Präfixes. Zum Beispiel, wenn Sie möchten, dass alle Klassennamen mit 'my_prefix_' beginnen (d. h. etwa 'my_prefix_1' ... 'my_prefix_NNN'), dann weisen Sie dieser Eigenschaft vor der Konvertierung einfach 'my_prefix_' zu. Bleibt diese Eigenschaft unverändert (d. h. null bleibt als Wert), erzeugt der Konverter die Klassennamen selbst (es wird etwas wie \".stl_01 {}\" ... \".stl_NN {}\" sein). |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | Dieses Feld kann eine Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung von PDF zu HTML verwendet werden muss, um das Speichern von CSS‑Dateien zu handhaben, die sich auf das erstellte HTML‑Dokument als Ganzes oder auf dessen Seiten beziehen (falls mehrere HTML‑Seiten erzeugt werden). Wenn Sie die CSS‑Datei auf eine bestimmte Weise behandeln möchten, erstellen Sie bitte die entsprechende Methode und weisen Sie dieser Eigenschaft das daraus erstellte Delegat zu. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | Das Ergebnis der Konvertierung kann eine oder mehrere HTML‑Seiten enthalten. Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung einer HTML‑Seite (genauer gesagt – Markup‑HTML, ohne extern verlinkte Dateien, falls vorhanden) implementiert, die während der Konvertierung erstellt wurde. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Dieser Handler kann verwendet werden, um Konvertierungs‑Fortschrittsereignisse zu behandeln, z. b. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | Dieses Feld kann die Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung für die benutzerdefinierte Handhabung der erstellten referenzierten Ressourcendateien (wie Bilder und Schriftarten) verwendet werden muss, die mit den Knoten des gespeicherten HTML verknüpft sind. |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | Dieses Feld kann eine benutzerdefinierte Methode enthalten, die die URL (oder URL‑Vorlage, falls die Mehrseitengenerierung aktiviert ist – siehe Details unten) des betreffenden CSS zurückgibt, wie sie im erzeugten Ergebnis‑HTML eingefügt werden soll. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Gibt den Namen einer installierten Schriftart an, die verwendet wird, um jede Dokumentschriftart zu ersetzen, die nicht eingebettet und nicht im System installiert ist. Ist der Wert null, wird die Standardschriftart für die Ersetzung verwendet. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | Setzt {@code HtmlDocumentType}. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | Liste der in PDF eingebetteten Schriftartnamen, die nicht in HTML eingebettet werden. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | Mit dieser Eigenschaft können Sie explizit festlegen, welche Seiten des Dokuments konvertiert werden sollen. Seiten in dieser Liste müssen 1‑basierte Nummern haben. D.h. gültige Seitennummern müssen aus dem Bereich (1...[NumberOfPagesInConvertedDocument]) stammen. Die Reihenfolge des Auftretens der Seiten in dieser Liste beeinflusst nicht ihre Reihenfolge in den resultierenden HTML‑Seite(n) – in den Ergebnisseiten werden sie stets in der Reihenfolge angezeigt, in der sie im Quell‑PDF vorkommen. Ist diese Liste null (wie standardmäßig), werden alle Seiten konvertiert. Wenn eine Seitennummer dieser Liste außerhalb des Bereichs der vorhandenen Seiten (1-[amountOfPagesInDocument]) liegt, wird eine Ausnahme ausgelöst. |
| [setFixedLayout](#setFixedLayout-boolean-) | Setzt einen Wert, der angibt, ob das HTML als Fixed‑Layout erstellt wird. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | Dieses Attribut gibt den Absatztext in voller Breite für den Flow‑Modus an, FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | Definiert eine spezielle Kodierungsregel, um die PDF‑Dekodierung für das aktuelle Dokument anzupassen |
| [setFontSavingMode](#setFontSavingMode-int-) | Definiert den Schriftart‑Speichermodus, der beim Speichern von PDF in das gewünschte Format verwendet wird |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | Manchmal liegen spezifische Anforderungen an die Erzeugung von HTML‑Markup vor. Dieser Parameter definiert HTML‑Vorbereitungsmodi, die bei der Konvertierung von PDF zu HTML verwendet werden können, um solchen spezifischen Anforderungen gerecht zu werden. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Liest oder setzt die Angabe, dass Fehler im Zusammenhang mit fehlenden Schriftarten ignoriert werden. true – bedeutet, dass Fehler wegen fehlender Schriftarten ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false ist standardmäßig. |
| [setImageResolution](#setImageResolution-int-) | Liefert oder setzt die Auflösung für die Bilddarstellung. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | Setzt den Modus der Buchstabenpositionierung in Wörtern im resultierenden HTML. |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | Dieses Attribut legt die minimale Breite einer Grafikpfad‑Linie fest. Ist die Linienstärke kleiner als 1 px, rundet Adobe Acrobat sie auf diesen Wert. Dieses Attribut kann also verwendet werden, um dieses Verhalten für HTML‑Browser zu emulieren. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | Dieses Attribut stellt eine Gruppe von Einstellungen dar, die zum Zeichnen des Rahmens (falls vorhanden) im resultierenden HTML-Dokument um den Bereich verwendet werden, der die Quell‑PDF‑Seite repräsentiert. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | Dieses Attribut repräsentiert eine Gruppe zusätzlicher Seitenränder (falls vorhanden) im resultierenden HTML‑Dokument um den Bereich, der die Quell‑PDF‑Seite darstellt. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | Wenn das Attribut 'SplitOnPages=false' ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, in einer großen Ergebnis‑HTML‑Datei zusammengefasst. Dieses Flag bestimmt, ob das Ergebnis‑HTML so erzeugt wird, dass der Fluss der Bereiche, die PDF‑Seiten im Ergebnis‑HTML repräsentieren, von der Bildschirmauflösung des Betrachters abhängt. Angenommen, die Breite des Bildschirms beim Betrachter ist groß genug, um zwei oder mehr Seiten nebeneinander horizontal anzuzeigen. Wenn dieses Flag auf true gesetzt ist, wird diese Möglichkeit genutzt (so viele Seiten wie möglich werden horizontal nebeneinander angezeigt, dann wird die nächste horizontale Gruppe von Seiten unter der ersten angezeigt). Andernfalls fließen die Seiten so: Die nächste Seite wird immer unter der vorherigen angezeigt. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | Es definiert, ob referenzierte Dateien (HTML, Schriftarten, Bilder, CSS‑Dateien) in die Haupt‑HTML‑Datei eingebettet oder als separate Binär‑Entitäten erzeugt werden. |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | Dieses Attribut schaltet den Modus ein, in dem Textglyphen nicht zu Wörtern und Zeichenketten gruppiert werden. Dieser Modus ermöglicht maximale Präzision bei der Positionierung von Glyphen auf der Seite und kann für die Konvertierung von Dokumenten mit Noten oder Glyphen verwendet werden, die einzeln voneinander platziert werden sollen. Dieser Parameter wird nur auf das Dokument angewendet, wenn der Wert des FixedLayout‑Attributs true ist. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | Konvertierte PDFs können Rasterbilder enthalten. Dieser Parameter definiert, wie sie bei der Konvertierung von PDF zu HTML behandelt werden sollen. |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Definiert, ob im erzeugten HTML der obere und untere leere Bereich ohne Inhalt (falls vorhanden) entfernt wird. |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | Wenn das Attribut RenderTextAsImage auf true gesetzt ist, wird der Text aus der Quelle im HTML zu einem Bild. Dies kann nützlich sein, um Text nicht auswählbar zu machen oder wenn HTML‑Text nicht korrekt gerendert wird. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | Gibt an, dass die vollständige Schriftart gespeichert wird; unterstützt nur True‑Type‑Fonts. Standardmäßig ist SaveFullFont = false und der Konverter speichert das Teilset der ursprünglichen Schriftart, das zum Anzeigen des Textes im Dokument benötigt wird. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | PDF kann Texte enthalten, die von anderen Elementen (z. B. Bildern) überlagert werden, aber im Acrobat Reader in die Zwischenablage kopiert werden können (dies geschieht häufig, wenn das Dokument Bilder und daraus extrahierte OCR‑Texte enthält). Diese Einstellung teilt dem Konverter mit, ob solche Texte als transparente, auswählbare Texte im Ergebnis‑HTML gespeichert werden sollen, um das Verhalten des Acrobat Readers nachzuahmen (andernfalls werden solche Texte normalerweise als versteckt gespeichert und können nicht in die Zwischenablage kopiert werden). |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Pdf kann transparente Texte enthalten, die in die Zwischenablage kopiert werden können (normalerweise passiert das, wenn das Dokument Bilder und daraus extrahierte OCR‑Texte enthält). Diese Einstellung teilt dem Konverter mit, ob wir solche Texte als transparente auswählbare Texte im Ergebnis‑HTML speichern müssen. |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | Dieses Attribut gibt eine sequentielle Gruppierung von Glyphen und Wörtern zu Zeichenketten an. Zum Beispiel haben Tags und Wörter in konvertiertem HTML unterschiedliche Reihenfolge und Sie möchten, dass sie übereinstimmen. Dieser Parameter wird nur auf das Dokument angewendet, wenn der Wert des FixedLayout‑Attributs true ist. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | Liefert oder setzt den Pfad zu dem Verzeichnis, in dem alle Bilder gespeichert werden müssen, die beim Speichern des Dokuments als HTML auftreten. Ist der Parameter leer oder null, werden Bilddateien (falls vorhanden) zusammen mit den anderen an HTML gebundenen Dateien gespeichert. Dies hat keine Auswirkung, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die betreffende Bilddatei zu verarbeiten. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | Liefert oder setzt den Pfad zu dem Verzeichnis, in dem ausschließlich SVG‑Bilder gespeichert werden müssen, wenn sie beim Speichern des Dokuments als HTML auftreten. Ist der Parameter leer oder null, werden SVG‑Dateien (falls vorhanden) zusammen mit den anderen Bilddateien (in der Nähe der Ausgabedatei) oder in einem speziellen Bildordner (wenn im Parameter SpecialImagesFolderIfAny angegeben) gespeichert. Dies hat keine Auswirkung, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die betreffende Bilddatei zu verarbeiten. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | Wenn der Mehrseitigen‑Modus ausgewählt ist (d. h. 'SplitIntoPages' ist 'true'), definiert dieses Attribut, ob für jede Ergebnis‑HTML‑Seite eine separate CSS‑Datei erstellt werden soll. Standardmäßig ist dieses Attribut false, sodass ein großes gemeinsames CSS für alle erstellten Seiten erzeugt wird. Die Gesamtsumme der in diesem Modus (ein CSS pro Seite) erzeugten CSS‑Dateien ist in der Regel viel größer als die Größe einer einzigen großen CSS‑Datei, weil in dem ersten Fall CSS‑Klassen in mehreren CSS‑Dateien für jede Seite dupliziert werden. Daher sollte diese Einstellung nur verwendet werden, wenn Sie an einer späteren Verarbeitung jeder HTML‑Seite unabhängig voneinander interessiert sind und daher die Größe des CSS jeder einzelnen Seite das kritischste Problem darstellt. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | Setzt das Flag, das angibt, ob jede Seite des Quelldokuments in ein eigenes Ziel‑HTML‑Dokument konvertiert wird, d. h. ob das Ergebnis‑HTML in mehrere HTML‑Seiten aufgeteilt wird. |
| [setTitle](#setTitle-java.lang.String-) | Liefert oder setzt den HTML‑Seitentitel. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | PDF selbst enthält keine Unterstreichungs‑Marker für Texte. Sie werden durch eine Linie unter dem Text simuliert. Diese Option ermöglicht es dem Konverter, zu versuchen zu erraten, dass diese oder jene Linie eine Textunterstreichung ist, und diese Information in CSS zu hinterlegen, anstatt die Unterstreichung grafisch zu zeichnen. |
| [setUseZOrder](#setUseZOrder-boolean-) | Wenn das Attribut UseZORder auf true gesetzt ist, werden Grafiken und Text dem resultierenden HTML‑Dokument entsprechend der Z‑Reihenfolge im ursprünglichen PDF‑Dokument hinzugefügt. Ist dieses Attribut false, werden alle Grafiken als einzelne Ebene eingefügt, was bei überlappenden Objekten zu unnötigen Effekten führen kann. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

Initialisiert eine neue Instanz der HtmlSaveOptions‑Klasse.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

Initialisiert eine neue Instanz der {@code HtmlSaveOptions}‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fixedLayout |  | boolescher Wert |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
Initialisiert eine neue Instanz der HtmlSaveOptions‑Klasse.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
Initialisiert eine neue Instanz der HtmlSaveOptions‑Klasse.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

Wenn das Attribut 'SplitOnPages=false' gesetzt ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, nicht in einzelne HTML‑Seiten aufgeteilt, sondern in einer großen Ergebnis‑HTML‑Datei zusammengefasst. Jede Quell‑PDF‑Seite wird jedoch in HTML mit ihrem eigenen rechteckigen Bereich dargestellt (falls nötig können diese Bereiche mit dem speziellen Attribut 'PageBorderIfAny' begrenzt werden, um die Kanten des Seitenpapiers zu zeigen). Dieser Parameter definiert die Breite des Randes, der zwingend um die ausgegebenen HTML‑Bereiche, die die Seiten des Quell‑PDF‑Dokuments repräsentieren, gelassen wird. Im Wesentlichen definiert er das garantierte Intervall zwischen den HTML‑Darstellungen von PDF‑„Papier“‑Seiten bei dieser Art der Konvertierung.

**Returns:**
int-Wert @deprecated AdditionalMarginWidthInPoints ist veraltet, bitte verwenden Sie stattdessen PageMarginIfAny.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

Dieser Parameter definiert die erforderlichen Antialiasing‑Maßnahmen während der Konvertierung zusammengesetzter Hintergrundbilder von PDF nach HTML.

**Returns:**
AntialiasingProcessingType‑Element @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist.

**Returns:**
int-Wert

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

Wenn der PDFtoHTML-Konverter Ergebnis‑CSS-Dateien erzeugt, werden CSS‑Klassennamen (etwa \".stl_01 {}\" ... \".stl_NN {}\") generiert und im Ergebnis‑CSS verwendet. Diese Eigenschaft ermöglicht das Erzwingen eines Klassennamen‑Präfixes. Zum Beispiel, wenn Sie möchten, dass alle Klassennamen mit 'my_prefix_' beginnen (d. h. etwa 'my_prefix_1' ... 'my_prefix_NNN'), dann weisen Sie dieser Eigenschaft vor der Konvertierung einfach 'my_prefix_' zu. Bleibt diese Eigenschaft unverändert (d. h. null bleibt als Wert), erzeugt der Konverter die Klassennamen selbst (es wird etwas wie \".stl_01 {}\" ... \".stl_NN {}\" sein).

**Returns:**
String Wert

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

Dieses Feld kann eine Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung von PDF zu HTML verwendet werden muss, um das Speichern von CSS‑Dateien zu handhaben, die sich auf das erstellte HTML‑Dokument als Ganzes oder auf dessen Seiten beziehen (falls mehrere HTML‑Seiten erzeugt werden). Wenn Sie die CSS‑Datei auf eine bestimmte Weise behandeln möchten, erstellen Sie bitte die entsprechende Methode und weisen Sie dieser Eigenschaft das daraus erstellte Delegat zu.

**Returns:**
CssSavingStrategy‑Instanz

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

Das Ergebnis der Konvertierung kann eine oder mehrere HTML‑Seiten enthalten. Sie können dieser Eigenschaft ein Delegat zuweisen, das aus einer benutzerdefinierten Methode erstellt wurde, welche die Verarbeitung einer HTML‑Seite (genauer gesagt – Markup‑HTML, ohne externe verknüpfte Dateien, falls vorhanden) implementiert, die während der Konvertierung erzeugt wurde. In einem solchen Fall kann die Verarbeitung (wie das Speichern des Seiten‑HTMLs in einen Stream oder auf die Festplatte) in diesem benutzerdefinierten Code durchgeführt werden. Dabei müssen alle erforderlichen Aktionen zum Speichern der HTML‑Seite im Code der bereitgestellten Methode vorgenommen werden, da das Speichern des Ergebnisses im Code des Konverters nicht verwendet wird. Sollte die Verarbeitung aus irgendeinem Grund vom Code des Konverters selbst und nicht vom benutzerdefinierten Code durchgeführt werden müssen, setzen Sie bitte im benutzerdefinierten Code das Flag 'CustomProcessingCancelled' der Variablen des Parameters 'htmlSavingInfo': Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource vom Konverter selbst durchgeführt werden sollen, so wie es wäre, wenn kein externes benutzerdefiniertes Code‑Verfahren vorhanden wäre.

**Returns:**
HtmlPageMarkupSavingStrategy‑Instanz

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Dieser Handler kann verwendet werden, um Fortschrittsereignisse der Konvertierung zu behandeln, z. B. um eine Fortschrittsleiste oder Meldungen über die aktuelle Anzahl verarbeiteter Seiten anzuzeigen. Ein Beispiel für den Code des Handlers, der den Fortschritt in der Konsole anzeigt, ist : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler‑Instanz

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

Dieses Feld kann die zu verwendende Speicherstrategie enthalten (falls vorhanden), die während der Konvertierung für die benutzerdefinierte Verarbeitung der erstellten referenzierten Ressourcendateien (wie Bilder und Schriftarten) in Bezug auf die Knoten des gespeicherten HTML verwendet wird. Diese Strategie muss Ressourcen verarbeiten und einen String zurückgeben, der die gewünschte URL der gespeicherten Ressource im erzeugten HTML darstellt.

**Returns:**
ResourceSavingStrategy‑Instanz

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

Dieses Feld kann eine benutzerdefinierte Methode enthalten, die die URL (oder URL‑Vorlage, wenn die Mehrseitengenerierung aktiviert ist – siehe Details unten) des betreffenden CSS zurückgibt, wie sie in das erzeugte Ergebnis‑HTML eingefügt werden soll. Zum Beispiel, wenn Sie möchten, dass der Konverter eine bestimmte URL anstelle des Standard‑CSS‑Dateinamens in das erzeugte CSS einfügt, sollten Sie einfach eine Methode erstellen und in diese Eigenschaft einfügen, die die gewünschte URL erzeugt. Ist das Flag „SplitCssIntoPages“ gesetzt, muss diese benutzerdefinierte Strategie (falls vorhanden) nicht die exakte URL des CSS, sondern eine Vorlagenzeichenkette zurückgeben, die (nach dem Ersetzen des Platzhalters durch die Seitennummer mit der String.Format‑Funktion im Konverter) in die URL für das CSS der jeweiligen Seite aufgelöst werden kann. Beispiele für erwartete Rückgabe‑Zeichenketten in einem solchen Fall sind: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' )

**Returns:**
CssUrlMakingStrategy‑Instanz

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Gibt den Namen einer installierten Schriftart an, die verwendet wird, um jede Dokumentschriftart zu ersetzen, die nicht eingebettet und nicht im System installiert ist. Ist der Wert null, wird die Standardschriftart für die Ersetzung verwendet.

**Returns:**
String‑Wert: Schriftname

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

Liefert den {@code HtmlDocumentTypeInternal}.

**Returns:**
Der {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

Liste der in PDF eingebetteten Schriftartnamen, die nicht in HTML eingebettet werden.

**Returns:**
Array von String‑Elementen

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

Mit dieser Eigenschaft können Sie explizit festlegen, welche Seiten des Dokuments konvertiert werden sollen. Seiten in dieser Liste müssen 1‑basierte Nummern haben. D.h. gültige Seitennummern müssen aus dem Bereich (1...[NumberOfPagesInConvertedDocument]) stammen. Die Reihenfolge des Auftretens der Seiten in dieser Liste beeinflusst nicht ihre Reihenfolge in den resultierenden HTML‑Seite(n) – in den Ergebnisseiten werden sie stets in der Reihenfolge angezeigt, in der sie im Quell‑PDF vorkommen. Ist diese Liste null (wie standardmäßig), werden alle Seiten konvertiert. Wenn eine Seitennummer dieser Liste außerhalb des Bereichs der vorhandenen Seiten (1-[amountOfPagesInDocument]) liegt, wird eine Ausnahme ausgelöst.

**Returns:**
int‑Array

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

Dieses Attribut gibt den Absatztext in voller Breite für den Flow‑Modus an, FixedLayout = false

**Returns:**
boolescher Wert

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

Definiert eine spezielle Kodierungsregel, um die PDF‑Dekodierung für das aktuelle Dokument anzupassen

**Returns:**
FontEncodingRules‑Element @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

Definiert den Schriftart‑Speichermodus, der beim Speichern von PDF in das gewünschte Format verwendet wird

**Returns:**
FontSavingModes‑Element @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> Schriftquellen von vorab gespeicherten Schriftarten. </p>

**Returns:**
FontSourceCollection‑Objekt <hr> <p> Schriften können vorab zum Zweck des Zwischenspeicherns gespeichert und dann an den HTML‑Konvertierungsprozess übergeben werden. Beispielsweise kann dies im Szenario der Dokumentaufteilung und bei der Verarbeitung von Dokumentseiten in mehreren Threads mit einem einzigen Satz von Schriften nützlich sein. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

Manchmal liegen spezifische Anforderungen an die Erzeugung von HTML‑Markup vor. Dieser Parameter definiert HTML‑Vorbereitungsmodi, die bei der Konvertierung von PDF zu HTML verwendet werden können, um solchen spezifischen Anforderungen gerecht zu werden.

**Returns:**
HtmlMarkupGenerationModes‑Element @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

Liefert oder setzt die Auflösung für die Bilddarstellung.

**Returns:**
Wert: Auflösung

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

Setzt den Modus der Buchstabenpositionierung in Wörtern im resultierenden HTML.

**Returns:**
LettersPositioningMethods‑Element @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

Dieses Attribut legt die minimale Breite einer Grafikpfad‑Linie fest. Ist die Linienstärke kleiner als 1 px, rundet Adobe Acrobat sie auf diesen Wert. Dieses Attribut kann also verwendet werden, um dieses Verhalten für HTML‑Browser zu emulieren.

**Returns:**
float-Wert

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

Dieses Attribut repräsentiert eine Gruppe von Einstellungen, die zum Zeichnen eines Rahmens (falls vorhanden) im resultierenden HTML‑Dokument um den Bereich verwendet werden, der die Quell‑PDF‑Seite darstellt. Im Wesentlichen betrifft es die Anzeige der Papierkanten der Seite, nicht den Seitenrand, der im PDF selbst referenziert wird.

**Returns:**
BorderInfo‑Instanz

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

Dieses Attribut repräsentiert eine Gruppe zusätzlicher Seitenränder (falls vorhanden) im resultierenden HTML‑Dokument um den Bereich, der die Quell‑PDF‑Seite darstellt.

**Returns:**
MarginInfo‑Instanz

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

Es definiert, ob referenzierte Dateien (HTML, Schriftarten, Bilder, CSS‑Dateien) in die Haupt‑HTML‑Datei eingebettet oder als separate Binär‑Entitäten erzeugt werden.

**Returns:**
PartsEmbeddingModes‑Element @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

Konvertierte PDFs können Rasterbilder enthalten. Dieser Parameter definiert, wie sie bei der Konvertierung von PDF zu HTML behandelt werden sollen.

**Returns:**
RasterImagesSavingModes‑Element @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

Liefert oder setzt den Pfad zu dem Verzeichnis, in dem alle Bilder gespeichert werden müssen, die beim Speichern des Dokuments als HTML auftreten. Ist der Parameter leer oder null, werden Bilddateien (falls vorhanden) zusammen mit den anderen an HTML gebundenen Dateien gespeichert. Dies hat keine Auswirkung, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die betreffende Bilddatei zu verarbeiten.

**Returns:**
String Wert

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

Liefert oder setzt den Pfad zu dem Verzeichnis, in dem ausschließlich SVG‑Bilder gespeichert werden müssen, wenn sie beim Speichern des Dokuments als HTML auftreten. Ist der Parameter leer oder null, werden SVG‑Dateien (falls vorhanden) zusammen mit den anderen Bilddateien (in der Nähe der Ausgabedatei) oder in einem speziellen Bildordner (wenn im Parameter SpecialImagesFolderIfAny angegeben) gespeichert. Dies hat keine Auswirkung, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die betreffende Bilddatei zu verarbeiten.

**Returns:**
String Wert

### getTitle {#getTitle--}
```
public final String getTitle()
```

Liefert oder setzt den HTML‑Seitentitel.

**Returns:**
String Wert

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

Gibt das Flag zurück, das angibt, ob gefundene SVG-Grafiken (falls vorhanden) beim Speichern in das SVGZ-Format komprimiert (gezippt) werden. Wert: Der {@code HtmlDocumentType}.

**Returns:**
boolescher Wert

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

Wenn das Attribut ConvertMarkedContentToLayers auf true gesetzt ist, werden alle Elemente innerhalb eines PDF-markierten Inhalts (Layer) in ein HTML‑div mit dem Attribut "data-pdflayer" eingefügt, das einen Layer‑Namen angibt. Dieser Layer‑Name wird aus optionalen Eigenschaften des PDF-markierten Inhalts extrahiert. Wenn dieses Attribut false ist (standardmäßig), werden keine Layer aus dem PDF-markierten Inhalt erstellt.

**Returns:**
boolescher Wert

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

Gibt einen Wert zurück, der angibt, ob das HTML als Fixed‑Layout erstellt wird.

**Returns:**
Wert: {@code true} wenn [fixed layout]; andernfalls {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

Liest oder setzt die Angabe, dass Fehler im Zusammenhang mit fehlenden Schriftarten ignoriert werden. true – bedeutet, dass Fehler wegen fehlender Schriftarten ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false ist standardmäßig.

**Returns:**
boolescher Wert

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

Wenn das Attribut 'SplitOnPages=false' ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, in einer großen Ergebnis‑HTML‑Datei zusammengefasst. Dieses Flag bestimmt, ob das Ergebnis‑HTML so erzeugt wird, dass der Fluss der Bereiche, die PDF‑Seiten im Ergebnis‑HTML repräsentieren, von der Bildschirmauflösung des Betrachters abhängt. Angenommen, die Breite des Bildschirms beim Betrachter ist groß genug, um zwei oder mehr Seiten nebeneinander horizontal anzuzeigen. Wenn dieses Flag auf true gesetzt ist, wird diese Möglichkeit genutzt (so viele Seiten wie möglich werden horizontal nebeneinander angezeigt, dann wird die nächste horizontale Gruppe von Seiten unter der ersten angezeigt). Andernfalls fließen die Seiten so: Die nächste Seite wird immer unter der vorherigen angezeigt.

**Returns:**
boolescher Wert

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

Dieses Attribut schaltet den Modus ein, in dem Textglyphen nicht zu Wörtern und Zeichenketten gruppiert werden. Dieser Modus ermöglicht maximale Präzision bei der Positionierung von Glyphen auf der Seite und kann für die Konvertierung von Dokumenten mit Noten oder Glyphen verwendet werden, die einzeln voneinander platziert werden sollen. Dieser Parameter wird nur auf das Dokument angewendet, wenn der Wert des FixedLayout‑Attributs true ist.

**Returns:**
boolescher Wert

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

Definiert, ob im erzeugten HTML der obere und untere leere Bereich ohne Inhalt (falls vorhanden) entfernt wird.

**Returns:**
boolescher Wert

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

Wenn das Attribut RenderTextAsImage auf true gesetzt ist, wird der Text aus der Quelle im HTML zu einem Bild. Dies kann nützlich sein, um Text nicht auswählbar zu machen oder wenn HTML‑Text nicht korrekt gerendert wird.

**Returns:**
boolescher Wert

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

Gibt an, dass die vollständige Schriftart gespeichert wird; unterstützt nur True‑Type‑Fonts. Standardmäßig ist SaveFullFont = false und der Konverter speichert das Teilset der ursprünglichen Schriftart, das zum Anzeigen des Textes im Dokument benötigt wird.

**Returns:**
boolescher Wert

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

PDF kann Texte enthalten, die von anderen Elementen (z. B. Bildern) überlagert werden, aber im Acrobat Reader in die Zwischenablage kopiert werden können (dies geschieht häufig, wenn das Dokument Bilder und daraus extrahierte OCR‑Texte enthält). Diese Einstellung teilt dem Konverter mit, ob solche Texte als transparente, auswählbare Texte im Ergebnis‑HTML gespeichert werden sollen, um das Verhalten des Acrobat Readers nachzuahmen (andernfalls werden solche Texte normalerweise als versteckt gespeichert und können nicht in die Zwischenablage kopiert werden).

**Returns:**
boolescher Wert

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

Pdf kann transparente Texte enthalten, die in die Zwischenablage kopiert werden können (normalerweise passiert das, wenn das Dokument Bilder und daraus extrahierte OCR‑Texte enthält). Diese Einstellung teilt dem Konverter mit, ob wir solche Texte als transparente auswählbare Texte im Ergebnis‑HTML speichern müssen.

**Returns:**
boolescher Wert

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

Dieses Attribut gibt eine sequentielle Gruppierung von Glyphen und Wörtern zu Zeichenketten an. Zum Beispiel haben Tags und Wörter in konvertiertem HTML unterschiedliche Reihenfolge und Sie möchten, dass sie übereinstimmen. Dieser Parameter wird nur auf das Dokument angewendet, wenn der Wert des FixedLayout‑Attributs true ist.

**Returns:**
boolescher Wert

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

Wenn der Mehrseitigen‑Modus ausgewählt ist (d. h. 'SplitIntoPages' ist 'true'), definiert dieses Attribut, ob für jede Ergebnis‑HTML‑Seite eine separate CSS‑Datei erstellt werden soll. Standardmäßig ist dieses Attribut false, sodass ein großes gemeinsames CSS für alle erstellten Seiten erzeugt wird. Die Gesamtsumme der in diesem Modus (ein CSS pro Seite) erzeugten CSS‑Dateien ist in der Regel viel größer als die Größe einer einzigen großen CSS‑Datei, weil in dem ersten Fall CSS‑Klassen in mehreren CSS‑Dateien für jede Seite dupliziert werden. Daher sollte diese Einstellung nur verwendet werden, wenn Sie an einer späteren Verarbeitung jeder HTML‑Seite unabhängig voneinander interessiert sind und daher die Größe des CSS jeder einzelnen Seite das kritischste Problem darstellt.

**Returns:**
boolescher Wert

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

Gibt das Flag zurück, das angibt, ob jede Seite des Quelldokuments in ein eigenes Ziel‑HTML‑Dokument konvertiert wird, d. h. ob das Ergebnis‑HTML in mehrere HTML‑Seiten aufgeteilt wird.

**Returns:**
boolescher Wert

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

PDF selbst enthält keine Unterstreichungs‑Marker für Texte. Sie werden durch eine Linie unter dem Text simuliert. Diese Option ermöglicht es dem Konverter, zu versuchen zu erraten, dass diese oder jene Linie eine Textunterstreichung ist, und diese Information in CSS zu hinterlegen, anstatt die Unterstreichung grafisch zu zeichnen.

**Returns:**
boolescher Wert

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

Wenn das Attribut UseZORder auf true gesetzt ist, werden Grafiken und Text dem resultierenden HTML‑Dokument entsprechend der Z‑Reihenfolge im ursprünglichen PDF‑Dokument hinzugefügt. Ist dieses Attribut false, werden alle Grafiken als einzelne Ebene eingefügt, was bei überlappenden Objekten zu unnötigen Effekten führen kann.

**Returns:**
boolescher Wert

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

Wenn das Attribut 'SplitOnPages=false' gesetzt ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, nicht in einzelne HTML‑Seiten aufgeteilt, sondern in einer großen Ergebnis‑HTML‑Datei zusammengefasst. Jede Quell‑PDF‑Seite wird jedoch in HTML mit ihrem eigenen rechteckigen Bereich dargestellt (falls nötig können diese Bereiche mit dem speziellen Attribut 'PageBorderIfAny' begrenzt werden, um die Kanten des Seitenpapiers zu zeigen). Dieser Parameter definiert die Breite des Randes, der zwingend um die ausgegebenen HTML‑Bereiche, die die Seiten des Quell‑PDF‑Dokuments repräsentieren, gelassen wird. Im Wesentlichen definiert er das garantierte Intervall zwischen den HTML‑Darstellungen von PDF‑„Papier“‑Seiten bei dieser Art der Konvertierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert @deprecated AdditionalMarginWidthInPoints ist veraltet, bitte verwenden Sie stattdessen PageMarginIfAny. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

Dieser Parameter definiert die erforderlichen Antialiasing‑Maßnahmen während der Konvertierung zusammengesetzter Hintergrundbilder von PDF nach HTML.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| antialiasingProcessing |  | AntialiasingProcessingType‑Element @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definiert die Batch-Größe, wenn die stapelweise Konvertierung für das Quell- und Zielformatspaar anwendbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

Setzt das Flag, das angibt, ob gefundene SVG‑Grafiken (falls vorhanden) beim Speichern in das SVGZ‑Format komprimiert (gezippt) werden. Wert: {@code HtmlDocumentType}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

Wenn das Attribut ConvertMarkedContentToLayers auf true gesetzt ist, werden alle Elemente innerhalb eines PDF-markierten Inhalts (Layer) in ein HTML‑div mit dem Attribut "data-pdflayer" eingefügt, das einen Layer‑Namen angibt. Dieser Layer‑Name wird aus optionalen Eigenschaften des PDF-markierten Inhalts extrahiert. Wenn dieses Attribut false ist (standardmäßig), werden keine Layer aus dem PDF-markierten Inhalt erstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
Wenn der PDFtoHTML-Konverter Ergebnis‑CSS-Dateien erzeugt, werden CSS‑Klassennamen (etwa \".stl_01 {}\" ... \".stl_NN {}\") generiert und im Ergebnis‑CSS verwendet. Diese Eigenschaft ermöglicht das Erzwingen eines Klassennamen‑Präfixes. Zum Beispiel, wenn Sie möchten, dass alle Klassennamen mit 'my_prefix_' beginnen (d. h. etwa 'my_prefix_1' ... 'my_prefix_NNN'), dann weisen Sie dieser Eigenschaft vor der Konvertierung einfach 'my_prefix_' zu. Bleibt diese Eigenschaft unverändert (d. h. null bleibt als Wert), erzeugt der Konverter die Klassennamen selbst (es wird etwas wie \".stl_01 {}\" ... \".stl_NN {}\" sein).

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
Dieses Feld kann eine Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung von PDF zu HTML verwendet werden muss, um das Speichern von CSS‑Dateien zu handhaben, die sich auf das erstellte HTML‑Dokument als Ganzes oder auf dessen Seiten beziehen (falls mehrere HTML‑Seiten erzeugt werden). Wenn Sie die CSS‑Datei auf eine bestimmte Weise behandeln möchten, erstellen Sie bitte die entsprechende Methode und weisen Sie dieser Eigenschaft das daraus erstellte Delegat zu.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
Das Ergebnis der Konvertierung kann eine oder mehrere HTML‑Seiten enthalten. Sie können dieser Eigenschaft einen Delegaten zuweisen, der aus einer benutzerdefinierten Methode erstellt wurde, die die Verarbeitung einer HTML‑Seite (genauer gesagt – Markup‑HTML, ohne extern verlinkte Dateien, falls vorhanden) implementiert, die während der Konvertierung erstellt wurde.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Dieser Handler kann verwendet werden, um Konvertierungs‑Fortschrittsereignisse zu behandeln, z. b.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
Dieses Feld kann die Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung für die benutzerdefinierte Handhabung der erstellten referenzierten Ressourcendateien (wie Bilder und Schriftarten) verwendet werden muss, die mit den Knoten des gespeicherten HTML verknüpft sind.

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
Dieses Feld kann eine benutzerdefinierte Methode enthalten, die die URL (oder URL‑Vorlage, falls die Mehrseitengenerierung aktiviert ist – siehe Details unten) des betreffenden CSS zurückgibt, wie sie im erzeugten Ergebnis‑HTML eingefügt werden soll.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Gibt den Namen einer installierten Schriftart an, die verwendet wird, um jede Dokumentschriftart zu ersetzen, die nicht eingebettet und nicht im System installiert ist. Ist der Wert null, wird die Standardschriftart für die Ersetzung verwendet.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
Setzt {@code HtmlDocumentType}.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
Liste der in PDF eingebetteten Schriftartnamen, die nicht in HTML eingebettet werden.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

Mit dieser Eigenschaft können Sie explizit festlegen, welche Seiten des Dokuments konvertiert werden sollen. Seiten in dieser Liste müssen 1‑basierte Nummern haben. D.h. gültige Seitennummern müssen aus dem Bereich (1...[NumberOfPagesInConvertedDocument]) stammen. Die Reihenfolge des Auftretens der Seiten in dieser Liste beeinflusst nicht ihre Reihenfolge in den resultierenden HTML‑Seite(n) – in den Ergebnisseiten werden sie stets in der Reihenfolge angezeigt, in der sie im Quell‑PDF vorkommen. Ist diese Liste null (wie standardmäßig), werden alle Seiten konvertiert. Wenn eine Seitennummer dieser Liste außerhalb des Bereichs der vorhandenen Seiten (1-[amountOfPagesInDocument]) liegt, wird eine Ausnahme ausgelöst.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

Setzt einen Wert, der angibt, ob das HTML als Fixed‑Layout erstellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | : {@code true} wenn [fixed layout]; ansonsten, {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

Dieses Attribut gibt den Absatztext in voller Breite für den Flow‑Modus an, FixedLayout = false

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

Definiert eine spezielle Kodierungsregel, um die PDF‑Dekodierung für das aktuelle Dokument anzupassen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontEncodingStrategy |  | FontEncodingRules‑Element @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

Definiert den Schriftart‑Speichermodus, der beim Speichern von PDF in das gewünschte Format verwendet wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontSavingMode |  | FontSavingModes‑Element @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

Manchmal liegen spezifische Anforderungen an die Erzeugung von HTML‑Markup vor. Dieser Parameter definiert HTML‑Vorbereitungsmodi, die bei der Konvertierung von PDF zu HTML verwendet werden können, um solchen spezifischen Anforderungen gerecht zu werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlMarkupGenerationMode |  | HtmlMarkupGenerationModes‑Element @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Liest oder setzt die Angabe, dass Fehler im Zusammenhang mit fehlenden Schriftarten ignoriert werden. true – bedeutet, dass Fehler wegen fehlender Schriftarten ignoriert werden. Textsegmente, die sich auf falsche Ressourcen beziehen, werden während der Verarbeitung übersprungen. false ist standardmäßig.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

Liefert oder setzt die Auflösung für die Bilddarstellung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Wert: Auflösung |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
Setzt den Modus der Buchstabenpositionierung in Wörtern im resultierenden HTML.

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

Dieses Attribut legt die minimale Breite einer Grafikpfad‑Linie fest. Ist die Linienstärke kleiner als 1 px, rundet Adobe Acrobat sie auf diesen Wert. Dieses Attribut kann also verwendet werden, um dieses Verhalten für HTML‑Browser zu emulieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
Dieses Attribut stellt eine Gruppe von Einstellungen dar, die zum Zeichnen des Rahmens (falls vorhanden) im resultierenden HTML-Dokument um den Bereich verwendet werden, der die Quell‑PDF‑Seite repräsentiert.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
Dieses Attribut repräsentiert eine Gruppe zusätzlicher Seitenränder (falls vorhanden) im resultierenden HTML‑Dokument um den Bereich, der die Quell‑PDF‑Seite darstellt.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

Wenn das Attribut 'SplitOnPages=false' ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, in einer großen Ergebnis‑HTML‑Datei zusammengefasst. Dieses Flag bestimmt, ob das Ergebnis‑HTML so erzeugt wird, dass der Fluss der Bereiche, die PDF‑Seiten im Ergebnis‑HTML repräsentieren, von der Bildschirmauflösung des Betrachters abhängt. Angenommen, die Breite des Bildschirms beim Betrachter ist groß genug, um zwei oder mehr Seiten nebeneinander horizontal anzuzeigen. Wenn dieses Flag auf true gesetzt ist, wird diese Möglichkeit genutzt (so viele Seiten wie möglich werden horizontal nebeneinander angezeigt, dann wird die nächste horizontale Gruppe von Seiten unter der ersten angezeigt). Andernfalls fließen die Seiten so: Die nächste Seite wird immer unter der vorherigen angezeigt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize |  | boolescher Wert |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

Es definiert, ob referenzierte Dateien (HTML, Schriftarten, Bilder, CSS‑Dateien) in die Haupt‑HTML‑Datei eingebettet oder als separate Binär‑Entitäten erzeugt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| partsEmbeddingMode |  | PartsEmbeddingModes‑Element @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

Dieses Attribut schaltet den Modus ein, in dem Textglyphen nicht zu Wörtern und Zeichenketten gruppiert werden. Dieser Modus ermöglicht maximale Präzision bei der Positionierung von Glyphen auf der Seite und kann für die Konvertierung von Dokumenten mit Noten oder Glyphen verwendet werden, die einzeln voneinander platziert werden sollen. Dieser Parameter wird nur auf das Dokument angewendet, wenn der Wert des FixedLayout‑Attributs true ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

Konvertierte PDFs können Rasterbilder enthalten. Dieser Parameter definiert, wie sie bei der Konvertierung von PDF zu HTML behandelt werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImagesSavingMode |  | RasterImagesSavingModes‑Element @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

Definiert, ob im erzeugten HTML der obere und untere leere Bereich ohne Inhalt (falls vorhanden) entfernt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | boolescher Wert |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

Wenn das Attribut RenderTextAsImage auf true gesetzt ist, wird der Text aus der Quelle im HTML zu einem Bild. Dies kann nützlich sein, um Text nicht auswählbar zu machen oder wenn HTML‑Text nicht korrekt gerendert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

Gibt an, dass die vollständige Schriftart gespeichert wird; unterstützt nur True‑Type‑Fonts. Standardmäßig ist SaveFullFont = false und der Konverter speichert das Teilset der ursprünglichen Schriftart, das zum Anzeigen des Textes im Dokument benötigt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

PDF kann Texte enthalten, die von anderen Elementen (z. B. Bildern) überlagert werden, aber im Acrobat Reader in die Zwischenablage kopiert werden können (dies geschieht häufig, wenn das Dokument Bilder und daraus extrahierte OCR‑Texte enthält). Diese Einstellung teilt dem Konverter mit, ob solche Texte als transparente, auswählbare Texte im Ergebnis‑HTML gespeichert werden sollen, um das Verhalten des Acrobat Readers nachzuahmen (andernfalls werden solche Texte normalerweise als versteckt gespeichert und können nicht in die Zwischenablage kopiert werden).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | boolescher Wert |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

Pdf kann transparente Texte enthalten, die in die Zwischenablage kopiert werden können (normalerweise passiert das, wenn das Dokument Bilder und daraus extrahierte OCR‑Texte enthält). Diese Einstellung teilt dem Konverter mit, ob wir solche Texte als transparente auswählbare Texte im Ergebnis‑HTML speichern müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| saveTransparentTexts |  | boolescher Wert |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

Dieses Attribut gibt eine sequentielle Gruppierung von Glyphen und Wörtern zu Zeichenketten an. Zum Beispiel haben Tags und Wörter in konvertiertem HTML unterschiedliche Reihenfolge und Sie möchten, dass sie übereinstimmen. Dieser Parameter wird nur auf das Dokument angewendet, wenn der Wert des FixedLayout‑Attributs true ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
Liefert oder setzt den Pfad zu dem Verzeichnis, in dem alle Bilder gespeichert werden müssen, die beim Speichern des Dokuments als HTML auftreten. Ist der Parameter leer oder null, werden Bilddateien (falls vorhanden) zusammen mit den anderen an HTML gebundenen Dateien gespeichert. Dies hat keine Auswirkung, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die betreffende Bilddatei zu verarbeiten.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
Liefert oder setzt den Pfad zu dem Verzeichnis, in dem ausschließlich SVG‑Bilder gespeichert werden müssen, wenn sie beim Speichern des Dokuments als HTML auftreten. Ist der Parameter leer oder null, werden SVG‑Dateien (falls vorhanden) zusammen mit den anderen Bilddateien (in der Nähe der Ausgabedatei) oder in einem speziellen Bildordner (wenn im Parameter SpecialImagesFolderIfAny angegeben) gespeichert. Dies hat keine Auswirkung, wenn die Eigenschaft CustomImageSavingStrategy erfolgreich verwendet wurde, um die betreffende Bilddatei zu verarbeiten.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

Wenn der Mehrseitigen‑Modus ausgewählt ist (d. h. 'SplitIntoPages' ist 'true'), definiert dieses Attribut, ob für jede Ergebnis‑HTML‑Seite eine separate CSS‑Datei erstellt werden soll. Standardmäßig ist dieses Attribut false, sodass ein großes gemeinsames CSS für alle erstellten Seiten erzeugt wird. Die Gesamtsumme der in diesem Modus (ein CSS pro Seite) erzeugten CSS‑Dateien ist in der Regel viel größer als die Größe einer einzigen großen CSS‑Datei, weil in dem ersten Fall CSS‑Klassen in mehreren CSS‑Dateien für jede Seite dupliziert werden. Daher sollte diese Einstellung nur verwendet werden, wenn Sie an einer späteren Verarbeitung jeder HTML‑Seite unabhängig voneinander interessiert sind und daher die Größe des CSS jeder einzelnen Seite das kritischste Problem darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

Setzt das Flag, das angibt, ob jede Seite des Quelldokuments in ein eigenes Ziel‑HTML‑Dokument konvertiert wird, d. h. ob das Ergebnis‑HTML in mehrere HTML‑Seiten aufgeteilt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTitle {#setTitle-java.lang.String-}
Liefert oder setzt den HTML‑Seitentitel.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

PDF selbst enthält keine Unterstreichungs‑Marker für Texte. Sie werden durch eine Linie unter dem Text simuliert. Diese Option ermöglicht es dem Konverter, zu versuchen zu erraten, dass diese oder jene Linie eine Textunterstreichung ist, und diese Information in CSS zu hinterlegen, anstatt die Unterstreichung grafisch zu zeichnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | boolescher Wert |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

Wenn das Attribut UseZORder auf true gesetzt ist, werden Grafiken und Text dem resultierenden HTML‑Dokument entsprechend der Z‑Reihenfolge im ursprünglichen PDF‑Dokument hinzugefügt. Ist dieses Attribut false, werden alle Grafiken als einzelne Ebene eingefügt, was bei überlappenden Objekten zu unnötigen Effekten führen kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
