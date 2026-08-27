---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse dar, um ein PDF anzuzeigen oder zu drucken."
type: docs
weight: 610
url: /de/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

Stellt eine Klasse dar, um ein PDF anzuzeigen oder zu drucken.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | Fügt das Abonnement für das Druckereignis der letzten Seite hinzu/entfernt es. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Fügt das Abonnement für das Druckereignis der letzten Seite hinzu/entfernt es. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfViewer](#PdfViewer--) | Initialisiert ein neues {@code PdfViewer}-Objekt. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | Initialisiert ein neues {@code PdfViewer}-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initialisiert die Fassade. |
| [bindPdf](#bindPdf-java.lang.String-) | Initialisiert die Fassade. |
| [close](#close--) | Schließt die aktuelle PDF-Datei. |
| [closePdfFile](#closePdfFile--) | Schließt die aktuelle PDF-Datei. |
| [decodeAllPages](#decodeAllPages--) | Liefert die Seiten der aktuellen PDF-Datei. |
| [decodePage](#decodePage-int-) | Dekodiert eine Seite einer PDF-Datei. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Dekodiert die Seite zu einem BufferedImage |
| [dispose](#dispose--) | Gibt die Ressourcen der Fassade frei. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [getAutoResize](#getAutoResize--) | Setzt einen booleschen Wert, der angibt, ob die Datei mit optimierter Größe gedruckt werden soll. |
| [getAutoRotate](#getAutoRotate--) | Liefert einen booleschen Wert, der angibt, ob die Datei mit automatischer Drehung gedruckt werden soll. |
| [getAutoRotateMode](#getAutoRotateMode--) | Liefert einen AutoRotateMode-Wert, der die Drehrichtung angibt. |
| [getCoordinateType](#getCoordinateType--) | Ermittelt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| [getCopiesPrinted](#getCopiesPrinted--) | Liefert die gedruckten Kopien. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Liefert die standardmäßigen Seiteneinstellungen. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | Liefert die standardmäßigen Druckereinstellungen. |
| [getFormPresentationMode](#getFormPresentationMode--) | Liefert den Formularpräsentationsmodus. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Liefert einen Wert, der die horizontale Ausrichtung angibt. |
| [getPageCount](#getPageCount--) | Liefert die Seitenanzahl der aktuellen PDF-Datei. |
| [getPassword](#getPassword--) | Liefert das Passwort des Eingabedokuments. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> Liefert oder setzt einen booleschen Wert, der angibt, ob die Seite in Graustufen gedruckt wird. Standardmäßig ist false. </p> <hr> Standard false ist false. |
| [getPrintAsImage](#getPrintAsImage--) | <p> Erhält einen Modus für PdfViewer, um als Bild zu drucken. </p> |
| [getPrinterJobName](#getPrinterJobName--) | Ermittelt den Namen des Dokuments in der Druckwarteschlange, wenn das Dokument gedruckt wird. Der Standardwert ist der Dateiname. |
| [getPrintPageDialog](#getPrintPageDialog--) | Ermittelt einen booleschen Wert, der angibt, ob der Seitenzahl-Dialog beim Drucken erzeugt wird. |
| [getPrintStatus](#getPrintStatus--) | Ermittelt das Ergebnis des Druckauftrags. Bei Erfolg null; andernfalls ein Ausnahmeobjekt. |
| [getRenderingOptions](#getRenderingOptions--) | Ruft Rendering-Optionen ab. |
| [getResolution](#getResolution--) | Ermittelt oder setzt die Auflösung während der Anzeige und des Druckens. Je höher die Auflösung, desto langsamer die Geschwindigkeit. Der Standardwert ist 150. Diese Eigenschaft ändert die Bildauflösung in den Konvertierungsabläufen von Seite zu Bild: wenn {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) auf {@code } gesetzt ist, oder wenn die Methode {@link #decodePage(int)} oder {@link #decodeAllPages} aufgerufen wird. Um eine Druckerauflösung für das direkte Drucken auf einen Drucker festzulegen, verwenden Sie die Eigenschaft {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) in der Klasse {@code PageSettings}. |
| [getScaleFactor](#getScaleFactor--) | Ermittelt einen Gleitkommawert, der den Skalierungsfaktor angibt. Der Standardwert ist 1,0. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | Ermittelt die Verwendung der Konvertierung einer pdf-Seite in eine Zwischen-PNG-Datei während des Druckens im Dateimodus. Verwenden Sie sie, wenn die Größe der Ausgabedatei wichtig ist. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ermittelt einen Wert, der die vertikale Ausrichtung angibt |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Diese Methode ist veraltet. Ermittelt das Flag, das die Sichtbarkeit versteckter Bereiche auf der Seite steuert. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Öffnet einen Pdf-Dateistream. Decodiert jedoch nicht tatsächlich die Seiten der Pdf-Datei. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Öffnet eine Pdf-Datei, decodiert jedoch nicht tatsächlich die Seiten der Pdf-Datei. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> Druckt das Pdf-Dokument mit dem Standarddrucker. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Druckt das Pdf-Dokument mit Druckereinstellungen. Die Ausgabeseitengröße passt sich der Größe der ersten Seite des Dokuments an. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Druckt das PDF-Dokument mit Einstellungen. Wenn die Dokumentgröße nicht mit der Seitengröße kompatibel ist, erweitert pdf.kit sie, um zur Seitengröße zu passen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //druckt die Datei mit angepasster Größe viewer.setAutoRotate ( true); //druckt die Datei mit angepasster Drehung viewer.setPrintPageDialog ( false);//erzeugt keinen Seitenzahl-Dialog beim Drucken PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> Öffnet und druckt einen großen PDF-Stream. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr enthält oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //druckt die Datei mit angepasster Größe viewer.setAutoRotate ( true); //druckt die Datei mit angepasster Drehung viewer.printPageDialog=false;//erzeugt keinen Seitenzahl-Dialog beim Drucken viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und Drucken der Datei, sodass Sie OpenPdfFile() nicht explizit aufrufen müssen. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Öffnet und druckt einen großen PDF-Stream mit angegebenen Druckereinstellungen. Wenn Ihre PDF-Datei Hunderte von Seiten oder mehr enthält oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // druckt die Datei mit angepasster Größe viewer.setAutoRotate(true); // druckt die Datei mit angepasster Drehung viewer.setPrintPageDialog(false); // erzeugt keinen Seitenzahl-Dialog beim // Drucken PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und Drucken der Datei, sodass Sie OpenPdfFile() nicht explizit aufrufen müssen. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Öffnet und druckt einen großen PDF‑Stream mit angegebenen Seiteneinstellungen und Druckereinstellungen. Wenn Ihre PDF‑Datei Hunderte von Seiten oder mehr enthält oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und das Drucken der Datei, sodass Sie nicht explizit die Methode OpenPdfFile() aufrufen müssen. |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> Öffnet und druckt eine große PDF‑Datei. Wenn Ihre PDF‑Datei Hunderte von Seiten oder mehr enthält oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Öffnet und druckt eine große PDF‑Datei mit angegebenen Druckereinstellungen. Wenn Ihre PDF‑Datei Hunderte von Seiten oder mehr enthält oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und das Drucken der Datei, sodass Sie nicht explizit die Methode OpenPdfFile() aufrufen müssen. |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Öffnet und druckt eine große Pdf-Datei mit angegebenen Seiten‑Einstellungen und Drucker‑Einstellungen. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und Drucken der Datei, sodass Sie OpenPdfFile() nicht explizit aufrufen müssen. |
| [save](#save-java.io.InputStream-) | Speichert das resultierende PDF-Dokument in einen Stream. |
| [save](#save-java.lang.String-) | Speichert das resultierende PDF-Dokument in einer Datei. |
| [setAutoResize](#setAutoResize-boolean-) | Setzt einen booleschen Wert, der angibt, ob die Datei mit optimierter Größe gedruckt werden soll. |
| [setAutoRotate](#setAutoRotate-boolean-) | Setzt einen booleschen Wert, der angibt, ob die Datei automatisch rotiert gedruckt werden soll |
| [setAutoRotateMode](#setAutoRotateMode-int-) | Setzt einen AutoRotateMode-Wert, der die Drehrichtung angibt |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Setzt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Setzt den Formular-Präsentationsmodus. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Setzt einen Wert, der die horizontale Ausrichtung angibt |
| [setPassword](#setPassword-java.lang.String-) | Setzt das Passwort des Eingabedokuments. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> Liefert oder setzt einen booleschen Wert, der angibt, ob die Seite in Graustufen gedruckt wird. Standardmäßig ist false. </p> <hr> Standard false ist false. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> Setzt einen Modus für PdfViewer, um als Bild zu drucken. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | Setzt den Namen des Dokuments in der Druckwarteschlange, wenn das Dokument gedruckt wird. Der Standardwert ist der Dateiname. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | Setzt einen booleschen Wert, der angibt, ob beim Drucken der Seitenzahl‑Dialog erzeugt wird. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Setzt Rendering-Optionen. |
| [setResolution](#setResolution-int-) | Setzt die Auflösung während der Anzeige und des Druckens. Je höher die Auflösung, desto langsamer die Geschwindigkeit. Der Standardwert ist 150. Diese Eigenschaft ändert die Bildauflösung in den Page‑to‑Image‑Konvertierungsabläufen: wenn {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) auf {@code } gesetzt ist, oder wenn die Methode {@link #decodePage(int)} oder {@link #decodeAllPages} aufgerufen wird. Um eine Druckerauflösung für den Direktdruck auf einen Drucker festzulegen, verwenden Sie die {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)})‑Eigenschaft in der {@code PageSettings}-Klasse. |
| [setScaleFactor](#setScaleFactor-float-) | Setzt einen Gleitkommawert, der den Skalierungsfaktor angibt. Der Standardwert ist 1,0. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Veraltet. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | Legt fest, ob während des Druckens im Dateimodus die Umwandlung einer PDF‑Seite in eine Zwischen‑PNG‑Datei verwendet wird. Verwenden Sie dies, wenn die Größe der Ausgabedatei wichtig ist. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Setzt einen Wert, der die vertikale Ausrichtung angibt |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

Fügt das Abonnement für das Druckereignis der letzten Seite hinzu/entfernt es.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

Fügt das Abonnement für das Druckereignis der letzten Seite hinzu/entfernt es.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

Initialisiert ein neues {@code PdfViewer}-Objekt.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
Initialisiert ein neues {@code PdfViewer}-Objekt.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.io.InputStream-}
Initialisiert die Fassade.

### bindPdf {#bindPdf-java.lang.String-}
Initialisiert die Fassade.

### close {#close--}
```
public void close()
```

Schließt die aktuelle PDF-Datei.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

Schließt die aktuelle PDF-Datei.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

Liefert die Seiten der aktuellen PDF-Datei.

**Returns:**
Gibt das Array von PDF‑Seitenbildern zurück.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

Dekodiert eine Seite einer PDF-Datei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Die Seitennummer einer PDF‑Datei, die zwischen 1 und PageCount liegen muss. |

**Returns:**
Gibt das PDF‑Seitenbild zurück.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
Dekodiert die Seite zu einem BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Gibt die Ressourcen der Fassade frei. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

Setzt einen booleschen Wert, der angibt, ob die Datei mit optimierter Größe gedruckt werden soll.

**Returns:**
Boolescher Wert: Wenn false, wird die Seite ohne Skalierung gedruckt. Wenn true, wird die Seite mit Skalierung gedruckt, um in den druckbaren Bereich zu passen.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

Liefert einen booleschen Wert, der angibt, ob die Datei mit automatischer Drehung gedruckt werden soll.

**Returns:**
boolescher Wert

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

Liefert einen AutoRotateMode-Wert, der die Drehrichtung angibt.

**Returns:**
AutoRotateMode‑Element @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Ermittelt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet.

**Returns:**
PageCoordinateType-Element @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

Liefert die gedruckten Kopien.

**Returns:**
int-Wert

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Liefert die standardmäßigen Seiteneinstellungen.

**Returns:**
Seiten‑Einstellungsobjekt.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

Liefert die standardmäßigen Druckereinstellungen.

**Returns:**
Seiten‑Einstellungsobjekt.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Liefert den Formularpräsentationsmodus.

**Returns:**
FormPresentationMode-Element @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Liefert einen Wert, der die horizontale Ausrichtung angibt.

**Returns:**
HorizontalAlignment‑Element @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Liefert die Seitenanzahl der aktuellen PDF-Datei.

**Returns:**
Gibt die Seitenanzahl zurück.

### getPassword {#getPassword--}
```
public String getPassword()
```

Liefert das Passwort des Eingabedokuments.

**Returns:**
String Wert

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> Liefert oder setzt einen booleschen Wert, der angibt, ob die Seite in Graustufen gedruckt wird. Standardmäßig ist false. </p> <hr> Standard false ist false.

**Returns:**
boolescher Wert

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> Erhält einen Modus für PdfViewer, um als Bild zu drucken. </p>

**Returns:**
boolescher Wert <hr> Wenn true, wird immer als Bild gedruckt (generiert ein Bild, das gedruckt wird). Wenn false, wird direkt an das Gerät gedruckt, wenn alle Funktionen unterstützt werden. Falls das Dokument nicht unterstützte Funktionen enthält, kann das System automatisch entscheiden, als Bild zu drucken. Der Standardwert ist false.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

Ermittelt den Namen des Dokuments in der Druckwarteschlange, wenn das Dokument gedruckt wird. Der Standardwert ist der Dateiname.

**Returns:**
String Wert

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

Ermittelt einen booleschen Wert, der angibt, ob der Seitenzahl-Dialog beim Drucken erzeugt wird.

**Returns:**
boolescher Wert

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

Ermittelt das Ergebnis des Druckauftrags. Bei Erfolg null; andernfalls ein Ausnahmeobjekt.

**Returns:**
Ausnahmeobjekt oder null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Ruft Rendering-Optionen ab.

**Returns:**
RenderingOptions-Objekt

### getResolution {#getResolution--}
```
public int getResolution()
```

Ermittelt oder setzt die Auflösung während der Anzeige und des Druckens. Je höher die Auflösung, desto langsamer die Geschwindigkeit. Der Standardwert ist 150. Diese Eigenschaft ändert die Bildauflösung in den Konvertierungsabläufen von Seite zu Bild: wenn {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) auf {@code } gesetzt ist, oder wenn die Methode {@link #decodePage(int)} oder {@link #decodeAllPages} aufgerufen wird. Um eine Druckerauflösung für das direkte Drucken auf einen Drucker festzulegen, verwenden Sie die Eigenschaft {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) in der Klasse {@code PageSettings}.

**Returns:**
int-Wert

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

Ermittelt einen Gleitkommawert, der den Skalierungsfaktor angibt. Der Standardwert ist 1,0.

**Returns:**
Gleitkommawert.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

Ermittelt die Verwendung der Konvertierung einer pdf-Seite in eine Zwischen-PNG-Datei während des Druckens im Dateimodus. Verwenden Sie sie, wenn die Größe der Ausgabedatei wichtig ist.

**Returns:**
boolescher Wert.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Ermittelt einen Wert, der die vertikale Ausrichtung angibt

**Returns:**
VerticalAlignment Element @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Diese Methode ist veraltet. Ermittelt das Flag, das die Sichtbarkeit versteckter Bereiche auf der Seite steuert.

**Returns:**
boolescher Wert

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Öffnet einen Pdf-Dateistream. Decodiert jedoch nicht die Seiten der Pdf-Datei. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Öffnet eine Pdf-Datei, decodiert jedoch nicht die Seiten der Pdf-Datei. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> Druckt das Pdf-Dokument mit dem Standarddrucker. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //druckt die Datei mit angepasster Größe viewer.setAutoRotate ( true); //druckt die Datei mit angepasster Drehung viewer.setPrintPageDialog ( false); //erstellt keinen Seitenzahl-Dialog beim Drucken viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Druckt das Pdf-Dokument mit Druckereinstellungen. Die Ausgabeseitengröße passt sich an die Größe der ersten Seite des Dokuments an. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //druckt die Datei mit angepasster Größe viewer.setAutoRotate ( true); //druckt die Datei mit angepasster Drehung viewer.setPrintPageDialog ( false); //erstellt keinen Seitenzahl-Dialog beim Drucken PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Druckt das Pdf-Dokument mit Einstellungen. Wenn die Dokumentgröße nicht zur Seitengröße passt, erweitert pdf.kit sie, um zur Seitengröße zu passen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //druckt die Datei mit angepasster Größe viewer.setAutoRotate ( true); //druckt die Datei mit angepasster Drehung viewer.setPrintPageDialog ( false);//erstellt keinen Seitenzahl-Dialog beim Drucken PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> Öffnet und druckt einen großen Pdf‑Strom. Wenn Ihre Pdf‑Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@\"d:\\test.pdf\"))); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und das Drucken der Datei, sodass Sie die OpenPdfFile() nicht explizit aufrufen müssen.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Öffnet und druckt einen großen Pdf‑Strom mit angegebenen Druckereinstellungen. Wenn Ihre Pdf‑Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream(\"d:\\\\middleware.pdf\"), ps); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und das Drucken der Datei, sodass Sie die OpenPdfFile() nicht explizit aufrufen müssen.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Öffnet und druckt einen großen Pdf‑Strom mit angegebenen Seiteneinstellungen und Druckereinstellungen. Wenn Ihre Pdf‑Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um eine bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize(\"A4\", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream(\"d:\\\\middleware.pdf\"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und das Drucken der Datei, sodass Sie die OpenPdfFile() nicht explizit aufrufen müssen.

### printLargePdf {#printLargePdf-java.lang.String-}
<p> Öffnet und druckt eine große Pdf-Datei. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf(\"d:\\test.pdf\"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Öffnet und druckt eine große Pdf-Datei mit angegebenen Druckereinstellungen. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(\"d:\\\\test.pdf\",ps); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und Drucken der Datei, sodass Sie OpenPdfFile() nicht explizit aufrufen müssen.

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Öffnet und druckt eine große Pdf-Datei mit angegebenen Seiteneinstellungen und Druckereinstellungen. Wenn Ihre Pdf-Datei Hunderte von Seiten oder mehr hat oder ihre Größe mehr als 3 MB beträgt, wird diese Methode empfohlen, um bessere Leistung zu erzielen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize(\"A4\", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf(\"d:\\\\test.pdf\", pgs, ps); viewer.closePdfFile(); </pre> <hr> Diese Methode integriert das Öffnen und Drucken der Datei, sodass Sie OpenPdfFile() nicht explizit aufrufen müssen.

### save {#save-java.io.InputStream-}
Speichert das resultierende PDF-Dokument in einen Stream.

### save {#save-java.lang.String-}
Speichert das resultierende PDF-Dokument in einer Datei.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

Setzt einen booleschen Wert, der angibt, ob die Datei mit optimierter Größe gedruckt werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Boolescher Wert: Wenn false, wird die Seite ohne Skalierung gedruckt. Wenn true, wird die Seite mit Skalierung gedruckt, um in den druckbaren Bereich zu passen. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

Setzt einen booleschen Wert, der angibt, ob die Datei automatisch rotiert gedruckt werden soll

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

Setzt einen AutoRotateMode-Wert, der die Drehrichtung angibt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | AutoRotateMode‑Element @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Setzt den Seitencoordinate-Typ (Media-/Crop-Boxen). Der CropBox-Wert wird standardmäßig verwendet.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Setzt den Formular-Präsentationsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | FormPresentationMode-Element |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Setzt einen Wert, der die horizontale Ausrichtung angibt

### setPassword {#setPassword-java.lang.String-}
Setzt das Passwort des Eingabedokuments.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> Liefert oder setzt einen booleschen Wert, der angibt, ob die Seite in Graustufen gedruckt wird. Standardmäßig ist false. </p> <hr> Standard false ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> Setzt einen Modus für PdfViewer, um als Bild zu drucken. </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert <hr> Wenn true, wird immer als Bild gedruckt (generiert ein Bild, das gedruckt wird). Wenn false, wird direkt an das Gerät gedruckt, wenn alle Funktionen unterstützt werden. Falls das Dokument nicht unterstützte Funktionen enthält, kann das System automatisch entscheiden, als Bild zu drucken. Der Standardwert ist false. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
Setzt den Namen des Dokuments in der Druckwarteschlange, wenn das Dokument gedruckt wird. Der Standardwert ist der Dateiname.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

Setzt einen booleschen Wert, der angibt, ob beim Drucken der Seitenzahl‑Dialog erzeugt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Setzt Rendering-Optionen.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Setzt die Auflösung während der Anzeige und des Druckens. Je höher die Auflösung, desto langsamer die Geschwindigkeit. Der Standardwert ist 150. Diese Eigenschaft ändert die Bildauflösung in den Page‑to‑Image‑Konvertierungsabläufen: wenn {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) auf {@code } gesetzt ist, oder wenn die Methode {@link #decodePage(int)} oder {@link #decodeAllPages} aufgerufen wird. Um eine Druckerauflösung für den Direktdruck auf einen Drucker festzulegen, verwenden Sie die {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)})‑Eigenschaft in der {@code PageSettings}-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

Setzt einen Gleitkommawert, der den Skalierungsfaktor angibt. Der Standardwert ist 1,0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Gleitkommawert. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Veraltet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

Legt fest, ob während des Druckens im Dateimodus die Umwandlung einer PDF‑Seite in eine Zwischen‑PNG‑Datei verwendet wird. Verwenden Sie dies, wenn die Größe der Ausgabedatei wichtig ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Setzt einen Wert, der die vertikale Ausrichtung angibt
