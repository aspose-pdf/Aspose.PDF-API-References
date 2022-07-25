---
title: Document
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse die das PDF-Dokument darstellt
type: docs
weight: 1870
url: /de/net/aspose.pdf/document/
---
## Document class

Klasse, die das PDF-Dokument darstellt

```csharp
public sealed class Document : IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Document](document#constructor)() | Initialisiert leeres Dokument. |
| [Document](document#constructor_1)(Stream) | Neue Dokumentinstanz aus der initialisieren*input* stream. |
| [Document](document#constructor_6)(string) | Einfach Dokument mit initieren*filename* . Das Gleiche wie[`Document`](./document) . |
| [Document](document#constructor_3)(Stream, bool) | Neue Dokumentinstanz aus der initialisieren*input* stream. |
| [Document](document#constructor_2)(Stream, LoadOptions) | Öffnet ein vorhandenes Dokument aus einem Stream und stellt die erforderliche Konvertierung bereit, um ein PDF-Dokument zu erhalten. |
| [Document](document#constructor_4)(Stream, string) | Neue Dokumentinstanz aus der initialisieren*input* stream. |
| [Document](document#constructor_7)(string, LoadOptions) | Öffnet ein vorhandenes Dokument aus einer Datei und bietet die erforderlichen Konvertierungsoptionen, um ein PDF-Dokument zu erhalten. |
| [Document](document#constructor_8)(string, string) | Initialisiert eine neue Instanz von[`Document`](../document) Klasse zum Arbeiten mit verschlüsselten Dokumenten. |
| [Document](document#constructor_5)(Stream, string, bool) | Neue Dokumentinstanz aus der initialisieren*input* stream. |
| [Document](document#constructor_9)(string, string, bool) | Initialisiert eine neue Instanz von[`Document`](../document) Klasse zum Arbeiten mit verschlüsselten Dokumenten. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions) { get; } | Ruft Dokumentaktionen ab. Diese Eigenschaft ist eine Instanz der DocumentActions-Klasse, die es ermöglicht, BeforClosing-, BeforSaving- usw. Aktionen zu erhalten/einzustellen. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent) { get; set; } | Ermöglicht das Zusammenführen von Seiteninhalten, um die Dokumentgröße zu optimieren. Wenn sie verwendet werden, können unterschiedliche, aber duplizierte Seiten auf das gleiche Inhaltsobjekt verweisen. Bitte beachten Sie, dass dieser Modus Nebeneffekte verursachen kann, wie z. B. das Ändern des Seiteninhalts, wenn eine andere Seite geändert wird. |
| [Background](../../aspose.pdf/document/background) { get; set; } | Ruft die Hintergrundfarbe des Dokuments ab oder legt sie fest. |
| [CenterWindow](../../aspose.pdf/document/centerwindow) { get; set; } | Ruft oder setzt ein Flag, das angibt, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird. |
| [Collection](../../aspose.pdf/document/collection) { get; set; } | Holt Sammlung von Dokumenten. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm) { get; } | Ruft Sicherheitseinstellungen ab, wenn das Dokument verschlüsselt ist. Wenn das Dokument nicht verschlüsselt ist, wird die entsprechende Ausnahme in .net 1.1 ausgelöst oder CryptoAlgorithm ist für andere .net-Versionen null. |
| [Destinations](../../aspose.pdf/document/destinations) { get; } | Ruft die Sammlung von Zielen ab. Veraltet. Bitte verwenden Sie NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction) { get; set; } | Ruft die Lesereihenfolge des Textes ab oder legt sie fest: L2R (von links nach rechts) oder R2L (von rechts nach links). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications) { get; set; } | Viele Operationen mit Schriftarten können nicht ausgeführt werden, wenn diese Operationen durch die Lizenz dieser Schriftart verboten sind. Einige Schriftarten können beispielsweise nicht in ein PDF-Dokument eingebettet werden, wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Dieses Flag wird verwendet, um alle Lizenzbeschränkungen für alle Schriftarten im aktuellen PDF-Dokument zu deaktivieren. Seien Sie vorsichtig, wenn Sie dieses Flag verwenden. Wenn es gesetzt ist, bedeutet dies, dass die Person, die dieses Flag setzt, die gesamte Verantwortung für mögliche Lizenz-/Gesetzesverstöße auf sich trägt. Also übernimmt er es auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie absolut sicher sind, dass Sie nicht gegen das Urheberrechtsgesetz verstoßen. Standardmäßig falsch. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle) { get; set; } | Ruft oder setzt ein Flag, das angibt, ob die Fenstertitelleiste des Dokuments den Dokumenttitel anzeigen soll. |
| [Duplex](../../aspose.pdf/document/duplex) { get; set; } | Ruft die Behandlungsoption für den Duplexdruck ab oder legt sie fest, die verwendet werden soll, wenn die Datei aus dem Druckdialogfeld gedruckt wird. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles) { get; } | Ruft eine Sammlung von Dateien ab, die in das Dokument eingebettet sind. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts) { get; set; } | Eigenschaft, die angibt, dass das Dokument alle standardmäßigen Type1-Schriftarten einbetten muss, deren Flag IsEmbedded auf true gesetzt ist. Alle PDF-Fonts können in das Dokument eingebettet werden, indem einfach das Flag IsEmbedded auf true gesetzt wird, aber PDF-Standard-Type1-Fonts sind eine Ausnahme von dieser Regel. Das Einbetten von Standard-Type1-Fonts erfordert viel Zeit, daher ist es notwendig, diese Fonts einzubetten und nicht nur das Flag zu setzen IsEmbedded auf true für die angegebene Schriftart gesetzt, aber auch ein zusätzliches Flag auf Dokumentebene gesetzt - EmbedStandardFonts = true; Diese Eigenschaft kann nur einmal für alle Schriftarten gesetzt werden. Standardmäßig false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload) { get; set; } | Flag abrufen oder setzen, das das teilweise Entladen des Dokuments aus dem Speicher ermöglicht. Dadurch kann die Speicherauslastung verringert werden, kann sich jedoch negativ auf die Leistung auswirken. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization) { get; set; } | Ruft ein Flag ab oder setzt es, um die Bereinigung von Signaturfeldern zu verwalten. Standardmäßig aktiviert. |
| [FileName](../../aspose.pdf/document/filename) { get; } | Name der PDF-Datei, die dieses Dokument verursacht hat |
| [FitWindow](../../aspose.pdf/document/fitwindow) { get; set; } | Ruft ein Flag ab oder setzt es, das angibt, ob die Größe des Dokumentfensters geändert werden muss, damit es auf die erste angezeigte Seite passt. |
| [FontUtilities](../../aspose.pdf/document/fontutilities) { get; } | IDocumentFontUtilities-Instanz |
| [Form](../../aspose.pdf/document/form) { get; } | Ruft das Acro-Formular des Dokuments ab. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange) { get; set; } | Ausnahme auslösen, wenn das Dokument mit Änderungen gespeichert wird und Signatur hat |
| [HideMenubar](../../aspose.pdf/document/hidemenubar) { get; set; } | Ruft oder setzt ein Flag, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar) { get; set; } | Ruft oder setzt ein Flag, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui) { get; set; } | Ruft oder setzt ein Flag, das angibt, ob Elemente der Benutzeroberfläche ausgeblendet werden sollen, wenn das Dokument aktiv ist. |
| [Id](../../aspose.pdf/document/id) { get; } | Ruft die ID ab. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects) { get; set; } | Ruft oder setzt Flag zum Ignorieren von Fehlern in Quelldateien. Wenn Seiten aus dem Quelldokument in das Zieldokument kopiert werden, wird der Kopiervorgang mit der Ausnahme gestoppt, wenn einige Objekte in den Quelldateien beschädigt sind, wenn dieses Flag falsch ist. Beispiel: dest.Pages.Add(src.Pages); Wenn dieses Flag auf true gesetzt ist, werden beschädigte Objekte durch leere Werte ersetzt. Standardmäßig: true. |
| [Info](../../aspose.pdf/document/info) { get; } | Ruft Dokumentinformationen ab. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted) { get; } | Ruft den verschlüsselten Status des Dokuments ab. Wahr, wenn das Dokument verschlüsselt ist. |
| [IsLinearized](../../aspose.pdf/document/islinearized) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Dokument linearisiert ist. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant) { get; } | Ruft das Dokument pdfa-konform ab. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant) { get; } | Ruft das Dokument pdfua-konform ab. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed) { get; set; } | Ruft ab oder legt fest, ob das Dokument pdfa-konform ist. |
| [JavaScript](../../aspose.pdf/document/javascript) { get; } | Sammlung von JavaScript auf Dokumentebene. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure) { get; } | Ruft die logische Struktur des Dokuments ab. |
| [Metadata](../../aspose.pdf/document/metadata) { get; } | Metadaten des Dokuments. (Ein PDF-Dokument kann allgemeine Informationen enthalten, wie z. B. Titel, Autor sowie Erstellungs- und Änderungsdatum des Dokuments. Solche globalen Informationen über das Dokument (im Gegensatz zu seinem Inhalt oder seiner Struktur) werden als Metadaten bezeichnet und sind soll bei der Katalogisierung und Suche nach Dokumenten in externen Datenbanken helfen.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations) { get; } | Sammlung benannter Ziele im Dokument. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode) { get; set; } | Ruft den Seitenmodus ab oder legt ihn fest und gibt an, wie das Dokument beim Verlassen des Vollbildmodus angezeigt werden soll. |
| [OpenAction](../../aspose.pdf/document/openaction) { get; set; } | Ruft die beim Öffnen des Dokuments durchgeführte Aktion ab oder legt sie fest. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize) { get; set; } | Holt oder setzt Optimierungs-Flag. Wenn Seiten zu einem Dokument hinzugefügt werden, werden gleiche Ressourcenströme in der resultierenden Datei zu einem PDF-Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der resultierenden Dateigröße, kann jedoch zu einer langsameren Ausführung und größeren Speicheranforderungen führen. Standardwert: false. |
| [Outlines](../../aspose.pdf/document/outlines) { get; } | Ruft Dokumentumrisse ab. |
| [PageInfo](../../aspose.pdf/document/pageinfo) { get; set; } | Ruft die Seiteninformationen ab oder legt sie fest. (nur für Generator) |
| [PageLabels](../../aspose.pdf/document/pagelabels) { get; } | Ruft Seitenbeschriftungen im Dokument ab. |
| [PageLayout](../../aspose.pdf/document/pagelayout) { get; set; } | Ermittelt oder setzt das Seitenlayout, das verwendet werden soll, wenn das Dokument geöffnet wird. |
| [PageMode](../../aspose.pdf/document/pagemode) { get; set; } | Ruft den Seitenmodus ab oder setzt ihn und gibt an, wie das Dokument beim Öffnen angezeigt werden soll. |
| [Pages](../../aspose.pdf/document/pages) { get; } | Ruft eine Sammlung von Dokumentseiten ab oder legt sie fest. Beachten Sie, dass die Seiten in der Sammlung von 1 an nummeriert sind. |
| [PdfFormat](../../aspose.pdf/document/pdfformat) { get; } | Ruft das PDF-Format ab |
| [Permissions](../../aspose.pdf/document/permissions) { get; } | Ruft Berechtigungen des Dokuments ab. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent) { get; } | Erhält Zugriff auf TaggedPdf-Inhalte. |
| [Version](../../aspose.pdf/document/version) { get; } | Ruft eine PDF-Version aus dem Header der PDF-Datei ab. |
| static [IsLicensed](../../aspose.pdf/document/islicensed) { get; } | Ruft den lizenzierten Status des Systems ab. Gibt „true“ zurück, wenn das System im lizenzierten Modus arbeitet, andernfalls „false“. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml)(Stream) | XML an document binden |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_3)(string) | XML an document binden |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_1)(Stream, Stream) | xml/xsl an document binden |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_4)(string, string) | xml/xsl an document binden |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_2)(Stream, Stream, XmlReaderSettings) | xml/xsl an document binden |
| [ChangePasswords](../../aspose.pdf/document/changepasswords)(string, string, string) | Ändert Dokumentpasswörter. Diese Aktion kann nur mit dem Besitzerpasswort durchgeführt werden. |
| [Check](../../aspose.pdf/document/check)(bool) | Dokument validiert. |
| [Convert](../../aspose.pdf/document/convert#convert_3)(CallBackGetHocr) | Dokument konvertieren und Fehler in der angegebenen Datei speichern. |
| [Convert](../../aspose.pdf/document/convert#convert_2)(PdfFormatConversionOptions) | Dokument mit angegebenen Konvertierungsoptionen konvertieren |
| [Convert](../../aspose.pdf/document/convert#convert_4)(Stream, PdfFormat, ConvertErrorAction) | Dokument konvertieren und Fehler im angegebenen Stream speichern. |
| [Convert](../../aspose.pdf/document/convert#convert_6)(string, PdfFormat, ConvertErrorAction) | Dokument konvertieren und Fehler in der angegebenen Datei speichern. |
| [Convert](../../aspose.pdf/document/convert#convert)(Fixup, Stream, bool, object[]) | Konvertieren Sie das Dokument, indem Sie das Fixup anwenden. |
| [Convert](../../aspose.pdf/document/convert#convert_1)(Fixup, string, bool, object[]) | Konvertieren Sie das Dokument, indem Sie das Fixup anwenden. |
| [Convert](../../aspose.pdf/document/convert#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Dokument konvertieren und Fehler in der angegebenen Datei speichern. |
| [Convert](../../aspose.pdf/document/convert#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Dokument konvertieren und Fehler in der angegebenen Datei speichern. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream)(Page) | Seite für DSR-, OMR- und OCR-Bildstream in PNG konvertieren. |
| [Decrypt](../../aspose.pdf/document/decrypt)() | Entschlüsselt das Dokument. Rufen Sie dann Speichern auf, um eine entschlüsselte Version des Dokuments zu erhalten. |
| [Dispose](../../aspose.pdf/document/dispose)() | Schließt alle von diesem Dokument verwendeten Ressourcen. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Verschlüsselt das Dokument. Rufen Sie auf und speichern Sie, um eine verschlüsselte Version des Dokuments zu erhalten. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Verschlüsselt das Dokument. Rufen Sie auf und speichern Sie, um eine verschlüsselte Version des Dokuments zu erhalten. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Verschlüsselt das Dokument. Rufen Sie auf und speichern Sie, um eine verschlüsselte Version des Dokuments zu erhalten. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf)(Stream) | Alle Dokumentanmerkungen in den Stream exportieren. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf_1)(string) | Exportiert alle Dokumentanmerkungen in die XFDF-Datei |
| [Flatten](../../aspose.pdf/document/flatten#flatten)() | Entfernt alle Felder aus dem Dokument und setzt stattdessen ihre Werte. |
| [Flatten](../../aspose.pdf/document/flatten#flatten_1)(FlattenSettings) | Entfernt alle Felder aus dem Dokument und setzt stattdessen ihre Werte. |
| [FreeMemory](../../aspose.pdf/document/freememory)() | Speicher löschen |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue)(string) | Gibt den Artikelwert aus dem Katalogwörterbuch zurück. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid)(string) | Ruft ein Objekt mit angegebener ID im Dokument ab. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata)(Stream) | XMP-Metadaten aus dem Dokument abrufen. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importiert Anmerkungen aus dem Stream in das Dokument. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importiert Anmerkungen aus der XFDF-Datei in das Dokument. |
| [Optimize](../../aspose.pdf/document/optimize)() | Dokument linearisieren, um - die erste Seite so schnell wie möglich zu öffnen; - die nächste Seite anzuzeigen oder per Link zur nächsten Seite so schnell wie möglich zu folgen; - die Seite inkrementell anzuzeigen, wenn sie ankommt, wenn Daten für eine Seite geliefert werden über einen langsamen Kanal (zeigen Sie zuerst die nützlichsten Daten an); - Ermöglichen Sie Benutzerinteraktionen, wie z. B. das Folgen eines Links, noch bevor die gesamte Seite empfangen und angezeigt wurde. Durch Aufrufen dieser Methode wird das Dokument nicht wirklich gespeichert . Im Gegensatz dazu ist das Dokument nur so vorbereitet, dass es eine optimierte Struktur hat, aufrufen und dann Speichern, um ein optimiertes Dokument zu erhalten. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources)() | Ressourcen im Dokument optimieren: 1. Ressourcen, die auf den Dokumentseiten nicht verwendet werden, werden entfernt; 2. Gleiche Ressourcen werden zu einem Objekt zusammengefügt; 3. Nicht verwendete Objekte werden gelöscht. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources_1)(OptimizationOptions) | Ressourcen im Dokument gemäß definierter Optimierungsstrategie optimieren. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs)() | Prozessparagrafen für Generator. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata)() | Entfernt Metadaten aus dem Dokument. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance)() | PDFA-Konformität aus dem Dokument entfernen |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance)() | Entfernen Sie die pdfUa-Konformität aus dem Dokument |
| [Repair](../../aspose.pdf/document/repair)() | Repariert defektes Dokument. |
| [Save](../../aspose.pdf/document/save#save)() | Dokument inkrementell speichern (dh mit inkrementeller Aktualisierungstechnik). |
| [Save](../../aspose.pdf/document/save#save_1)(SaveOptions) | Speichert das Dokument mit Speicheroptionen. |
| [Save](../../aspose.pdf/document/save#save_2)(Stream) | Speichert das Dokument im Stream. |
| [Save](../../aspose.pdf/document/save#save_5)(string) | Speichert das Dokument in der angegebenen Datei. |
| [Save](../../aspose.pdf/document/save#save_3)(Stream, SaveFormat) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| [Save](../../aspose.pdf/document/save#save_4)(Stream, SaveOptions) | Speichert das Dokument in einem Stream mit Speicheroptionen. |
| [Save](../../aspose.pdf/document/save#save_6)(string, SaveFormat) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| [Save](../../aspose.pdf/document/save#save_7)(string, SaveOptions) | Speichert das Dokument unter einem neuen Namen und setzt seine Speicheroptionen. |
| [Save](../../aspose.pdf/document/save#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | Speichert das Dokument in einem Antwortstrom mit Speicheroptionen. |
| [SaveXml](../../aspose.pdf/document/savexml)(string) | Dokument in XML speichern. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_2)(DocumentDevice, Stream) | Sendet das gesamte Dokument zur Verarbeitung an das Dokumentgerät. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_3)(DocumentDevice, string) | Sendet das gesamte Dokument zur Verarbeitung an das Dokumentgerät. |
| [SendTo](../../aspose.pdf/document/sendto#sendto)(DocumentDevice, int, int, Stream) | Sendet bestimmte Seiten des Dokuments zur Verarbeitung an das Dokumentgerät. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_1)(DocumentDevice, int, int, string) | Sendet das gesamte Dokument zur Verarbeitung an das Dokumentgerät. |
| [SetTitle](../../aspose.pdf/document/settitle)(string) | Titel für PDF-Dokument festlegen |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata)(Stream) | XMP-Metadaten des Dokuments festlegen. |
| [Validate](../../aspose.pdf/document/validate#validate)(PdfFormatConversionOptions) | Validieren Sie das Dokument in der angegebenen Datei. |
| [Validate](../../aspose.pdf/document/validate#validate_1)(Stream, PdfFormat) | Validieren Sie das Dokument in der angegebenen Datei. |
| [Validate](../../aspose.pdf/document/validate#validate_2)(string, PdfFormat) | Validieren Sie das Dokument in der angegebenen Datei. |
| static [Convert](../../aspose.pdf/document/convert#convert)(Stream, LoadOptions, Stream, SaveOptions) | Konvertiert Stream im Quellformat in Stream im Zielformat. |
| static [Convert](../../aspose.pdf/document/convert#convert_1)(Stream, LoadOptions, string, SaveOptions) | Konvertiert Stream im Quellformat in Zieldatei im Zielformat. |
| static [Convert](../../aspose.pdf/document/convert#convert_2)(string, LoadOptions, Stream, SaveOptions) | Konvertiert Quelldatei im Quellformat in Stream im Zielformat. |
| static [Convert](../../aspose.pdf/document/convert#convert_3)(string, LoadOptions, string, SaveOptions) | Konvertiert Quelldatei im Quellformat in Zieldatei im Zielformat. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| delegate [CallBackGetHocr](document.callbackgethocr) | Die Rückrufprozedur für Hocr-Erkennung. |
| delegate [FontSubstitutionHandler](document.fontsubstitutionhandler) | Stellt die Methode dar, die das FontSubstitution-Ereignis behandelt. |
| interface [IDocumentFontUtilities](document.idocumentfontutilities) | Enthält die Funktionalität zum Optimieren von Schriftarten |

### Siehe auch

* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
