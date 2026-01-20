---
title: Aspose::Pdf::Facades::PdfFileEditor class
linktitle: PdfFileEditor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor class. Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc in C++.'
type: docs
weight: 2000
url: /cpp/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class


Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.

```cpp
class PdfFileEditor : public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Nested classes

* Class [ContentsResizeParameters](./contentsresizeparameters/)
* Class [ContentsResizeValue](./contentsresizevalue/)
* Class [CorruptedItem](./corrupteditem/)
* Class [PageBreak](./pagebreak/)
## Enums

| Enum | Description |
| --- | --- |
| [ConcatenateCorruptedFileAction](./concatenatecorruptedfileaction/) | Action performed when corrupted file was met in concatenation process. |
## Methods

| Method | Description |
| --- | --- |
| [AddMargins](./addmargins/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double, double, double) | Resizes page contents and add specifed margins. Margins are specified in default space units. |
| [AddMargins](./addmargins/)(System::String, System::String, System::ArrayPtr\<int32_t\>, double, double, double, double) | Resizes page contents and add specifed margins. Margins are specified in default space units. |
| [AddMarginsPct](./addmarginspct/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double, double, double) | Resizes page contents and add specified margins. Margins are specified in percents of intitial page size. |
| [AddMarginsPct](./addmarginspct/)(System::String, System::String, System::ArrayPtr\<int32_t\>, double, double, double, double) | Resizes page contents and add specified margins. Margins are specified in percents of intitial page size. |
| [AddPageBreak](./addpagebreak/)(System::SharedPtr\<Document\>, System::SharedPtr\<Document\>, System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>) | Adds page breaks into document pages. |
| [AddPageBreak](./addpagebreak/)(System::String, System::String, System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>) | Adds page breaks into document pages. |
| [AddPageBreak](./addpagebreak/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<PdfFileEditor::PageBreak\>\>) | Adds page breaks into document pages. |
| [Append](./append/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage. |
| [Append](./append/)(System::String, System::ArrayPtr\<System::String\>, int32_t, int32_t, System::String) | Appends pages, which are chosen from portFiles documents. The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage. |
| [Append](./append/)(System::String, System::String, int32_t, int32_t, System::String) | Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile. |
| [Append](./append/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream. |
| [Append](./append/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Appends documents to source document and saves result into response object. |
| [Append](./append/)(System::String, System::ArrayPtr\<System::String\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Appends documents to source document and saves result into HttpResponse object. |
| [Concatenate](./concatenate/)(System::String, System::String, System::String) | Concatenates two files. |
| [Concatenate](./concatenate/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Concatenates two files. |
| [Concatenate](./concatenate/)(System::ArrayPtr\<System::SharedPtr\<Document\>\>, System::SharedPtr\<Document\>) | Concatenates documents. |
| [Concatenate](./concatenate/)(System::ArrayPtr\<System::String\>, System::String) | Concatenates files into one file. |
| [Concatenate](./concatenate/)(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::IO::Stream\>) | Concatenates files. |
| [Concatenate](./concatenate/)(System::String, System::String, System::String, System::String) | Merges two [Pdf](../../aspose.pdf/) documents into a new [Pdf](../../aspose.pdf/) document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two [Pdf](../../aspose.pdf/) document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](./concatenate/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Merges two [Pdf](../../aspose.pdf/) documents into a new [Pdf](../../aspose.pdf/) document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two [Pdf](../../aspose.pdf/) document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](./concatenate/)(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::Web::HttpResponse\>) | Concatenates files and saves reslt into HttpResposnse object. |
| [Concatenate](./concatenate/)(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::Web::HttpResponse\>) | Concatenates files and stores result into HttpResponse object. |
| [Delete](./delete/)(System::String, System::ArrayPtr\<int32_t\>, System::String) | Deletes pages specified by number array from input file, saves as a new [Pdf](../../aspose.pdf/) file. |
| [Delete](./delete/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) | Deletes pages specified by number array from input file, saves as a new [Pdf](../../aspose.pdf/) file. |
| [Delete](./delete/)(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Deletes specified pages from document and stores result into HttpResponse object. |
| [Delete](./delete/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Deletes specified pages from document and saves result into HttpResponse object. |
| [Extract](./extract/)(System::String, int32_t, int32_t, System::String) | Extracts pages from input file,saves as a new [Pdf](../../aspose.pdf/) file. |
| [Extract](./extract/)(System::String, System::ArrayPtr\<int32_t\>, System::String) | Extracts pages specified by number array, saves as a new PDF file. |
| [Extract](./extract/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Extracts pages from input file,saves as a new [Pdf](../../aspose.pdf/) file. |
| [Extract](./extract/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) | Extracts pages specified by number array, saves as a new [Pdf](../../aspose.pdf/) file. |
| [Extract](./extract/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Extracts specified pages form source file and stores result into HttpResponse object. |
| [Extract](./extract/)(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Extracts specified pages from source file and stores result into HttpResponse object. |
| [get_AllowConcatenateExceptions](./get_allowconcatenateexceptions/)() | If set to true, exceptions are thrown if error occured. Else excetion are not thrown and methods return false if failed. |
| [get_AttachmentName](./get_attachmentname/)() const | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [get_CloseConcatenatedStreams](./get_closeconcatenatedstreams/)() const | If set to true, streams are closed after operation. |
| [get_ConcatenationPacketSize](./get_concatenationpacketsize/)() const | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [get_ConversionLog](./get_conversionlog/)() | Gets log of conversion process. |
| [get_CopyLogicalStructure](./get_copylogicalstructure/)() const | If true then logical structure of the file is copied when concatenation is performed. |
| [get_CopyOutlines](./get_copyoutlines/)() const | If true then outlines will be copied. |
| [get_CorruptedFileAction](./get_corruptedfileaction/)() const | This property defines behavior when concatenating process met corrupted file. Possible values are: StopWithError and ConcatenateIgnoringCorrupted. |
| [get_CorruptedItems](./get_corrupteditems/)() | Array of encountered problems when concatenation was performed. For every corrupted document from passed to [Concatenate()](./concatenate/) function new [CorruptedItem](./corrupteditem/) entry is created. This property may be used only when CorruptedFileAction is ConcatenateIgnoringCorrupted. |
| [get_IncrementalUpdates](./get_incrementalupdates/)() const | If true, incremental updates are made during concatenation. |
| [get_KeepActions](./get_keepactions/)() const | If true actions will be copied from source documents. Defaulkt value : true. |
| [get_KeepFieldsUnique](./get_keepfieldsunique/)() const | If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property. |
| [get_LastException](./get_lastexception/)() const | Gets last occured exception. May be used to check the reason of failure. |
| [get_MergeDuplicateLayers](./get_mergeduplicatelayers/)() const | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document. |
| [get_MergeDuplicateOutlines](./get_mergeduplicateoutlines/)() const | If true, duplicate outlines are merged. |
| [get_OptimizeSize](./get_optimizesize/)() const | Gets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [get_OwnerPassword](./get_ownerpassword/)() const | Sets owner's password if the source input [Pdf](../../aspose.pdf/) file is encrypted. This property is not implemented yet. |
| [get_PreserveUserRights](./get_preserveuserrights/)() const | If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored. |
| [get_RemoveSignatures](./get_removesignatures/)() const | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [get_SaveOptions](./get_saveoptions/)() const | Gets save options when result is stored as HttpResponse. Default value: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_UniqueSuffix](./get_uniquesuffix/)() const | Format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| [get_UseDiskBuffer](./get_usediskbuffer/)() | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. |
| [Insert](./insert/)(System::String, int32_t, System::String, int32_t, int32_t, System::String) | Inserts pages from an other file into the [Pdf](../../aspose.pdf/) file at a position. |
| [Insert](./insert/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Inserts pages from an other file into the input [Pdf](../../aspose.pdf/) file. |
| [Insert](./insert/)(System::String, int32_t, System::String, System::ArrayPtr\<int32_t\>, System::String) | Inserts pages from an other file into the input [Pdf](../../aspose.pdf/) file. |
| [Insert](./insert/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) | Inserts pages from an other file into the input [Pdf](../../aspose.pdf/) file. |
| [Insert](./insert/)(System::String, int32_t, System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Inserts contents of file into source file and stores result into HttpResponse object. |
| [Insert](./insert/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Inserts document into other document and stores result into response object. |
| [MakeBooklet](./makebooklet/)(System::String, System::String) | Makes booklet from the input file to output file. |
| [MakeBooklet](./makebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Makes booklet from the InputStream to outputStream. |
| [MakeBooklet](./makebooklet/)(System::String, System::String, System::SharedPtr\<PageSize\>) | Makes booklet from the inputFile to outputFile. |
| [MakeBooklet](./makebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>) | Makes booklet from the input stream and save result into output stream. |
| [MakeBooklet](./makebooklet/)(System::String, System::String, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) | Makes customized booklet from the firstInputFile to outputFile. |
| [MakeBooklet](./makebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) | Makes customized booklet from the firstInputStream to outputStream. |
| [MakeBooklet](./makebooklet/)(System::String, System::String, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) | Makes customized booklet from the firstInputFile to outputFile. |
| [MakeBooklet](./makebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) | Makes booklet from the firstInputStream to outputStream. |
| [MakeBooklet](./makebooklet/)(System::String, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes booklet from source file and stores result into HttpResponse objects. |
| [MakeBooklet](./makebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Make booklet from PDF file and stores it into HttpResponse. |
| [MakeBooklet](./makebooklet/)(System::String, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes booklet from source file and stores result into HttpResponse objects. |
| [MakeBooklet](./makebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes booklet from source file and stores result into HttpResponse. |
| [MakeNUp](./makenup/)(System::String, System::String, int32_t, int32_t) | Makes N-Up document from the firstInputFile to outputFile. |
| [MakeNUp](./makenup/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t) | Makes N-Up document from the input stream and saves result into output stream. |
| [MakeNUp](./makenup/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<PageSize\>) | Makes N-Up document from the first input stream to output stream. |
| [MakeNUp](./makenup/)(System::String, System::String, System::String) | Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally. |
| [MakeNUp](./makenup/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Makes N-Up document from the two input PDF streams to outputStream. |
| [MakeNUp](./makenup/)(System::ArrayPtr\<System::String\>, System::String, bool) | Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false. |
| [MakeNUp](./makenup/)(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::IO::Stream\>, bool) | Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false. |
| [MakeNUp](./makenup/)(System::String, System::String, int32_t, int32_t, System::SharedPtr\<PageSize\>) | Makes N-Up document from the input file to outputFile. |
| [MakeNUp](./makenup/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes N-up document and stores result into HttpResponse object. |
| [MakeNUp](./makenup/)(System::String, int32_t, int32_t, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes N-up document and stores result into HttpResponse object. |
| [MakeNUp](./makenup/)(System::String, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Makes N-up document and stores result into HttpResponse. |
| [MakeNUp](./makenup/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Makes N-up document and stores result into HttpResponse. |
| [PdfFileEditor](./pdffileeditor/)() | [PdfFileEditor](./) constructor. |
| [ResizeContents](./resizecontents/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) | Resizes contents of pages of the document. |
| [ResizeContents](./resizecontents/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units. |
| [ResizeContents](./resizecontents/)(System::String, System::String, System::ArrayPtr\<int32_t\>, double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units. |
| [ResizeContents](./resizecontents/)(System::String, System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) | Resizes contents of pages in document. If page is shrinked blank margins are added around the page. |
| [ResizeContents](./resizecontents/)(System::SharedPtr\<Document\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) | Resizes pages of document. Blank margins are added around of shrinked page. |
| [ResizeContents](./resizecontents/)(System::SharedPtr\<Document\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) | Resizes pages of document. Blank margins are added around of shrinked page. |
| [ResizeContents](./resizecontents/)(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>, System::SharedPtr\<System::Web::HttpResponse\>) | Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object. |
| [ResizeContents](./resizecontents/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>, System::SharedPtr\<System::Web::HttpResponse\>) | Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object. |
| [ResizeContentsPct](./resizecontentspct/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents. |
| [ResizeContentsPct](./resizecontentspct/)(System::String, System::String, System::ArrayPtr\<int32_t\>, double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents. |
| [set_AllowConcatenateExceptions](./set_allowconcatenateexceptions/)(bool) | If set to true, exceptions are thrown if error occured. Else excetion are not thrown and methods return false if failed. |
| [set_AttachmentName](./set_attachmentname/)(System::String) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [set_CloseConcatenatedStreams](./set_closeconcatenatedstreams/)(bool) | If set to true, streams are closed after operation. |
| [set_ConcatenationPacketSize](./set_concatenationpacketsize/)(int32_t) | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [set_CopyLogicalStructure](./set_copylogicalstructure/)(bool) | If true then logical structure of the file is copied when concatenation is performed. |
| [set_CopyOutlines](./set_copyoutlines/)(bool) | If true then outlines will be copied. |
| [set_CorruptedFileAction](./set_corruptedfileaction/)(PdfFileEditor::ConcatenateCorruptedFileAction) | This property defines behavior when concatenating process met corrupted file. Possible values are: StopWithError and ConcatenateIgnoringCorrupted. |
| [set_IncrementalUpdates](./set_incrementalupdates/)(bool) | If true, incremental updates are made during concatenation. |
| [set_KeepActions](./set_keepactions/)(bool) | If true actions will be copied from source documents. Defaulkt value : true. |
| [set_KeepFieldsUnique](./set_keepfieldsunique/)(bool) | If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property. |
| [set_MergeDuplicateLayers](./set_mergeduplicatelayers/)(bool) | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document. |
| [set_MergeDuplicateOutlines](./set_mergeduplicateoutlines/)(bool) | If true, duplicate outlines are merged. |
| [set_OptimizeSize](./set_optimizesize/)(bool) | Sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [set_OwnerPassword](./set_ownerpassword/)(System::String) | Sets owner's password if the source input [Pdf](../../aspose.pdf/) file is encrypted. This property is not implemented yet. |
| [set_PreserveUserRights](./set_preserveuserrights/)(bool) | If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored. |
| [set_RemoveSignatures](./set_removesignatures/)(bool) | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [set_SaveOptions](./set_saveoptions/)(System::SharedPtr\<Aspose::Pdf::SaveOptions\>) | Sets save options when result is stored as HttpResponse. Default value: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_UniqueSuffix](./set_uniquesuffix/)(System::String) | Format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| [set_UseDiskBuffer](./set_usediskbuffer/)(bool) | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. |
| [SplitFromFirst](./splitfromfirst/)(System::String, int32_t, System::String) | Splits [Pdf](../../aspose.pdf/) file from first page to specified location,and saves the front part as a new file. |
| [SplitFromFirst](./splitfromfirst/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>) | Splits from start to specified location,and saves the front part in output Stream. |
| [SplitFromFirst](./splitfromfirst/)(System::String, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Splits document from first page to location and saves result into HttpResponse objects. |
| [SplitFromFirst](./splitfromfirst/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Splits document from start to specified location and stores result into HttpResponse object. |
| [SplitToBulks](./splittobulks/)(System::String, System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>) | Splits the [Pdf](../../aspose.pdf/) file into several documents.The documents can be single-page or multi-pages. |
| [SplitToBulks](./splittobulks/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>) | Splits the [Pdf](../../aspose.pdf/) file into several documents.The documents can be single-page or multi-pages. |
| [SplitToEnd](./splittoend/)(System::String, int32_t, System::String) | Splits from location, and saves the rear part as a new file. |
| [SplitToEnd](./splittoend/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>) | Splits from specified location, and saves the rear part as a new file Stream. |
| [SplitToEnd](./splittoend/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Splits from specified location, and saves the rear part into HttpResponse object. |
| [SplitToEnd](./splittoend/)(System::String, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Splits from specified location, and saves the rear part into HttpResponse object. |
| [SplitToPages](./splittopages/)(System::String) | Splits the PDF file into single-page documents. |
| [SplitToPages](./splittopages/)(System::SharedPtr\<System::IO::Stream\>) | Splits the [Pdf](../../aspose.pdf/) file into single-page documents. |
| [SplitToPages](./splittopages/)(System::String, System::String) | Split the [Pdf](../../aspose.pdf/) file into single-page documents and saves it into specified path. Path is specifield by field name temaplate. |
| [SplitToPages](./splittopages/)(System::SharedPtr\<System::IO::Stream\>, System::String) | Split the [Pdf](../../aspose.pdf/) file into single-page documents and saves it into specified path. Path is specifield by field name temaplate. |
| [TryAppend](./tryappend/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage. |
| [TryAppend](./tryappend/)(System::String, System::ArrayPtr\<System::String\>, int32_t, int32_t, System::String) | Appends pages, which are chosen from portFiles documents. The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage. |
| [TryAppend](./tryappend/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Appends documents to source document and saves result into response object. |
| [TryAppend](./tryappend/)(System::String, System::ArrayPtr\<System::String\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Appends documents to source document and saves result into HttpResponse object. |
| [TryConcatenate](./tryconcatenate/)(System::String, System::String, System::String) | Concatenates two files. |
| [TryConcatenate](./tryconcatenate/)(System::ArrayPtr\<System::SharedPtr\<Document\>\>, System::SharedPtr\<Document\>) | Concatenates documents. |
| [TryConcatenate](./tryconcatenate/)(System::ArrayPtr\<System::String\>, System::String) | Concatenates files into one file. |
| [TryConcatenate](./tryconcatenate/)(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::IO::Stream\>) | Concatenates files. |
| [TryConcatenate](./tryconcatenate/)(System::String, System::String, System::String, System::String) | Merges two [Pdf](../../aspose.pdf/) documents into a new [Pdf](../../aspose.pdf/) document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two [Pdf](../../aspose.pdf/) document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](./tryconcatenate/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Merges two [Pdf](../../aspose.pdf/) documents into a new [Pdf](../../aspose.pdf/) document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two [Pdf](../../aspose.pdf/) document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](./tryconcatenate/)(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::Web::HttpResponse\>) | Concatenates files and saves reslt into HttpResposnse object. |
| [TryConcatenate](./tryconcatenate/)(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::Web::HttpResponse\>) | Concatenates files and stores result into HttpResponse object. |
| [TryDelete](./trydelete/)(System::String, System::ArrayPtr\<int32_t\>, System::String) | Deletes pages specified by number array from input file, saves as a new [Pdf](../../aspose.pdf/) file. |
| [TryDelete](./trydelete/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) | Deletes pages specified by number array from input file, saves as a new [Pdf](../../aspose.pdf/) file. |
| [TryDelete](./trydelete/)(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Deletes specified pages from document and stores result into HttpResponse object. |
| [TryDelete](./trydelete/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Deletes specified pages from document and saves result into HttpResponse object. |
| [TryExtract](./tryextract/)(System::String, int32_t, int32_t, System::String) | Extracts pages from input file,saves as a new [Pdf](../../aspose.pdf/) file. |
| [TryExtract](./tryextract/)(System::String, System::ArrayPtr\<int32_t\>, System::String) | Extracts pages specified by number array, saves as a new PDF file. |
| [TryExtract](./tryextract/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) | Extracts pages specified by number array, saves as a new [Pdf](../../aspose.pdf/) file. |
| [TryExtract](./tryextract/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Extracts specified pages form source file and stores result into HttpResponse object. |
| [TryExtract](./tryextract/)(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Extracts specified pages from source file and stores result into HttpResponse object. |
| [TryInsert](./tryinsert/)(System::String, int32_t, System::String, System::ArrayPtr\<int32_t\>, System::String) | Inserts pages from an other file into the input [Pdf](../../aspose.pdf/) file. |
| [TryInsert](./tryinsert/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::IO::Stream\>) | Inserts pages from an other file into the input [Pdf](../../aspose.pdf/) file. |
| [TryInsert](./tryinsert/)(System::String, int32_t, System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Inserts contents of file into source file and stores result into HttpResponse object. |
| [TryInsert](./tryinsert/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Inserts document into other document and stores result into response object. |
| [TryMakeBooklet](./trymakebooklet/)(System::String, System::String) | Makes booklet from the input file to output file. |
| [TryMakeBooklet](./trymakebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Makes booklet from the InputStream to outputStream. |
| [TryMakeBooklet](./trymakebooklet/)(System::String, System::String, System::SharedPtr\<PageSize\>) | Makes booklet from the inputFile to outputFile. |
| [TryMakeBooklet](./trymakebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>) | Makes booklet from the input stream and save result into output stream. |
| [TryMakeBooklet](./trymakebooklet/)(System::String, System::String, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) | Makes customized booklet from the firstInputFile to outputFile. |
| [TryMakeBooklet](./trymakebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) | Makes customized booklet from the firstInputStream to outputStream. |
| [TryMakeBooklet](./trymakebooklet/)(System::String, System::String, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) | Makes customized booklet from the firstInputFile to outputFile. |
| [TryMakeBooklet](./trymakebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>) | Makes booklet from the firstInputStream to outputStream. |
| [TryMakeBooklet](./trymakebooklet/)(System::String, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes booklet from source file and stores result into HttpResponse objects. |
| [TryMakeBooklet](./trymakebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<System::Web::HttpResponse\>) | Make booklet from PDF file and stores it into HttpResponse. |
| [TryMakeBooklet](./trymakebooklet/)(System::String, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes booklet from source file and stores result into HttpResponse objects. |
| [TryMakeBooklet](./trymakebooklet/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes booklet from source file and stores result into HttpResponse. |
| [TryMakeNUp](./trymakenup/)(System::String, System::String, int32_t, int32_t) | Makes N-Up document from the firstInputFile to outputFile. |
| [TryMakeNUp](./trymakenup/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t) | Makes N-Up document from the input stream and saves result into output stream. |
| [TryMakeNUp](./trymakenup/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<PageSize\>) | Makes N-Up document from the first input stream to output stream. |
| [TryMakeNUp](./trymakenup/)(System::String, System::String, System::String) | Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally. |
| [TryMakeNUp](./trymakenup/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Makes N-Up document from the two input PDF streams to outputStream. |
| [TryMakeNUp](./trymakenup/)(System::ArrayPtr\<System::String\>, System::String, bool) | Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false. |
| [TryMakeNUp](./trymakenup/)(System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>, System::SharedPtr\<System::IO::Stream\>, bool) | Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false. |
| [TryMakeNUp](./trymakenup/)(System::String, System::String, int32_t, int32_t, System::SharedPtr\<PageSize\>) | Makes N-Up document from the input file to outputFile. |
| [TryMakeNUp](./trymakenup/)(System::String, int32_t, int32_t, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes N-up document and stores result into HttpResponse object. |
| [TryMakeNUp](./trymakenup/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<PageSize\>, System::SharedPtr\<System::Web::HttpResponse\>) | Makes N-up document and stores result into HttpResponse object. |
| [TryMakeNUp](./trymakenup/)(System::String, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Makes N-up document and stores result into HttpResponse. |
| [TryMakeNUp](./trymakenup/)(System::SharedPtr\<System::IO::Stream\>, int32_t, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Makes N-up document and stores result into HttpResponse. |
| [TryResizeContents](./tryresizecontents/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) | Resizes contents of pages of the document. |
| [TryResizeContents](./tryresizecontents/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units. |
| [TryResizeContents](./tryresizecontents/)(System::String, System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>) | Resizes contents of pages in document. If page is shrinked blank margins are added around the page. |
| [TryResizeContents](./tryresizecontents/)(System::String, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>, System::SharedPtr\<System::Web::HttpResponse\>) | Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object. |
| [TryResizeContents](./tryresizecontents/)(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>, System::SharedPtr\<System::Web::HttpResponse\>) | Resizes contents of pages in document. If page is shrinked blank margins are added around the page. Result is stored into HttpResponse object. |
| [TrySplitFromFirst](./trysplitfromfirst/)(System::String, int32_t, System::String) | Splits [Pdf](../../aspose.pdf/) file from first page to specified location,and saves the front part as a new file. |
| [TrySplitFromFirst](./trysplitfromfirst/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>) | Splits from start to specified location,and saves the front part in output Stream. |
| [TrySplitFromFirst](./trysplitfromfirst/)(System::String, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Splits document from first page to location and saves result into HttpResponse objects. |
| [TrySplitFromFirst](./trysplitfromfirst/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Splits document from start to specified location and stores result into HttpResponse object. |
| [TrySplitToEnd](./trysplittoend/)(System::String, int32_t, System::String) | Splits from location, and saves the rear part as a new file. |
| [TrySplitToEnd](./trysplittoend/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::IO::Stream\>) | Splits from specified location, and saves the rear part as a new file Stream. |
| [TrySplitToEnd](./trysplittoend/)(System::SharedPtr\<System::IO::Stream\>, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Splits from specified location, and saves the rear part into HttpResponse object. |
| [TrySplitToEnd](./trysplittoend/)(System::String, int32_t, System::SharedPtr\<System::Web::HttpResponse\>) | Splits from specified location, and saves the rear part into HttpResponse object. |
## See Also

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
