---
title: IPdfFileEditor
second_title: Aspose.PDF for Java API Reference
description: Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.
type: docs
weight: 290
url: /java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.

## Methods

| Method | Description |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Resizes page contents and add specifed margins. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Resizes page contents and add specifed margins. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Resizes page contents and add specified margins. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Resizes page contents and add specified margins. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Appends pages, which are chosen from array of documents in portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Appends pages, which are chosen from portFiles documents. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatenates documents. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatenates files |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatenates two files. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatenates files into one file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatentates two files. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extracts pages specified by number array, saves as a new Pdf file. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extracts pages from input file,saves as a new Pdf file. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extracts pages specified by number array, saves as a new PDF file. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extracts pages from input file,saves as a new Pdf file. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | is Allow Concatenate Exceptions |
| [getAttachmentName](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpServletResponse objects as attachment. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | If set to true, streams are closed after operation. |
| [getContentDisposition](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpServletResponse object. |
| [getConversionLog](#getConversionLog--) | Gets log of conversion process. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | This property defines behavior when concatenating process met corrupted file. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | If true, incremental updates are made during concatenation. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | If true then field names will be made unique when forms are concatenated. |
| [getLastException](#getLastException--) | Gets last occured exception. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | If true, duplicate outlines are merged. |
| [getOwnerPassword](#getOwnerPassword--) | Gets owner's password if the source input Pdf file is encrypted. |
| [getPreserveUserRights](#getPreserveUserRights--) | If true, user rights of first document are applied to concatenated document. |
| [getRemoveSignatures](#getRemoveSignatures--) | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [getSaveOptions](#getSaveOptions--) | Gets or sets save options when result is stored as HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Get format of the suffix which is added to field name to make it unique when forms are concatenated. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Inserts pages from an other file into the input Pdf file. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Inserts pages from an other file into the input Pdf file. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Inserts pages from an other file into the input Pdf file. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Inserts pages from an other file into the Pdf file at a position. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Makes booklet from the InputStream to outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Makes customized booklet from the firstInputStream to outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Makes booklet from the input stream and save result into output stream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Makes booklet from the firstInputStream to outputStream. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Makes booklet from the input file to output file. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Makes customized booklet from the firstInputFile to outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Makes booklet from the inputFile to outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Makes customized booklet from the firstInputFile to outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Makes N-Up document from the multi input PDF streams to outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Makes N-Up document from the two input PDF streams to outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Makes N-Up document from the input stream and saves result into output stream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Makes N-Up document from the first input stream to output stream. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Makes N-Up document from the multi input PDF files to outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Makes N-Up document from the firstInputFile to outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Makes N-Up document from the input file to outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Makes N-Up document from the two input PDF files to outputFile. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Resizes contents of document pages. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Resizes contents of document pages. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Resizes contents of document pages. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Resizes contents of document pages. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | If set to true, exceptions are thrown if error occured. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | If set to true, streams are closed after operation. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Sets how content will be stored when result of operation is stored into HttpServletResponse object. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | This property defines behavior when concatenating process met corrupted file. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | If true, incremental updates are made during concatenation. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | If true then field names will be made unique when forms are concatenated. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | If true, duplicate outlines are merged. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Sets owner's password if the source input Pdf file is encrypted. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | If true, user rights of first document are applied to concatenated document. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpServletResponse. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Set format of the suffix which is added to field name to make it unique when forms are concatenated. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Splits from start to specified location,and saves the front part in output Stream. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Splits Pdf file from first page to specified location,and saves the front part as a new file. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Splits from specified location, and saves the rear part as a new file Stream. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Splits from location, and saves the rear part as a new file. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Splits the Pdf file into single-page documents. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Split the Pdf file into single-page documents and saves it into specified path. |
| [splitToPages](#splitToPages-java.lang.String-) | Splits the PDF file into single-page documents. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Split the Pdf file into single-page documents and saves it into specified path. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Resizes page contents and add specifed margins.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Resizes page contents and add specifed margins.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Resizes page contents and add specified margins.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Resizes page contents and add specified margins.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Appends pages, which are chosen from array of documents in portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Appends pages, which are chosen from portFiles documents.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatenates documents.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatenates files

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatenates two files.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatenates files into one file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatentates two files.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Deletes pages specified by number array from input file, saves as a new Pdf file.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Deletes pages specified by number array from input file, saves as a new Pdf file.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extracts pages specified by number array, saves as a new Pdf file.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extracts pages from input file,saves as a new Pdf file.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extracts pages specified by number array, saves as a new PDF file.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extracts pages from input file,saves as a new Pdf file.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

is Allow Concatenate Exceptions

**Returns:**
boolean value

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Gets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

**Returns:**
string value

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

If set to true, streams are closed after operation.

**Returns:**
boolean value

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Gets how content will be stored when result of operation is stored into HttpServletResponse object.

**Returns:**
ContentDisposition element

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

Gets log of conversion process.

**Returns:**
string value

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

This property defines behavior when concatenating process met corrupted file.

**Returns:**
ConcatenateCorruptedFileAction element

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

If true, incremental updates are made during concatenation.

**Returns:**
boolean value

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

If true then field names will be made unique when forms are concatenated.

**Returns:**
boolean value

### getLastException {#getLastException--}
```
Exception getLastException()
```

Gets last occured exception.

**Returns:**
java.lang.Exception object

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true.

**Returns:**
boolean value

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

If true, duplicate outlines are merged.

**Returns:**
boolean value

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

Gets owner's password if the source input Pdf file is encrypted.

**Returns:**
string value

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

If true, user rights of first document are applied to concatenated document.

**Returns:**
boolean value

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Returns:**
boolean value

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Gets or sets save options when result is stored as HttpServletResponse.

**Returns:**
SaveOptions object

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

Get format of the suffix which is added to field name to make it unique when forms are concatenated.

**Returns:**
string value

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Inserts pages from an other file into the input Pdf file.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Inserts pages from an other file into the input Pdf file.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Inserts pages from an other file into the input Pdf file.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Inserts pages from an other file into the Pdf file at a position.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Makes booklet from the InputStream to outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Makes customized booklet from the firstInputStream to outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Makes booklet from the input stream and save result into output stream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Makes booklet from the firstInputStream to outputStream.

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

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Makes N-Up document from the input stream and saves result into output stream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Makes N-Up document from the first input stream to output stream.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Makes N-Up document from the multi input PDF files to outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Makes N-Up document from the firstInputFile to outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Makes N-Up document from the input file to outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Makes N-Up document from the two input PDF files to outputFile.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Resizes contents of document pages.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Resizes contents of document pages.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Resizes contents of document pages.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Resizes contents of document pages.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

If set to true, exceptions are thrown if error occured.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Sets name of attachment when result of operation is stored into HttpServletResponse objects as attachment.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

If set to true, streams are closed after operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Sets how content will be stored when result of operation is stored into HttpServletResponse object.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets PDF file format.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

This property defines behavior when concatenating process met corrupted file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ConcatenateCorruptedFileAction element |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

If true, incremental updates are made during concatenation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

If true then field names will be made unique when forms are concatenated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

If true, duplicate outlines are merged.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Sets owner's password if the source input Pdf file is encrypted.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

If true, user rights of first document are applied to concatenated document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sets save options when result is stored as HttpServletResponse.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Set format of the suffix which is added to field name to make it unique when forms are concatenated.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Splits from start to specified location,and saves the front part in output Stream.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Splits Pdf file from first page to specified location,and saves the front part as a new file.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Splits the Pdf file into several documents.The documents can be single-page or multi-pages.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Splits from specified location, and saves the rear part as a new file Stream.

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
