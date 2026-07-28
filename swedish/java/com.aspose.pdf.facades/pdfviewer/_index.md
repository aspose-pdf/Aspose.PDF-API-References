---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att visa eller skriva ut en pdf."
type: docs
weight: 610
url: /sv/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

Representerar en klass för att visa eller skriva ut en pdf.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | Lägger till/ta bort prenumeration på utskrifts‑händelsen för sista sidan. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Lägger till/ta bort prenumeration på utskrifts‑händelsen för sista sidan. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfViewer](#PdfViewer--) | Initierar ett nytt {@code PdfViewer}-objekt. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | Initierar ett nytt {@code PdfViewer}-objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.lang.String-) | Initierar fasaden. |
| [close](#close--) | Stänger den aktuella Pdf‑filen. |
| [closePdfFile](#closePdfFile--) | Stänger den aktuella Pdf‑filen. |
| [decodeAllPages](#decodeAllPages--) | Hämta sidor från den aktuella pdf‑filen. |
| [decodePage](#decodePage-int-) | Avkodar en sida i en Pdf‑fil. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Avkodar sida till BufferedImage |
| [dispose](#dispose--) | Frigör fasadens resurser. Denna metod är föråldrad, använd close() istället. |
| [getAutoResize](#getAutoResize--) | Ställer in ett booleskt värde som indikerar om filen ska skrivas ut med optimerad storlek. |
| [getAutoRotate](#getAutoRotate--) | Hämtar ett booleskt värde som indikerar om filen ska skrivas ut med automatisk rotation |
| [getAutoRotateMode](#getAutoRotateMode--) | Hämtar ett AutoRotateMode‑värde som indikerar rotationsriktning |
| [getCoordinateType](#getCoordinateType--) | Hämtar sidans koordinattyp (Media-/Crop-boxar). CropBox-värdet används som standard. |
| [getCopiesPrinted](#getCopiesPrinted--) | Hämtar antal utskrivna kopior |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Hämtar standardinställningarna för sidan. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | Hämtar standardinställningarna för skrivaren. |
| [getFormPresentationMode](#getFormPresentationMode--) | Hämtar formulärpresentationsläge. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Hämtar ett värde som indikerar horisontell justering |
| [getPageCount](#getPageCount--) | Hämtar sidantalet för den aktuella Pdf‑filen. |
| [getPassword](#getPassword--) | Hämtar lösenordet för inmatningsdokumentet. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> Hämtar eller anger ett booleskt värde som indikerar om sidan skrivs ut i gråskala. Standard är falskt. </p> <hr> Standard falskt är falskt. |
| [getPrintAsImage](#getPrintAsImage--) | <p> Hämtar ett läge för PdfViewer att skriva ut som bild. </p> |
| [getPrinterJobName](#getPrinterJobName--) | Hämtar dokumentets namn i skrivarens kö när dokumentet skrivs ut. Standardvärdet är filnamnet. |
| [getPrintPageDialog](#getPrintPageDialog--) | Hämtar ett booleskt värde som indikerar om sidnumreringsdialogen ska visas vid utskrift. |
| [getPrintStatus](#getPrintStatus--) | Hämtar resultatet av utskriftsjobbet. Om lyckat är null; annars ett undantagsobjekt. |
| [getRenderingOptions](#getRenderingOptions--) | Hämtar renderingsalternativ. |
| [getResolution](#getResolution--) | Hämtar eller anger upplösning vid visning och utskrift. Ju högre upplösning, desto långsammare hastighet. Standardvärdet är 150. Denna egenskap ändrar bildens upplösning i konverteringsflöden från sida till bild: när {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) är satt till {@code }, eller när {@link #decodePage(int)} eller {@link #decodeAllPages} metoden anropas. För att ange en skrivarupplösning för direkt utskrift till en skrivare, använd {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) egenskapen i {@code PageSettings} klassen. |
| [getScaleFactor](#getScaleFactor--) | Hämtar ett flyttal som indikerar skalningsfaktor. Standardvärdet är 1.0. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | Hämtar användningen av konvertering av pdf-sida till en mellanliggande png-fil under utskrift i filläge. Använd den när storleken på utdatafilen är viktig. |
| [getVerticalAlignment](#getVerticalAlignment--) | Hämtar ett värde som indikerar vertikal justering |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Denna metod är föråldrad. Hämtar flagga som styr synligheten för dolda områden på sidan. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Öppnar en Pdf-filström. Men avkodar inte faktiskt sidorna i Pdf-filen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Öppnar en Pdf-fil, men avkodar inte faktiskt sidorna i Pdf-filen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> Skriver ut Pdf-dokumentet med standardskrivare. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //skriv filen med justerad storlek viewer.setAutoRotate ( true); //skriv filen med justerad rotation viewer.setPrintPageDialog ( false); //visa inte sidnumreringsdialogen vid utskrift viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Skriver ut Pdf-dokumentet med skrivarinställningar. Utskrifts sidstorlek kommer att anpassas till dokumentets första sidstorlek. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //skriv filen med justerad storlek viewer.setAutoRotate ( true); //skriv filen med justerad rotation viewer.setPrintPageDialog ( false); //visa inte sidnumreringsdialogen vid utskrift PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Skriver ut PDF-dokumentet med inställningar. Om dokumentets storlek inte är kompatibel med sidstorleken, kommer pdf.kit att utöka den för att passa sidstorleken. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //skriv ut filen med justerad storlek viewer.setAutoRotate ( true); //skriv ut filen med justerad rotation viewer.setPrintPageDialog ( false);//visa inte sidnumreringsdialogen vid utskrift PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> Öppnar och skriver ut en stor PDF-ström. Om din PDF-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //skriv ut filen med justerad storlek viewer.setAutoRotate ( true); //skriv ut filen med justerad rotation viewer.printPageDialog=false;//visa inte sidnumreringsdialogen vid utskrift viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Öppnar och skriver ut en stor PDF-ström med angivna skrivarinställningar. Om din PDF-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // skriv ut filen med justerad storlek viewer.setAutoRotate(true); // skriv ut filen med justerad rotation viewer.setPrintPageDialog(false); // visa inte sidnumreringsdialogen när // utskrift PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Öppnar och skriver ut en stor Pdf‑ström med angivna sidinställningar och skrivarinställningar. Om din Pdf‑fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //skriv ut filen med justerad storlek viewer.setAutoRotate ( true); //skriv ut filen med justerad rotation viewer.setPrintPageDialog ( false);//visa inte sidnummerdialogen när utskrift PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit. |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> Öppnar och skriver ut en stor Pdf‑fil. Om din Pdf‑fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); //skriv ut filen med justerad storlek viewer.setAutoRotate(true); //skriv ut filen med justerad rotation viewer.setPrintPageDialog(false);//visa inte sidnummerdialogen när //utskrift viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Öppnar och skriver ut en stor Pdf‑fil med angivna skrivarinställningar. Om din Pdf‑fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //skriv ut filen med justerad storlek viewer.setAutoRotate ( true); //skriv ut filen med justerad rotation viewer.setPrintPageDialog ( false);//visa inte sidnummerdialogen när utskrift PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit. |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Öppnar och skriver ut en stor Pdf-fil med angivna sidinställningar och skrivarinställningar. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit. |
| [save](#save-java.io.InputStream-) | Sparar det resulterande PDF-dokumentet till en ström. |
| [save](#save-java.lang.String-) | Sparar det resulterande PDF-dokumentet till en fil. |
| [setAutoResize](#setAutoResize-boolean-) | Ställer in ett booleskt värde som indikerar om filen ska skrivas ut med optimerad storlek. |
| [setAutoRotate](#setAutoRotate-boolean-) | Ställer in ett booleskt värde som indikerar om filen ska skrivas ut med automatisk rotation |
| [setAutoRotateMode](#setAutoRotateMode-int-) | Ställer in ett AutoRotateMode‑värde som indikerar rotationsriktning |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Ställer in formulärets presentationsläge. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Ställer in ett värde som indikerar horisontell justering |
| [setPassword](#setPassword-java.lang.String-) | Ställer in lösenord för inmatningsdokumentet. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> Hämtar eller anger ett booleskt värde som indikerar om sidan skrivs ut i gråskala. Standard är falskt. </p> <hr> Standard falskt är falskt. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> Ställer in ett läge för PdfViewer att skriva ut som bild. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | Ställer in namn på dokumentet i skrivarens kö när dokumentet skrivs ut. Standardvärdet är filnamnet. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | Ställer in ett booleskt värde som indikerar om sidnumreringsdialogen ska visas vid utskrift. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Ställer in renderingsalternativ. |
| [setResolution](#setResolution-int-) | Ställer in upplösning vid visning och utskrift. Högre upplösning ger långsammare hastighet. Standardvärdet är 150. Denna egenskap ändrar bildupplösningen i flöden för sid‑till‑bild‑konvertering: när {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) är satt till {@code }, eller när {@link #decodePage(int)} eller {@link #decodeAllPages}-metoden anropas. För att ange en skrivarupplösning för direkt utskrift till en skrivare, använd {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)})‑egenskapen i {@code PageSettings}-klassen. |
| [setScaleFactor](#setScaleFactor-float-) | Ställer in ett flyttal som indikerar skalningsfaktor. Standardvärdet är 1,0. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Föråldrad. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | Ställer in användning av konvertering av pdf-sida till en mellanliggande png‑fil vid utskrift i filläge. Använd detta när storleken på utdatafilen är viktig. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ställer in ett värde som indikerar vertikal justering |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

Lägger till/ta bort prenumeration på utskrifts‑händelsen för sista sidan.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

Lägger till/ta bort prenumeration på utskrifts‑händelsen för sista sidan.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

Initierar ett nytt {@code PdfViewer}-objekt.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
Initierar ett nytt {@code PdfViewer}-objekt.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initierar fasaden.

### bindPdf {#bindPdf-java.io.InputStream-}
Initierar fasaden.

### bindPdf {#bindPdf-java.lang.String-}
Initierar fasaden.

### close {#close--}
```
public void close()
```

Stänger den aktuella Pdf‑filen.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

Stänger den aktuella Pdf‑filen.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

Hämta sidor från den aktuella pdf‑filen.

**Returns:**
returnerar en array av Pdf‑sidbilder.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

Avkodar en sida i en Pdf‑fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Sidnumret för en Pdf‑fil som måste vara mellan 1 och PageCount. |

**Returns:**
returnerar Pdf‑sidbilden.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
Avkodar sida till BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Frigör fasadens resurser. Denna metod är föråldrad, använd close() istället.

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

Ställer in ett booleskt värde som indikerar om filen ska skrivas ut med optimerad storlek.

**Returns:**
booleskt värde: Om false skrivs sidan utan skalning. Om true skrivs sidan med skalning för att passa utskriftsområdet.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

Hämtar ett booleskt värde som indikerar om filen ska skrivas ut med automatisk rotation

**Returns:**
booleskt värde

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

Hämtar ett AutoRotateMode‑värde som indikerar rotationsriktning

**Returns:**
AutoRotateMode‑element @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Hämtar sidans koordinattyp (Media-/Crop-boxar). CropBox-värdet används som standard.

**Returns:**
PageCoordinateType-element @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

Hämtar antal utskrivna kopior

**Returns:**
int‑värde

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Hämtar standardinställningarna för sidan.

**Returns:**
Sidinställningsobjekt.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

Hämtar standardinställningarna för skrivaren.

**Returns:**
Sidinställningsobjekt.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Hämtar formulärpresentationsläge.

**Returns:**
FormPresentationMode-element @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Hämtar ett värde som indikerar horisontell justering

**Returns:**
HorizontalAlignment-element @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Hämtar sidantalet för den aktuella Pdf‑filen.

**Returns:**
returnerar sidantal.

### getPassword {#getPassword--}
```
public String getPassword()
```

Hämtar lösenordet för inmatningsdokumentet.

**Returns:**
String värde

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> Hämtar eller anger ett booleskt värde som indikerar om sidan skrivs ut i gråskala. Standard är falskt. </p> <hr> Standard falskt är falskt.

**Returns:**
booleskt värde

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> Hämtar ett läge för PdfViewer att skriva ut som bild. </p>

**Returns:**
booleskt värde <hr> Om true skrivs alltid som bild (genererar en bild som skrivs ut) Om false skrivs direkt till enhet om alla funktioner stöds. Om dokumentet innehåller funktioner som inte stöds kan systemet automatiskt besluta att skriva ut som bild. Standardvärdet är false.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

Hämtar dokumentets namn i skrivarens kö när dokumentet skrivs ut. Standardvärdet är filnamnet.

**Returns:**
String värde

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

Hämtar ett booleskt värde som indikerar om sidnumreringsdialogen ska visas vid utskrift.

**Returns:**
booleskt värde

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

Hämtar resultatet av utskriftsjobbet. Om lyckat är null; annars ett undantagsobjekt.

**Returns:**
undantagsobjekt eller null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Hämtar renderingsalternativ.

**Returns:**
RenderingOptions‑objekt

### getResolution {#getResolution--}
```
public int getResolution()
```

Hämtar eller anger upplösning vid visning och utskrift. Ju högre upplösning, desto långsammare hastighet. Standardvärdet är 150. Denna egenskap ändrar bildens upplösning i konverteringsflöden från sida till bild: när {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) är satt till {@code }, eller när {@link #decodePage(int)} eller {@link #decodeAllPages} metoden anropas. För att ange en skrivarupplösning för direkt utskrift till en skrivare, använd {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) egenskapen i {@code PageSettings} klassen.

**Returns:**
int‑värde

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

Hämtar ett flyttal som indikerar skalningsfaktor. Standardvärdet är 1.0.

**Returns:**
flyttal.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

Hämtar användningen av konvertering av pdf-sida till en mellanliggande png-fil under utskrift i filläge. Använd den när storleken på utdatafilen är viktig.

**Returns:**
booleskt värde.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Hämtar ett värde som indikerar vertikal justering

**Returns:**
VerticalAlignment-element @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Denna metod är föråldrad. Hämtar flagga som styr synligheten för dolda områden på sidan.

**Returns:**
booleskt värde

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Öppnar en Pdf-filström. Men avkodar faktiskt inte sidorna i Pdf-filen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Öppnar en Pdf-fil, men avkodar faktiskt inte sidorna i Pdf-filen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> Skriver ut Pdf-dokumentet med standardskrivare. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //skriv ut filen med justerad storlek viewer.setAutoRotate ( true); //skriv ut filen med justerad rotation viewer.setPrintPageDialog ( false); //visa inte sidnummerdialogen vid utskrift viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Skriver ut Pdf-dokumentet med skrivarinställningar. Utskriftssidans storlek kommer att anpassas till dokumentets första sidstorlek. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //skriv ut filen med justerad storlek viewer.setAutoRotate ( true); //skriv ut filen med justerad rotation viewer.setPrintPageDialog ( false); //visa inte sidnummerdialogen vid utskrift PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Skriver ut Pdf-dokumentet med inställningar. Om dokumentets storlek inte är kompatibel med sidstorleken, kommer pdf.kit att utöka den för att passa sidstorleken. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //skriv ut filen med justerad storlek viewer.setAutoRotate ( true); //skriv ut filen med justerad rotation viewer.setPrintPageDialog ( false);//visa inte sidnummerdialogen vid utskrift PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> Öppnar och skriver ut en stor Pdf-ström. Om din Pdf-fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //skriv ut filen med justerad storlek viewer.setAutoRotate ( true); //skriv ut filen med justerad rotation viewer.printPageDialog=false;//visa inte sidnummerdialogen vid utskrift viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Öppnar och skriver ut en stor Pdf-ström med angivna skrivarinställningar. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Öppnar och skriver ut en stor Pdf-ström med angivna sidinställningar och skrivarinställningar. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit.

### printLargePdf {#printLargePdf-java.lang.String-}
<p> Öppnar och skriver ut en stor Pdf-fil. Om din Pdf-fil har hundratals sidor eller fler eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\test.pdf"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Öppnar och skriver ut en stor Pdf‑fil med angivna skrivarinställningar. Om din Pdf‑fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //skriv ut filen med justerad storlek viewer.setAutoRotate ( true); //skriv ut filen med justerad rotation viewer.setPrintPageDialog ( false);//visa inte sidnumreringsdialogen vid utskrift PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit.

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Öppnar och skriver ut en stor Pdf‑fil med angivna sidinställningar och skrivarinställningar. Om din Pdf‑fil har hundratals sidor eller mer eller dess storlek är mer än 3 MB, rekommenderas denna metod för att få bättre prestanda. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // skriv ut filen med justerad storlek viewer.setAutoRotate(true); // skriv ut filen med justerad rotation viewer.setPrintPageDialog(false); // visa inte sidnumreringsdialogen vid utskrift // utskrift PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Denna metod har integrerat öppning och utskrift av filen och du behöver inte anropa OpenPdfFile() explicit.

### save {#save-java.io.InputStream-}
Sparar det resulterande PDF-dokumentet till en ström.

### save {#save-java.lang.String-}
Sparar det resulterande PDF-dokumentet till en fil.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

Ställer in ett booleskt värde som indikerar om filen ska skrivas ut med optimerad storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde: Om false skrivs sidan utan skalning. Om true skrivs sidan med skalning för att passa utskriftsområdet. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

Ställer in ett booleskt värde som indikerar om filen ska skrivas ut med automatisk rotation

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

Ställer in ett AutoRotateMode‑värde som indikerar rotationsriktning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | AutoRotateMode‑element @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Ställer in sidkoordinattypen (Media/Crop-boxar). CropBox-värdet används som standard.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Ställer in formulärets presentationsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | FormPresentationMode‑element |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Ställer in ett värde som indikerar horisontell justering

### setPassword {#setPassword-java.lang.String-}
Ställer in lösenord för inmatningsdokumentet.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> Hämtar eller anger ett booleskt värde som indikerar om sidan skrivs ut i gråskala. Standard är falskt. </p> <hr> Standard falskt är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> Ställer in ett läge för PdfViewer att skriva ut som bild. </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde <hr> Om true skrivs alltid som bild (genererar en bild som skrivs ut) Om false skrivs direkt till enhet om alla funktioner stöds. Om dokumentet innehåller funktioner som inte stöds kan systemet automatiskt besluta att skriva ut som bild. Standardvärdet är false. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
Ställer in namn på dokumentet i skrivarens kö när dokumentet skrivs ut. Standardvärdet är filnamnet.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

Ställer in ett booleskt värde som indikerar om sidnumreringsdialogen ska visas vid utskrift.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Ställer in renderingsalternativ.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Ställer in upplösning vid visning och utskrift. Högre upplösning ger långsammare hastighet. Standardvärdet är 150. Denna egenskap ändrar bildupplösningen i flöden för sid‑till‑bild‑konvertering: när {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) är satt till {@code }, eller när {@link #decodePage(int)} eller {@link #decodeAllPages}-metoden anropas. För att ange en skrivarupplösning för direkt utskrift till en skrivare, använd {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)})‑egenskapen i {@code PageSettings}-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

Ställer in ett flyttal som indikerar skalningsfaktor. Standardvärdet är 1,0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttal. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Föråldrad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

Ställer in användning av konvertering av pdf-sida till en mellanliggande png‑fil vid utskrift i filläge. Använd detta när storleken på utdatafilen är viktig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ställer in ett värde som indikerar vertikal justering
