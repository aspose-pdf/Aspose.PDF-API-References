---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Document-Klasse. Klasse, die ein PDF-Dokument repräsentiert
type: docs
weight: 3780
url: /de/net/aspose.pdf/document/
---
## Dokumentklasse

Klasse, die ein PDF-Dokument repräsentiert.

```csharp
public sealed class Document : IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Document](document/#constructor)() | Initialisiert ein leeres Dokument. |
| [Document](document/#constructor_1)(PdfVersion) | Initialisiert ein leeres Dokument anhand der Version. |
| [Document](document/#constructor_2)(Stream) | Initialisiert eine neue Document-Instanz aus dem *input* stream. |
| [Document](document/#constructor_7)(string) | Initialisiert Document nur mit *filename*. Dasselbe wie [`Document`](./document/). |
| [Document](document/#constructor_4)(Stream, bool) | Initialisiert eine neue Document-Instanz aus dem *input* stream. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Öffnet ein bestehendes Dokument aus einem Stream und wendet die notwendige Konvertierung an, um ein PDF-Dokument zu erhalten. |
| [Document](document/#constructor_5)(Stream, string) | Initialisiert eine neue Document-Instanz aus dem *input* stream. |
| [Document](document/#constructor_9)(string, bool) | Initialisiert Document nur mit *filename*. Dasselbe wie [`Document`](./document/). |
| [Document](document/#constructor_8)(string, LoadOptions) | Öffnet ein bestehendes Dokument aus einer Datei und wendet die erforderlichen Konvertierungsoptionen an, um ein PDF-Dokument zu erhalten. |
| [Document](document/#constructor_10)(string, string) | Initialisiert eine neue Instanz der `Document`-Klasse für die Arbeit mit einem verschlüsselten Dokument. |
| [Document](document/#constructor_6)(Stream, string, bool) | Initialisiert eine neue Document-Instanz aus dem *input* stream. |
| [Document](document/#constructor_11)(string, string, bool) | Initialisiert eine neue Instanz der `Document`-Klasse für die Arbeit mit einem verschlüsselten Dokument. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Ruft Dokumentaktionen ab. Diese Eigenschaft ist eine Instanz der DocumentActions-Klasse, welche das Abrufen/Setzen von BeforClosing, BeforSaving etc. Aktionen ermöglicht. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Ermöglicht es, Seiteninhalte zusammenzuführen, um die Dokumentgröße zu optimieren. Falls verwendet, können unterschiedliche, aber duplizierte Seiten auf dasselbe Inhaltsobjekt verweisen. Bitte beachten Sie, dass dieser Modus Nebenwirkungen verursachen kann, wie beispielsweise Änderungen am Seiteninhalt, wenn eine andere Seite geändert wird. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Ruft die Hintergrundfarbe des Dokuments ab oder legt sie fest. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Ruft das Flag ab oder legt es fest, ob das Fenster des Dokuments zentriert auf dem Bildschirm angezeigt wird. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Ruft die Dokumentensammlung ab. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Ruft die Sicherheitseinstellungen ab, falls das Dokument verschlüsselt ist. Ist das Dokument nicht verschlüsselt, wird in .net 1.1 eine entsprechende Ausnahme ausgelöst oder CryptoAlgorithm ist in anderen .net-Versionen null. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Ruft die Sammlung der Ziele ab. Veraltet. Bitte verwenden Sie NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Ruft die Leserichtung des Texts ab oder legt sie fest: L2R (von links nach rechts) oder R2L (von rechts nach links). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Viele Operationen mit Fonts können nicht ausgeführt werden, wenn diese durch die Lizenz des Fonts untersagt sind. Zum Beispiel kann ein Font nicht in ein PDF-Dokument eingebettet werden, wenn die Lizenzvorgaben das Einbetten dieses Fonts deaktivieren. Dieses Flag wird verwendet, um jegliche Lizenzbeschränkungen für alle Fonts im aktuellen PDF-Dokument zu deaktivieren. Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet dies, dass die Person, die dieses Flag setzt, die volle Verantwortung für eventuelle Lizenz- bzw. Gesetzesverletzungen übernimmt. Er geschieht also auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich absolut sicher sind, dass Sie nicht gegen das Urheberrecht verstoßen. Standardmäßig false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Ruft das Flag ab oder legt es fest, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Ruft die Einstellung für den beidseitigen Druckmodus ab oder legt sie fest, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Ruft die Sammlung der in das Dokument eingebetteten Dateien ab. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Eigenschaft, die angibt, dass das Dokument alle Standard-Type1-Fonts einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist. Alle PDF-Fonts können in das Dokument eingebettet werden, indem das Flag IsEmbedded einfach auf true gesetzt wird, aber bei Standard-Type1-Fonts gilt eine Ausnahme. Das Einbetten von Standard-Type1-Fonts erfordert viel Zeit, daher ist es notwendig, nicht nur das Flag IsEmbedded für den jeweiligen Font auf true zu setzen, sondern auch ein zusätzliches Flag auf Dokumentebene – EmbedStandardFonts = true. Diese Eigenschaft kann nur einmal für alle Fonts gesetzt werden. Standardmäßig false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Ruft das Flag ab oder legt es fest, das es ermöglicht, Teile des Dokuments aus dem Arbeitsspeicher zu entladen. Dies ermöglicht eine Verringerung des Speicherverbrauchs, kann jedoch die Leistung negativ beeinträchtigen. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Ruft das Flag zum Verwalten der Bereinigung von Signaturfeldern ab oder legt es fest. Standardmäßig aktiviert. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Name der PDF-Datei, die dieses Dokument verursacht hat |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Ruft das Flag ab oder legt es fest, ob das Dokumentfenster an die erste angezeigte Seite angepasst werden soll. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Instanz von IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Ruft das Acro-Formular des Dokuments ab. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Löst eine Ausnahme aus, wenn das Dokument mit Änderungen und Signaturen gespeichert wird. |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Ruft das Flag ab oder legt es fest, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Ruft das Flag ab oder legt es fest, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Ruft das Flag ab oder legt es fest, ob die Benutzeroberflächen-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. |
| [Id](../../aspose.pdf/document/id/) { get; } | Ruft die ID ab. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Ruft das Flag ab oder legt es fest, ob Fehler in Quelldateien ignoriert werden sollen. Wenn Seiten aus dem Quelldokument in das Zieldokument kopiert werden, wird der Kopiervorgang mit einer Ausnahme beendet, falls einige Objekte in den Quelldateien beschädigt sind und dieses Flag auf false gesetzt ist. Beispiel: dest.Pages.Add(src.Pages); Ist dieses Flag auf true gesetzt, werden beschädigte Objekte durch leere Werte ersetzt. Standardmäßig: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Ruft die Dokumentinformationen ab. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Ruft den Verschlüsselungsstatus des Dokuments ab. True, wenn das Dokument verschlüsselt ist. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Dokument linearisiert ist. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Ruft ab, ob das Dokument PDF/A-konform ist. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Ruft ab, ob das Dokument PDF/UA-konform ist. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Ruft ab oder legt fest, ob Lücken in Xref erlaubt sind. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Sammlung von JavaScript auf Dokumentebene. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Ruft die logische Struktur des Dokuments ab. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Dokument-Metadaten. (Ein PDF-Dokument kann allgemeine Informationen enthalten, wie den Titel, den Autor sowie das Erstellungs- und Änderungsdatum. Solche globalen Informationen über das Dokument (im Gegensatz zu seinem Inhalt oder seiner Struktur) werden als Metadaten bezeichnet und sollen bei der Katalogisierung und Suche von Dokumenten in externen Datenbanken helfen.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Sammlung der benannten Ziele im Dokument. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Ruft den Seitenmodus ab oder legt ihn fest, der bestimmt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Ruft die beim Öffnen des Dokuments ausgeführte Aktion ab oder legt sie fest. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Ruft das Optimierungsflag ab oder legt es fest. Wenn Seiten zum Dokument hinzugefügt werden, werden gleiche Ressourcestreams in der resultierenden Datei zu einem PDF-Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der Dateigröße, kann jedoch zu langsameren Ausführungen und einem höheren Speicherbedarf führen. Standardwert: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Ruft die Dokumentgliederungen ab. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Ruft die Sammlung der Output-Intents im Dokument ab. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Ruft die Seiteninformationen ab oder legt sie fest. (Nur für den Generator; wird beim Lesen des Dokuments nicht ausgefüllt) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Ruft die Seitenbeschriftungen im Dokument ab. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Ruft das Seitenlayout ab oder legt es fest, das beim Öffnen des Dokuments verwendet werden soll. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Ruft den Seitenmodus ab oder legt ihn fest, der bestimmt, wie das Dokument beim Öffnen angezeigt werden soll. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Ruft die Sammlung der Dokumentseiten ab oder legt sie fest. Beachten Sie, dass die Seiten in der Sammlung ab 1 nummeriert sind. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Ruft das PDF-Format ab. |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Ruft die Berechtigungen des Dokuments ab. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Ruft das Flag ab oder legt es fest, ob die PDF-Seitengröße zur Auswahl des Eingabefachs verwendet werden soll. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Ruft die Skalierungsoption ab oder legt sie fest, die ausgewählt werden soll, wenn ein Druckdialog für dieses Dokument angezeigt wird. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Gewährt Zugriff auf TaggedPdf-Inhalte. |
| [Version](../../aspose.pdf/document/version/) { get; } | Ruft eine Version von PDF aus dem PDF-Dateikopf ab. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Liest und legt die Dateigrößengrenze für das Laden einer gesamten Datei in den Speicher fest. Der Wert wird in Megabyte angegeben. Der Standardwert beträgt 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Ruft den Lizenzstatus des Systems ab. Gibt true zurück, wenn das System im lizenzierten Modus arbeitet, und andernfalls false. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Fügt Dokumente zusammen. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Fügt PDF-Dateien zusammen. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Fügt Dokumente zusammen. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Fügt Dokumente zusammen. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Bindet XML an das Dokument. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Bindet XML an das Dokument. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Bindet XML/XSL an das Dokument. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Bindet XML/XSL an das Dokument. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Bindet XML/XSL an das Dokument. |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Ändert die Dokumentpasswörter. Diese Aktion kann nur mit dem Besitzerpasswort durchgeführt werden. |
| [Check](../../aspose.pdf/document/check/)(bool) | Validiert das Dokument. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Konvertiert das Dokument unter Verwendung der angegebenen Konvertierungsoptionen. |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Erkennt Bilder im Dokument und fügt Hocr-Strings darüber ein. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Erkennt Bilder im Dokument und fügt Hocr-Strings darüber ein. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Konvertiert das Dokument und speichert Fehler in den angegebenen Stream. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Konvertiert das Dokument und speichert Fehler in der angegebenen Datei. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Konvertiert das Dokument unter Anwendung des Fixups. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Konvertiert das Dokument unter Anwendung des Fixups. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konvertiert das Dokument und speichert Fehler in der angegebenen Datei. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konvertiert das Dokument und speichert Fehler in der angegebenen Datei. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Konvertiert die Seite zu PNG für DSR-, OMR- und OCR-Bildstream. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Entschlüsselt das Dokument. Rufen Sie anschließend Save auf, um eine entschlüsselte Version des Dokuments zu erhalten. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Schließt alle vom Dokument verwendeten Ressourcen. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Verschlüsselt das Dokument. Rufen Sie anschließend Save auf, um eine verschlüsselte Version des Dokuments zu erhalten. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Verschlüsselt das Dokument. Rufen Sie anschließend Save auf, um eine verschlüsselte Version des Dokuments zu erhalten. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Verschlüsselt das Dokument. Rufen Sie anschließend Save auf, um eine verschlüsselte Version des Dokuments zu erhalten. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Exportiert alle Dokumentanmerkungen in einen Stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Exportiert alle Dokumentanmerkungen in eine XFDF-Datei. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Entfernt alle Felder aus dem Dokument und ersetzt sie durch ihre Werte. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Entfernt alle Felder (und Anmerkungen) aus dem Dokument und ersetzt sie durch ihre Werte. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Ersetzt transparenten Inhalt durch undurchsichtige Raster- und Vektorgrafiken. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Leert den Speicher. |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Gibt den Wert eines Elements aus dem Katalogwörterbuch zurück. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Ruft ein Objekt mit der angegebenen ID im Dokument ab. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Ruft XMP-Metadaten aus dem Dokument ab. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Prüft, ob das aktuelle PDF-Dokument mit inkrementellen Updates gespeichert wurde. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importiert Anmerkungen aus einem Stream in das Dokument. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importiert Anmerkungen aus einer XFDF-Datei in das Dokument. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Prüft, ob das Dokument einen Aufruf der Repair-Methode erfordert. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Lädt eine Datei und konvertiert sie in PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Fügt Dokumente zusammen. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Fügt PDF-Dateien zusammen. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Fügt Dokumente zusammen. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Fügt Dokumente zusammen. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Linearisiert das Dokument, um – die erste Seite so schnell wie möglich zu öffnen; – die nächste Seite anzuzeigen oder einen Link zur nächsten Seite so schnell wie möglich bereitzustellen; – die Seite schrittweise anzuzeigen, während sie über einen langsamen Kanal (wobei die nützlichsten Daten zuerst angezeigt werden) geliefert wird; – Benutzerinteraktionen, wie beispielsweise das Folgen eines Links, zu ermöglichen, noch bevor die gesamte Seite empfangen und angezeigt wurde. Das Aufrufen dieser Methode speichert das Dokument nicht tatsächlich. Stattdessen wird das Dokument lediglich für eine optimierte Struktur vorbereitet. Rufen Sie anschließend Save auf, um das optimierte Dokument zu erhalten. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Optimiert Ressourcen im Dokument: 1. Ressourcen, die auf den Dokumentseiten nicht verwendet werden, werden entfernt; 2. Gleiche Ressourcen werden zu einem Objekt zusammengeführt; 3. Ungenutzte Objekte werden gelöscht. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Optimiert Ressourcen im Dokument gemäß der definierten Optimierungsstrategie. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organisiert die Seitennoden eines Dokuments in einen ausbalancierten Baum. Dies geschieht nur, wenn das Dokument mehr als nodesNumInSubtrees Seitenobjekte enthält; andernfalls wird nichts unternommen. Rufen Sie diese Methode nicht auf, während Sie über die Pages-Elemente iterieren, da dies unvorhersehbare Ergebnisse liefern kann. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Verarbeitet Absätze für den Generator. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Entfernt Metadaten aus dem Dokument. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Entfernt die PDF/A-Konformität aus dem Dokument. |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Entfernt die PDF/UA-Konformität aus dem Dokument. |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Repariert ein beschädigtes Dokument. |
| [Save](../../aspose.pdf/document/save/#save)() | Speichert das Dokument inkrementell (d.h. unter Verwendung der inkrementellen Aktualisierungstechnik). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Speichert das Dokument mit den Speicheroptionen. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Speichert das Dokument in einem Stream. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Speichert das Dokument in der angegebenen Datei. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Speichert das Dokument in einem Stream mit Speicheroptionen. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Speichert das Dokument inkrementell (d.h. unter Verwendung der inkrementellen Aktualisierungstechnik). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Speichert das Dokument mit den Speicheroptionen. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Speichert das Dokument in einem Stream. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Speichert das Dokument in der angegebenen Datei. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Speichert das Dokument in einem Stream mit Speicheroptionen. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Speichert das Dokument als XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Sendet das gesamte Dokument an das DocumentDevice zur Verarbeitung. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Sendet das gesamte Dokument an das DocumentDevice zur Verarbeitung. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Sendet bestimmte Seiten des Dokuments an das DocumentDevice zur Verarbeitung. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Sendet das gesamte Dokument an das DocumentDevice zur Verarbeitung. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Setzt den Titel für das PDF-Dokument. |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Setzt die XMP-Metadaten des Dokuments. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Validiert das Dokument in der angegebenen Datei. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Validiert das Dokument in der angegebenen Datei. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Validiert das Dokument in der angegebenen Datei. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Konvertiert einen Stream im Quellformat in einen Stream im Zielformat. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Konvertiert einen Stream im Quellformat in eine Zieldatei im Zielformat. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Konvertiert eine Quelldatei im Quellformat in einen Stream im Zielformat. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Konvertiert eine Quelldatei im Quellformat in eine Zieldatei im Zielformat. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Setzt die Dateigrößengrenze für das Laden einer gesamten Datei in den Speicher auf den Standardwert von 210 Mb. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Ereignisse

| Name | Beschreibung |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Tritt auf, wenn ein Font einen anderen Font im Dokument ersetzt. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Repräsentiert die Methode, die das FontSubstitution-Ereignis behandelt. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Enthält Funktionalitäten zur Anpassung von Fonts. |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Repräsentiert die Optionen für Merge-Methoden. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Repräsentiert Optionen zur Reparatur eines PDF-Dokuments. |

### Siehe auch

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)