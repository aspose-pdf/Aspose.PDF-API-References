---
title: PdfFileEditor
second_title: Aspose.PDF for Java API Reference
description: Implements operations with PDF file concatenation splitting extracting pages making booklet etc.
type: docs
weight: 39
url: /java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, com.aspose.pdf.facades.APdfFileEditor

**All Implemented Interfaces:**
[com.aspose.pdf.facades.IPdfFileEditor](../../com.aspose.pdf.facades/ipdffileeditor)
```
public final class PdfFileEditor extends APdfFileEditor implements IPdfFileEditor
```

Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileEditor()](#PdfFileEditor--) | PdfFileEditor constructor. |
## Methods

| Method | Description |
| --- | --- |
| [addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Resizes page contents and add specifed margins. |
| [addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-) | Resizes page contents and add specifed margins. |
| [addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-) | Resizes page contents and add specified margins. |
| [addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)](#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-) | Resizes page contents and add specified margins. |
| [addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Adds page breaks into document pages. |
| [addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Adds page breaks into document pages. |
| [addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Adds page breaks into document pages. |
| [addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks)](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak---) | Adds page breaks into document pages. |
| [append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream. |
| [append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)](#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-) | Appends pages, which are chosen from array of documents in portStreams. |
| [append(String inputFile, String portFile, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile. |
| [append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)](#append-java.lang.String-java.lang.String---int-int-java.lang.String-) | Appends pages, which are chosen from portFiles documents. |
| [concatenate(IDocument[] src, IDocument dest)](#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-) | Concatenates documents. |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. |
| [concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatenates two files. |
| [concatenate(InputStream[] inputStream, OutputStream outputStream)](#concatenate-java.io.InputStream---java.io.OutputStream-) | Concatenates files |
| [concatenate(String firstInputFile, String secInputFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatentates two files. |
| [concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. |
| [concatenate(String[] inputFiles, String outputFile)](#concatenate-java.lang.String---java.lang.String-) | Concatenates files into one file. |
| [delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#delete-java.io.InputStream-int---java.io.OutputStream-) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [delete(String inputFile, int[] pageNumber, String outputFile)](#delete-java.lang.String-int---java.lang.String-) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extracts pages from input file,saves as a new Pdf file. |
| [extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)](#extract-java.io.InputStream-int---java.io.OutputStream-) | Extracts pages specified by number array, saves as a new Pdf file. |
| [extract(String inputFile, int startPage, int endPage, String outputFile)](#extract-java.lang.String-int-int-java.lang.String-) | Extracts pages from input file,saves as a new Pdf file. |
| [extract(String inputFile, int[] pageNumber, String outputFile)](#extract-java.lang.String-int---java.lang.String-) | Extracts pages specified by number array, saves as a new PDF file. |
| [getAllowConcatenateExceptions()](#getAllowConcatenateExceptions--) | If set to true, exceptions are thrown if error occured. |
| [getAttachmentName()](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpServletResponse objects as attachment. |
| [getClass()](#getClass--) |  |
| [getCloseConcatenatedStreams()](#getCloseConcatenatedStreams--) | If set to true, streams are closed after operation. |
| [getConcatenationPacketSize()](#getConcatenationPacketSize--) | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. |
| [getContentDisposition()](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpServletResponse object. |
| [getConversionLog()](#getConversionLog--) | Gets log of conversion process. |
| [getCopyLogicalStructure()](#getCopyLogicalStructure--) | If true then logical structure of the file is copied when concatenation is performed. |
| [getCopyOutlines()](#getCopyOutlines--) | If true then outlines will be copied. |
| [getCorruptedFileAction()](#getCorruptedFileAction--) | This property defines behavior when concatenating process met corrupted file. |
| [getCorruptedItems()](#getCorruptedItems--) | Array of encountered problems when concatenation was performed. |
| [getCustomProgressConcatenationHandler()](#getCustomProgressConcatenationHandler--) | Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. |
| [getIncrementalUpdates()](#getIncrementalUpdates--) | If true, incremental updates are made during concatenation. |
| [getKeepActions()](#getKeepActions--) | If true actions will be copied from source documents. |
| [getKeepFieldsUnique()](#getKeepFieldsUnique--) | If true then field names will be made unique when forms are concatenated. |
| [getLastException()](#getLastException--) | Gets last occurred exception. |
| [getMergeDuplicateLayers()](#getMergeDuplicateLayers--) | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. |
| [getMergeDuplicateOutlines()](#getMergeDuplicateOutlines--) | If true, duplicate outlines are merged. |
| [getOptimizeSize()](#getOptimizeSize--) | Gets or sets optimization flag. |
| [getOwnerPassword()](#getOwnerPassword--) | Gets owner's password if the source input Pdf file is encrypted. |
| [getPreserveUserRights()](#getPreserveUserRights--) | If true, user rights of first document are applied to concatenated document. |
| [getRemoveSignatures()](#getRemoveSignatures--) | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [getSaveOptions()](#getSaveOptions--) | Gets or sets save options when result is stored as HttpServletResponse. |
| [getUniqueSuffix()](#getUniqueSuffix--) | Get format of the suffix which is added to field name to make it unique when forms are concatenated. |
| [hashCode()](#hashCode--) |  |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Inserts pages from an other file into the input Pdf file. |
| [insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)](#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-) | Inserts pages from an other file into the input Pdf file. |
| [insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Inserts pages from an other file into the Pdf file at a position. |
| [insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)](#insert-java.lang.String-int-java.lang.String-int---java.lang.String-) | Inserts pages from an other file into the input Pdf file. |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [isUseDiskBuffer()](#isUseDiskBuffer--) | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream)](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Makes booklet from the InputStream to outputStream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Makes booklet from the input stream and save result into output stream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---) | Makes booklet from the firstInputStream to outputStream. |
| [makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)](#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---) | Makes customized booklet from the firstInputStream to outputStream. |
| [makeBooklet(String inputFile, String outputFile)](#makeBooklet-java.lang.String-java.lang.String-) | Makes booklet from the input file to output file. |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Makes booklet from the inputFile to outputFile. |
| [makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---) | Makes customized booklet from the firstInputFile to outputFile. |
| [makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)](#makeBooklet-java.lang.String-java.lang.String-int---int---) | Makes customized booklet from the firstInputFile to outputFile. |
| [makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Makes N-Up document from the two input PDF streams to outputStream. |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Makes N-Up document from the input stream and saves result into output stream. |
| [makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Makes N-Up document from the first input stream to output stream. |
| [makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)](#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-) | Makes N-Up document from the multi input PDF streams to outputStream. |
| [makeNUp(String inputFile, String outputFile, int x, int y)](#makeNUp-java.lang.String-java.lang.String-int-int-) | Makes N-Up document from the firstInputFile to outputFile. |
| [makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Makes N-Up document from the input file to outputFile. |
| [makeNUp(String firstInputFile, String secondInputFile, String outputFile)](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Makes N-Up document from the two input PDF files to outputFile. |
| [makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)](#makeNUp-java.lang.String---java.lang.String-boolean-) | Makes N-Up document from the multi input PDF files to outputFile. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes pages of document. |
| [resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes pages of document. |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes contents of pages of the document. |
| [resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-) | Resizes contents of document pages. |
| [resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContents-java.lang.String-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes contents of pages in document. |
| [resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContents-java.lang.String-java.lang.String-int---double-double-) | Resizes contents of document pages. |
| [resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-) | Resizes contents of document pages. |
| [resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)](#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-) | Resizes contents of document pages. |
| [resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes pages of document. |
| [resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes pages of document. |
| [setAllowConcatenateExceptions(boolean value)](#setAllowConcatenateExceptions-boolean-) | If set to true, exceptions are thrown if error occured. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment. |
| [setCloseConcatenatedStreams(boolean value)](#setCloseConcatenatedStreams-boolean-) | If set to true, streams are closed after operation. |
| [setConcatenationPacketSize(int value)](#setConcatenationPacketSize-int-) | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Sets how content will be stored when result of operation is stored into HttpServletResponse object. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. |
| [setCopyLogicalStructure(boolean value)](#setCopyLogicalStructure-boolean-) | If true then logical structure of the file is copied when concatenation is performed. |
| [setCopyOutlines(boolean value)](#setCopyOutlines-boolean-) | If true then outlines will be copied. |
| [setCorruptedFileAction(int value)](#setCorruptedFileAction-int-) | This property defines behavior when concatenating process met corrupted file. |
| [setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler)](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. |
| [setIncrementalUpdates(boolean value)](#setIncrementalUpdates-boolean-) | If true, incremental updates are made during concatenation. |
| [setKeepActions(boolean value)](#setKeepActions-boolean-) | If true actions will be copied from source documents. |
| [setKeepFieldsUnique(boolean value)](#setKeepFieldsUnique-boolean-) | If true then field names will be made unique when forms are concatenated. |
| [setMergeDuplicateLayers(boolean value)](#setMergeDuplicateLayers-boolean-) |  |
| [setMergeDuplicateOutlines(boolean value)](#setMergeDuplicateOutlines-boolean-) | If true, duplicate outlines are merged. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Gets or sets optimization flag. |
| [setOwnerPassword(String value)](#setOwnerPassword-java.lang.String-) | Sets owner's password if the source input Pdf file is encrypted. |
| [setPreserveUserRights(boolean value)](#setPreserveUserRights-boolean-) | If true, user rights of first document are applied to concatenated document. |
| [setRemoveSignatures(boolean value)](#setRemoveSignatures-boolean-) | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [setUniqueSuffix(String value)](#setUniqueSuffix-java.lang.String-) | Set format of the suffix which is added to field name to make it unique when forms are concatenated. |
| [setUseDiskBuffer(boolean value)](#setUseDiskBuffer-boolean-) | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. |
| [splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Splits from start to specified location,and saves the front part in output Stream. |
| [splitFromFirst(String inputFile, int location, String outputFile)](#splitFromFirst-java.lang.String-int-java.lang.String-) | Splits Pdf file from first page to specified location,and saves the front part as a new file. |
| [splitToBulks(InputStream inputStream, int[][] numberOfPage)](#splitToBulks-java.io.InputStream-int-----) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [splitToBulks(String inputFile, int[][] numberOfPage)](#splitToBulks-java.lang.String-int-----) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [splitToEnd(InputStream inputStream, int location, OutputStream outputStream)](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Splits from specified location, and saves the rear part as a new file Stream. |
| [splitToEnd(String inputFile, int location, String outputFile)](#splitToEnd-java.lang.String-int-java.lang.String-) | Splits from location, and saves the rear part as a new file. |
| [splitToPages(InputStream inputStream)](#splitToPages-java.io.InputStream-) | Splits the Pdf file into single-page documents. |
| [splitToPages(InputStream inputStream, String fileNameTemplate)](#splitToPages-java.io.InputStream-java.lang.String-) | Split the Pdf file into single-page documents and saves it into specified path. |
| [splitToPages(String inputFile)](#splitToPages-java.lang.String-) | Splits the PDF file into single-page documents. |
| [splitToPages(String inputFile, String fileNameTemplate)](#splitToPages-java.lang.String-java.lang.String-) | Split the Pdf file into single-page documents and saves it into specified path. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileEditor() {#PdfFileEditor--}
```
public PdfFileEditor()
```


PdfFileEditor constructor.

### addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public boolean addMargins(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Resizes page contents and add specifed margins. Margins are specified in default space units.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  InmputStream src = new FileInputStream("input.pdf");
  OutputStream dest = new FileInputStream("output.pdf");
  fileEditor.addMargins(src, dest, 
      //process pages 1, 2, 3
      new int[] { 1, 2, 3}, 
      //left margin is 10 units
      10, 
      //right margin is 5 units
      5, 
      //top margin is 5 units
      5, 
      //bottom margin is 5 units
      5);
      dest.Close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin. |
| rightMargin | double | Right margin. |
| topMargin | double | Top margin. |
| bottomMargin | double | Bottom margin. |

**Returns:**
boolean - boolean value
### addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMargins-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public boolean addMargins(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Resizes page contents and add specifed margins. Margins are specified in default space units.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  fileEditor.addMargins("input.pdf", "output.pdf", 
      //process pages 1, 2, 3
      new int[] { 1, 2, 3}, 
      //left margin is 10 units
      10, 
      //right margin is 5 units
      5, 
      //top margin is 5 units
      5, 
      //bottom margin is 5 units
      5);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin. |
| rightMargin | double | Right margin. |
| topMargin | double | Top margin. |
| bottomMargin | double | Bottom margin. |

**Returns:**
boolean - true if resize was successful.
### addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int---double-double-double-double-}
```
public boolean addMarginsPct(InputStream source, OutputStream destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Resizes page contents and add specified margins. Margins are specified in percents of intitial page size.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  InmputStream src = new FileInputStream("input.pdf");
  OutputStream dest = new FileInputStream("output.pdf");
  fileEditor.addMarginsPct(src, dest, 
      //process pages 1, 2, 3
      new int[] { 1, 2, 3}, 
      //left margin is 15% of page width 
      15, 
      //right margin is 10% of page width
      10, 
      //top margin is 20% of page width
      20, 
      //bottom margin is 5% of page width
      5);
      dest.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin in percents of initial page size. |
| rightMargin | double | Right margin in percents of initial page size. |
| topMargin | double | Top margin in percents of initial page size. |
| bottomMargin | double | Bottom margin in percents of initial page size. |

**Returns:**
boolean - boolean value
### addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin) {#addMarginsPct-java.lang.String-java.lang.String-int---double-double-double-double-}
```
public boolean addMarginsPct(String source, String destination, int[] pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


Resizes page contents and add specified margins. Margins are specified in percents of intitial page size.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
  fileEditor.addMarginsPct("input.pdf", "output.pdf", 
      //process pages 1, 2, 3
      new int[] { 1, 2, 3}, 
      //left margin is 15% of page width 
      15, 
      //right margin is 10% of page width
      10, 
      //top margin is 20% of page width
      20, 
      //bottom margin is 5% of page width
      5);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| leftMargin | double | Left margin in percents of initial page size. |
| rightMargin | double | Right margin in percents of initial page size. |
| topMargin | double | Top margin in percents of initial page size. |
| bottomMargin | double | Bottom margin in percents of initial page size. |

**Returns:**
boolean - true if resize was successful
### addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public final void addPageBreak(Document src, Document dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Adds page breaks into document pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [Document](../../com.aspose.pdf/document) | Source document. |
| dest | [Document](../../com.aspose.pdf/document) | Destination document. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Array of PageBreak objects which describe places of page breaks. |

### addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public void addPageBreak(IDocument src, IDocument dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Adds page breaks into document pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [IDocument](../../com.aspose.pdf/idocument) | Source document. |
| dest | [IDocument](../../com.aspose.pdf/idocument) | Destination document. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Array of PageBreak objects which describe places of page breaks. |

### addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public final void addPageBreak(InputStream src, OutputStream dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Adds page breaks into document pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | java.io.InputStream | Source which contains source document. |
| dest | java.io.OutputStream | Source where destination document will be saved. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Array of PageBreak object describing pages and places where page break will be added. |

### addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks) {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak---}
```
public void addPageBreak(String src, String dest, PdfFileEditor.PageBreak[] pageBreaks)
```


Adds page breaks into document pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | java.lang.String | Path to source document. |
| dest | java.lang.String | Path to destination document. |
| pageBreaks | [PageBreak\[\]](../../com.aspose.pdf.facades/pagebreak) | Array of PageBreak object describing pages and places where page break will be added. |

### append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean append(InputStream inputStream, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, stream1,  3, 5, outstream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input file Stream. |
| portStream | java.io.InputStream | Pages from Pdf file Stream. |
| startPage | int | Page starts in portFile Stream. |
| endPage | int | Page ends in portFile Stream. |
| outputStream | java.io.OutputStream | Output Pdf file Stream. |

**Returns:**
boolean - True for success, or false.
### append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream) {#append-java.io.InputStream-java.io.InputStream---int-int-java.io.OutputStream-}
```
public boolean append(InputStream inputStream, InputStream[] portStreams, int startPage, int endPage, OutputStream outputStream)
```


Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream instream = new FileInputStream("input.pdf");
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OtputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Pdf stream. |
| portStreams | java.io.InputStream[] | Documents to copy pages from. |
| startPage | int | Page starts in portStreams documents. |
| endPage | int | Page ends in portStreams documents . |
| outputStream | java.io.OutputStream | Output Pdf stream. |

**Returns:**
boolean - True for success, or false.
### append(String inputFile, String portFile, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
```
public boolean append(String inputFile, String portFile, int startPage, int endPage, String outputFile)
```


Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| portFile | java.lang.String | Pages from Pdf file. |
| startPage | int | Page starts in portFile. |
| endPage | int | Page ends in portFile. |
| outputFile | java.lang.String | Output Pdf document. |

**Returns:**
boolean - True if operation was succeeded.
### append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile) {#append-java.lang.String-java.lang.String---int-int-java.lang.String-}
```
public boolean append(String inputFile, String[] portFiles, int startPage, int endPage, String outputFile)
```


Appends pages, which are chosen from portFiles documents. The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| portFiles | java.lang.String[] | Documents to copy pages from. |
| startPage | int | Page starts in portFiles documents. |
| endPage | int | Page ends in portFiles documents . |
| outputFile | java.lang.String | Output Pdf document. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(IDocument[] src, IDocument dest) {#concatenate-com.aspose.pdf.IDocument---com.aspose.pdf.IDocument-}
```
public boolean concatenate(IDocument[] src, IDocument dest)
```


Concatenates documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [IDocument\[\]](../../com.aspose.pdf/idocument) | Array of source documents. |
| dest | [IDocument](../../com.aspose.pdf/idocument) | Destination document. |

**Returns:**
boolean - True if concatenation is successful.
### concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean concatenate(InputStream firstInputStream, InputStream secInputStream, InputStream blankPageStream, OutputStream outputStream)
```


Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 InputStream blank = new FileInputStream("blank.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | The first Pdf Stream. |
| secInputStream | java.io.InputStream | The second Pdf Stream. |
| blankPageStream | java.io.InputStream | The Pdf Stream with blank page |
| outputStream | java.io.OutputStream | Output Pdf Stream. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream) {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean concatenate(InputStream firstInputStream, InputStream secInputStream, OutputStream outputStream)
```


Concatenates two files.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(stream1, stream2, outstream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | Stream of first file. |
| secInputStream | java.io.InputStream | Stream of second file. |
| outputStream | java.io.OutputStream | Stream where result file will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(InputStream[] inputStream, OutputStream outputStream) {#concatenate-java.io.InputStream---java.io.OutputStream-}
```
public boolean concatenate(InputStream[] inputStream, OutputStream outputStream)
```


Concatenates files

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("file1.pdf");
 InputStream stream2 = new FileInputStream("file2.pdf");
 OutputStream outstream = new FileOutputStream("outfile.pdf");
 fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream[] | Array of streams to be concatenated. |
| outputStream | java.io.OutputStream | Stream where result file will be stored. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(String firstInputFile, String secInputFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean concatenate(String firstInputFile, String secInputFile, String outputFile)
```


Concatentates two files.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | java.lang.String | First file to concatenate. |
| secInputFile | java.lang.String | Second file to concatenate. |
| outputFile | java.lang.String | Output file. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile) {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean concatenate(String firstInputFile, String secInputFile, String blankPageFile, String outputFile)
```


Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | java.lang.String | First file. |
| secInputFile | java.lang.String | Second file. |
| blankPageFile | java.lang.String | PDF file with blank page. |
| outputFile | java.lang.String | Result file. |

**Returns:**
boolean - True if operation was succeeded.
### concatenate(String[] inputFiles, String outputFile) {#concatenate-java.lang.String---java.lang.String-}
```
public boolean concatenate(String[] inputFiles, String outputFile)
```


Concatenates files into one file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.concatenate(new String[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Array of files to concatenate. |
| outputFile | java.lang.String | Name of output file. |

**Returns:**
boolean - True if operation was succeeded.
### delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#delete-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean delete(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Deletes pages specified by number array from input file, saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream intputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input file Stream. |
| pageNumber | int[] | Index of page out of the input file. |
| outputStream | java.io.OutputStream | Output file stream. |

**Returns:**
boolean - True for success, or false.
### delete(String inputFile, int[] pageNumber, String outputFile) {#delete-java.lang.String-int---java.lang.String-}
```
public boolean delete(String inputFile, int[] pageNumber, String outputFile)
```


Deletes pages specified by number array from input file, saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input file path. |
| pageNumber | int[] | Index of page out of the input file. |
| outputFile | java.lang.String | Output file path. |

**Returns:**
boolean - True if operation was succeeded.
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
### extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream) {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean extract(InputStream inputStream, int startPage, int endPage, OutputStream outputStream)
```


Extracts pages from input file,saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.extract(sourceStream, 1, 3, 6, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input file Stream. |
| startPage | int | Start page number. |
| endPage | int | End page number. |
| outputStream | java.io.OutputStream | Output Pdf file Stream. |

**Returns:**
boolean - True for success, or false.
### extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream) {#extract-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean extract(InputStream inputStream, int[] pageNumber, OutputStream outputStream)
```


Extracts pages specified by number array, saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileInputStream("out.pdf");
 pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input file Stream. |
| pageNumber | int[] | Index of page out of the input file. |
| outputStream | java.io.OutputStream | Output file stream. |

**Returns:**
boolean - True for success, or false.
### extract(String inputFile, int startPage, int endPage, String outputFile) {#extract-java.lang.String-int-int-java.lang.String-}
```
public boolean extract(String inputFile, int startPage, int endPage, String outputFile)
```


Extracts pages from input file,saves as a new Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file path. |
| startPage | int | Start page number. |
| endPage | int | End page number. |
| outputFile | java.lang.String | Output Pdf file path. |

**Returns:**
boolean - True for success, or false.
### extract(String inputFile, int[] pageNumber, String outputFile) {#extract-java.lang.String-int---java.lang.String-}
```
public boolean extract(String inputFile, int[] pageNumber, String outputFile)
```


Extracts pages specified by number array, saves as a new PDF file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input file path. |
| pageNumber | int[] | Index of page out of the input file. |
| outputFile | java.lang.String | Output file path. |

**Returns:**
boolean - True if operation was succeeded.
### getAllowConcatenateExceptions() {#getAllowConcatenateExceptions--}
```
public boolean getAllowConcatenateExceptions()
```


If set to true, exceptions are thrown if error occured. Else excetion are not thrown and methods return false if failed.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setAllowConcatenatedException (true);
```

**Returns:**
boolean - boolean value
### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


Gets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

**Returns:**
java.lang.String - String value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCloseConcatenatedStreams() {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```


If set to true, streams are closed after operation.

**Returns:**
boolean - boolean value
### getConcatenationPacketSize() {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```


Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true.

**Returns:**
int - int value
### getContentDisposition() {#getContentDisposition--}
```
public int getContentDisposition()
```


Gets how content will be stored when result of operation is stored into HttpServletResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
int - ContentDisposition element
### getConversionLog() {#getConversionLog--}
```
public String getConversionLog()
```


Gets log of conversion process.

**Returns:**
java.lang.String
### getCopyLogicalStructure() {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```


If true then logical structure of the file is copied when concatenation is performed.

**Returns:**
boolean - boolean value
### getCopyOutlines() {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```


If true then outlines will be copied.

**Returns:**
boolean - boolean value
### getCorruptedFileAction() {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```


This property defines behavior when concatenating process met corrupted file. Possible values are: StopWithError and ConcatenateIgnoringCorrupted.

**Returns:**
int - ConcatenateCorruptedFileAction element
### getCorruptedItems() {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem[] getCorruptedItems()
```


Array of encountered problems when concatenation was performed. For every corrupted document from passed to Concatenate() function new CorruptedItem entry is created. This property may be used only when CorruptedFileAction is ConcatenateIgnoringCorrupted.

--------------------

```
//concatenate documents and show information about corrupted documents
	      PdfFileEditor pfe = new PdfFileEditor();
	      pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted);
	      ```
if (pfe.getCorruptedItems().length >0)
```
	      {
	        for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems())
	        {
	           System.out.println(item.getIndex()+ " reason: " + item.getException());
	        }
	      }
```

**Returns:**
com.aspose.pdf.facades.PdfFileEditor.CorruptedItem[] - array of PdfFileEditor.CorruptedItem
### getCustomProgressConcatenationHandler() {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```


Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. This field uses different types of events.

Simple concatenation has 8 events :
1)AllPagesCopied
2)DocumentEmbeddedFiles
3)DocumentForms
4)DocumentOutlines
5)DocumentJavaScript
6)DocumentLogicalStructure
7)DocumentConcated.
8)TotalPercentage.

Parallel concatenation informs about every page concatenation and has 3 events:
1)PageConcatenated
2)BlankPage
3)TotalPercentage

**Returns:**
[ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) - ConcatenationProgressHandler instance
### getIncrementalUpdates() {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```


If true, incremental updates are made during concatenation.

**Returns:**
boolean - boolean value
### getKeepActions() {#getKeepActions--}
```
public final boolean getKeepActions()
```


If true actions will be copied from source documents. Defaulkt value : true.

**Returns:**
boolean - boolean value
### getKeepFieldsUnique() {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```


If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property.

**Returns:**
boolean - boolean value
### getLastException() {#getLastException--}
```
public final RuntimeException getLastException()
```


Gets last occurred exception. May be used to check the reason of failure.

```
PdfFileEditor pfe = new PdfFileEditor();
  if (!pfe.tryConcatenate("file1.pdf", "file2.pdf", "file3.pdf"))
  {
     System.out.println("Error occured:");
     if (pfe.getLastException() != null)
     {
         System.out.println((pfe.getLastException().getMessage());
         if (pfe.getLastException().getInnerException() != null)
             System.out.println((pfe.getLastException().getInnerException().getMessage());
     }
  }
```

**Returns:**
java.lang.RuntimeException
### getMergeDuplicateLayers() {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```


Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document.

**Returns:**
boolean
### getMergeDuplicateOutlines() {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```


If true, duplicate outlines are merged.

**Returns:**
boolean - boolean value
### getOptimizeSize() {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```


Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Returns:**
boolean - boolean value
### getOwnerPassword() {#getOwnerPassword--}
```
public String getOwnerPassword()
```


Gets owner's password if the source input Pdf file is encrypted. This property is not implemented yet.

**Returns:**
java.lang.String - String value
### getPreserveUserRights() {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```


If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored.

**Returns:**
boolean - boolean value
### getRemoveSignatures() {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```


If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Returns:**
boolean - boolean value
### getSaveOptions() {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```


Gets or sets save options when result is stored as HttpServletResponse. Default value: PdfSaveOptions.

**Returns:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - SaveOptions object
### getUniqueSuffix() {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```


Get format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
```
public boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int startPage, int endPage, OutputStream outputStream)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 outstream sourceStream = new FileInputStream("file1.pdf");
 outstream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | java.io.InputStream | Stream of Pdf file for pages. |
| startPage | int | From which page to start. |
| endPage | int | To which page to end. |
| outputStream | java.io.OutputStream | Output Stream. |

**Returns:**
boolean - True for success, or false.
### insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream) {#insert-java.io.InputStream-int-java.io.InputStream-int---java.io.OutputStream-}
```
public boolean insert(InputStream inputStream, int insertLocation, InputStream portStream, int[] pageNumber, OutputStream outputStream)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 outstream sourceStream = new FileInputStream("file1.pdf");
 outstream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileoutputStream("out.pdf");
 pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Stream of Pdf file. |
| insertLocation | int | Insert position in input file. |
| portStream | java.io.InputStream | Stream of Pdf file for pages. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputStream | java.io.OutputStream | Output Stream. |

**Returns:**
boolean - True if operation was succeeded.
### insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile) {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int startPage, int endPage, String outputFile)
```


Inserts pages from an other file into the Pdf file at a position.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| insertLocation | int | Position in input file. |
| portFile | java.lang.String | The porting Pdf file. |
| startPage | int | Start position in portFile. |
| endPage | int | End position in portFile. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile) {#insert-java.lang.String-int-java.lang.String-int---java.lang.String-}
```
public boolean insert(String inputFile, int insertLocation, String portFile, int[] pageNumber, String outputFile)
```


Inserts pages from an other file into the input Pdf file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 outstream sourceStream = new FileInputStream("file1.pdf");
 outstream insertedStream = new FileInputStream("file2.pdf");
 OutputStream outStream = new FileInputStream("out.pdf");
 pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input Pdf file. |
| insertLocation | int | Insert position in input file. |
| portFile | java.lang.String | Pages from the Pdf file. |
| pageNumber | int[] | The page number of the ported in portFile. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Returns:**
boolean - boolean value
### isUseDiskBuffer() {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```


If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates.

**Returns:**
boolean - boolean value
### makeBooklet(InputStream inputStream, OutputStream outputStream) {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream)
```


Makes booklet from the InputStream to outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | output pdf stream. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize)
```


Makes booklet from the input stream and save result into output stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileInputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input PDF stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation was succeeded.
### makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, PageSize pageSize, int[] leftPages, int[] rightPages)
```


Makes booklet from the firstInputStream to outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The input stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages) {#makeBooklet-java.io.InputStream-java.io.OutputStream-int---int---}
```
public boolean makeBooklet(InputStream inputStream, OutputStream outputStream, int[] leftPages, int[] rightPages)
```


Makes customized booklet from the firstInputStream to outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | The input stream. |
| outputStream | java.io.OutputStream | output pdf stream. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile) {#makeBooklet-java.lang.String-java.lang.String-}
```
public boolean makeBooklet(String inputFile, String outputFile)
```


Makes booklet from the input file to output file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
```
public boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize)
```


Makes booklet from the inputFile to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation is succeeded.
### makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int---int---}
```
public boolean makeBooklet(String inputFile, String outputFile, PageSize pageSize, int[] leftPages, int[] rightPages)
```


Makes customized booklet from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file. |
| outputFile | java.lang.String | Output pdf file path and name. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |
| leftPages | int[] | The left pages. |
| rightPages | int[] | The right pages. |

**Returns:**
boolean - boolean - True for success, or false.
### makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages) {#makeBooklet-java.lang.String-java.lang.String-int---int---}
```
public boolean makeBooklet(String inputFile, String outputFile, int[] leftPages, int[] rightPages)
```


Makes customized booklet from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | The input file. |
| outputFile | java.lang.String | Output pdf file path and name. |
| leftPages | int[] | The left pages of the booklet. |
| rightPages | int[] | The right pages of the booklet. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream) {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
```
public boolean makeNUp(InputStream firstInputStream, InputStream secondInputStream, OutputStream outputStream)
```


Makes N-Up document from the two input PDF streams to outputStream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream input1 = new FileInputStream("input1.pdf");
 InputStream input2 = new FileInputStream("input2.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(input1, input2, output);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | java.io.InputStream | first input stream. |
| secondInputStream | java.io.InputStream | second input stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
```
public boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y)
```


Makes N-Up document from the input stream and saves result into output stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.makeNUp(inputStream, outputStream, 3, 3);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize) {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp(InputStream inputStream, OutputStream outputStream, int x, int y, PageSize pageSize)
```


Makes N-Up document from the first input stream to output stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream inputStream = new FileInputStream("input.pdf");
 OutputStream outputStream = new FileOutputStream("output.pdf");
 pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input pdf stream. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - True if operation was succeeded.
### makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise) {#makeNUp-java.io.InputStream---java.io.OutputStream-boolean-}
```
public boolean makeNUp(InputStream[] inputStreams, OutputStream outputStream, boolean isSidewise)
```


Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream stream1 = new FileInputStream("input1.pdf");
 InputStream stream2 = new FileInputStream("input2.pdf");
 InputStream stream3 = new FileInputStream("input3.pdf");
 OutputStream output = new FileOutputStream("output.pdf");
 pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStreams | java.io.InputStream[] | Input Pdf streams. |
| outputStream | java.io.OutputStream | Output pdf stream. |
| isSidewise | boolean | Piled up way, true for horizontally and flase for vertically |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String inputFile, String outputFile, int x, int y) {#makeNUp-java.lang.String-java.lang.String-int-int-}
```
public boolean makeNUp(String inputFile, String outputFile, int x, int y)
```


Makes N-Up document from the firstInputFile to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize) {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
```
public boolean makeNUp(String inputFile, String outputFile, int x, int y, PageSize pageSize)
```


Makes N-Up document from the input file to outputFile.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input pdf file path and name. |
| outputFile | java.lang.String | Output pdf file path and name. |
| x | int | Number of columns. |
| y | int | Number of rows. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | The page size of the output pdf file. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String firstInputFile, String secondInputFile, String outputFile) {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
```
public boolean makeNUp(String firstInputFile, String secondInputFile, String outputFile)
```


Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | java.lang.String | first input file. |
| secondInputFile | java.lang.String | second input file. |
| outputFile | java.lang.String | Output pdf file path and name. |

**Returns:**
boolean - boolean - True for success, or false.
### makeNUp(String[] inputFiles, String outputFile, boolean isSidewise) {#makeNUp-java.lang.String---java.lang.String-boolean-}
```
public boolean makeNUp(String[] inputFiles, String outputFile, boolean isSidewise)
```


Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | java.lang.String[] | Input Pdf files. |
| outputFile | java.lang.String | Output pdf file path and name. |
| isSidewise | boolean | Piled up way, true for horizontally and flase for vertically. |

**Returns:**
boolean - boolean - True for success, or false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents(Document source, IPdfFileEditor.ContentsResizeParameters parameters)
```


Resizes pages of document. Blank margins are added around of shrinked page.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 Document src = new Document("input.pdf");
 Document dest = new Document();
 APdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
     //left margin = 10% of page width
     PdfFileEditor.ContentsResizeValue.percents(10),
     //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
     null,
     //right margin is 10% of page
     PdfFileEditor.ContentsResizeValue.percents(10),
     //top margin = 10% of height
     PdfFileEditor.ContentsResizeValue.percents(10),
     //new contents height is calculated automatically (similar to width)
     null,
     //bottom margin is 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents(doc, parameters);
 dest.save("output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | Source document. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |

### resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContents(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


Resizes pages of document. Blank margins are added around of shrinked page.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 Document doc = new Document("input.pdf");
 PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
     //left margin = 10% of page width
     PdfFileEditor.ContentsResizeValue.percents(10),
     //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
     null,
     //right margin is 10% of page 
     PdfFileEditor.ContentsResizeValue.percents(10),
     //top margin = 10% of height
     PdfFileEditor.ContentsResizeValue.percents(10),
     //new contents height is calculated automatically (similar to width)
     null,
     //bottom margin is 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents(doc, new int[] { 1, 2, 3}, parameters);
 doc.save("output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | Source document. |
| pages | int[] | List of page indexes. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |

### resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents(InputStream source, OutputStream destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


Resizes contents of pages of the document.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
	      InputStream src = new FileInputStream("input.pdf");
	      OutputStream dest = new FileOutputStream("output.pdf");
	      PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
	          //left margin = 10% of page width
	          PdfFileEditor.ContentsResizeValue.percents(10),
	          //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
	          null,
	          //right margin is 10% of page 
	          PdfFileEditor.ContentsResizeValue.percents(10),
	          //top margin = 10% of height
	          PdfFileEditor.ContentsResizeValue.percents(10),
	          //new contents height is calculated automatically (similar to width)
	          null,
	          //bottom margin is 10%
	          PdfFileEditor.ContentsResizeValue.percents(10)
	             );
	      fileEditor.resizeContents(src, dest, new int[] { 1, 2, 3}, parameters);
	      dest.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream with source document. |
| destination | java.io.OutputStream | Stream with the destination document. |
| pages | int[] | Array of page indexes. |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Resize parameters. |

**Returns:**
boolean - Returns true if success.
### resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContents(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizeContents(src, dest, 
 //resize all pages of document
 null, 
 //new contents width = 200
 200, 
 //new contents height = 300
 300);
 // rest area of page will be empty
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

**Returns:**
boolean - True if resize was successful.
### resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContents-java.lang.String-java.lang.String-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public boolean resizeContents(String source, String destination, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


Resizes contents of pages in document. If page is shrinked blank margins are added around the page.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
     //left margin = 10% of page width
     PdfFileEditor.ContentsResizeValue.percents(10),
     //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
     null,
     //right margin is 10% of page 
     PdfFileEditor.ContentsResizeValue.percents(10),
     //top margin = 10% of height
     PdfFileEditor.ContentsResizeValue.percents(10),
     //new contents height is calculated automatically (similar to width)
     null,
     //bottom margin is 10%
     PdfFileEditor.ContentsResizeValue.percents(10)
        );
 fileEditor.resizeContents("input.pdf", "output.pdf", new int[] { 1, 2,.3}, parameters);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Source document path. |
| destination | java.lang.String | Destination document path. |
| pages | int[] | Array of page indexes (page index starts from 1). |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | Parameters of page resize. |

**Returns:**
boolean - trure if resize was successful.
### resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContents-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContents(String source, String destination, int[] pages, double newWidth, double newHeight)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizeContents("input.pdf", "output.pdf", 
 //resize all pages of document
 null, 
 //new contents width = 200
 200, 
 //new contents height = 300
 300);
 // rest area of page will be empty
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in default space units. |
| newHeight | double | New height of page contents in default space units. |

**Returns:**
boolean - True if resize was successful.
### resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int---double-double-}
```
public boolean resizeContentsPct(InputStream source, OutputStream destination, int[] pages, double newWidth, double newHeight)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 InputStream src = new FileInputStream("input.pdf");
 OutputStream dest = new FileOutputStream("output.pdf");
 fileEditor.resizePct(src, dest, 
 //resize all pages of document
 null, 
 //new contents width = 60% of initial size
 60, 
 //new contents height = 60% of initial size
 60);
 // Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
 // The same for top and bottom margins.
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.io.InputStream | Stream which contains source document. |
| destination | java.io.OutputStream | Stream where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

**Returns:**
boolean - boolean value
### resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight) {#resizeContentsPct-java.lang.String-java.lang.String-int---double-double-}
```
public boolean resizeContentsPct(String source, String destination, int[] pages, double newWidth, double newHeight)
```


Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents.

--------------------

```
PdfFileEditor fileEditor = new PdfFileEditor();
 fileEditor.resizePct("input.pdf", "output.pdf",
 //resize all pages of document
 null, 
 //new contents width = 60% of initial size
 60, 
 //new contents height = 60% of initial size
 60);
 // Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
 // The same for top and bottom margins.
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | java.lang.String | Path to source document. |
| destination | java.lang.String | Path where resultant document will be saved. |
| pages | int[] | Array of page indexes. If null then all document pages will be processed. |
| newWidth | double | New width of page contents in percents. |
| newHeight | double | New height of page contents in percetns. |

**Returns:**
boolean - true if resize was successful.
### resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization(Document source, IPdfFileEditor.ContentsResizeParameters parameters)
```


Resizes pages of document. Blank margins are added around of shrinked page. Normalization helps to avoid not grouped saved content state unexpected behavior.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Document](../../com.aspose.pdf/document) | Document instance |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | ContentsResizeParameters instance |

### resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters) {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int---com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
```
public void resizeContentsWithNormalization(IDocument source, int[] pages, IPdfFileEditor.ContentsResizeParameters parameters)
```


Resizes pages of document. Blank margins are added around of shrinked page. Normalization helps to avoid not grouped saved content state unexpected behavior.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IDocument](../../com.aspose.pdf/idocument) | Document instance |
| pages | int[] | array of int values |
| parameters | [ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) | ContentsResizeParameters instance |

### setAllowConcatenateExceptions(boolean value) {#setAllowConcatenateExceptions-boolean-}
```
public void setAllowConcatenateExceptions(boolean value)
```


If set to true, exceptions are thrown if error occured. Else excetion are not thrown and methods return false if failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setAllowConcatenatedException (true);
``` |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName(String value)
```


Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setCloseConcatenatedStreams(boolean value) {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```


If set to true, streams are closed after operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
  pfe.setCloseConcatenatedStreams (true);
``` |

### setConcatenationPacketSize(int value) {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```


Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int value)
```


Sets how content will be stored when result of operation is stored into HttpServletResponse object. Possible value: inline / attachment. Default: inline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat value)
```


Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | int value |

### setCopyLogicalStructure(boolean value) {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```


If true then logical structure of the file is copied when concatenation is performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCopyOutlines(boolean value) {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```


If true then outlines will be copied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCorruptedFileAction(int value) {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```


This property defines behavior when concatenating process met corrupted file. Possible values are: StopWithError and ConcatenateIgnoringCorrupted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler) {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
```
public void setCustomProgressConcatenationHandler(PdfFileEditor.ConcatenationProgressHandler customProgressConcatenationHandler)
```


Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. This field uses different types of events.

Simple concatenation has 8 events :
1)AllPagesCopied
2)DocumentEmbeddedFiles
3)DocumentForms
4)DocumentOutlines
5)DocumentJavaScript
6)DocumentLogicalStructure
7)DocumentConcated.
8)TotalPercentage.

Parallel concatenation informs about every page concatenation and has 3 events:
1)PageConcatenated
2)BlankPage
3)TotalPercentage

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProgressConcatenationHandler | [ConcatenationProgressHandler](../../com.aspose.pdf.facades/concatenationprogresshandler) | ConcatenationProgressHandler instance |

### setIncrementalUpdates(boolean value) {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```


If true, incremental updates are made during concatenation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeepActions(boolean value) {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```


If true actions will be copied from source documents. Defaulkt value : true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeepFieldsUnique(boolean value) {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```


If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMergeDuplicateLayers(boolean value) {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```


Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setMergeDuplicateOutlines(boolean value) {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```


If true, duplicate outlines are merged.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```


Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setOwnerPassword(String value) {#setOwnerPassword-java.lang.String-}
```
public void setOwnerPassword(String value)
```


Sets owner's password if the source input Pdf file is encrypted. This property is not implemented yet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setPreserveUserRights(boolean value) {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```


If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRemoveSignatures(boolean value) {#setRemoveSignatures-boolean-}
```
public final void setRemoveSignatures(boolean value)
```


If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


Sets save options when result is stored as HttpServletResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | SaveOptions object |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | boolean value |

### setUniqueSuffix(String value) {#setUniqueSuffix-java.lang.String-}
```
public void setUniqueSuffix(String value)
```


Set format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

--------------------

```
PdfFileEditor ed = new PdfFileEditor();
   ed.setUniqueSuffix ( "_%NUM%");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setUseDiskBuffer(boolean value) {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```


If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### splitFromFirst(InputStream inputStream, int location, OutputStream outputStream) {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitFromFirst(InputStream inputStream, int location, OutputStream outputStream)
```


Splits from start to specified location,and saves the front part in output Stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileOutputStream("out.pdf");
 pfe.splitFromFirst(sourceStream, 5, outStream);
```

--------------------

The streams are NOT closed after this operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source Pdf file Stream. |
| location | int | The splitting point. |
| outputStream | java.io.OutputStream | Output file Stream. |

**Returns:**
boolean - True for success, or false.
### splitFromFirst(String inputFile, int location, String outputFile) {#splitFromFirst-java.lang.String-int-java.lang.String-}
```
public boolean splitFromFirst(String inputFile, int location, String outputFile)
```


Splits Pdf file from first page to specified location,and saves the front part as a new file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitFromFirst("input.pdf", 5, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source Pdf file. |
| location | int | The splitting point. |
| outputFile | java.lang.String | Output Pdf file. |

**Returns:**
boolean - True for success, or false.
### splitToBulks(InputStream inputStream, int[][] numberOfPage) {#splitToBulks-java.io.InputStream-int-----}
```
public ByteArrayInputStream[] splitToBulks(InputStream inputStream, int[][] numberOfPage)
```


Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input PDF stream. |
| numberOfPage | int[][] | The start page and the end page of each document. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a PDF document.
### splitToBulks(String inputFile, int[][] numberOfPage) {#splitToBulks-java.lang.String-int-----}
```
public ByteArrayInputStream[] splitToBulks(String inputFile, int[][] numberOfPage)
```


Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input PDF file. |
| numberOfPage | int[][] | Array which contains array of double elements, which is start and end pages of document. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a PDF document.
### splitToEnd(InputStream inputStream, int location, OutputStream outputStream) {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
```
public boolean splitToEnd(InputStream inputStream, int location, OutputStream outputStream)
```


Splits from specified location, and saves the rear part as a new file Stream.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 InputStream sourceStream = new FileInputStream("file1.pdf");
 OutputStream outStream = new FileInputStream("out.pdf");
 pfe.splitToEnd(sourceStream, 5, outStream);
```

--------------------

The streams are NOT closed after this operation unless CloseConcatedStreams is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source Pdf file Stream. |
| location | int | The splitting position. |
| outputStream | java.io.OutputStream | Output Pdf file Stream. |

**Returns:**
boolean - True if splitting was successful.
### splitToEnd(String inputFile, int location, String outputFile) {#splitToEnd-java.lang.String-int-java.lang.String-}
```
public boolean splitToEnd(String inputFile, int location, String outputFile)
```


Splits from location, and saves the rear part as a new file.

--------------------

```
PdfFileEditor pfe = new PdfFileEditor();
 pfe.splitToEnd("input.pdf", 5, "out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source Pdf file. |
| location | int | The splitting position. |
| outputFile | java.lang.String | Output Pdf file path. |

**Returns:**
boolean - True for success, or false.
### splitToPages(InputStream inputStream) {#splitToPages-java.io.InputStream-}
```
public ByteArrayInputStream[] splitToPages(InputStream inputStream)
```


Splits the Pdf file into single-page documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Input Pdf stream. |

**Returns:**
java.io.ByteArrayInputStream[] - ByteArrayInputStream[] array
### splitToPages(InputStream inputStream, String fileNameTemplate) {#splitToPages-java.io.InputStream-java.lang.String-}
```
public void splitToPages(InputStream inputStream, String fileNameTemplate)
```


Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream of the soruce document. |
| fileNameTemplate | java.lang.String | Template of resultant file name. Must contain %NUM% which is replaced with page number . For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

### splitToPages(String inputFile) {#splitToPages-java.lang.String-}
```
public ByteArrayInputStream[] splitToPages(String inputFile)
```


Splits the PDF file into single-page documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input PDF file name. |

**Returns:**
java.io.ByteArrayInputStream[] - Output PDF streams, each stream buffers a single-page PDF document.
### splitToPages(String inputFile, String fileNameTemplate) {#splitToPages-java.lang.String-java.lang.String-}
```
public void splitToPages(String inputFile, String fileNameTemplate)
```


Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Input file name. |
| fileNameTemplate | java.lang.String | Template of resultant file name. Must contain %NUM% which is replaced with page number . For example, if c:/dir/page%NUM%.pdf is specified, resultant files will have the following names: c:/dir/page1.pdf, c:/dir/page2.pdf etc. |

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

