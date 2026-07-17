---
title: PdfFileEditorWeb
linktitle: PdfFileEditorWeb
second_title: Aspose.PDF for Java API Reference
description: 'Represents PdfFileEditorWeb class Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.'
type: docs
weight: 480
url: /java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

Represents PdfFileEditorWeb class Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | PdfFileEditorWeb constructor. |

## Methods

| Method | Description |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Resizes page contents and add specifed margins. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Resizes page contents and add specifed margins. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Resizes page contents and add specified margins. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Resizes page contents and add specified margins. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adds page breaks into document pages. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adds page breaks into document pages. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adds page breaks into document pages. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adds page breaks into document pages. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | Appends documents to source document and saves result into response object. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Appends pages, which are chosen from array of documents in portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | Appends documents to source document and saves result into HttpServletResponse object. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Appends pages, which are chosen from portFiles documents. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatenates documents. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | Concatenates files and stores result into HttpServletResponse object. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatenates files |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatenates two files. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | Concatenates files and saves reslt into HttpResposnse object. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatenates files into one file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatenates two files. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Deletes specified pages from document and saves result into HttpServletResponse object. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Deletes specified pages from document and stores result into HttpServletResponse object. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Extracts specified pages form source file and stores result into HttpServletResponse object. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extracts pages specified by number array, saves as a new Pdf file. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extracts pages from input file,saves as a new Pdf file. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Extracts specified pages from source file and stores result into HttpServletResponse object. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extracts pages specified by number array, saves as a new PDF file. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extracts pages from input file,saves as a new Pdf file. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Deprecated. This property is deprecated and can not be used to allow throwing exceptions. |
| [getAttachmentName](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpServletResponse objects as attachment. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | If set to true, streams are closed after operation. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. |
| [getContentDisposition](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpServletResponse object. |
| [getConversionLog](#getConversionLog--) | Gets log of conversion process. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | If true then logical structure of the file is copied when concatenation is performed. |
| [getCopyOutlines](#getCopyOutlines--) | If true then outlines will be copied. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | This property defines behavior when concatenating process met corrupted file. |
| [getCorruptedItems](#getCorruptedItems--) | Array of encountered problems when concatenation was performed. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | If true, incremental updates are made during concatenation. |
| [getKeepActions](#getKeepActions--) | If true actions will be copied from source documents. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | If true then field names will be made unique when forms are concatenated. |
| [getLastException](#getLastException--) | Gets last occurred exception. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | If true, duplicate outlines are merged. |
| [getOptimizeSize](#getOptimizeSize--) | Gets or sets optimization flag. |
| [getOwnerPassword](#getOwnerPassword--) | Gets owner's password if the source input Pdf file is encrypted. |
| [getPreserveUserRights](#getPreserveUserRights--) | If true, user rights of first document are applied to concatenated document. |
| [getRemoveSignatures](#getRemoveSignatures--) | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [getSaveOptions](#getSaveOptions--) | Gets or sets save options when result is stored as HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Get format of the suffix which is added to field name to make it unique when forms are concatenated. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Inserts document into other document and stores result into response object. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Inserts pages from an other file into the input Pdf file. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Inserts pages from an other file into the input Pdf file. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Inserts contents of file into source file and stores result into HttpServletResponse object. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Inserts pages from an other file into the input Pdf file. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Inserts pages from an other file into the Pdf file at a position. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Makes booklet from the InputStream to outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Makes customized booklet from the firstInputStream to outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Makes booklet from the input stream and save result into output stream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Makes booklet from the firstInputStream to outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Makes booklet from source file and stores result into HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Make booklet from PDF file and stores it into HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Makes booklet from source file and stores result into HttpServletResponse objects. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Makes booklet from source file and stores result into HttpServletResponse objects. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Makes booklet from the input file to output file. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Makes customized booklet from the firstInputFile to outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Makes booklet from the inputFile to outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Makes customized booklet from the firstInputFile to outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Makes N-Up document from the multi input PDF streams to outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Makes N-Up document from the two input PDF streams to outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Makes N-up document and stores result into HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Makes N-up document and stores result into HttpServletResponse object. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Makes N-Up document from the input stream and saves result into output stream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Makes N-Up document from the first input stream to output stream. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Makes N-Up document from the multi input PDF files to outputFile. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Makes N-up document and stores result into HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Makes N-up document and stores result into HttpServletResponse object. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Makes N-Up document from the firstInputFile to outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Makes N-Up document from the input file to outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Makes N-Up document from the two input PDF files to outputFile. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes pages of document. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes pages of document. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Resizes contents of document pages. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes contents of pages of the document. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Resizes contents of pages in document. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Resizes contents of pages in document. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Resizes contents of document pages. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes contents of pages in document. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Resizes contents of document pages. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Resizes contents of document pages. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes pages of document. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Resizes pages of document. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Deprecated. This property is deprecated and can not be used to allow throwing exceptions. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | If set to true, streams are closed after operation. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Sets how content will be stored when result of operation is stored into HttpServletResponse object. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | If true then logical structure of the file is copied when concatenation is performed. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | If true then outlines will be copied. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | This property defines behavior when concatenating process met corrupted file. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | If true, incremental updates are made during concatenation. |
| [setKeepActions](#setKeepActions-boolean-) | If true actions will be copied from source documents. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | If true then field names will be made unique when forms are concatenated. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | If true, duplicate outlines are merged. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Gets or sets optimization flag. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Sets owner's password if the source input Pdf file is encrypted. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | If true, user rights of first document are applied to concatenated document. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Set format of the suffix which is added to field name to make it unique when forms are concatenated. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Splits document from start to specified location and stores result into HttpServletResponse object. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Splits from start to specified location,and saves the front part in output Stream. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Splits document from first page to location and saves result into HttpServletResponse objects. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Splits Pdf file from first page to specified location,and saves the front part as a new file. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Splits from specified location, and saves the rear part into HttpServletResponse object. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Splits from specified location, and saves the rear part as a new file Stream. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Splits from specified location, and saves the rear part into HttpServletResponse object. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Splits from location, and saves the rear part as a new file. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Splits the Pdf file into single-page documents. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Split the Pdf file into single-page documents and saves it into specified path. |
| [splitToPages](#splitToPages-java.lang.String-) | Splits the PDF file into single-page documents. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Split the Pdf file into single-page documents and saves it into specified path. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

PdfFileEditorWeb constructor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Resizes page contents and add specifed margins.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Resizes page contents and add specifed margins.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Resizes page contents and add specified margins.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Resizes page contents and add specified margins.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adds page breaks into document pages.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adds page breaks into document pages.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adds page breaks into document pages.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adds page breaks into document pages.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
Appends documents to source document and saves result into response object.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Appends pages, which are chosen from array of documents in portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
Appends documents to source document and saves result into HttpServletResponse object.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Appends pages, which are chosen from portFiles documents.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatenates documents.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
Concatenates files and stores result into HttpServletResponse object.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatenates files

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatenates two files.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
Concatenates files and saves reslt into HttpResposnse object.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatenates files into one file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatenates two files.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Deletes specified pages from document and saves result into HttpServletResponse object.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Deletes pages specified by number array from input file, saves as a new Pdf file.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Deletes specified pages from document and stores result into HttpServletResponse object.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Deletes pages specified by number array from input file, saves as a new Pdf file.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Extracts specified pages form source file and stores result into HttpServletResponse object.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extracts pages specified by number array, saves as a new Pdf file.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extracts pages from input file,saves as a new Pdf file.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Extracts specified pages from source file and stores result into HttpServletResponse object.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extracts pages specified by number array, saves as a new PDF file.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extracts pages from input file,saves as a new Pdf file.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

Deprecated. This property is deprecated and can not be used to allow throwing exceptions.

**Returns:**
Boolean value

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Gets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

**Returns:**
string value

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

If set to true, streams are closed after operation.

**Returns:**
boolean value

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true.

**Returns:**
int value

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Gets how content will be stored when result of operation is stored into HttpServletResponse object.

**Returns:**
ContentDisposition element

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Gets log of conversion process.

**Returns:**
string value

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

If true then logical structure of the file is copied when concatenation is performed.

**Returns:**
boolean value

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

If true then outlines will be copied.

**Returns:**
boolean value

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

This property defines behavior when concatenating process met corrupted file.

**Returns:**
ConcatenateCorruptedFileAction element

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

Array of encountered problems when concatenation was performed.

**Returns:**
PdfFileEditor.CorruptedItem array

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code.

**Returns:**
ConcatenationProgressHandler instance

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

If true, incremental updates are made during concatenation.

**Returns:**
boolean value

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

If true actions will be copied from source documents.

**Returns:**
boolean value

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

If true then field names will be made unique when forms are concatenated.

**Returns:**
boolean value

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Gets last occurred exception.

**Returns:**
java.lang.Exception object

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true.

**Returns:**
boolean value

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

If true, duplicate outlines are merged.

**Returns:**
boolean value

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Gets or sets optimization flag.

**Returns:**
boolean value

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Gets owner's password if the source input Pdf file is encrypted.

**Returns:**
String object

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

If true, user rights of first document are applied to concatenated document.

**Returns:**
boolean value

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Returns:**
boolean value

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Gets or sets save options when result is stored as HttpServletResponse.

**Returns:**
SaveOptions object

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Get format of the suffix which is added to field name to make it unique when forms are concatenated.

**Returns:**
String object

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Inserts document into other document and stores result into response object.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Inserts pages from an other file into the input Pdf file.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Inserts pages from an other file into the input Pdf file.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Inserts contents of file into source file and stores result into HttpServletResponse object.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Inserts pages from an other file into the input Pdf file.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Inserts pages from an other file into the Pdf file at a position.

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other.

**Returns:**
boolean value

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates.

**Returns:**
boolean value

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Makes booklet from the InputStream to outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Makes customized booklet from the firstInputStream to outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Makes booklet from the input stream and save result into output stream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Makes booklet from the firstInputStream to outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Makes booklet from source file and stores result into HttpServletResponse.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Make booklet from PDF file and stores it into HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Makes booklet from source file and stores result into HttpServletResponse objects.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Makes booklet from source file and stores result into HttpServletResponse objects.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
Makes booklet from the input file to output file.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
Makes customized booklet from the firstInputFile to outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
Makes booklet from the inputFile to outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
Makes customized booklet from the firstInputFile to outputFile.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
Makes N-Up document from the multi input PDF streams to outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Makes N-Up document from the two input PDF streams to outputStream.

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
Makes N-up document and stores result into HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Makes N-up document and stores result into HttpServletResponse object.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Makes N-Up document from the input stream and saves result into output stream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Makes N-Up document from the first input stream to output stream.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Makes N-Up document from the multi input PDF files to outputFile.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
Makes N-up document and stores result into HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Makes N-up document and stores result into HttpServletResponse object.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Makes N-Up document from the firstInputFile to outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Makes N-Up document from the input file to outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Makes N-Up document from the two input PDF files to outputFile.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Resizes pages of document.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Resizes pages of document.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Resizes contents of document pages.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Resizes contents of pages of the document.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Resizes contents of pages in document.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Resizes contents of pages in document.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Resizes contents of document pages.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Resizes contents of pages in document.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Resizes contents of document pages.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Resizes contents of document pages.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Resizes pages of document.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Resizes pages of document.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

Deprecated. This property is deprecated and can not be used to allow throwing exceptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | Boolean value |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

If set to true, streams are closed after operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Sets how content will be stored when result of operation is stored into HttpServletResponse object.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets PDF file format.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

If true then logical structure of the file is copied when concatenation is performed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

If true then outlines will be copied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

This property defines behavior when concatenating process met corrupted file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ConcatenateCorruptedFileAction element |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Representation of internal progress events processor that works during concatenation and translates concatenation events of internal concatenation stages into external customer's code.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

If true, incremental updates are made during concatenation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

If true actions will be copied from source documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

If true then field names will be made unique when forms are concatenated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

If true, duplicate outlines are merged.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Gets or sets optimization flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Sets owner's password if the source input Pdf file is encrypted.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

If true, user rights of first document are applied to concatenated document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sets save options when result is stored as HttpServletResponse.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | boolean value |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Set format of the suffix which is added to field name to make it unique when forms are concatenated.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Splits document from start to specified location and stores result into HttpServletResponse object.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Splits from start to specified location,and saves the front part in output Stream.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Splits document from first page to location and saves result into HttpServletResponse objects.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Splits Pdf file from first page to specified location,and saves the front part as a new file.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Splits from specified location, and saves the rear part into HttpServletResponse object.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Splits from specified location, and saves the rear part as a new file Stream.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Splits from specified location, and saves the rear part into HttpServletResponse object.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
Splits from location, and saves the rear part as a new file.

### splitToPages {#splitToPages-java.io.InputStream-}
Splits the Pdf file into single-page documents.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Split the Pdf file into single-page documents and saves it into specified path.

### splitToPages {#splitToPages-java.lang.String-}
Splits the PDF file into single-page documents.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Split the Pdf file into single-page documents and saves it into specified path.
