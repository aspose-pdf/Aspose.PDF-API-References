---
title: "Dokument"
linktitle: "Dokument"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein PDF-Dokument darstellt."
type: docs
weight: 1060
url: /de/java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Document

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class Document extends Object implements IDocument
```

Klasse, die ein PDF-Dokument darstellt.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Dies tritt auf, wenn eine Schriftart eine andere Schriftart im Dokument ersetzt. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Document](#Document--) | Initialisiert ein leeres Dokument. |
| [Document](#Document-byte:A-) | Initialisiert eine neue Document-Instanz aus dem {@code input}-Byte‑Array. |
| [Document](#Document-java.io.InputStream-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.io.InputStream-boolean-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.io.InputStream-java.lang.String-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-com.aspose.pdf.PdfVersion-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.lang.String-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.lang.String-boolean-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.lang.String-java.lang.String-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialisiert ein leeres Dokument. |
| [Document](#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initialisiert ein leeres Dokument. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [afterImport](#afterImport--) | Alle registrierten Anmerkungen enumerieren und AfterImport für jede von ihnen aufrufen. |
| [bindXml](#bindXml-java.io.InputStream-) | XML an Dokument binden |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | XML/XSL an Dokument binden |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | XML/XSL an Dokument binden |
| [bindXml](#bindXml-java.lang.String-) | XML an Dokument binden |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | XML/XSL an Dokument binden |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Ändert die Dokument-Passwörter. Diese Aktion kann nur mit dem Besitzer‑Passwort durchgeführt werden. |
| [check](#check-boolean-) | Validiert Dokument. |
| [close](#close--) | Schließt alle von diesem Dokument verwendeten Ressourcen. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Erkennen Sie Bilder im Dokument und fügen Sie hocr‑Zeichenketten darüber ein. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Konvertieren Sie das Dokument, indem Sie das Fixup anwenden. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Konvertieren Sie das Dokument, indem Sie das Fixup anwenden. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Konvertieren Sie das Dokument, indem Sie das Fixup anwenden. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Konvertieren Sie das Dokument, indem Sie das Fixup anwenden. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Konvertiert einen Stream im Quellformat in einen Stream im Zielformat. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Konvertiert einen Stream im Quellformat in eine Zieldatei im Zielformat. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konvertieren Sie das Dokument und speichern Sie Fehler in den angegebenen Stream. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Konvertiert Dokument mit angegebenen Konvertierungsoptionen |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Konvertiert die Quelldatei im Quellformat in einen Stream im Zielformat. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Konvertiert die Quelldatei im Quellformat in eine Zieldatei im Zielformat. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konvertieren Sie das Dokument und speichern Sie Fehler in den angegebenen Stream. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Konvertiert die Seite zu PNG für DSR-, OMR‑ und OCR‑Bildstreams. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können. |
| [decrypt](#decrypt--) | Entschlüsselt das Dokument. Rufen Sie anschließend Save auf, um die entschlüsselte Version des Dokuments zu erhalten. |
| [dispose](#dispose--) | Schließt alle von diesem Dokument verwendeten Ressourcen. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Verschlüsselt das Dokument. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Verschlüsselt das Dokument. Rufen Sie anschließend Save auf, um die verschlüsselte Version des Dokuments zu erhalten. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Verschlüsselt das Dokument. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Verschlüsselt das Dokument. Rufen Sie anschließend Save auf, um die verschlüsselte Version des Dokuments zu erhalten. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Verschlüsselt das Dokument. Rufen Sie anschließend Save auf, um die verschlüsselte Version des Dokuments zu erhalten. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Verschlüsselt das Dokument. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exportiert alle Dokumentannotationen in einen Stream. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exportiert alle Dokument-Anmerkungen in eine XFDF-Datei |
| [flatten](#flatten--) | Entfernt alle Felder (und Anmerkungen) aus dem Dokument und legt stattdessen deren Werte ab. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Entfernt alle Felder (und Anmerkungen) aus dem Dokument und legt stattdessen deren Werte ab. |
| [flattenTransparency](#flattenTransparency--) | Ersetzt transparenten Inhalt durch nichttransparentes Raster- und Vektorgrafiken. |
| [freeMemory](#freeMemory--) | Löscht Speicher |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Benachrichtigung über fehlende Schriften beim Verarbeiten von Dokumenten. |
| [getActions](#getActions--) | <p> Ruft Dokumentaktionen ab. Diese Eigenschaft ist eine Instanz der Klasse DocumentActions, die das Abrufen/Setzen von BeforClosing-, BeforSaving‑ usw. Aktionen ermöglicht. </p> |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Ermöglicht das Zusammenführen von Seiteninhalten, um die Dokumentgröße zu optimieren. |
| [getBackground](#getBackground--) | Liefert die Hintergrundfarbe des Dokuments. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Gibt den Elementwert aus dem Katalogwörterbuch zurück. |
| [getCollection](#getCollection--) | Ermittelt die Sammlung des Dokuments. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Liefert Sicherheitseinstellungen, wenn das Dokument verschlüsselt ist. Ist das Dokument nicht verschlüsselt, wird in .net 1.1 die entsprechende Ausnahme ausgelöst oder CryptoAlgorithm ist in anderen .net‑Versionen null. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Ermittelt einen benutzerdefinierten Sicherheits-Handler. |
| [getDefaultCopier](#getDefaultCopier--) | Gibt den Kopierer zurück, der zum Kopieren von Seiten in dieses Dokument verwendet wird. |
| [getDestinations](#getDestinations--) | Ermittelt die Sammlung der Ziele. |
| [getDirection](#getDirection--) | Ermittelt die Lesereihenfolge des Textes: L2R (von links nach rechts) oder R2L (von rechts nach links). |
| [getDuplex](#getDuplex--) | Ermittelt oder legt die Option zur Handhabung des Duplexdruckmodus fest, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Ermittelt die Sammlung von in das Dokument eingebetteten Dateien. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Ermittelt oder legt das Flag zur Verwaltung der Bereinigung von Signaturfeldern fest. |
| [getEngineDoc](#getEngineDoc--) | Instanz von IPdfDocument, die zum Zugriff auf die interne Dokumentstruktur verwendet wird. Nur intern. |
| [getFileName](#getFileName--) | Name der PDF‑Datei, die dieses Dokument verursacht hat |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Liest und setzt das Dateigrößenlimit für das Laden einer gesamten Datei in den Speicher. |
| [getFontUtilities](#getFontUtilities--) | Instanz von IDocumentFontUtilities |
| [getForm](#getForm--) | Ermittelt das Acro‑Formular des Dokuments. |
| [getId](#getId--) | Ermittelt die ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Liest oder setzt das Flag zum Ignorieren von Fehlern in Quelldateien. Wenn Seiten aus dem Quelldokument in das Zieldokument kopiert werden, wird der Kopiervorgang bei beschädigten Objekten in den Quelldateien mit einer Ausnahme abgebrochen, wenn dieses Flag false ist. Beispiel: dest.Pages.Add(src.Pages); Ist das Flag auf true gesetzt, werden beschädigte Objekte durch leere Werte ersetzt. Standardwert: true. |
| [getInfo](#getInfo--) | Ermittelt die Dokumentinformationen. |
| [getJavaScript](#getJavaScript--) | Sammlung von JavaScript auf Dokumentebene. |
| [getLogicalStructure](#getLogicalStructure--) | Ermittelt die logische Struktur des Dokuments. |
| [getMetadata](#getMetadata--) | Dokument-Metadaten. (Ein PDF-Dokument kann allgemeine Informationen enthalten, wie den Titel des Dokuments, den Autor sowie Erstellungs- und Änderungsdaten. Solche globalen Informationen über das Dokument (im Gegensatz zu dessen Inhalt oder Struktur) werden Metadaten genannt und sollen bei der Katalogisierung und Suche nach Dokumenten in externen Datenbanken unterstützen.) |
| [getMetadataStream](#getMetadataStream--) | Gibt den rohen Metadaten‑Stream zurück |
| [getNamedDestinations](#getNamedDestinations--) | Sammlung benannter Ziele im Dokument. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Ermittelt den Seitenmodus, der festlegt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
| [getObjectById](#getObjectById-java.lang.String-) | Ermittelt ein Objekt mit der angegebenen ID im Dokument. |
| [getOpenAction](#getOpenAction--) | <p> Ruft die beim Öffnen des Dokuments ausgeführte Aktion ab. </p> <hr> <pre> Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction(); </pre> |
| [getOptimizeSize](#getOptimizeSize--) | Liest das Optimierungs-Flag. Wenn Seiten zum Dokument hinzugefügt werden, werden gleiche Ressourcen‑Streams in der resultierenden Datei zu einem PDF‑Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der Dateigröße, kann jedoch zu langsameren Ausführungen und höherem Speicherbedarf führen. Standardwert: false. |
| [getOutlines](#getOutlines--) | Liefert Dokumentgliederungen. |
| [getOutputIntents](#getOutputIntents--) | Liest die Sammlung der Output‑Intents im Dokument. |
| [getPageInfo](#getPageInfo--) | Liefert die Seiteninformationen. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt) |
| [getPageLabels](#getPageLabels--) | Liefert Seitenbeschriftungen im Dokument. |
| [getPageLayout](#getPageLayout--) | Liefert das Seitenlayout, das beim Öffnen des Dokuments verwendet werden soll. |
| [getPageMode](#getPageMode--) | Liefert den Seitenmodus, der angibt, wie das Dokument beim Öffnen angezeigt werden soll. |
| [getPages](#getPages--) | <p> Gibt die Sammlung von Dokumentseiten zurück. Beachten Sie, dass die Seiten in der Sammlung ab 1 nummeriert sind. </p> |
| [getPdfFormat](#getPdfFormat--) | Ermittelt das PDF/A-Format |
| [getPermissions](#getPermissions--) | Liefert die Berechtigungen des Dokuments. |
| [getPrintScaling](#getPrintScaling--) | Liefert die Option zur Handhabung der Druckskalierung, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [getTaggedContent](#getTaggedContent--) | Ruft den Zugriff auf TaggedPdf-Inhalt ab. Das Beispiel zeigt, wie man getaggten Inhalt verwendet, um ein neues Dokument mit Kopfzeile, Absätzen und Bildern zu erstellen. // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage(\"en-US\"); // Set title for PDF document taggedContent.setTitle(\"Example document\"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText(\"The Header\"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag(\"Paragraph\"); p.setText(\"The text of paragraph.\"); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText(\"Figure 1\"); figure1.setTitle(\"Image 1\"); figure1.setTag(\"Fig\"); figure1.setImage(\"path/of/image.jpg\"); // Save document document.save(\"example.pdf\"); |
| [getVersion](#getVersion--) | Liefert eine Version von PDF aus dem PDF-Dateikopf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Liefert XMP-Metadaten aus dem Dokument. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Überprüft, ob das aktuelle PDF-Dokument mit inkrementellen Updates gespeichert wurde. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Importiert Anmerkungen aus einem Stream in das Dokument. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importiert Anmerkungen aus einer XFDF-Datei in das Dokument. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Flag, das über den Ersatz einer fehlenden Schriftart informiert. |
| [isCenterWindow](#isCenterWindow--) | <p> Gibt das Flag zurück, das angibt, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird. </p> |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | <p> Gibt das Flag zurück, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. </p> |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Liest oder setzt einen Wert, der angibt, ob das Protokollieren von Benachrichtigungen aktiviert werden soll. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Liest oder setzt ein Flag, das das teilweise Entladen des Dokuments aus dem Speicher ermöglicht. |
| [isEncrypted](#isEncrypted--) | Gibt den Verschlüsselungsstatus des Dokuments zurück. Wahr, wenn das Dokument verschlüsselt ist. |
| [isFitWindow](#isFitWindow--) | <p> Gibt das Flag zurück, das angibt, ob das Dokumentfenster auf die erste angezeigte Seite angepasst werden muss. </p> |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Wirft eine Ausnahme, wenn das Dokument mit Änderungen gespeichert wird und eine Signatur enthält |
| [isHideMenubar](#isHideMenubar--) | <p> Gibt das Flag zurück, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. </p> |
| [isHideToolBar](#isHideToolBar--) | <p> Gibt das Flag zurück, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. </p> |
| [isHideWindowUI](#isHideWindowUI--) | <p> Gibt das Flag zurück, das angibt, ob Benutzeroberflächenelemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. </p> |
| [isLicensed](#isLicensed--) | Gibt den lizenzierten Zustand des Systems zurück. |
| [isLinearized](#isLinearized--) | Liest einen Wert, der angibt, ob das Dokument linearisiert ist. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. Wir können einige Vorgänge ausführen und nach dem Aufruf von save weiter mit dem Dokument arbeiten, wenn dieser ManualDispose-Parameter aktiviert ist. |
| [isPdfaCompliant](#isPdfaCompliant--) | Gibt zurück, ob das Dokument PDF/A-konform ist. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Liefert, ob das Dokument PDF/UA-konform ist. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Ruft ein Flag ab, das angibt, ob die PDF‑Seitengröße zur Auswahl des Eingabepapierschachs verwendet werden soll. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | Überprüft, ob das Dokument einen Aufruf der Repair-Methode erfordert. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | Standardmäßig ist ein PDF/A-Validierungsprozess erforderlich, um PDF/A-konforme Daten zu aktualisieren oder zu entfernen, wenn einige Regeln verletzt wurden. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Liest oder setzt, ob das Dokument PDF/A‑konform ist. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | Lädt eine Datei und konvertiert sie zu PDF. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Führt Dokumente zusammen. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Führt Dokumente zusammen. |
| [merge](#merge-com.aspose.pdf.Document...-) | Führt Dokumente zusammen. |
| [merge](#merge-java.lang.String...-) | Führt PDF-Dateien zusammen. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Führt Dokumente zusammen. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Führt Dokumente zusammen. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | Führt Dokumente zusammen. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | Führt PDF-Dateien zusammen. |
| [optimize](#optimize--) | Linearisiere das Dokument, um - die erste Seite so schnell wie möglich zu öffnen; - die nächste Seite anzuzeigen oder dem Link zur nächsten Seite so schnell wie möglich zu folgen; - die Seite schrittweise anzuzeigen, sobald sie eintrifft, wenn Daten für eine Seite über einen langsamen Kanal übertragen werden (die nützlichsten Daten zuerst anzeigen); - Benutzerinteraktionen, wie das Folgen eines Links, zu ermöglichen, noch bevor die gesamte Seite empfangen und angezeigt wurde. Der Aufruf dieser Methode speichert das Dokument nicht wirklich. Im Gegenteil, das Dokument wird nur für eine optimierte Struktur vorbereitet; rufen Sie dann Save auf, um das optimierte Dokument zu erhalten. |
| [optimizeResources](#optimizeResources--) | Optimieren Sie Ressourcen im Dokument: 1. Ressourcen, die auf den Dokumentseiten nicht verwendet werden, werden entfernt; 2. Gleiche Ressourcen werden zu einem Objekt zusammengeführt; 3. Unbenutzte Objekte werden gelöscht. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimieren Sie Ressourcen im Dokument: 1. Ressourcen, die auf den Dokumentseiten nicht verwendet werden, werden entfernt; 2. Gleiche Ressourcen werden zu einem Objekt zusammengeführt; 3. Unbenutzte Objekte werden gelöscht. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organisiert die Seitenbaumknoten in einem Dokument zu einem balancierten Baum. Nur wenn das Dokument mehr als nodesNumInSubtrees Seitenobjekte hat, wird etwas getan; andernfalls passiert nichts. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organisiert die Seitenbaumknoten in einem Dokument zu einem balancierten Baum. Nur wenn das Dokument mehr als nodesNumInSubtrees Seitenobjekte hat, wird etwas getan; andernfalls passiert nichts. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Interne Methode |
| [processParagraphs](#processParagraphs--) | Speichert das Dokument in einen Stream. |
| [removeMetadata](#removeMetadata--) | Entfernt Metadaten aus dem Dokument. |
| [removePdfaCompliance](#removePdfaCompliance--) | Entfernt PDF/A‑Konformität aus dem Dokument |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Entfernt PDF/UA‑Konformität aus dem Dokument |
| [repair](#repair--) | Repariert ein beschädigtes Dokument. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Repariert ein beschädigtes Dokument. |
| [resumeUpdate](#resumeUpdate--) | setzt die Dokumentaktualisierung fort |
| [save](#save--) | <p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden. |
| [save](#save-java.io.OutputStream-) | <p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | <p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | <p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden. |
| [save](#save-com.aspose.pdf.SaveOptions-) | <p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | <p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden. |
| [save](#save-java.lang.String-) | <p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | <p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | <p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Speichert das PDF‑Dokument inkrementell in den angegebenen Stream. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Speichert das PDF‑Dokument inkrementell in den angegebenen Stream. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Speichert das PDF‑Dokument inkrementell in den angegebenen Stream. |
| [saveXml](#saveXml-java.lang.String-) | Dokument als XML speichern. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sendet bestimmte Seiten des Dokuments an das Dokumentgerät zur Verarbeitung. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Benachrichtigung über fehlende Schriften beim Verarbeiten von Dokumenten. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Festlegen des Flags für das vom Programm bestimmte Schriftbild im Falle einer fehlenden Schriftart. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Ermöglicht das Zusammenführen von Seiteninhalten, um die Dokumentgröße zu optimieren. |
| [setBackground](#setBackground-java.awt.Color-) | Setzt die Hintergrundfarbe des Dokuments. |
| [setCenterWindow](#setCenterWindow-boolean-) | Setzt das Flag, das angibt, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Setzt die Sammlung des Dokuments. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Liest den Konvertierungsparameter für den PDF/UA‑Konverter (nur Metadaten und Dokumentkatalog konvertieren, wenn auf true gesetzt). |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | Setzt das Dateigrößenlimit für das Laden einer gesamten Datei in den Speicher auf den Standardwert von 210 Mb. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Legt die Lesereihenfolge des Textes fest: L2R (von links nach rechts) oder R2L (von rechts nach links). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Legt das Flag fest, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. |
| [setDuplex](#setDuplex-int-) | Ermittelt oder legt die Option zur Handhabung des Duplexdruckmodus fest, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Protokollieren von Benachrichtigungen aktiviert werden soll. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | Liest oder setzt ein Flag, das das teilweise Entladen des Dokuments aus dem Speicher ermöglicht. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Ermittelt oder legt das Flag zur Verwaltung der Bereinigung von Signaturfeldern fest. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | Liest und setzt das Dateigrößenlimit für das Laden einer gesamten Datei in den Speicher. |
| [setFitWindow](#setFitWindow-boolean-) | Legt das Flag fest, das angibt, ob das Dokumentfenster an die erste angezeigte Seite angepasst werden muss. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | Wirft eine Ausnahme, wenn das Dokument mit Änderungen gespeichert wird und eine Signatur enthält |
| [setHideMenubar](#setHideMenubar-boolean-) | Legt das Flag fest, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [setHideToolBar](#setHideToolBar-boolean-) | Legt das Flag fest, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Legt das Flag fest, das angibt, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Liest oder setzt das Flag zum Ignorieren von Fehlern in Quelldateien. Wenn Seiten aus dem Quelldokument in das Zieldokument kopiert werden, wird der Kopiervorgang bei beschädigten Objekten in den Quelldateien mit einer Ausnahme abgebrochen, wenn dieses Flag false ist. Beispiel: dest.Pages.Add(src.Pages); Ist das Flag auf true gesetzt, werden beschädigte Objekte durch leere Werte ersetzt. Standardwert: true. |
| [setLinearized](#setLinearized-boolean-) | Legt einen Wert fest, der angibt, ob das Dokument linearisiert ist. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. Wir können einige Vorgänge ausführen und mit dem Dokument weiterarbeiten, nachdem die Methode save aufgerufen wurde, wenn dieser ManualDispose‑Parameter aktiviert ist. Es wird jedoch dringend empfohlen, die dispose‑Methode aufzurufen, wenn die Document‑Instanz nicht mehr benötigt wird. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Legt den Seitenmodus fest, der angibt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | <p> Legt die beim Öffnen des Dokuments auszuführende Aktion fest. <p> |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Setzt das Optimierungs‑Flag. Wenn Seiten zum Dokument hinzugefügt werden, werden gleiche Ressourcen‑Streams in der resultierenden Datei zu einem PDF‑Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der resultierenden Dateigröße, kann jedoch zu einer langsameren Ausführung und höheren Speicheranforderungen führen. Standardwert: false. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Legt die Seiteninformationen fest (nur für den Generator, beim Lesen des Dokuments nicht ausgefüllt). |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Legt das Seitenlayout fest, das beim Öffnen des Dokuments verwendet werden soll. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Legt den Seitenmodus fest, der angibt, wie das Dokument beim Öffnen angezeigt werden soll. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Legt ein Flag fest, das angibt, ob die PDF‑Seitengröße zur Auswahl des Eingabepapierfachs verwendet werden soll. |
| [setPrintScaling](#setPrintScaling-int-) | Legt die Option zur Handhabung der Druckskalierung fest, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | Standardmäßig ist der pdfa‑Validierungsprozess erforderlich, um pdfa zu aktualisieren oder zu entfernen, wenn einige Regeln verletzt wurden. |
| [setTitle](#setTitle-java.lang.String-) | Titel für PDF‑Dokument festlegen |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | XMP-Metadaten des Dokuments festlegen. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Liest oder setzt, ob das Dokument PDF/A‑konform ist. |
| [suppressUpdate](#suppressUpdate--) | Unterdrückt das Aktualisieren von Inhaltsdaten für alle Seiten. Der Inhalt wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird. |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Dokument in die angegebene Datei validieren. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Dokument in die angegebene Datei validieren. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Dokument in die angegebene Datei validieren. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

Dies tritt auf, wenn eine Schriftart eine andere Schriftart im Dokument ersetzt.

### Document {#Document--}
```
public Document()
```

Initialisiert ein leeres Dokument.

### Document {#Document-byte:A-}
```
public Document(byte[] input)
```

Initialisiert eine neue Document-Instanz aus dem {@code input}-Byte‑Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe |  | Byte‑Array mit PDF‑Dokument. |

### Document {#Document-java.io.InputStream-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.io.InputStream-boolean-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.io.InputStream-java.lang.String-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialisiert ein leeres Dokument.

### Document {#Document-com.aspose.pdf.PdfVersion-}
Initialisiert ein leeres Dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-}
Initialisiert ein leeres Dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-}
Initialisiert ein leeres Dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
Initialisiert ein leeres Dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialisiert ein leeres Dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.lang.String-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.lang.String-boolean-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.lang.String-java.lang.String-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.lang.String-java.lang.String-boolean-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialisiert ein leeres Dokument.

### Document {#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initialisiert ein leeres Dokument.

### afterImport {#afterImport--}
```
public void afterImport()
```

Alle registrierten Anmerkungen enumerieren und AfterImport für jede von ihnen aufrufen.

### bindXml {#bindXml-java.io.InputStream-}
XML an Dokument binden

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
XML/XSL an Dokument binden

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
XML/XSL an Dokument binden

### bindXml {#bindXml-java.lang.String-}
XML an Dokument binden

### bindXml {#bindXml-java.lang.String-java.lang.String-}
XML/XSL an Dokument binden

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Ändert die Dokument-Passwörter. Diese Aktion kann nur mit dem Besitzer‑Passwort durchgeführt werden.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
```

Validiert Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| doRepair |  | Wenn true, werden gefundene Probleme repariert. |

**Returns:**
boolescher Wert

### close {#close--}
```
public void close()
```

Schließt alle von diesem Dokument verwendeten Ressourcen.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Erkennen Sie Bilder im Dokument und fügen Sie hocr‑Zeichenketten darüber ein.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Konvertieren Sie das Dokument, indem Sie das Fixup anwenden.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Konvertieren Sie das Dokument, indem Sie das Fixup anwenden.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Konvertieren Sie das Dokument, indem Sie das Fixup anwenden.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Konvertieren Sie das Dokument, indem Sie das Fixup anwenden.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Konvertiert einen Stream im Quellformat in einen Stream im Zielformat.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Konvertiert einen Stream im Quellformat in eine Zieldatei im Zielformat.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konvertieren Sie das Dokument und speichern Sie Fehler in den angegebenen Stream.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Konvertiert Dokument mit angegebenen Konvertierungsoptionen

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Konvertiert die Quelldatei im Quellformat in einen Stream im Zielformat.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Konvertiert die Quelldatei im Quellformat in eine Zieldatei im Zielformat.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konvertieren Sie das Dokument und speichern Sie Fehler in den angegebenen Stream.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Konvertiert die Seite zu PNG für DSR-, OMR‑ und OCR‑Bildstreams.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können.

### decrypt {#decrypt--}
```
public void decrypt()
```

Entschlüsselt das Dokument. Rufen Sie anschließend Save auf, um die entschlüsselte Version des Dokuments zu erhalten.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Schließt alle von diesem Dokument verwendeten Ressourcen. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Verschlüsselt das Dokument.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Verschlüsselt das Dokument. Rufen Sie anschließend Save auf, um die verschlüsselte Version des Dokuments zu erhalten.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Verschlüsselt das Dokument.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Verschlüsselt das Dokument. Rufen Sie anschließend Save auf, um die verschlüsselte Version des Dokuments zu erhalten.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Verschlüsselt das Dokument. Rufen Sie anschließend Save auf, um die verschlüsselte Version des Dokuments zu erhalten.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Verschlüsselt das Dokument.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exportiert alle Dokumentannotationen in einen Stream.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exportiert alle Dokument-Anmerkungen in eine XFDF-Datei

### flatten {#flatten--}
```
public void flatten()
```

Entfernt alle Felder (und Anmerkungen) aus dem Dokument und legt stattdessen deren Werte ab.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Entfernt alle Felder (und Anmerkungen) aus dem Dokument und legt stattdessen deren Werte ab.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

Ersetzt transparenten Inhalt durch nichttransparentes Raster- und Vektorgrafiken.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Löscht Speicher

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

Benachrichtigung über fehlende Schriften beim Verarbeiten von Dokumenten.

**Returns:**
ADocument.AbsentFontHandler‑Instanz

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

<p> Ruft Dokumentaktionen ab. Diese Eigenschaft ist eine Instanz der Klasse DocumentActions, die das Abrufen/Setzen von BeforClosing-, BeforSaving‑ usw. Aktionen ermöglicht. </p>

**Returns:**
DocumentActionCollection object <hr> <pre> Dieses Beispiel zeigt, wie man die nach dem Öffnen auszuführende Aktion des Dokuments erhält: Document document = new Document("PdfWithOpenAction.pdf"); DocumentActionCollection actions = document.getActions(); PdfAction afterSavingAction = actions.getAfterSaving(); </pre>

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Ermöglicht das Zusammenführen von Seiteninhalten, um die Dokumentgröße zu optimieren.

**Returns:**
Wert boolescher Wert

### getBackground {#getBackground--}
```
public Color getBackground()
```

Liefert die Hintergrundfarbe des Dokuments.

**Returns:**
Color-Objekt

### getCatalogValue {#getCatalogValue-java.lang.String-}
Gibt den Elementwert aus dem Katalogwörterbuch zurück.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

Ermittelt die Sammlung des Dokuments.

**Returns:**
Sammlungsobjekt

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

Liefert Sicherheitseinstellungen, wenn das Dokument verschlüsselt ist. Ist das Dokument nicht verschlüsselt, wird in .net 1.1 die entsprechende Ausnahme ausgelöst oder CryptoAlgorithm ist in anderen .net‑Versionen null.

**Returns:**
CryptoAlgorithm Element @see CryptoAlgorithm

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public final com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Ermittelt einen benutzerdefinierten Sicherheits-Handler.

**Returns:**
ICustomSecurityHandler-Instanz

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

Gibt den Kopierer zurück, der zum Kopieren von Seiten in dieses Dokument verwendet wird.

**Returns:**
Copier-Objekt

### getDestinations {#getDestinations--}
```
public DestinationCollection getDestinations()
```

Ermittelt die Sammlung der Ziele.

**Returns:**
DestinationCollection Element

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Ermittelt die Lesereihenfolge des Textes: L2R (von links nach rechts) oder R2L (von rechts nach links).

**Returns:**
Direction Element @see Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Ermittelt oder legt die Option zur Handhabung des Duplexdruckmodus fest, die beim Drucken der Datei über den Druckdialog verwendet wird.

**Returns:**
PrintDuplex-Element

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

Ermittelt die Sammlung von in das Dokument eingebetteten Dateien.

**Returns:**
EmbeddedFileCollection-Objekt

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist.

**Returns:**
boolescher Wert

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

Ermittelt oder legt das Flag zur Verwaltung der Bereinigung von Signaturfeldern fest.

**Returns:**
boolescher Wert

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instanz von IPdfDocument, die zum Zugriff auf die interne Dokumentstruktur verwendet wird. Nur intern.

**Returns:**
IPdfDocument-Objekt

### getFileName {#getFileName--}
```
public String getFileName()
```

Name der PDF‑Datei, die dieses Dokument verursacht hat

**Returns:**
String-Objekt

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Liest und setzt das Dateigrößenlimit für das Laden einer gesamten Datei in den Speicher.

**Returns:**
int-Wert

### getFontUtilities {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```

Instanz von IDocumentFontUtilities

**Returns:**
Instanz von IDocumentFontUtilities

### getForm {#getForm--}
```
public Form getForm()
```

Ermittelt das Acro‑Formular des Dokuments.

**Returns:**
Form-Objekt

### getId {#getId--}
```
public Id getId()
```

Ermittelt die ID.

**Returns:**
Id-Objekt

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Liest oder setzt das Flag zum Ignorieren von Fehlern in Quelldateien. Wenn Seiten aus dem Quelldokument in das Zieldokument kopiert werden, wird der Kopiervorgang bei beschädigten Objekten in den Quelldateien mit einer Ausnahme abgebrochen, wenn dieses Flag false ist. Beispiel: dest.Pages.Add(src.Pages); Ist das Flag auf true gesetzt, werden beschädigte Objekte durch leere Werte ersetzt. Standardwert: true.

**Returns:**
boolescher Wert

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

Ermittelt die Dokumentinformationen.

**Returns:**
DocumentInfo-Objekt

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

Sammlung von JavaScript auf Dokumentebene.

**Returns:**
JavaScriptCollection Objekt

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

Ermittelt die logische Struktur des Dokuments.

**Returns:**
RootElement-Objekt

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

Dokument-Metadaten. (Ein PDF-Dokument kann allgemeine Informationen enthalten, wie den Titel des Dokuments, den Autor sowie Erstellungs- und Änderungsdaten. Solche globalen Informationen über das Dokument (im Gegensatz zu dessen Inhalt oder Struktur) werden Metadaten genannt und sollen bei der Katalogisierung und Suche nach Dokumenten in externen Datenbanken unterstützen.)

**Returns:**
Metadata-Objekt

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Gibt den rohen Metadaten‑Stream zurück

**Returns:**
IPdfStreamAccessor-Objekt

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

Sammlung benannter Ziele im Dokument.

**Returns:**
NamedDestinationCollection-Instanz

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

Ermittelt den Seitenmodus, der festlegt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird.

**Returns:**
PageMode Element @see PageMode

### getObjectById {#getObjectById-java.lang.String-}
Ermittelt ein Objekt mit der angegebenen ID im Dokument.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

<p> Ruft die beim Öffnen des Dokuments ausgeführte Aktion ab. </p> <hr> <pre> Example demonstrates how to get CenterWindow flag: Document document = new Document("sample.pdf"); IAppointment value = document.getOpenAction(); </pre>

**Returns:**
IAppointment-Objekt

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Liest das Optimierungs-Flag. Wenn Seiten zum Dokument hinzugefügt werden, werden gleiche Ressourcen‑Streams in der resultierenden Datei zu einem PDF‑Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der Dateigröße, kann jedoch zu langsameren Ausführungen und höherem Speicherbedarf führen. Standardwert: false.

**Returns:**
boolescher Wert

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

Liefert Dokumentgliederungen.

**Returns:**
OutlineCollection-Objekt

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

Liest die Sammlung der Output‑Intents im Dokument.

**Returns:**
OutputIntents Instanz

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Liefert die Seiteninformationen. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt)

**Returns:**
Die Seiteninfo.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

Liefert Seitenbeschriftungen im Dokument.

**Returns:**
PageLabelCollection-Objekt

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

Liefert das Seitenlayout, das beim Öffnen des Dokuments verwendet werden soll.

**Returns:**
PageLayout Element @see PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Liefert den Seitenmodus, der angibt, wie das Dokument beim Öffnen angezeigt werden soll.

**Returns:**
PageMode Element @see PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

<p> Gibt die Sammlung von Dokumentseiten zurück. Beachten Sie, dass die Seiten in der Sammlung ab 1 nummeriert sind. </p>

**Returns:**
PageCollection Objekt <hr> <pre> Das folgende Beispiel demonstriert, wie man mit den Dokumentseiten arbeitet: Wie man die Anzahl der Seiten ermittelt und das Rechteck der Startseite des Dokuments erhält. Document document = new Document("sample.pdf"); PageCollection pages = document.getPages(); System.out.println("Document contains " + pages.size()); Page page = pages.get_Item(1); Rectangle rect = page.getRect(); </pre>

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Ermittelt das PDF/A-Format

**Returns:**
PdfFormat Element @see PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

Liefert die Berechtigungen des Dokuments.

**Returns:**
int-Wert

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

Liefert die Option zur Handhabung der Druckskalierung, die beim Drucken der Datei über den Druckdialog verwendet wird.

**Returns:**
PrintScaling-Element

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```

Ruft den Zugriff auf TaggedPdf-Inhalt ab. Das Beispiel zeigt, wie man getaggten Inhalt verwendet, um ein neues Dokument mit Kopfzeile, Absätzen und Bildern zu erstellen. // Create new document Document document = new Document(); // Get the tagged content ITaggedContent taggedContent = document.getTaggedContent(); // Set language for document taggedContent.setLanguage(\"en-US\"); // Set title for PDF document taggedContent.setTitle(\"Example document\"); // Creating and adding Section SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Create Header HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText(\"The Header\"); sect.appendChild(h1); // Create paragraph ParagraphElement p = taggedContent.createParagraphElement(); p.setTag(\"Paragraph\"); p.setText(\"The text of paragraph.\"); sect.appendChild(p); // Create illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText(\"Figure 1\"); figure1.setTitle(\"Image 1\"); figure1.setTag(\"Fig\"); figure1.setImage(\"path/of/image.jpg\"); // Save document document.save(\"example.pdf\");

**Returns:**
ITaggedContent-Instanz

### getVersion {#getVersion--}
```
public String getVersion()
```

Liefert eine Version von PDF aus dem PDF-Dateikopf.

**Returns:**
String Wert

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Liefert XMP-Metadaten aus dem Dokument.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

Überprüft, ob das aktuelle PDF-Dokument mit inkrementellen Updates gespeichert wurde.

**Returns:**
true, wenn das PDF-Dokument inkrementelle Updates hat; andernfalls false.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
Importiert Anmerkungen aus einem Stream in das Dokument.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importiert Anmerkungen aus einer XFDF-Datei in das Dokument.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

Flag, das über den Ersatz einer fehlenden Schriftart informiert.

**Returns:**
boolescher Wert

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

<p> Gibt das Flag zurück, das angibt, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird. </p>

**Returns:**
boolescher Wert <hr> <pre> Beispiel zeigt, wie man das CenterWindow-Flag erhält: Document document = new Document("sample.pdf"); boolean value = document.isCenterWindow(); </pre>

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind.

**Returns:**
boolescher Wert standardmäßig false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

<p> Gibt das Flag zurück, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. </p>

**Returns:**
boolescher Wert <hr> <pre> Beispiel zeigt, wie man das DisplayDocTitle-Flag erhält: Document document = new Document("sample.pdf"); boolean value = document.isDisplayDocTitle(); </pre>

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

Liest oder setzt einen Wert, der angibt, ob das Protokollieren von Benachrichtigungen aktiviert werden soll.

**Returns:**
boolescher Wert

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

Liest oder setzt ein Flag, das das teilweise Entladen des Dokuments aus dem Speicher ermöglicht.

**Returns:**
boolescher Wert

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Gibt den Verschlüsselungsstatus des Dokuments zurück. Wahr, wenn das Dokument verschlüsselt ist.

**Returns:**
boolescher Wert

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

<p> Gibt das Flag zurück, das angibt, ob das Dokumentfenster auf die erste angezeigte Seite angepasst werden muss. </p>

**Returns:**
boolescher Wert <hr> <pre> Beispiel zeigt, wie man das FitWindow-Flag erhält: Document document = new Document("sample.pdf"); boolean value = document.isFitWindow(); </pre>

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

Wirft eine Ausnahme, wenn das Dokument mit Änderungen gespeichert wird und eine Signatur enthält

**Returns:**
boolescher Wert

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

<p> Gibt das Flag zurück, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. </p>

**Returns:**
boolescher Wert <hr> <pre> Beispiel zeigt, wie man das HideMenubar-Flag erhält: Document document = new Document("sample.pdf"); boolean value = document.isHideMenubar(); </pre>

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

<p> Gibt das Flag zurück, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. </p>

**Returns:**
boolescher Wert <hr> <pre> Beispiel zeigt, wie man das HideToolBar-Flag erhält: Document document = new Document("sample.pdf"); boolean value = document.isHideToolBar(); </pre>

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

<p> Gibt das Flag zurück, das angibt, ob Benutzeroberflächenelemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. </p>

**Returns:**
boolescher Wert <hr> <pre> Beispiel zeigt, wie man das HideWindowUI-Flag erhält: Document document = new Document("sample.pdf"); boolean value = document.isHideWindowUI(); </pre>

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

Gibt den lizenzierten Zustand des Systems zurück.

**Returns:**
boolescher Wert

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

Liest einen Wert, der angibt, ob das Dokument linearisiert ist.

**Returns:**
boolescher Wert

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. Wir können einige Vorgänge ausführen und nach dem Aufruf von save weiter mit dem Dokument arbeiten, wenn dieser ManualDispose-Parameter aktiviert ist.

**Returns:**
boolescher Wert. (Standardwert == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

Gibt zurück, ob das Dokument PDF/A-konform ist.

**Returns:**
boolescher Wert

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

Liefert, ob das Dokument PDF/UA-konform ist.

**Returns:**
boolescher Wert

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

Ruft ein Flag ab, das angibt, ob die PDF‑Seitengröße zur Auswahl des Eingabepapierschachs verwendet werden soll.

**Returns:**
boolescher Wert

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
Überprüft, ob das Dokument einen Aufruf der Repair-Methode erfordert.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

Standardmäßig ist ein PDF/A-Validierungsprozess erforderlich, um PDF/A-konforme Daten zu aktualisieren oder zu entfernen, wenn einige Regeln verletzt wurden.

**Returns:**
boolescher Wert

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

Liest oder setzt, ob das Dokument PDF/A‑konform ist.

**Returns:**
boolescher Wert

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
Lädt eine Datei und konvertiert sie zu PDF.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Führt Dokumente zusammen.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Führt Dokumente zusammen.

### merge {#merge-com.aspose.pdf.Document...-}
Führt Dokumente zusammen.

### merge {#merge-java.lang.String...-}
Führt PDF-Dateien zusammen.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Führt Dokumente zusammen.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Führt Dokumente zusammen.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
Führt Dokumente zusammen.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
Führt PDF-Dateien zusammen.

### optimize {#optimize--}
```
public void optimize()
```

Linearisiere das Dokument, um - die erste Seite so schnell wie möglich zu öffnen; - die nächste Seite anzuzeigen oder dem Link zur nächsten Seite so schnell wie möglich zu folgen; - die Seite schrittweise anzuzeigen, sobald sie eintrifft, wenn Daten für eine Seite über einen langsamen Kanal übertragen werden (die nützlichsten Daten zuerst anzeigen); - Benutzerinteraktionen, wie das Folgen eines Links, zu ermöglichen, noch bevor die gesamte Seite empfangen und angezeigt wurde. Der Aufruf dieser Methode speichert das Dokument nicht wirklich. Im Gegenteil, das Dokument wird nur für eine optimierte Struktur vorbereitet; rufen Sie dann Save auf, um das optimierte Dokument zu erhalten.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Optimieren Sie Ressourcen im Dokument: 1. Ressourcen, die auf den Dokumentseiten nicht verwendet werden, werden entfernt; 2. Gleiche Ressourcen werden zu einem Objekt zusammengeführt; 3. Unbenutzte Objekte werden gelöscht.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimieren Sie Ressourcen im Dokument: 1. Ressourcen, die auf den Dokumentseiten nicht verwendet werden, werden entfernt; 2. Gleiche Ressourcen werden zu einem Objekt zusammengeführt; 3. Unbenutzte Objekte werden gelöscht.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Organisiert die Seitenbaumknoten in einem Dokument zu einem balancierten Baum. Nur wenn das Dokument mehr als nodesNumInSubtrees Seitenobjekte hat, wird etwas getan; andernfalls passiert nichts.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organisiert die Seitenbaumknoten in einem Dokument zu einem balancierten Baum. Nur wenn das Dokument mehr als nodesNumInSubtrees Seitenobjekte hat, wird etwas getan; andernfalls passiert nichts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodesNumInSubtrees |  | Gewünschte Anzahl von Unterknoten. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Interne Methode

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Speichert das Dokument in einen Stream.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

Entfernt Metadaten aus dem Dokument.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

Entfernt PDF/A‑Konformität aus dem Dokument

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

Entfernt PDF/UA‑Konformität aus dem Dokument

### repair {#repair--}
```
public void repair()
```

Repariert ein beschädigtes Dokument.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
Repariert ein beschädigtes Dokument.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

setzt die Dokumentaktualisierung fort

### save {#save--}
```
public void save()
```

<p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden.

### save {#save-java.io.OutputStream-}
<p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
<p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
<p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden.

### save {#save-com.aspose.pdf.SaveOptions-}
<p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden.

### save {#save-com.aspose.ms.System.IO.Stream-}
<p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden.

### save {#save-java.lang.String-}
<p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
<p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
<p> Dokument inkrementell speichern (d. h. mit inkrementeller Aktualisierungstechnik). </p> <hr> <p> Um das Dokument inkrementell zu speichern, sollten wir die Dokumentdatei zum Schreiben öffnen. Daher darf Document nicht mit InputStream, sondern mit dem Pfad zur Datei initialisiert werden, wie im nächsten Code‑Snippet: Document doc = new Document(\"document.pdf\"); // einige Änderungen vornehmen und das Dokument inkrementell speichern doc.save(); </p> Falls das Dokument mit InputStream initialisiert wurde, ist das Schreiben in einen InputStream unmöglich, daher empfehlen wir die separaten Methoden \"save\" zum Speichern des Dokuments oder \"saveIncrementally\" zum inkrementellen Speichern des Dokuments zu verwenden.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
Speichert das PDF‑Dokument inkrementell in den angegebenen Stream.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
Speichert das PDF‑Dokument inkrementell in den angegebenen Stream.

### saveIncrementally {#saveIncrementally-java.lang.String-}
Speichert das PDF‑Dokument inkrementell in den angegebenen Stream.

### saveXml {#saveXml-java.lang.String-}
Dokument als XML speichern.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Sendet bestimmte Seiten des Dokuments an das Dokumentgerät zur Verarbeitung.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung.

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
Benachrichtigung über fehlende Schriften beim Verarbeiten von Dokumenten.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Festlegen des Flags für das vom Programm bestimmte Schriftbild im Falle einer fehlenden Schriftart.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  |  |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Ermöglicht das Zusammenführen von Seiteninhalten, um die Dokumentgröße zu optimieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBackground {#setBackground-java.awt.Color-}
Setzt die Hintergrundfarbe des Dokuments.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

Setzt das Flag, das angibt, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Setzt die Sammlung des Dokuments.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

Liest den Konvertierungsparameter für den PDF/UA‑Konverter (nur Metadaten und Dokumentkatalog konvertieren, wenn auf true gesetzt).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

Setzt das Dateigrößenlimit für das Laden einer gesamten Datei in den Speicher auf den Standardwert von 210 Mb.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Legt die Lesereihenfolge des Textes fest: L2R (von links nach rechts) oder R2L (von rechts nach links).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert standardmäßig false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

Legt das Flag fest, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Ermittelt oder legt die Option zur Handhabung des Duplexdruckmodus fest, die beim Drucken der Datei über den Druckdialog verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | PrintDuplex-Element |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob das Protokollieren von Benachrichtigungen aktiviert werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

Liest oder setzt ein Flag, das das teilweise Entladen des Dokuments aus dem Speicher ermöglicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

Ermittelt oder legt das Flag zur Verwaltung der Bereinigung von Signaturfeldern fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

Liest und setzt das Dateigrößenlimit für das Laden einer gesamten Datei in den Speicher.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

Legt das Flag fest, das angibt, ob das Dokumentfenster an die erste angezeigte Seite angepasst werden muss.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

Wirft eine Ausnahme, wenn das Dokument mit Änderungen gespeichert wird und eine Signatur enthält

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

Legt das Flag fest, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

Legt das Flag fest, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

Legt das Flag fest, das angibt, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Liest oder setzt das Flag zum Ignorieren von Fehlern in Quelldateien. Wenn Seiten aus dem Quelldokument in das Zieldokument kopiert werden, wird der Kopiervorgang bei beschädigten Objekten in den Quelldateien mit einer Ausnahme abgebrochen, wenn dieses Flag false ist. Beispiel: dest.Pages.Add(src.Pages); Ist das Flag auf true gesetzt, werden beschädigte Objekte durch leere Werte ersetzt. Standardwert: true.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

Legt einen Wert fest, der angibt, ob das Dokument linearisiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. Wir können einige Vorgänge ausführen und mit dem Dokument weiterarbeiten, nachdem die Methode save aufgerufen wurde, wenn dieser ManualDispose‑Parameter aktiviert ist. Es wird jedoch dringend empfohlen, die dispose‑Methode aufzurufen, wenn die Document‑Instanz nicht mehr benötigt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| manualDisposeEnabled |  | boolescher Wert. (Standardwert == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Legt den Seitenmodus fest, der angibt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
<p> Legt die beim Öffnen des Dokuments auszuführende Aktion fest. <p>

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Setzt das Optimierungs‑Flag. Wenn Seiten zum Dokument hinzugefügt werden, werden gleiche Ressourcen‑Streams in der resultierenden Datei zu einem PDF‑Objekt zusammengeführt, wenn dieses Flag gesetzt ist. Dies ermöglicht eine Verringerung der resultierenden Dateigröße, kann jedoch zu einer langsameren Ausführung und höheren Speicheranforderungen führen. Standardwert: false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Legt die Seiteninformationen fest (nur für den Generator, beim Lesen des Dokuments nicht ausgefüllt).

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Legt das Seitenlayout fest, das beim Öffnen des Dokuments verwendet werden soll.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Legt den Seitenmodus fest, der angibt, wie das Dokument beim Öffnen angezeigt werden soll.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
public final void setPickTrayByPdfSize(boolean value)
```

Legt ein Flag fest, das angibt, ob die PDF‑Seitengröße zur Auswahl des Eingabepapierfachs verwendet werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

Legt die Option zur Handhabung der Druckskalierung fest, die beim Drucken der Datei über den Druckdialog verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | PrintDuplex-Element |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

Standardmäßig ist der pdfa‑Validierungsprozess erforderlich, um pdfa zu aktualisieren oder zu entfernen, wenn einige Regeln verletzt wurden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | boolescher Wert |

### setTitle {#setTitle-java.lang.String-}
Titel für PDF‑Dokument festlegen

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
XMP-Metadaten des Dokuments festlegen.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

Liest oder setzt, ob das Dokument PDF/A‑konform ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Unterdrückt das Aktualisieren von Inhaltsdaten für alle Seiten. Der Inhalt wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird.

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Dokument in die angegebene Datei validieren.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
Dokument in die angegebene Datei validieren.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Dokument in die angegebene Datei validieren.
