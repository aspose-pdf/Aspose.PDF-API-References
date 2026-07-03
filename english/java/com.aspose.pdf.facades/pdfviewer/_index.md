---
title: PdfViewer
second_title: Aspose.PDF for Java API Reference
description: Represents a class to view or print a pdf.
type: docs
weight: 610
url: /java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

Represents a class to view or print a pdf.

## Fields

| Field | Description |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | Adds/removes subscription on the last page printing event. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Adds/removes subscription on the last page printing event. |

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfViewer](#PdfViewer--) | Initializes new {@code PdfViewer} object. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | Initializes new {@code PdfViewer} object. |

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.lang.String-) | Initializes the facade. |
| [close](#close--) | Closes the current Pdf file. |
| [closePdfFile](#closePdfFile--) | Closes the current Pdf file. |
| [decodeAllPages](#decodeAllPages--) | Get pages of current pdf file. |
| [decodePage](#decodePage-int-) | Decodes a page of one Pdf file. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Decodes page to BufferedImage |
| [dispose](#dispose--) | Disposes the facade resources. This method is obsolete, use close() instead. |
| [getAutoResize](#getAutoResize--) | Sets a bool value that indicates whether the file be printed with optimized size. |
| [getAutoRotate](#getAutoRotate--) | Gets a bool value that indicates whether the file be printed with auto rotation |
| [getAutoRotateMode](#getAutoRotateMode--) | Gets an AutoRotateMode value that indicates direction of rotation |
| [getCoordinateType](#getCoordinateType--) | Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [getCopiesPrinted](#getCopiesPrinted--) | Gets copies printed |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Gets the default page settings. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | Gets the default printer settings. |
| [getFormPresentationMode](#getFormPresentationMode--) | Gets form presentation mode. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Gets a value that indicates horizontal alignment |
| [getPageCount](#getPageCount--) | Gets page count of the current Pdf file. |
| [getPassword](#getPassword--) | Gets input document password. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> Gets or sets a bool value that indicates whether the page is being printed as grayscale. By default is false. </p> <hr> Default false is false. |
| [getPrintAsImage](#getPrintAsImage--) | <p> Gets a mode for PdfViewer to print as image. </p> |
| [getPrinterJobName](#getPrinterJobName--) | Gets name of document in printer queue when document is printed. Default value is file name. |
| [getPrintPageDialog](#getPrintPageDialog--) | Gets a bool value that indicates whether produce the page number dialog when printing. |
| [getPrintStatus](#getPrintStatus--) | Gets the result of printing job. If success than null; otherwise, exception object. |
| [getRenderingOptions](#getRenderingOptions--) | Gets rendering options. |
| [getResolution](#getResolution--) | Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150. This property changes the image resolution in page-to-image conversion flows: when the {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) is set to {@code }, or when {@link #decodePage(int)} or {@link #decodeAllPages} method is called. To set a printer resolution for direct printing to a printer, use the {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) property in the {@code PageSettings} class. |
| [getScaleFactor](#getScaleFactor--) | Gets a floating point value that indicates scale factor. The default value is 1.0. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | Gets the using of conversion of pdf page into intermidiate png file during printing in file mode. Use it when the size of output file is important. |
| [getVerticalAlignment](#getVerticalAlignment--) | Gets a value that indicates vertical alignment |
| [isShowHiddenAreas](#isShowHiddenAreas--) | This method is Deprecated Gets flag that controls visibility of hidden areas on the page. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Opens a Pdf file stream. But does not actually decode the pages of the Pdf file. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Opens a Pdf file, but does not actually decode the pages of the Pdf file. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> Prints the Pdf document using default printer. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Prints the Pdf document with printer settings. The output page size will fit the the document first page size. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Prints the Pdf document with settings. If the document size is not complatible to page size, pdf.kit will extend it to fit page size. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> Opens and prints a large Pdf stream. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Opens and prints a large Pdf stream with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Opens and prints a large Pdf stream with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly. |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Opens and prints a large Pdf file with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly. |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Opens and prints a large Pdf file with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly. |
| [save](#save-java.io.InputStream-) | Saves the result PDF document to stream. |
| [save](#save-java.lang.String-) | Saves the result PDF document to file. |
| [setAutoResize](#setAutoResize-boolean-) | Sets a bool value that indicates whether the file be printed with optimized size. |
| [setAutoRotate](#setAutoRotate-boolean-) | Sets a bool value that indicates whether the file be printed with auto rotation |
| [setAutoRotateMode](#setAutoRotateMode-int-) | Sets an AutoRotateMode value that indicates direction of rotation |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Sets form presentation mode. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets a value that indicates horizontal alignment |
| [setPassword](#setPassword-java.lang.String-) | Sets input document password. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> Gets or sets a bool value that indicates whether the page is being printed as grayscale. By default is false. </p> <hr> Default false is false. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> Sets a mode for PdfViewer to print as image. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | Sets name of document in printer queue when document is printed. Default value is file name. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | Sets a boolean value that indicates whether produce the page number dialog when printing. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Sets rendering options. |
| [setResolution](#setResolution-int-) | Sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150. This property changes the image resolution in page-to-image conversion flows: when the {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) is set to {@code }, or when {@link #decodePage(int)} or {@link #decodeAllPages} method is called. To set a printer resolution for direct printing to a printer, use the {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) property in the {@code PageSettings} class. |
| [setScaleFactor](#setScaleFactor-float-) | Sets a floating point value that indicates scale factor. The default value is 1.0. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Deprecated. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | Sets the using of conversion of pdf page into intermidiate png file during printing in file mode. Use it when the size of output file is important. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets a value that indicates vertical alignment |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

Adds/removes subscription on the last page printing event.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

Adds/removes subscription on the last page printing event.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

Initializes new {@code PdfViewer} object.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
Initializes new {@code PdfViewer} object.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initializes the facade.

### bindPdf {#bindPdf-java.io.InputStream-}
Initializes the facade.

### bindPdf {#bindPdf-java.lang.String-}
Initializes the facade.

### close {#close--}
```
public void close()
```

Closes the current Pdf file.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

Closes the current Pdf file.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

Get pages of current pdf file.

**Returns:**
return the array of Pdf page images.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

Decodes a page of one Pdf file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber |  | The page number of one Pdf file which must be between 1 and PageCount. |

**Returns:**
return the Pdf page image.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
Decodes page to BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Disposes the facade resources. This method is obsolete, use close() instead.

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

Sets a bool value that indicates whether the file be printed with optimized size.

**Returns:**
boolean value: If false print page without page scaling. If true print page with scaling to fit to printable area.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

Gets a bool value that indicates whether the file be printed with auto rotation

**Returns:**
boolean value

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

Gets an AutoRotateMode value that indicates direction of rotation

**Returns:**
AutoRotateMode element @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Returns:**
PageCoordinateType element @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

Gets copies printed

**Returns:**
int value

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Gets the default page settings.

**Returns:**
Page settings object.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

Gets the default printer settings.

**Returns:**
Page settings object.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Gets form presentation mode.

**Returns:**
FormPresentationMode element @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Gets a value that indicates horizontal alignment

**Returns:**
HorizontalAlignment element @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Gets page count of the current Pdf file.

**Returns:**
return page count.

### getPassword {#getPassword--}
```
public String getPassword()
```

Gets input document password.

**Returns:**
String value

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> Gets or sets a bool value that indicates whether the page is being printed as grayscale. By default is false. </p> <hr> Default false is false.

**Returns:**
boolean value

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> Gets a mode for PdfViewer to print as image. </p>

**Returns:**
boolean value <hr> If true prints always as image (generates image that is printed) If false prints directly to device if all features are supported. In case document contains non-supported features the system may automatically decide to print as image. Default falue is false.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

Gets name of document in printer queue when document is printed. Default value is file name.

**Returns:**
String value

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

Gets a bool value that indicates whether produce the page number dialog when printing.

**Returns:**
boolean value

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

Gets the result of printing job. If success than null; otherwise, exception object.

**Returns:**
exception object or null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Gets rendering options.

**Returns:**
RenderingOptions object

### getResolution {#getResolution--}
```
public int getResolution()
```

Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150. This property changes the image resolution in page-to-image conversion flows: when the {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) is set to {@code }, or when {@link #decodePage(int)} or {@link #decodeAllPages} method is called. To set a printer resolution for direct printing to a printer, use the {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) property in the {@code PageSettings} class.

**Returns:**
int value

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

Gets a floating point value that indicates scale factor. The default value is 1.0.

**Returns:**
floating point value.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

Gets the using of conversion of pdf page into intermidiate png file during printing in file mode. Use it when the size of output file is important.

**Returns:**
boolean value.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Gets a value that indicates vertical alignment

**Returns:**
VerticalAlignment element @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

This method is Deprecated Gets flag that controls visibility of hidden areas on the page.

**Returns:**
boolean value

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Opens a Pdf file stream. But does not actually decode the pages of the Pdf file. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Opens a Pdf file, but does not actually decode the pages of the Pdf file. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> Prints the Pdf document using default printer. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Prints the Pdf document with printer settings. The output page size will fit the the document first page size. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Prints the Pdf document with settings. If the document size is not complatible to page size, pdf.kit will extend it to fit page size. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> Opens and prints a large Pdf stream. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf"))); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Opens and prints a large Pdf stream with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Opens and prints a large Pdf stream with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### printLargePdf {#printLargePdf-java.lang.String-}
<p> Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\test.pdf"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Opens and prints a large Pdf file with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Opens and prints a large Pdf file with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

### save {#save-java.io.InputStream-}
Saves the result PDF document to stream.

### save {#save-java.lang.String-}
Saves the result PDF document to file.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

Sets a bool value that indicates whether the file be printed with optimized size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value: If false print page without page scaling. If true print page with scaling to fit to printable area. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

Sets a bool value that indicates whether the file be printed with auto rotation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

Sets an AutoRotateMode value that indicates direction of rotation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | AutoRotateMode element @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Sets form presentation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | FormPresentationMode element |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets a value that indicates horizontal alignment

### setPassword {#setPassword-java.lang.String-}
Sets input document password.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> Gets or sets a bool value that indicates whether the page is being printed as grayscale. By default is false. </p> <hr> Default false is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> Sets a mode for PdfViewer to print as image. </p>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value <hr> If true prints always as image (generates image that is printed) If false prints directly to device if all features are supported. In case document contains non-supported features the system may automatically decide to print as image. Default falue is false. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
Sets name of document in printer queue when document is printed. Default value is file name.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

Sets a boolean value that indicates whether produce the page number dialog when printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Sets rendering options.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150. This property changes the image resolution in page-to-image conversion flows: when the {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) is set to {@code }, or when {@link #decodePage(int)} or {@link #decodeAllPages} method is called. To set a printer resolution for direct printing to a printer, use the {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) property in the {@code PageSettings} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

Sets a floating point value that indicates scale factor. The default value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | floating point value. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Deprecated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

Sets the using of conversion of pdf page into intermidiate png file during printing in file mode. Use it when the size of output file is important.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Sets a value that indicates vertical alignment
