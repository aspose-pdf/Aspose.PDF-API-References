---
title: PdfViewer
second_title: Aspose.PDF for Java API Reference
description: Represents a class to view or print a pdf.
type: docs
weight: 53
url: /java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget

**All Implemented Interfaces:**
[com.aspose.pdf.facades.IFacade](../../com.aspose.pdf.facades/ifacade)
```
public final class PdfViewer extends IVentureLicenseTarget implements IFacade
```

Represents a class to view or print a pdf.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfViewer()](#PdfViewer--) | Initializes new  PdfViewer  object. |
| [PdfViewer(IDocument document)](#PdfViewer-com.aspose.pdf.IDocument-) | Initializes new  PdfViewer  object. |
## Fields

| Field | Description |
| --- | --- |
| [EndPrint](#EndPrint) | Adds/removes subscription on the last page printing event. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Adds/removes subscription on the last page printing event. |
## Methods

| Method | Description |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Initializes the facade. |
| [close()](#close--) | Closes the current Pdf file. |
| [closePdfFile()](#closePdfFile--) | Closes the current Pdf file. |
| [decodeAllPages()](#decodeAllPages--) | Get pages of current pdf file. |
| [decodePage(int pageNumber)](#decodePage-int-) | Decodes a page of one Pdf file. |
| [decodePageToImage(int pageNumber, ImageType imageFormat)](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Decodes page to BufferedImage |
| [dispose()](#dispose--) | Disposes the facade resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoResize()](#getAutoResize--) | Sets a bool value that indicates whether the file be printed with optimized size. |
| [getAutoRotate()](#getAutoRotate--) | Gets a bool value that indicates whether the file be printed with auto rotation |
| [getAutoRotateMode()](#getAutoRotateMode--) | Gets an AutoRotateMode value that indicates direction of rotation |
| [getClass()](#getClass--) |  |
| [getCoordinateType()](#getCoordinateType--) | Gets the page coordinate type (Media/Crop boxes). |
| [getCopiesPrinted()](#getCopiesPrinted--) | Gets copies printed |
| [getDefaultPageSettings()](#getDefaultPageSettings--) | Gets the default page settings. |
| [getDefaultPrinterSettings()](#getDefaultPrinterSettings--) | Gets the default printer settings. |
| [getFormPresentationMode()](#getFormPresentationMode--) | Gets form presentation mode. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a value that indicates horizontal alignment |
| [getPageCount()](#getPageCount--) | Gets page count of the current Pdf file. |
| [getPassword()](#getPassword--) | Gets input document password. |
| [getPrintAsGrayscale()](#getPrintAsGrayscale--) | Gets or sets a bool value that indicates whether the page is being printed as grayscale. |
| [getPrintAsImage()](#getPrintAsImage--) | Gets a mode for PdfViewer to print as image. |
| [getPrintPageDialog()](#getPrintPageDialog--) | Gets a bool value that indicates whether produce the page number dialog when printing. |
| [getPrintStatus()](#getPrintStatus--) | Gets the result of printing job. |
| [getPrinterJobName()](#getPrinterJobName--) | Gets name of document in printer queue when document is printed. |
| [getRenderingOptions()](#getRenderingOptions--) | Gets rendering options. |
| [getResolution()](#getResolution--) | Gets or sets resolution during viewing and printing. |
| [getScaleFactor()](#getScaleFactor--) | Gets a floating point value that indicates scale factor. |
| [getUseIntermidiateImage()](#getUseIntermidiateImage--) | Gets the using of conversion of pdf page into intermidiate png file during printing in file mode. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a value that indicates vertical alignment |
| [hashCode()](#hashCode--) |  |
| [isShowHiddenAreas()](#isShowHiddenAreas--) | This method is Deprecated Gets flag that controls visibility of hidden areas on the page. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openPdfFile(InputStream inputStream)](#openPdfFile-java.io.InputStream-) | Opens a Pdf file stream. |
| [openPdfFile(String filePath)](#openPdfFile-java.lang.String-) | Opens a Pdf file, but does not actually decode the pages of the Pdf file. |
| [printDocument()](#printDocument--) | Prints the Pdf document using default printer. |
| [printDocumentWithSettings(PdfPrinterSettings printerSettings)](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Prints the Pdf document with printer settings. |
| [printDocumentWithSettings(PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Prints the Pdf document with settings. |
| [printLargePdf(InputStream inputStream)](#printLargePdf-java.io.InputStream-) | Opens and prints a large Pdf stream. |
| [printLargePdf(InputStream inputStream, PdfPrinterSettings printerSettings)](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | Opens and prints a large Pdf stream with specified printer settings. |
| [printLargePdf(InputStream inputStream, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Opens and prints a large Pdf stream with specified page settings and printer settings. |
| [printLargePdf(String filePath)](#printLargePdf-java.lang.String-) | Opens and prints a large Pdf file. |
| [printLargePdf(String filePath, PdfPrinterSettings printerSettings)](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | Opens and prints a large Pdf file with specified printer settings. |
| [printLargePdf(String filePath, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Opens and prints a large Pdf file with specified page settings and printer settings. |
| [save(InputStream destStream)](#save-java.io.InputStream-) | Saves the result PDF document to stream. |
| [save(String destFile)](#save-java.lang.String-) | Saves the result PDF document to file. |
| [setAutoResize(boolean value)](#setAutoResize-boolean-) | Sets a bool value that indicates whether the file be printed with optimized size. |
| [setAutoRotate(boolean value)](#setAutoRotate-boolean-) | Sets a bool value that indicates whether the file be printed with auto rotation |
| [setAutoRotateMode(int value)](#setAutoRotateMode-int-) | Sets an AutoRotateMode value that indicates direction of rotation |
| [setCoordinateType(int value)](#setCoordinateType-int-) | Sets the page coordinate type (Media/Crop boxes). |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | Sets form presentation mode. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a value that indicates horizontal alignment |
| [setPassword(String value)](#setPassword-java.lang.String-) | Sets input document password. |
| [setPrintAsGrayscale(boolean value)](#setPrintAsGrayscale-boolean-) | Gets or sets a bool value that indicates whether the page is being printed as grayscale. |
| [setPrintAsImage(boolean value)](#setPrintAsImage-boolean-) | Sets a mode for PdfViewer to print as image. |
| [setPrintPageDialog(boolean value)](#setPrintPageDialog-boolean-) | Sets a boolean value that indicates whether produce the page number dialog when printing. |
| [setPrinterJobName(String value)](#setPrinterJobName-java.lang.String-) | Sets name of document in printer queue when document is printed. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Sets rendering options. |
| [setResolution(int value)](#setResolution-int-) | Sets resolution during viewing and printing. |
| [setScaleFactor(float value)](#setScaleFactor-float-) | Sets a floating point value that indicates scale factor. |
| [setShowHiddenAreas(boolean value)](#setShowHiddenAreas-boolean-) |  |
| [setUseIntermidiateImage(boolean value)](#setUseIntermidiateImage-boolean-) | Sets the using of conversion of pdf page into intermidiate png file during printing in file mode. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a value that indicates vertical alignment |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfViewer() {#PdfViewer--}
```
public PdfViewer()
```


Initializes new  PdfViewer  object.

### PdfViewer(IDocument document) {#PdfViewer-com.aspose.pdf.IDocument-}
```
public PdfViewer(IDocument document)
```


Initializes new  PdfViewer  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document object. |

### EndPrint {#EndPrint}
```
public final PdfEvent<System.Drawing.Printing.PrintEventHandler> EndPrint
```


Adds/removes subscription on the last page printing event.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent<PdfQueryPageSettingsEventHandler> PdfQueryPageSettings
```


Adds/removes subscription on the last page printing event.

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |

### close() {#close--}
```
public void close()
```


Closes the current Pdf file.

### closePdfFile() {#closePdfFile--}
```
public void closePdfFile()
```


Closes the current Pdf file.

### decodeAllPages() {#decodeAllPages--}
```
public BufferedImage[] decodeAllPages()
```


Get pages of current pdf file.

**Returns:**
java.awt.image.BufferedImage[] - return the array of Pdf page images.
### decodePage(int pageNumber) {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```


Decodes a page of one Pdf file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The page number of one Pdf file which must be between 1 and PageCount. |

**Returns:**
java.awt.image.BufferedImage - return the Pdf page image.
### decodePageToImage(int pageNumber, ImageType imageFormat) {#decodePageToImage-int-com.aspose.pdf.ImageType-}
```
public BufferedImage decodePageToImage(int pageNumber, ImageType imageFormat)
```


Decodes page to BufferedImage

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | int value |
| imageFormat | [ImageType](../../com.aspose.pdf/imagetype) | ImageType object |

**Returns:**
java.awt.image.BufferedImage - BufferedImage value
### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade resources.

This method is obsolete, use close() instead.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoResize() {#getAutoResize--}
```
public boolean getAutoResize()
```


Sets a bool value that indicates whether the file be printed with optimized size.

**Returns:**
boolean - boolean value: If false print page without page scaling. If true print page with scaling to fit to printable area.
### getAutoRotate() {#getAutoRotate--}
```
public boolean getAutoRotate()
```


Gets a bool value that indicates whether the file be printed with auto rotation

**Returns:**
boolean - boolean value
### getAutoRotateMode() {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```


Gets an AutoRotateMode value that indicates direction of rotation

**Returns:**
int - AutoRotateMode element
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Returns:**
int - PageCoordinateType element
### getCopiesPrinted() {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```


Gets copies printed

**Returns:**
int - int value
### getDefaultPageSettings() {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```


Gets the default page settings.

**Returns:**
[PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) - Page settings object.
### getDefaultPrinterSettings() {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```


Gets the default printer settings.

**Returns:**
[PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) - Page settings object.
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Gets form presentation mode.

**Returns:**
int - FormPresentationMode element
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets a value that indicates horizontal alignment

**Returns:**
int - HorizontalAlignment element
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Gets page count of the current Pdf file.

**Returns:**
int - return page count.
### getPassword() {#getPassword--}
```
public String getPassword()
```


Gets input document password.

**Returns:**
java.lang.String - String value
### getPrintAsGrayscale() {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```


Gets or sets a bool value that indicates whether the page is being printed as grayscale. By default is false.

--------------------

Default false is false.

**Returns:**
boolean - boolean value
### getPrintAsImage() {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```


Gets a mode for PdfViewer to print as image.

**Returns:**
boolean - boolean value

--------------------

If true prints always as image (generates image that is printed) If false prints directly to device if all features are supported. In case document contains non-supported features the system may automatically decide to print as image. Default falue is false.
### getPrintPageDialog() {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```


Gets a bool value that indicates whether produce the page number dialog when printing.

**Returns:**
boolean - boolean value
### getPrintStatus() {#getPrintStatus--}
```
public Object getPrintStatus()
```


Gets the result of printing job. If success than null; otherwise, exception object.

**Returns:**
java.lang.Object - exception object or null
### getPrinterJobName() {#getPrinterJobName--}
```
public String getPrinterJobName()
```


Gets name of document in printer queue when document is printed. Default value is file name.

**Returns:**
java.lang.String - String value
### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


Gets rendering options.

**Returns:**
[RenderingOptions](../../com.aspose.pdf/renderingoptions) - RenderingOptions object
### getResolution() {#getResolution--}
```
public int getResolution()
```


Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150.

**Returns:**
int - int value
### getScaleFactor() {#getScaleFactor--}
```
public float getScaleFactor()
```


Gets a floating point value that indicates scale factor. The default value is 1.0.

**Returns:**
float - floating point value.
### getUseIntermidiateImage() {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```


Gets the using of conversion of pdf page into intermidiate png file during printing in file mode. Use it when the size of output file is important.

**Returns:**
boolean - boolean value.
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets a value that indicates vertical alignment

**Returns:**
int - VerticalAlignment element
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShowHiddenAreas() {#isShowHiddenAreas--}
```
public boolean isShowHiddenAreas()
```


This method is Deprecated Gets flag that controls visibility of hidden areas on the page.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### openPdfFile(InputStream inputStream) {#openPdfFile-java.io.InputStream-}
```
public void openPdfFile(InputStream inputStream)
```


Opens a Pdf file stream. But does not actually decode the pages of the Pdf file.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile(new FileInputStream("d:\\test.pdf")));
 viewer.closePdfFile();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The pdf stream to be opened. |

### openPdfFile(String filePath) {#openPdfFile-java.lang.String-}
```
public void openPdfFile(String filePath)
```


Opens a Pdf file, but does not actually decode the pages of the Pdf file.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.closePdfFile();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of Pdf file. |

### printDocument() {#printDocument--}
```
public void printDocument()
```


Prints the Pdf document using default printer.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.setAutoResize ( true);         //print the file with adjusted size
 viewer.setAutoRotate ( true);         //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);   //do not produce the page number dialog when printing
 viewer.printDocument(ps);
 viewer.closePdfFile();
```

### printDocumentWithSettings(PdfPrinterSettings printerSettings) {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printDocumentWithSettings(PdfPrinterSettings printerSettings)
```


Prints the Pdf document with printer settings. The output page size will fit the the document first page size.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.setAutoResize ( true);         //print the file with adjusted size
 viewer.setAutoRotate ( true);         //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);   //do not produce the page number dialog when printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName());
 viewer.printDocumentWithSettings(ps);
 viewer.closePdfFile();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | The printer setting of the printing document. |

### printDocumentWithSettings(PrintPageSettings pageSettings, PdfPrinterSettings printerSettings) {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printDocumentWithSettings(PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)
```


Prints the Pdf document with settings. If the document size is not complatible to page size, pdf.kit will extend it to fit page size.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.setAutoResize ( true);         //print the file with adjusted size
 viewer.setAutoRotate ( true);         //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName());
 PageSettings pgs = new PageSettings();
 pgs.setPaperSize ( new PaperSize("A4", 827, 1169));
 pgs.setMargins ( new Margins(0, 0, 0, 0));
 viewer.printDocumentWithSettings(pgs, ps);
 viewer.closePdfFile();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | The page setting of the printing document. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | The printer setting of the printing document.

--------------------

printerSettings object is used to print the document. pageSettings.PrinterSettings object is ignored. |

### printLargePdf(InputStream inputStream) {#printLargePdf-java.io.InputStream-}
```
public void printLargePdf(InputStream inputStream)
```


Opens and prints a large Pdf stream. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize ( true);        //print the file with adjusted size
 viewer.setAutoRotate ( true);        //print the file with adjusted rotation
 viewer.printPageDialog=false;//do not produce the page number dialog when printing
 viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
 viewer.closePdfFile();
```

--------------------

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The pdf stream to be opened and printed.. |

### printLargePdf(InputStream inputStream, PdfPrinterSettings printerSettings) {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(InputStream inputStream, PdfPrinterSettings printerSettings)
```


Opens and prints a large Pdf stream with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize(true); // print the file with adjusted size
 viewer.setAutoRotate(true); // print the file with adjusted rotation
 viewer.setPrintPageDialog(false); // do not produce the page number dialog when
 				  // printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName());
 viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps);
 viewer.closePdfFile();
```

--------------------

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The pdf stream to be opened and printed.. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | The printer settings. |

### printLargePdf(InputStream inputStream, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings) {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(InputStream inputStream, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)
```


Opens and prints a large Pdf stream with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize ( true);       //print the file with adjusted size
 viewer.setAutoRotate ( true);       //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName());
 PageSettings pgs = new PageSettings();
 pgs.setPaperSize ( new PaperSize("A4", 827, 1169));
 pgs.setMargins ( new Margins(0, 0, 0, 0));
 viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps);
 viewer.closePdfFile();
```

--------------------

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The pdf stream to be opened and printed. |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | The page settings. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | The printer settings. |

### printLargePdf(String filePath) {#printLargePdf-java.lang.String-}
```
public void printLargePdf(String filePath)
```


Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize(true); // print the file with adjusted size
 viewer.setAutoRotate(true); // print the file with adjusted rotation
 viewer.setPrintPageDialog(false);// do not produce the page number dialog when
 									// printing
 viewer.setPrintLargePdf("d:\test.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of Pdf file.

--------------------

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly. |

### printLargePdf(String filePath, PdfPrinterSettings printerSettings) {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(String filePath, PdfPrinterSettings printerSettings)
```


Opens and prints a large Pdf file with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize ( true);       //print the file with adjusted size
 viewer.setAutoRotate ( true);       //print the file with adjusted rotation
 viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName());
 viewer.printLargePdf("d:\\test.pdf",ps);
 viewer.closePdfFile();
```

--------------------

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of Pdf file. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | The printer settings. |

### printLargePdf(String filePath, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings) {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(String filePath, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)
```


Opens and prints a large Pdf file with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize(true); // print the file with adjusted size
 viewer.setAutoRotate(true); // print the file with adjusted rotation
 viewer.setPrintPageDialog(false); // do not produce the page number dialog when
 				  // printing
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName());
 PageSettings pgs = new PageSettings();
 pgs.setPaperSize(new PaperSize("A4", 827, 1169));
 pgs.setMargins(new Margins(0, 0, 0, 0));
 viewer.printLargePdf("d:\\test.pdf", pgs, ps);
 viewer.closePdfFile();
```

--------------------

This method has integrated the opening and the printing of the file and you need not calling the OpenPdfFile() explicitly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of Pdf file. |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | The page settings. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | The printer settings. |

### save(InputStream destStream) {#save-java.io.InputStream-}
```
public void save(InputStream destStream)
```


Saves the result PDF document to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.InputStream | The stream of output PDF document. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Saves the result PDF document to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destFile | java.lang.String | The path of output PDF document. |

### setAutoResize(boolean value) {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```


Sets a bool value that indicates whether the file be printed with optimized size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value: If false print page without page scaling. If true print page with scaling to fit to printable area. |

### setAutoRotate(boolean value) {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```


Sets a bool value that indicates whether the file be printed with auto rotation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setAutoRotateMode(int value) {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```


Sets an AutoRotateMode value that indicates direction of rotation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | AutoRotateMode element |

### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PageCoordinateType element |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


Sets form presentation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | FormPresentationMode element |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets a value that indicates horizontal alignment

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment element |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Sets input document password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setPrintAsGrayscale(boolean value) {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```


Gets or sets a bool value that indicates whether the page is being printed as grayscale. By default is false.

--------------------

Default false is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setPrintAsImage(boolean value) {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```


Sets a mode for PdfViewer to print as image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value

--------------------

If true prints always as image (generates image that is printed) If false prints directly to device if all features are supported. In case document contains non-supported features the system may automatically decide to print as image. Default falue is false. |

### setPrintPageDialog(boolean value) {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```


Sets a boolean value that indicates whether produce the page number dialog when printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setPrinterJobName(String value) {#setPrinterJobName-java.lang.String-}
```
public void setPrinterJobName(String value)
```


Sets name of document in printer queue when document is printed. Default value is file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


Sets rendering options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | RenderingOptions value |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setScaleFactor(float value) {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```


Sets a floating point value that indicates scale factor. The default value is 1.0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | floating point value. |

### setShowHiddenAreas(boolean value) {#setShowHiddenAreas-boolean-}
```
public void setShowHiddenAreas(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseIntermidiateImage(boolean value) {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```


Sets the using of conversion of pdf page into intermidiate png file during printing in file mode. Use it when the size of output file is important.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value. |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a value that indicates vertical alignment

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

