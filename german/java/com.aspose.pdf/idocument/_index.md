---
title: "IDocument"
linktitle: "IDocument"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Schnittstelle, die ein PDF-Dokument darstellt"
type: docs
weight: 2230
url: /de/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

Schnittstelle, die ein PDF-Dokument darstellt

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [afterImport](#afterImport--) | Alle registrierten Anmerkungen enumerieren und AfterImport für jede von ihnen aufrufen. |
| [bindXml](#bindXml-java.io.InputStream-) | XML an Dokument binden |
| [bindXml](#bindXml-java.lang.String-) | XML an Dokument binden |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | XML/XSL an Dokument binden |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Ändert Dokument-Passwörter. |
| [check](#check-boolean-) | Validiert Dokument. |
| [close](#close--) | Schließt alle von diesem Dokument verwendeten Ressourcen. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertiert Dokument in ein durchsuchbares Dokument. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. <p> Dies ermöglicht das Anzeigen/Verbergen von durchsuchbarem Text auf der Seite. Standardwert ist FALSE. Dies ermöglicht das Abrufen des Originalbildes aus PDF. Standardwert ist FALSE. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. <p> Dies ermöglicht das Anzeigen/Verbergen von durchsuchbarem Text auf der Seite. Standardwert ist FALSE. Dies ermöglicht das Abrufen des Originalbildes aus PDF. Standardwert ist FALSE. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Konvertiert Dokument mit angegebenen Konvertierungsoptionen |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Konvertiert Dokument und speichert Fehler in die angegebene Datei. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Interne Methode |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können. |
| [decrypt](#decrypt--) | Entschlüsselt das Dokument. |
| [dispose](#dispose--) | Veraltet. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Verschlüsselt das Dokument. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Verschlüsselt das Dokument. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Verschlüsselt das Dokument. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exportiert alle Dokument-Anmerkungen in eine XFDF-Datei |
| [flatten](#flatten--) | Entfernt alle Felder (und Anmerkungen) aus dem Dokument und legt stattdessen deren Werte ab. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Entfernt alle Felder aus dem Dokument und legt stattdessen deren Werte ab. |
| [flattenTransparency](#flattenTransparency--) | Ersetzt transparenten Inhalt durch nichttransparentes Raster- und Vektorgrafiken. |
| [freeMemory](#freeMemory--) | Löscht Speicher |
| [getActions](#getActions--) | Liefert Dokumentaktionen. |
| [getBackground](#getBackground--) | Liefert die Hintergrundfarbe des Dokuments. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Gibt den Elementwert aus dem Katalogwörterbuch zurück. |
| [getCollection](#getCollection--) | Ermittelt die Sammlung des Dokuments. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Ermittelt die Sicherheitseinstellungen, wenn das Dokument verschlüsselt ist. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Ermittelt einen benutzerdefinierten Sicherheits-Handler. |
| [getDefaultCopier](#getDefaultCopier--) | Gibt den Kopierer zurück, der zum Kopieren von Seiten in dieses Dokument verwendet wird. |
| [getDestinations](#getDestinations--) | Ermittelt die Sammlung der Ziele. |
| [getDirection](#getDirection--) | Ermittelt die Lesereihenfolge des Textes: L2R (von links nach rechts) oder R2L (von rechts nach links). |
| [getDuplex](#getDuplex--) | Ermittelt oder legt die Option zur Handhabung des Duplexdruckmodus fest, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Ermittelt die Sammlung von in das Dokument eingebetteten Dateien. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Ermittelt oder legt das Flag zur Verwaltung der Bereinigung von Signaturfeldern fest. |
| [getEngineDoc](#getEngineDoc--) | Instanz von IPdfDocument, die zum Zugriff auf die interne Dokumentstruktur verwendet wird. |
| [getFileName](#getFileName--) | Name der PDF‑Datei, die dieses Dokument verursacht hat |
| [getForm](#getForm--) | Ermittelt das Acro‑Formular des Dokuments. |
| [getId](#getId--) | Ermittelt die ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Ermittelt oder legt das Flag zum Ignorieren von Fehlern in Quelldateien fest. |
| [getInfo](#getInfo--) | Ermittelt die Dokumentinformationen. |
| [getLogicalStructure](#getLogicalStructure--) | Ermittelt die logische Struktur des Dokuments. |
| [getMetadata](#getMetadata--) | Dokument‑Metadaten. |
| [getMetadataStream](#getMetadataStream--) | Gibt den rohen Metadaten‑Stream zurück |
| [getNamedDestinations](#getNamedDestinations--) | Sammlung benannter Ziele im Dokument. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Ermittelt den Seitenmodus, der festlegt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
| [getObjectById](#getObjectById-java.lang.String-) | Ermittelt ein Objekt mit der angegebenen ID im Dokument. |
| [getOpenAction](#getOpenAction--) | Ermittelt die beim Öffnen des Dokuments ausgeführte Aktion. |
| [getOptimizeSize](#getOptimizeSize--) | Ermittelt das Optimierungs‑Flag. |
| [getOutlines](#getOutlines--) | Liefert Dokumentgliederungen. |
| [getPageInfo](#getPageInfo--) | Liefert die Seiteninformationen. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt) |
| [getPageLabels](#getPageLabels--) | Liefert Seitenbeschriftungen im Dokument. |
| [getPageLayout](#getPageLayout--) | Liefert das Seitenlayout, das beim Öffnen des Dokuments verwendet werden soll. |
| [getPageMode](#getPageMode--) | Liefert den Seitenmodus, der angibt, wie das Dokument beim Öffnen angezeigt werden soll. |
| [getPages](#getPages--) | Liefert die Sammlung der Dokumentseiten. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | Liefert die Berechtigungen des Dokuments. |
| [getPrintScaling](#getPrintScaling--) | Liefert die Option zur Handhabung der Druckskalierung, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [getTaggedContent](#getTaggedContent--) | Liefert Zugriff auf TaggedPdf-Inhalt. |
| [getVersion](#getVersion--) | Liefert eine Version von PDF aus dem PDF-Dateikopf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Liefert XMP-Metadaten aus dem Dokument. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importiert Anmerkungen aus einer XFDF-Datei in das Dokument. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Benachrichtigung über fehlende Schriftarten bei der Dokumentenverarbeitung |
| [isCenterWindow](#isCenterWindow--) | Liefert das Flag, das angibt, ob die Position des Dokumentfensters zentriert auf dem Bildschirm sein wird. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Liefert das Flag, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. |
| [isEncrypted](#isEncrypted--) | Liefert den verschlüsselten Status des Dokuments. |
| [isFitWindow](#isFitWindow--) | Liefert das Flag, das angibt, ob das Dokumentfenster auf die erste angezeigte Seite angepasst werden muss. |
| [isHideMenubar](#isHideMenubar--) | Liefert das Flag, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [isHideToolBar](#isHideToolBar--) | Liefert das Flag, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [isHideWindowUI](#isHideWindowUI--) | Liefert oder setzt das Flag, das angibt, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. |
| [isLinearized](#isLinearized--) | Liefert oder setzt einen Wert, der angibt, ob das Dokument linearisiert ist. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. Wir können einige Vorgänge ausführen und nach dem Aufruf von save weiter mit dem Dokument arbeiten, wenn dieser ManualDispose-Parameter aktiviert ist. |
| [isPdfaCompliant](#isPdfaCompliant--) | Liefert, ob das Dokument PDF/A-konform ist. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Liefert, ob das Dokument PDF/UA-konform ist. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Ruft ein Flag ab, das angibt, ob die PDF‑Seitengröße zur Auswahl des Eingabepapierschachs verwendet werden soll. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Liest oder setzt, ob das Dokument PDF/A‑konform ist. |
| [optimize](#optimize--) | Dokument linearisieren, um - die erste Seite so schnell wie möglich zu öffnen; - die nächste Seite anzuzeigen oder einem Link zur nächsten Seite so schnell wie möglich zu folgen; - die Seite schrittweise anzuzeigen, sobald sie ankommt, wenn Daten für eine Seite über einen langsamen Kanal übertragen werden (zuerst die nützlichsten Daten anzeigen); - Benutzerinteraktionen, wie das Folgen eines Links, zu ermöglichen, noch bevor die gesamte Seite empfangen und angezeigt wurde. |
| [optimizeResources](#optimizeResources--) | Ressourcen im Dokument optimieren: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Ressourcen im Dokument gemäß definierter Optimierungsstrategie optimieren. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organisiert Seitenbaumknoten in einem Dokument zu einem balancierten Baum. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organisiert Seitenbaumknoten in einem Dokument zu einem balancierten Baum. |
| [processParagraphs](#processParagraphs--) | Speichert das Dokument in einen Stream. |
| [removeMetadata](#removeMetadata--) | Entfernt Metadaten aus dem Dokument. |
| [removePdfaCompliance](#removePdfaCompliance--) | Entfernt PDF/A‑Konformität aus dem Dokument |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Entfernt PDF/UA‑Konformität aus dem Dokument |
| [repair](#repair--) | Repariert ein beschädigtes Dokument. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | Dokument inkrementell speichern (z. B. |
| [save](#save-java.io.OutputStream-) | Speichert das Dokument in einen Stream. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Dokument speichern |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest. |
| [save](#save-java.lang.String-) | Speichert das Dokument in die angegebene Datei. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Speichert das PDF‑Dokument inkrementell in den angegebenen Stream. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Speichert das PDF‑Dokument inkrementell in den angegebenen Stream. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Speichert das PDF‑Dokument inkrementell in den angegebenen Stream. |
| [saveXml](#saveXml-java.lang.String-) | Dokument als XML speichern. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Sendet bestimmte Seiten des Dokuments an das Dokumentgerät zur Verarbeitung. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Sendet das gesamte Dokument an das Dokumentgerät zur Verarbeitung. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Setzt ein Flag, um die vom Programm bestimmte Schriftart bei fehlender Schriftart festzulegen. |
| [setBackground](#setBackground-java.awt.Color-) | Setzt die Hintergrundfarbe des Dokuments. |
| [setCenterWindow](#setCenterWindow-boolean-) | Setzt ein Flag, das angibt, ob die Position des Dokumentfensters zentriert auf dem Bildschirm sein soll. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Setzt die Sammlung des Dokuments. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Liest den Konvertierungsparameter für den PDF/UA‑Konverter (nur Metadaten und Dokumentkatalog konvertieren, wenn auf true gesetzt). |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Legt die Lesereihenfolge des Textes fest: L2R (von links nach rechts) oder R2L (von rechts nach links). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Legt das Flag fest, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll. |
| [setDuplex](#setDuplex-int-) | Ermittelt oder legt die Option zur Handhabung des Duplexdruckmodus fest, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Ermittelt oder legt das Flag zur Verwaltung der Bereinigung von Signaturfeldern fest. |
| [setFitWindow](#setFitWindow-boolean-) | Legt das Flag fest, das angibt, ob das Dokumentfenster an die erste angezeigte Seite angepasst werden muss. |
| [setHideMenubar](#setHideMenubar-boolean-) | Legt das Flag fest, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [setHideToolBar](#setHideToolBar-boolean-) | Legt das Flag fest, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Legt das Flag fest, das angibt, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | Legt einen Wert fest, der angibt, ob das Dokument linearisiert ist. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. Wir können einige Vorgänge ausführen und weiter mit dem Dokument arbeiten, nachdem die Methode save aufgerufen wurde, wenn dieser ManualDispose‑Parameter aktiviert ist. Es wird jedoch dringend empfohlen, die dispose‑Methode aufzurufen, wenn die Document‑Instanz nicht mehr benötigt wird. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Legt den Seitenmodus fest, der angibt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Legt die beim Öffnen des Dokuments ausgeführte Aktion fest. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Legt das Optimierungs-Flag fest. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Legt die Seiteninformationen fest (nur für den Generator, beim Lesen des Dokuments nicht ausgefüllt). |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Legt das Seitenlayout fest, das beim Öffnen des Dokuments verwendet werden soll. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Legt den Seitenmodus fest, der angibt, wie das Dokument beim Öffnen angezeigt werden soll. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Legt ein Flag fest, das angibt, ob die PDF‑Seitengröße zur Auswahl des Eingabepapierfachs verwendet werden soll. |
| [setPrintScaling](#setPrintScaling-int-) | Legt die Option zur Handhabung der Druckskalierung fest, die beim Drucken der Datei über den Druckdialog verwendet wird. |
| [setTitle](#setTitle-java.lang.String-) | Titel für PDF‑Dokument festlegen |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | XMP-Metadaten des Dokuments festlegen. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Liest oder setzt, ob das Dokument PDF/A‑konform ist. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Dokument in die angegebene Datei validieren. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Dokument in die angegebene Datei validieren. |

### afterImport {#afterImport--}
```
void afterImport()
```

Alle registrierten Anmerkungen enumerieren und AfterImport für jede von ihnen aufrufen.

### bindXml {#bindXml-java.io.InputStream-}
XML an Dokument binden

### bindXml {#bindXml-java.lang.String-}
XML an Dokument binden

### bindXml {#bindXml-java.lang.String-java.lang.String-}
XML/XSL an Dokument binden

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Ändert Dokument-Passwörter.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
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
void close()
```

Schließt alle von diesem Dokument verwendeten Ressourcen.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertiert Dokument in ein durchsuchbares Dokument.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei. <p> Dies ermöglicht das Anzeigen/Verbergen von durchsuchbarem Text auf der Seite. Standardwert ist FALSE. Dies ermöglicht das Abrufen des Originalbildes aus PDF. Standardwert ist FALSE.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei. <p> Dies ermöglicht das Anzeigen/Verbergen von durchsuchbarem Text auf der Seite. Standardwert ist FALSE. Dies ermöglicht das Abrufen des Originalbildes aus PDF. Standardwert ist FALSE.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Konvertiert Dokument mit angegebenen Konvertierungsoptionen

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Konvertiert Dokument und speichert Fehler in die angegebene Datei.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Interne Methode

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertiert Dokument in ein durchsuchbares Dokument und überspringt Fehler von hochr, die nicht konvertiert werden können.

### decrypt {#decrypt--}
```
void decrypt()
```

Entschlüsselt das Dokument.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Veraltet.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Verschlüsselt das Dokument.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Verschlüsselt das Dokument.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Verschlüsselt das Dokument.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exportiert alle Dokument-Anmerkungen in eine XFDF-Datei

### flatten {#flatten--}
```
void flatten()
```

Entfernt alle Felder (und Anmerkungen) aus dem Dokument und legt stattdessen deren Werte ab.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Entfernt alle Felder aus dem Dokument und legt stattdessen deren Werte ab.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

Ersetzt transparenten Inhalt durch nichttransparentes Raster- und Vektorgrafiken.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

Löscht Speicher

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

Liefert Dokumentaktionen.

**Returns:**
DocumentActionCollection-Objekt

### getBackground {#getBackground--}
```
Color getBackground()
```

Liefert die Hintergrundfarbe des Dokuments.

**Returns:**
java.awt.Color-Objekt

### getCatalogValue {#getCatalogValue-java.lang.String-}
Gibt den Elementwert aus dem Katalogwörterbuch zurück.

### getCollection {#getCollection--}
```
Collection getCollection()
```

Ermittelt die Sammlung des Dokuments.

**Returns:**
Sammlungsobjekt

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

Ermittelt die Sicherheitseinstellungen, wenn das Dokument verschlüsselt ist.

**Returns:**
CryptoAlgorithm-Element oder null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Ermittelt einen benutzerdefinierten Sicherheits-Handler.

**Returns:**
ICustomSecurityHandler-Instanz

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

Gibt den Kopierer zurück, der zum Kopieren von Seiten in dieses Dokument verwendet wird.

**Returns:**
Copier-Objekt

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

Ermittelt die Sammlung der Ziele.

**Returns:**
DestinationCollection-Objekt

### getDirection {#getDirection--}
```
Direction getDirection()
```

Ermittelt die Lesereihenfolge des Textes: L2R (von links nach rechts) oder R2L (von rechts nach links).

**Returns:**
Direction-Element

### getDuplex {#getDuplex--}
```
int getDuplex()
```

Ermittelt oder legt die Option zur Handhabung des Duplexdruckmodus fest, die beim Drucken der Datei über den Druckdialog verwendet wird.

**Returns:**
PrintDuplex-Element

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

Ermittelt die Sammlung von in das Dokument eingebetteten Dateien.

**Returns:**
EmbeddedFileCollection-Objekt

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist.

**Returns:**
boolescher Wert

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

Ermittelt oder legt das Flag zur Verwaltung der Bereinigung von Signaturfeldern fest.

**Returns:**
boolescher Wert

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instanz von IPdfDocument, die zum Zugriff auf die interne Dokumentstruktur verwendet wird.

**Returns:**
IPdfDocument-Objekt

### getFileName {#getFileName--}
```
String getFileName()
```

Name der PDF‑Datei, die dieses Dokument verursacht hat

**Returns:**
String-Objekt

### getForm {#getForm--}
```
Form getForm()
```

Ermittelt das Acro‑Formular des Dokuments.

**Returns:**
Form-Objekt

### getId {#getId--}
```
Id getId()
```

Ermittelt die ID.

**Returns:**
Id-Objekt

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

Ermittelt oder legt das Flag zum Ignorieren von Fehlern in Quelldateien fest.

**Returns:**
boolescher Wert

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

Ermittelt die Dokumentinformationen.

**Returns:**
DocumentInfo-Objekt

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

Ermittelt die logische Struktur des Dokuments.

**Returns:**
RootElement-Objekt

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

Dokument‑Metadaten.

**Returns:**
Metadata-Objekt

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Gibt den rohen Metadaten‑Stream zurück

**Returns:**
IPdfStreamAccessor-Objekt

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

Sammlung benannter Ziele im Dokument.

**Returns:**
NamedDestinationCollection-Instanz

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

Ermittelt den Seitenmodus, der festlegt, wie das Dokument beim Verlassen des Vollbildmodus angezeigt wird.

**Returns:**
PageMode-Element

### getObjectById {#getObjectById-java.lang.String-}
Ermittelt ein Objekt mit der angegebenen ID im Dokument.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

Ermittelt die beim Öffnen des Dokuments ausgeführte Aktion.

**Returns:**
IAppointment-Objekt

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

Ermittelt das Optimierungs‑Flag.

**Returns:**
boolescher Wert

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

Liefert Dokumentgliederungen.

**Returns:**
OutlineCollection-Objekt

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

Liefert die Seiteninformationen. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt)

**Returns:**
Die Seiteninfo.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

Liefert Seitenbeschriftungen im Dokument.

**Returns:**
PageLabelCollection-Objekt

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

Liefert das Seitenlayout, das beim Öffnen des Dokuments verwendet werden soll.

**Returns:**
PageLayout-Element

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

Liefert den Seitenmodus, der angibt, wie das Dokument beim Öffnen angezeigt werden soll.

**Returns:**
PageMode-Element

### getPages {#getPages--}
```
PageCollection getPages()
```

Liefert die Sammlung der Dokumentseiten.

**Returns:**
boolescher Wert

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
PdfFormat-Element

### getPermissions {#getPermissions--}
```
int getPermissions()
```

Liefert die Berechtigungen des Dokuments.

**Returns:**
int-Wert

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

Liefert die Option zur Handhabung der Druckskalierung, die beim Drucken der Datei über den Druckdialog verwendet wird.

**Returns:**
PrintScaling-Element

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

Liefert Zugriff auf TaggedPdf-Inhalt.

**Returns:**
ITaggedContent-Instanz

### getVersion {#getVersion--}
```
String getVersion()
```

Liefert eine Version von PDF aus dem PDF-Dateikopf.

**Returns:**
String-Objekt

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Liefert XMP-Metadaten aus dem Dokument.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importiert Anmerkungen aus einer XFDF-Datei in das Dokument.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

Benachrichtigung über fehlende Schriftarten bei der Dokumentenverarbeitung

**Returns:**
boolescher Wert

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

Liefert das Flag, das angibt, ob die Position des Dokumentfensters zentriert auf dem Bildschirm sein wird.

**Returns:**
boolescher Wert

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind.

**Returns:**
boolescher Wert standardmäßig false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

Liefert das Flag, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll.

**Returns:**
boolescher Wert

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

Liefert den verschlüsselten Status des Dokuments.

**Returns:**
boolescher Wert

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

Liefert das Flag, das angibt, ob das Dokumentfenster auf die erste angezeigte Seite angepasst werden muss.

**Returns:**
boolescher Wert

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

Liefert das Flag, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist.

**Returns:**
boolescher Wert

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

Liefert das Flag, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist.

**Returns:**
boolescher Wert

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

Liefert oder setzt das Flag, das angibt, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist.

**Returns:**
boolescher Wert

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

Liefert oder setzt einen Wert, der angibt, ob das Dokument linearisiert ist.

**Returns:**
boolescher Wert

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. Wir können einige Vorgänge ausführen und nach dem Aufruf von save weiter mit dem Dokument arbeiten, wenn dieser ManualDispose-Parameter aktiviert ist.

**Returns:**
boolescher Wert. (Standardwert == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

Liefert, ob das Dokument PDF/A-konform ist.

**Returns:**
boolescher Wert

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

Liefert, ob das Dokument PDF/UA-konform ist.

**Returns:**
boolescher Wert

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

Ruft ein Flag ab, das angibt, ob die PDF‑Seitengröße zur Auswahl des Eingabepapierschachs verwendet werden soll.

**Returns:**
boolescher Wert

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

Liest oder setzt, ob das Dokument PDF/A‑konform ist.

**Returns:**
boolescher Wert

### optimize {#optimize--}
```
void optimize()
```

Dokument linearisieren, um - die erste Seite so schnell wie möglich zu öffnen; - die nächste Seite anzuzeigen oder einem Link zur nächsten Seite so schnell wie möglich zu folgen; - die Seite schrittweise anzuzeigen, sobald sie ankommt, wenn Daten für eine Seite über einen langsamen Kanal übertragen werden (zuerst die nützlichsten Daten anzeigen); - Benutzerinteraktionen, wie das Folgen eines Links, zu ermöglichen, noch bevor die gesamte Seite empfangen und angezeigt wurde.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

Ressourcen im Dokument optimieren: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Ressourcen im Dokument gemäß definierter Optimierungsstrategie optimieren.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

Organisiert Seitenbaumknoten in einem Dokument zu einem balancierten Baum.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organisiert Seitenbaumknoten in einem Dokument zu einem balancierten Baum.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodesNumInSubtrees |  | Gewünschte Anzahl von Unterknoten. Standardwert ist zehn. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

Speichert das Dokument in einen Stream.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

Entfernt Metadaten aus dem Dokument.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

Entfernt PDF/A‑Konformität aus dem Dokument

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

Entfernt PDF/UA‑Konformität aus dem Dokument

### repair {#repair--}
```
void repair()
```

Repariert ein beschädigtes Dokument.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

Dokument inkrementell speichern (z. B.

### save {#save-java.io.OutputStream-}
Speichert das Dokument in einen Stream.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Dokument speichern

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Speichert das Dokument unter einem neuen Namen und legt dabei die Speicheroptionen fest.

### save {#save-java.lang.String-}
Speichert das Dokument in die angegebene Datei.

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

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Setzt ein Flag, um die vom Programm bestimmte Schriftart bei fehlender Schriftart festzulegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | boolescher Wert |

### setBackground {#setBackground-java.awt.Color-}
Setzt die Hintergrundfarbe des Dokuments.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

Setzt ein Flag, das angibt, ob die Position des Dokumentfensters zentriert auf dem Bildschirm sein soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Setzt die Sammlung des Dokuments.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

Liest den Konvertierungsparameter für den PDF/UA‑Konverter (nur Metadaten und Dokumentkatalog konvertieren, wenn auf true gesetzt).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Legt die Lesereihenfolge des Textes fest: L2R (von links nach rechts) oder R2L (von rechts nach links).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert standardmäßig false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

Legt das Flag fest, das angibt, ob die Titelleiste des Dokumentfensters den Dokumenttitel anzeigen soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

Ermittelt oder legt die Option zur Handhabung des Duplexdruckmodus fest, die beim Drucken der Datei über den Druckdialog verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | PrintDuplex-Element |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

Eigenschaft, die festlegt, dass das Dokument alle Standard‑Type1‑Schriften einbetten muss, bei denen das Flag IsEmbedded auf true gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

Ermittelt oder legt das Flag zur Verwaltung der Bereinigung von Signaturfeldern fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

Legt das Flag fest, das angibt, ob das Dokumentfenster an die erste angezeigte Seite angepasst werden muss.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

Legt das Flag fest, das angibt, ob die Menüleiste ausgeblendet werden soll, wenn das Dokument aktiv ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

Legt das Flag fest, das angibt, ob die Symbolleiste ausgeblendet werden soll, wenn das Dokument aktiv ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

Legt das Flag fest, das angibt, ob UI-Elemente ausgeblendet werden sollen, wenn das Dokument aktiv ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

Legt einen Wert fest, der angibt, ob das Dokument linearisiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Standardmäßig schließt die Methode save interne Streams und gibt Speicherressourcen frei. Wir können einige Vorgänge ausführen und weiter mit dem Dokument arbeiten, nachdem die Methode save aufgerufen wurde, wenn dieser ManualDispose‑Parameter aktiviert ist. Es wird jedoch dringend empfohlen, die dispose‑Methode aufzurufen, wenn die Document‑Instanz nicht mehr benötigt wird.

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
void setOptimizeSize(boolean value)
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
void setPickTrayByPdfSize(boolean value)
```

Legt ein Flag fest, das angibt, ob die PDF‑Seitengröße zur Auswahl des Eingabepapierfachs verwendet werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

Legt die Option zur Handhabung der Druckskalierung fest, die beim Drucken der Datei über den Druckdialog verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | PrintDuplex-Element |

### setTitle {#setTitle-java.lang.String-}
Titel für PDF‑Dokument festlegen

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
XMP-Metadaten des Dokuments festlegen.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

Liest oder setzt, ob das Dokument PDF/A‑konform ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Dokument in die angegebene Datei validieren.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Dokument in die angegebene Datei validieren.
