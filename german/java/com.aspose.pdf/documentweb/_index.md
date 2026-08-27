---
title: "DocumentWeb"
linktitle: "DocumentWeb"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die DocumentWeb-Klasse dar"
type: docs
weight: 1170
url: /de/java/com.aspose.pdf/documentweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DocumentWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class DocumentWeb extends Object implements IDocument
```

Stellt die DocumentWeb-Klasse dar

## Felder

| Feld | Beschreibung |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Dies tritt auf, wenn eine Schriftart eine andere Schriftart im Dokument ersetzt. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DocumentWeb](#DocumentWeb--) | Initialisiert ein leeres DocumentWeb. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-) | Initialisiert ein leeres DocumentWeb. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Initialisiert ein leeres DocumentWeb. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-java.lang.String-) | Initialisiert ein leeres DocumentWeb. |
| [DocumentWeb](#DocumentWeb-java.lang.String-) | Initialisiert ein leeres DocumentWeb. |
| [DocumentWeb](#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-) | Initialisiert ein leeres DocumentWeb. |
| [DocumentWeb](#DocumentWeb-java.lang.String-java.lang.String-) | Initialisiert ein leeres DocumentWeb. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [afterImport](#afterImport--) | Alle registrierten Anmerkungen enumerieren und AfterImport für jede von ihnen aufrufen. |
| [bindXml](#bindXml-java.io.InputStream-) | XML an Dokument binden |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | XML/XSL an Dokument binden |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | XML/XSL an Dokument binden |
| [bindXml](#bindXml-java.lang.String-) | XML an Dokument binden |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | XML/XSL an Dokument binden |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Ändert Dokument-Passwörter. |
| [check](#check-boolean-) | Validiert Dokument. |
| [close](#close--) | Schließt alle von diesem Dokument verwendeten Ressourcen. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertiert Dokument in ein durchsuchbares Dokument. |
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
| [decrypt](#decrypt--) | Entschlüsselt das Dokument. |
| [dispose](#dispose--) | Veraltet. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Verschlüsselt das Dokument. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Verschlüsselt das Dokument. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Verschlüsselt das Dokument. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Verschlüsselt das Dokument. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Verschlüsselt das Dokument. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Verschlüsselt das Dokument. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exportiert alle Dokumentannotationen in einen Stream. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exportiert alle Dokument-Anmerkungen in eine XFDF-Datei |
| [flatten](#flatten--) | Entfernt alle Felder (und Anmerkungen) aus dem Dokument und legt stattdessen deren Werte ab. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Entfernt alle Felder aus dem Dokument und legt stattdessen deren Werte ab. |
| [flattenTransparency](#flattenTransparency--) | Ersetzt transparenten Inhalt durch nichttransparentes Raster- und Vektorgrafiken. |
| [freeMemory](#freeMemory--) | Löscht Speicher |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Benachrichtigung über fehlende Schriften beim Verarbeiten von Dokumenten. |
| [getActions](#getActions--) | Liefert Dokumentaktionen. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Ermöglicht das Zusammenführen von Seiteninhalten, um die Dokumentgröße zu optimieren. |
| [getBackground](#getBackground--) | Liefert die Hintergrundfarbe des Dokuments. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Gibt den Elementwert aus dem Katalogwörterbuch zurück. |
| [getCollection](#getCollection--) | Ermittelt die Sammlung des Dokuments. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Ermittelt die Sicherheitseinstellungen, wenn das Dokument verschlüsselt ist. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Ermittelt einen benutzerdefinierten Sicherheits-Handler. |
| [getDefaultCopier](#getDefaultCopier--) | Gibt den Kopierer zurück, der zum Kopieren von Seiten in dieses Dokument verwendet wird. |
| [getDestinations](#getDestinations--) | Veraltet. |
| [getDirection](#getDirection--) | Ermittelt die Lesereihenfolge des Textes: L2R (von links nach rechts) oder R2L (von rechts nach links). |
| [getDuplex](#getDuplex--) | Ermittelt oder legt die Option zur Handhabung des Duplexdruckmodus fest, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Ermittelt die Sammlung von in das Dokument eingebetteten Dateien. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Ermittelt oder legt das Flag zur Verwaltung der Bereinigung von Signaturfeldern fest. |
| [getEngineDoc](#getEngineDoc--) | Instanz von IPdfDocument, die zum Zugriff auf die interne Dokumentstruktur verwendet wird. |
| [getFileName](#getFileName--) | Name der PDF‑Datei, die dieses Dokument verursacht hat |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Liest und setzt das Dateigrößenlimit für das Laden einer gesamten Datei in den Speicher. |
| [getForm](#getForm--) | Ermittelt das Acro‑Formular des Dokuments. |
| [getId](#getId--) | Ermittelt die ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Ermittelt oder legt das Flag zum Ignorieren von Fehlern in Quelldateien fest. |
| [getInfo](#getInfo--) | Ermittelt die Dokumentinformationen. |
| [getJavaScript](#getJavaScript--) | Sammlung von JavaScript auf Dokumentebene. |
| [getLogicalStructure](#getLogicalStructure--) | Ermittelt die logische Struktur des Dokuments. |
| [getMetadata](#getMetadata--) | Dokument‑Metadaten. |
| [getMetadataStream](#getMetadataStream--) | Nur für den internen Gebrauch! |
| [getNamedDestinations](#getNamedDestinations--) | Sammlung benannter Ziele im Dokument. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Ermittelt den Seitenmodus, der festlegt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
| [getObjectById](#getObjectById-java.lang.String-) | Ermittelt ein Objekt mit der angegebenen ID im Dokument. |
| [getOpenAction](#getOpenAction--) | Ermittelt die beim Öffnen des Dokuments ausgeführte Aktion. |
| [getOptimizeSize](#getOptimizeSize--) | Ermittelt das Optimierungs‑Flag. |
| [getOutlines](#getOutlines--) | Liefert Dokumentgliederungen. |
| [getOutputIntents](#getOutputIntents--) | Liest die Sammlung der Output‑Intents im Dokument. |
| [getPageInfo](#getPageInfo--) | Liefert die Seiteninformationen. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt) |
| [getPageLabels](#getPageLabels--) | Liefert Seitenbeschriftungen im Dokument. |
| [getPageLayout](#getPageLayout--) | Liefert das Seitenlayout, das beim Öffnen des Dokuments verwendet werden soll. |
| [getPageMode](#getPageMode--) | Liefert den Seitenmodus, der angibt, wie das Dokument beim Öffnen angezeigt werden soll. |
| [getPages](#getPages--) | Liefert die Sammlung der Dokumentseiten. |
| [getPdfFormat](#getPdfFormat--) | Liefert das PDF-Format. |
| [getPermissions](#getPermissions--) | Liefert die Berechtigungen des Dokuments. |
| [getPrintScaling](#getPrintScaling--) | Liefert die Option zur Handhabung der Druckskalierung, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [getTaggedContent](#getTaggedContent--) | Liefert Zugriff auf TaggedPdf-Inhalt. |
| [getVersion](#getVersion--) | Liefert eine Version von PDF aus dem PDF-Dateikopf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Liefert XMP-Metadaten aus dem Dokument. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Überprüft, ob das aktuelle PDF-Dokument mit inkrementellen Updates gespeichert wurde. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Importiert Anmerkungen aus einem Stream in das Dokument. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importiert Anmerkungen aus einer XFDF-Datei in das Dokument. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Flag, das über den Ersatz einer fehlenden Schriftart informiert. |
| [isCenterWindow](#isCenterWindow--) | Liefert das Flag, das angibt, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Liefert das Flag, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Liest oder setzt einen Wert, der angibt, ob das Protokollieren von Benachrichtigungen aktiviert werden soll. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Liest oder setzt ein Flag, das das teilweise Entladen des Dokuments aus dem Speicher ermöglicht. |
| [isEncrypted](#isEncrypted--) | Liefert den verschlüsselten Status des Dokuments. |
| [isFitWindow](#isFitWindow--) | Liefert das Flag, das angibt, ob das Dokumentfenster auf die erste angezeigte Seite angepasst werden muss. |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Wirft eine Ausnahme, wenn das Dokument mit Änderungen gespeichert wird und eine Signatur enthält |
| [isHideMenubar](#isHideMenubar--) | Liefert das Flag, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [isHideToolBar](#isHideToolBar--) | Liefert das Flag, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [isHideWindowUI](#isHideWindowUI--) | Liefert oder setzt das Flag, das angibt, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. |
| [isLicensed](#isLicensed--) | Gibt den lizenzierten Zustand des Systems zurück. |
| [isLinearized](#isLinearized--) | Liefert oder setzt einen Wert, der angibt, ob das Dokument linearisiert ist. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. |
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
| [optimize](#optimize--) | Linearisieren Sie das Dokument, um - die erste Seite so schnell wie möglich zu öffnen; - die nächste Seite anzuzeigen oder einem Link zur nächsten Seite so schnell wie möglich zu folgen; - die Seite schrittweise anzuzeigen, sobald sie ankommt, wenn Daten für eine Seite über einen langsamen Kanal übertragen werden (die nützlichsten Daten zuerst anzeigen); - dem Benutzer zu ermöglichen, Interaktionen wie das Folgen eines Links durchzuführen, noch bevor die gesamte Seite empfangen und angezeigt wurde. |
| [optimizeResources](#optimizeResources--) | Ressourcen im Dokument optimieren: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Ressourcen im Dokument gemäß definierter Optimierungsstrategie optimieren. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organisiert Seitenbaumknoten in einem Dokument zu einem balancierten Baum. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organisiert Seitenbaumknoten in einem Dokument zu einem balancierten Baum. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Interne Methode |
| [processParagraphs](#processParagraphs--) | Speichert das Dokument im Generator. |
| [removeMetadata](#removeMetadata--) | Entfernt Metadaten aus dem Dokument. |
| [removePdfaCompliance](#removePdfaCompliance--) | Entfernt PDF/A‑Konformität aus dem Dokument |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Entfernt PDF/UA‑Konformität aus dem Dokument |
| [repair](#repair--) | Repariert ein beschädigtes Dokument. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Repariert ein beschädigtes Dokument. |
| [resumeUpdate](#resumeUpdate--) | setzt die Dokumentaktualisierung fort |
| [save](#save--) | Dokument inkrementell speichern (z. B. |
| [save](#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-) | Speichert das Dokument in einen Antwort-Stream mit Speicheroptionen. |
| [save](#save-java.io.OutputStream-) | Speichert das Dokument in einen Stream. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest. |
| [save](#save-com.aspose.pdf.SaveOptions-) | Speichert das Dokument mit Speicheroptionen. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | Nur für den internen Gebrauch. |
| [save](#save-java.lang.String-) | Speichert das Dokument in die angegebene Datei. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Speichert das PDF‑Dokument inkrementell in den angegebenen Stream. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Speichert das PDF‑Dokument inkrementell in den angegebenen Stream. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Speichert das PDF‑Dokument inkrementell in den angegebenen Stream. |
| [saveXml](#saveXml-java.lang.String-) | Dokument als XML speichern. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sendet bestimmte Seiten des Dokuments an das Dokumentgerät zur Verarbeitung. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Benachrichtigung über fehlende Schriften beim Verarbeiten von Dokumenten. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Setzt das Flag, um die fehlende Schriftart zu ersetzen. |
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
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Ermittelt oder legt das Flag zum Ignorieren von Fehlern in Quelldateien fest. |
| [setLinearized](#setLinearized-boolean-) | Legt einen Wert fest, der angibt, ob das Dokument linearisiert ist. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Legt den Seitenmodus fest, der angibt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Legt die beim Öffnen des Dokuments ausgeführte Aktion fest. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Legt das Optimierungs-Flag fest. |
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

### DocumentWeb {#DocumentWeb--}
```
public DocumentWeb()
```

Initialisiert ein leeres DocumentWeb.

### DocumentWeb {#DocumentWeb-java.io.InputStream-}
Initialisiert ein leeres DocumentWeb.

### DocumentWeb {#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Initialisiert ein leeres DocumentWeb.

### DocumentWeb {#DocumentWeb-java.io.InputStream-java.lang.String-}
Initialisiert ein leeres DocumentWeb.

### DocumentWeb {#DocumentWeb-java.lang.String-}
Initialisiert ein leeres DocumentWeb.

### DocumentWeb {#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-}
Initialisiert ein leeres DocumentWeb.

### DocumentWeb {#DocumentWeb-java.lang.String-java.lang.String-}
Initialisiert ein leeres DocumentWeb.

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
Ändert Dokument-Passwörter.

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
Boolescher Wert True – wenn das Dokument repariert wurde; andernfalls false.

### close {#close--}
```
public void close()
```

Schließt alle von diesem Dokument verwendeten Ressourcen.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertiert Dokument in ein durchsuchbares Dokument.

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

Entschlüsselt das Dokument.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Veraltet.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Verschlüsselt das Dokument.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Verschlüsselt das Dokument.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Verschlüsselt das Dokument.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Verschlüsselt das Dokument.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Verschlüsselt das Dokument.

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
Entfernt alle Felder aus dem Dokument und legt stattdessen deren Werte ab.

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

Liefert Dokumentaktionen.

**Returns:**
DocumentActionCollection-Objekt

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
java.awt.Color-Objekt

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

Ermittelt die Sicherheitseinstellungen, wenn das Dokument verschlüsselt ist.

**Returns:**
CryptoAlgorithm-Element oder null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
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
@Deprecated public DestinationCollection getDestinations()
```

Veraltet.

**Returns:**
DestinationCollection-Objekt

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Ermittelt die Lesereihenfolge des Textes: L2R (von links nach rechts) oder R2L (von rechts nach links).

**Returns:**
Direction-Element

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

Instanz von IPdfDocument, die zum Zugriff auf die interne Dokumentstruktur verwendet wird.

**Returns:**
IPdfDocument-Objekt

### getFileName {#getFileName--}
```
public String getFileName()
```

Name der PDF‑Datei, die dieses Dokument verursacht hat

**Returns:**
String Wert

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Liest und setzt das Dateigrößenlimit für das Laden einer gesamten Datei in den Speicher.

**Returns:**
int-Wert

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

Ermittelt oder legt das Flag zum Ignorieren von Fehlern in Quelldateien fest.

**Returns:**
Boolesche Werte

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

Dokument‑Metadaten.

**Returns:**
Metadata-Objekt

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Nur für den internen Gebrauch!

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
PageMode-Element

### getObjectById {#getObjectById-java.lang.String-}
Ermittelt ein Objekt mit der angegebenen ID im Dokument.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

Ermittelt die beim Öffnen des Dokuments ausgeführte Aktion.

**Returns:**
IAppointment-Objekt

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Ermittelt das Optimierungs‑Flag.

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
PageLayout-Element

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Liefert den Seitenmodus, der angibt, wie das Dokument beim Öffnen angezeigt werden soll.

**Returns:**
PageMode-Element

### getPages {#getPages--}
```
public PageCollection getPages()
```

Liefert die Sammlung der Dokumentseiten.

**Returns:**
boolescher Wert

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Liefert das PDF-Format.

**Returns:**
PdfFormat

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
public ITaggedContent getTaggedContent()
```

Liefert Zugriff auf TaggedPdf-Inhalt.

**Returns:**
ITaggedContent-Instanz

### getVersion {#getVersion--}
```
public String getVersion()
```

Liefert eine Version von PDF aus dem PDF-Dateikopf.

**Returns:**
String-Objekt

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

Liefert das Flag, das angibt, ob die Position des Dokumentfensters auf dem Bildschirm zentriert wird.

**Returns:**
boolescher Wert

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

Liefert das Flag, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll.

**Returns:**
boolescher Wert

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

Liefert den verschlüsselten Status des Dokuments.

**Returns:**
Boolescher Wert

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

Liefert das Flag, das angibt, ob das Dokumentfenster auf die erste angezeigte Seite angepasst werden muss.

**Returns:**
boolescher Wert

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

Liefert das Flag, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist.

**Returns:**
boolescher Wert

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

Liefert das Flag, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist.

**Returns:**
boolescher Wert

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

Liefert oder setzt das Flag, das angibt, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist.

**Returns:**
boolescher Wert

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

Liefert oder setzt einen Wert, der angibt, ob das Dokument linearisiert ist.

**Returns:**
boolescher Wert

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei.

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

Linearisieren Sie das Dokument, um - die erste Seite so schnell wie möglich zu öffnen; - die nächste Seite anzuzeigen oder einem Link zur nächsten Seite so schnell wie möglich zu folgen; - die Seite schrittweise anzuzeigen, sobald sie ankommt, wenn Daten für eine Seite über einen langsamen Kanal übertragen werden (die nützlichsten Daten zuerst anzeigen); - dem Benutzer zu ermöglichen, Interaktionen wie das Folgen eines Links durchzuführen, noch bevor die gesamte Seite empfangen und angezeigt wurde.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Ressourcen im Dokument optimieren: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Ressourcen im Dokument gemäß definierter Optimierungsstrategie optimieren.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Organisiert Seitenbaumknoten in einem Dokument zu einem balancierten Baum.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organisiert Seitenbaumknoten in einem Dokument zu einem balancierten Baum.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodesNumInSubtrees |  | Gewünschte Anzahl von Unterknoten. Standardwert ist zehn. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Interne Methode

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Speichert das Dokument im Generator.

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

Dokument inkrementell speichern (z. B.

### save {#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-}
Speichert das Dokument in einen Antwort-Stream mit Speicheroptionen.

### save {#save-java.io.OutputStream-}
Speichert das Dokument in einen Stream.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest.

### save {#save-com.aspose.pdf.SaveOptions-}
Speichert das Dokument mit Speicheroptionen.

### save {#save-com.aspose.ms.System.IO.Stream-}
Nur für den internen Gebrauch.

### save {#save-java.lang.String-}
Speichert das Dokument in die angegebene Datei.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
Speichert das Dokument unter einem neuen Namen zusammen mit einem Dateiformat.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest.

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
public void setAbsentFontTryToSubstitute(boolean substitute)
```

Setzt das Flag, um die fehlende Schriftart zu ersetzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ersetzen |  | boolescher Wert |

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

Ermittelt oder legt das Flag zum Ignorieren von Fehlern in Quelldateien fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Boolesche Werte |

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

Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| manualDisposeEnabled |  | boolescher Wert. (Standardwert == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Legt den Seitenmodus fest, der angibt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
Legt die beim Öffnen des Dokuments ausgeführte Aktion fest.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Legt das Optimierungs-Flag fest.

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
