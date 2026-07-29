---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Das com.aspose.pdf.facades‑Paket stellt Klassen bereit, die ursprünglich aus Aspose.Pdf.Kit stammen."
type: docs
weight: 180
url: /de/java/com.aspose.pdf.facades/
---
Das com.aspose.pdf.facades‑Paket stellt Klassen bereit, die ursprünglich aus Aspose.Pdf.Kit stammen.

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IFacade](./ifacade/) | Allgemeine Fassaden-Schnittstelle, die gemeinsame Fassadenmethoden definiert. |
| [IForm](./iform/) | Klasse, die ein Acro-Formularobjekt darstellt. |
| [IFormEditor](./iformeditor/) | Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.) |
| [IPdfFileEditor](./ipdffileeditor/) | Implementiert Operationen mit PDF-Dateien: Zusammenführen, Aufteilen, Extrahieren von Seiten, Erstellen eines Booklets usw. |
| [IPdfFileStamp](./ipdffilestamp/) | Schnittstelle zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF-Dateien. |
| [ISaveableFacade](./isaveablefacade/) | Fassaden-Schnittstelle, die Methoden definiert, die für alle speicherbaren Fassaden gemeinsam sind. |
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AlignmentType](./alignmenttype/) | Klasse enthält mögliche Ausrichtungstypen. Verwenden Sie stattdessen HorizontalAlignment. |
| [AutoRotateMode](./autorotatemode/) | Richtung der Drehung, wenn das Dokument gedruckt wird. |
| [BDCProperties](./bdcproperties/) | BDC-Operator-Eigenschaften. |
| [Bookmark](./bookmark/) | Stellt ein Lesezeichen dar. |
| [Bookmarks](./bookmarks/) | Stellt eine Sammlung von {@code Bookmark}-Objekten dar. |
| [CgmPdfProducer](./cgmpdfproducer/) | Stellt eine Klasse zur Erzeugung von PDF aus dem Computer Graphics Metafile (CGM)-Format dar. |
| [DataType](./datatype/) | Enumeriert Feldtypdefinitionen. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Aufzählung der Standard‑XMP‑Eigenschaften. |
| [DocumentPrivilege](./documentprivilege/) | Stellt die Berechtigungen für den Zugriff auf eine PDF-Datei dar. Siehe {@code PdfFileSecurity}. Es gibt 4 Möglichkeiten, diese Klasse zu verwenden: 1. Eine vordefinierte Berechtigung direkt verwenden. 2. Auf einer vordefinierten Berechtigung basieren und einige spezifische Berechtigungen ändern. 3. Auf einer vordefinierten Berechtigung basieren und eine spezifische Kombination von Adobe‑Professional‑Berechtigungen ändern. 4. Die Wege 2 und 3 kombinieren. //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | Enumeriert die beim Text verwendeten Kodierungstypen. |
| [Facade](./facade/) | Basisklassen-Fassade. |
| [FontColor](./fontcolor/) | Klasse, die die Farbe des Textes darstellt. |
| [Form](./form/) | Klasse, die ein Acro-Formularobjekt darstellt. |
| [Form.ImportStatus](./form.importstatus/) | Status des importierten Feldes |
| [FormattedText](./formattedtext/) | Klasse, die formatierte Texte darstellt. Enthält Informationen über Text sowie dessen Farbe, Größe und Stil. |
| [FormEditor](./formeditor/) | Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.) |
| [FormEditorWeb](./formeditorweb/) | Klasse zum Bearbeiten von Formularen (Hinzufügen/Löschen von Feldern usw.) |
| [FormFieldFacade](./formfieldfacade/) | Klasse zur Darstellung von Feldeigenschaften. |
| [FormWeb](./formweb/) | Darstellung der Acro form Interface. |
| [InternalHelper](./internalhelper/) | Hilfeklasse |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | Klasse zum Festlegen von Seiten­größen‑Anpassungsparametern. Ermöglicht das Setzen der folgenden Parameter: Größe der Ergebnisseite (Breite, Höhe) in Standard‑Raumeinheiten oder in Prozent der ursprünglichen Seitengröße; linke, obere, untere und rechte Ränder in Standard‑Raumeinheiten oder in Prozent der ursprünglichen Seitengröße; Einige Werte können für die automatische Berechnung auf null belassen werden. Diese Werte werden aus dem verbleibenden Seiteninhalt berechnet, nachdem explizit angegebene Werte berücksichtigt wurden. Beispiel: Wenn die Seitenbreite = 100 und die neue Seitenbreite auf 60 Einheiten festgelegt ist, werden die linken und rechten Ränder automatisch berechnet: (100 - 60) / 2 = 15. Diese Klasse wird in der Methode ResizeContents verwendet. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | Wert des Randes oder der Inhaltsgröße, angegeben in Prozent der Standard‑Raumeinheiten. Diese Klasse wird in ContentsResizeParameters verwendet. |
| [LineInfo](./lineinfo/) | Stellt die Informationen einer Zeile dar. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Stellt eine Klasse zur Arbeit mit PDF‑Dokumentannotationen (Kommentare) dar. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Stellt eine Klasse zur Arbeit mit Lesezeichen von PDF‑Dateien bereit, einschließlich Erstellen, Ändern, Exportieren, Importieren und Löschen. |
| [PdfContentEditor](./pdfcontenteditor/) | Stellt eine Klasse zum Bearbeiten des Inhalts von PDF‑Dateien dar. |
| [PdfConverter](./pdfconverter/) | Stellt eine Klasse zum Konvertieren jeder Seite einer PDF‑Datei in Bilder dar, unterstützt derzeit BMP, JPEG, PNG und TIFF. Unterstützte Inhalte in PDFs: Bilder, Formulare, Kommentare. |
| [PdfExtractor](./pdfextractor/) | Klasse zum Extrahieren von Bildern und Text aus PDF‑Dokumenten. |
| [PdfFileEditor](./pdffileeditor/) | Implementiert Operationen mit PDF-Dateien: Zusammenführen, Aufteilen, Extrahieren von Seiten, Erstellen eines Booklets usw. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Aktion, die ausgeführt wird, wenn im Zusammenführungsprozess eine beschädigte Datei gefunden wird. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | Stellt eine Klasse mit einer abstrakten Methode dar, die normalerweise von der aufrufenden Seite bereitgestellt wird und Fortschrittsereignisse aus der Zusammenführung verarbeitet. Ein solcher vom Kunden bereitgestellter Handler kann verwendet werden, um den gesamten Zusammenführungsfortschritt in der Konsole oder in einer Fortschrittsleiste anzuzeigen. Stellt Informationen über das aufgetretene Fortschrittsereignis dar. |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Klasse, die Informationen über beschädigte Dateien während der Zusammenführung bereitstellt. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Daten zur Position des Seitenumbruchs. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | Diese Klasse stellt Informationen über den Zusammenführungsfortschritt dar, die in einer externen Anwendung verwendet werden können. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | Dieses Enum beschreibt mögliche Typen von Fortschrittsereignissen, die während der Zusammenführung auftreten können. |
| [PdfFileEditorWeb](./pdffileeditorweb/) | Stellt die Klasse PdfFileEditorWeb dar, die Operationen mit PDF‑Dateien implementiert: Zusammenführen, Aufteilen, Seiten extrahieren, Heft erstellen usw. |
| [PdfFileInfo](./pdffileinfo/) | Stellt eine Klasse zum Zugriff auf Metainformationen eines PDF‑Dokuments dar. |
| [PdfFileMend](./pdffilemend/) | Stellt eine Klasse zum Hinzufügen von Texten und Bildern auf den Seiten eines bestehenden PDF‑Dokuments dar. |
| [PdfFileSanitization](./pdffilesanitization/) | Stellt eine API für Bereinigung und Wiederherstellung dar. Verwenden Sie sie, wenn Sie Dokumente nicht auf andere Weise erstellen/öffnen können. |
| [PdfFileSecurity](./pdffilesecurity/) | Stellt das Verschlüsseln oder Entschlüsseln einer PDF‑Datei mit Besitzer‑ oder Benutzerpasswort sowie das Ändern der Sicherheitseinstellungen und des Passworts dar. |
| [PdfFileSignature](./pdffilesignature/) | Stellt eine Klasse zum Signieren einer PDF‑Datei mit einem Zertifikat dar. |
| [PdfFileStamp](./pdffilestamp/) | Klasse zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF‑Dateien. |
| [PdfFileStampWeb](./pdffilestampweb/) | Klasse zum Hinzufügen von Stempeln (Wasserzeichen oder Hintergrund) zu PDF‑Dateien. Ermöglicht die Arbeit mit HttpServletResponse. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Klasse zum Entfernen sämtlichen Java‑Script‑Codes. |
| [PdfPageEditor](./pdfpageeditor/) | Stellt eine Klasse dar, um die Seite der PDF-Datei zu bearbeiten, einschließlich Drehen der Seite, Zoomen der Seite, Verschieben der Position und Ändern der Seitengröße. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Stellt ein Objekt dar, das aktuelle Druckseiteninformationen enthält. |
| [PdfProducer](./pdfproducer/) | <p> Stellt eine Klasse dar, um PDF aus anderen Formaten zu erzeugen. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Stellt die Methode dar, die das QueryPageSettings-Ereignis eines PrintDocument verarbeitet. |
| [PdfViewer](./pdfviewer/) | Stellt eine Klasse dar, um ein PDF anzuzeigen oder zu drucken. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Klasse zur Manipulation von XMP-Metadaten. |
| [PositioningMode](./positioningmode/) | Definiert den Positionierungsmodus. Mögliche Werte sind Legacy (Rückwärtskompatibilität) und Current (aktualisierte Berechnung der Textposition). |
| [PropertyFlag](./propertyflag/) | Aufzählung möglicher Feld-Flags. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Diese Klasse enthält Parameter, die das Verhalten von PdfContentEditor beim Ausführen einer ReplaceText-Operation definieren. |
| [SaveableFacade](./saveablefacade/) | <p> Basisklasse für alle speicherbaren Fassaden. |
| [SignatureName](./signaturename/) | Stellt eine Klasse für einen Signaturnamen dar. Stellt einen präziseren Signaturnamen dar. Wird anstelle von Zeichenkettennamen verwendet. Ermöglicht es, Signaturen mit denselben Zeichenkettennamen darzustellen. |
| [Stamp](./stamp/) | Klasse, die einen Stempel darstellt. |
| [StampInfo](./stampinfo/) | Klasse, die Stempelinformationen darstellt. |
| [TextProperties](./textproperties/) | Stellt Texteigenschaften wie: Textgröße, Farbe, Stil usw. dar. |
| [VerticalAlignmentType](./verticalalignmenttype/) | Klasse, die mögliche vertikale Ausrichtungswerte darstellt. Verwenden Sie stattdessen VerticalAlignment. |
| [ViewerPreference](./viewerpreference/) | Beschreibt die Viewer-Einstellungen (Seitenmodus, Nicht‑Vollbild‑Seitenmodus, Seitenlayout). |
| [WordWrapMode](./wordwrapmode/) | Definiert Strategien für den Wortumbruch |
## Enums

| Enum | Beschreibung |
| --- | --- |
| [Algorithm](./algorithm/) | Stellt Algorithmen dar, die zum Verschlüsseln von PDF-Dokumenten verwendet werden können. |
| [BlendingColorSpace](./blendingcolorspace/) | Klasse, die den Blending-Farbraum darstellt. |
| [FieldType](./fieldtype/) | Aufzählung möglicher Feldtypen. |
| [FontStyle](./fontstyle/) | Enumeriert 14 Schriftartenarten. |
| [ImageMergeMode](./imagemergemode/) | Stellt Modi zum Zusammenführen von Bildern dar. |
| [KeySize](./keysize/) | Definiert verschiedene Schlüssellängen, die zum Verschlüsseln von PDF-Dokumenten verwendet werden können. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Aktion, die ausgeführt wird, wenn die Schriftart das erforderliche Zeichen nicht enthält |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Geltungsbereich, in dem die Ersetzen‑Text‑Operation angewendet wird, standardmäßig REPLACE_FIRST. |
| [StampType](./stamptype/) | Beschreibt Stempeltypen. |
| [SubmitFormFlag](./submitformflag/) | Aufzählung möglicher Submit-Formular-Flags. |
