---
title: "PdfFileEditor Class"
linktitle: "PdfFileEditor"
articleTitle: "PdfFileEditor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileEditor class. Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc."
type: docs
weight: 340
url: "/net/aspose.pdf.facades/pdffileeditor/"
keywords: "PdfFileEditor, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFileEditor class

Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc.

```csharp
public sealed class PdfFileEditor
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileEditor](./pdffileeditor/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CloseConcatenatedStreams](./closeconcatenatedstreams/) { get; set; } | If set to true, streams are closed after operation. |
| [ConcatenationPacketSize](./concatenationpacketsize/) { get; set; } | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. |
| [ConversionLog](./conversionlog/) { get; } | Gets log of conversion process. |
| [ConvertTo](./convertto/) { set; } | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [CopyLogicalStructure](./copylogicalstructure/) { get; set; } | If true then logical structure of the file is copied when concatenation is performed. |
| [CopyOutlines](./copyoutlines/) { get; set; } | If true then outlines will be copied. |
| [CorruptedFileAction](./corruptedfileaction/) { get; set; } | This property defines behavior when concatenating process met corrupted file. Possible values are: StopWithError and ConcatenateIgnoringCorrupted. |
| [CorruptedItems](./corrupteditems/) { get; } | Array of encountered problems when concatenation was performed. For every corrupted document from passed to Concatenate() function new CorruptedItem entry is created. This property may be used only when CorruptedFileAction is ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](./incrementalupdates/) { get; set; } | If true, incremental updates are made during concatenation. |
| [KeepActions](./keepactions/) { get; set; } | If true actions will be copied from source documents. Defaulkt value : true. |
| [KeepFieldsUnique](./keepfieldsunique/) { get; set; } | If true then field names will be made unique when forms are concatenated. Suffixes will be added to field names, suffix template may be specified in UniqueSuffix property. |
| [LastException](./lastexception/) { get; } | Gets last occured exception. May be used to check the reason of failure. |
| [MergeDuplicateLayers](./mergeduplicatelayers/) { get; set; } | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. Else, layers with equal names will be save as different layers in resultant document. |
| [MergeDuplicateOutlines](./mergeduplicateoutlines/) { get; set; } | If true, duplicate outlines are merged. |
| [OptimizeSize](./optimizesize/) { get; set; } | Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [OwnerPassword](./ownerpassword/) { get; set; } | Sets owner's password if the source input Pdf file is encrypted. This property is not implemented yet. |
| [PreserveUserRights](./preserveuserrights/) { get; set; } | If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored. |
| [RemoveSignatures](./removesignatures/) { get; set; } | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [UniqueSuffix](./uniquesuffix/) { get; set; } | Format of the suffix which is added to field name to make it unique when forms are concatenated. This string must contain %NUM% substring which will be replaced with numbers. For example if UniqueSuffix = "ABC%NUM%" then for field "fieldName" names will be: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| [UseDiskBuffer](./usediskbuffer/) { get; set; } | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. |

## Methods

| Name | Description |
| --- | --- |
| [AddMargins](./addmargins/)(Stream, Stream, int[], double, double, double, double) | Resizes page contents and add specifed margins. Margins are specified in default space units. |
| [AddMargins](./addmargins/)(string, string, int[], double, double, double, double) | Resizes page contents and add specifed margins. Margins are specified in default space units. |
| [AddMarginsPct](./addmarginspct/)(Stream, Stream, int[], double, double, double, double) | Resizes page contents and add specified margins. Margins are specified in percents of intitial page size. |
| [AddMarginsPct](./addmarginspct/)(string, string, int[], double, double, double, double) | Resizes page contents and add specified margins. Margins are specified in percents of intitial page size. |
| [AddPageBreak](./addpagebreak/)(Document, Document, PageBreak[]) | Adds page breaks into document pages. |
| [AddPageBreak](./addpagebreak/)(Stream, Stream, PageBreak[]) | Adds page breaks into document pages. |
| [AddPageBreak](./addpagebreak/)(string, string, PageBreak[]) | Adds page breaks into document pages. |
| [Append](./append/)(Stream, Stream, int, int, Stream) | Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream. |
| [Append](./append/)(Stream, Stream[], int, int, Stream) | Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage. |
| [Append](./append/)(string, string, int, int, string) | Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile. |
| [Append](./append/)(string, string[], int, int, string) | Appends pages, which are chosen from portFiles documents. The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage. |
| [Concatenate](./concatenate/)(Document[], Document) | Concatenates documents. |
| [Concatenate](./concatenate/)(Stream[], Stream) | Concatenates files |
| [Concatenate](./concatenate/)(string[], string) | Concatenates files into one file. |
| [Concatenate](./concatenate/)(Stream, Stream, Stream) | Concatenates two files. |
| [Concatenate](./concatenate/)(string, string, string) | Concatenates two files. |
| [Concatenate](./concatenate/)(Stream, Stream, Stream, Stream) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](./concatenate/)(string, string, string, string) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Delete](./delete/)(Stream, int[], Stream) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [Delete](./delete/)(string, int[], string) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [Extract](./extract/)(Stream, int[], Stream) | Extracts pages specified by number array, saves as a new Pdf file. |
| [Extract](./extract/)(string, int[], string) | Extracts pages specified by number array, saves as a new PDF file. |
| [Extract](./extract/)(Stream, int, int, Stream) | Extracts pages from input file,saves as a new Pdf file. |
| [Extract](./extract/)(string, int, int, string) | Extracts pages from input file,saves as a new Pdf file. |
| [Insert](./insert/)(Stream, int, Stream, int[], Stream) | Inserts pages from an other file into the input Pdf file. |
| [Insert](./insert/)(string, int, string, int[], string) | Inserts pages from an other file into the input Pdf file. |
| [Insert](./insert/)(Stream, int, Stream, int, int, Stream) | Inserts pages from an other file into the input Pdf file. |
| [Insert](./insert/)(string, int, string, int, int, string) | Inserts pages from an other file into the Pdf file at a position. |
| [MakeBooklet](./makebooklet/)(Stream, Stream) | Makes booklet from the InputStream to outputStream. |
| [MakeBooklet](./makebooklet/)(string, string) | Makes booklet from the input file to output file. |
| [MakeBooklet](./makebooklet/)(Stream, Stream, PageSize) | Makes booklet from the input stream and save result into output stream. |
| [MakeBooklet](./makebooklet/)(string, string, PageSize) | Makes booklet from the inputFile to outputFile. |
| [MakeBooklet](./makebooklet/)(Stream, Stream, int[], int[]) | Makes customized booklet from the firstInputStream to outputStream. |
| [MakeBooklet](./makebooklet/)(string, string, int[], int[]) | Makes customized booklet from the firstInputFile to outputFile. |
| [MakeBooklet](./makebooklet/)(Stream, Stream, PageSize, int[], int[]) | Makes booklet from the firstInputStream to outputStream. |
| [MakeBooklet](./makebooklet/)(string, string, PageSize, int[], int[]) | Makes customized booklet from the firstInputFile to outputFile. |
| [MakeNUp](./makenup/)(Stream, Stream, Stream) | Makes N-Up document from the two input PDF streams to outputStream. |
| [MakeNUp](./makenup/)(Stream[], Stream, bool) | Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false. |
| [MakeNUp](./makenup/)(string, string, string) | Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally. |
| [MakeNUp](./makenup/)(string[], string, bool) | Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false. |
| [MakeNUp](./makenup/)(Stream, Stream, int, int) | Makes N-Up document from the input stream and saves result into output stream. |
| [MakeNUp](./makenup/)(string, string, int, int) | Makes N-Up document from the firstInputFile to outputFile. |
| [MakeNUp](./makenup/)(Stream, Stream, int, int, PageSize) | Makes N-Up document from the first input stream to output stream. |
| [MakeNUp](./makenup/)(string, string, int, int, PageSize) | Makes N-Up document from the input file to outputFile. |
| [ResizeContents](./resizecontents/)(Document, ContentsResizeParameters) | Resizes pages of document. Blank margins are added around of shrinked page. |
| [ResizeContents](./resizecontents/)(Document, int[], ContentsResizeParameters) | Resizes pages of document. Blank margins are added around of shrinked page. |
| [ResizeContents](./resizecontents/)(Stream, Stream, int[], ContentsResizeParameters) | Resizes contents of pages of the document. |
| [ResizeContents](./resizecontents/)(string, string, int[], ContentsResizeParameters) | Resizes contents of pages in document. If page is shrinked blank margins are added around the page. |
| [ResizeContents](./resizecontents/)(Stream, Stream, int[], double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units. |
| [ResizeContents](./resizecontents/)(string, string, int[], double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units. |
| [ResizeContentsPct](./resizecontentspct/)(Stream, Stream, int[], double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents. |
| [ResizeContentsPct](./resizecontentspct/)(string, string, int[], double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New contents size is specified in percents. |
| [SplitFromFirst](./splitfromfirst/)(Stream, int, Stream) | Splits from start to specified location,and saves the front part in output Stream. |
| [SplitFromFirst](./splitfromfirst/)(string, int, string) | Splits Pdf file from first page to specified location,and saves the front part as a new file. |
| [SplitToBulks](./splittobulks/)(Stream, int[][]) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [SplitToBulks](./splittobulks/)(string, int[][]) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [SplitToEnd](./splittoend/)(Stream, int, Stream) | Splits from specified location, and saves the rear part as a new file Stream. |
| [SplitToEnd](./splittoend/)(string, int, string) | Splits from location, and saves the rear part as a new file. |
| [SplitToPages](./splittopages/)(Stream) | Splits the Pdf file into single-page documents. |
| [SplitToPages](./splittopages/)(string) | Splits the PDF file into single-page documents. |
| [SplitToPages](./splittopages/)(Stream, string) | Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate. |
| [SplitToPages](./splittopages/)(string, string) | Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate. |
| [TryAppend](./tryappend/)(Stream, Stream[], int, int, Stream) | Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage. |
| [TryAppend](./tryappend/)(string, string[], int, int, string) | Appends pages, which are chosen from portFiles documents. The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage. |
| [TryConcatenate](./tryconcatenate/)(Document[], Document) | Concatenates documents. |
| [TryConcatenate](./tryconcatenate/)(Stream[], Stream) | Concatenates files |
| [TryConcatenate](./tryconcatenate/)(string[], string) | Concatenates files into one file. |
| [TryConcatenate](./tryconcatenate/)(string, string, string) | Concatenates two files. |
| [TryConcatenate](./tryconcatenate/)(Stream, Stream, Stream, Stream) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](./tryconcatenate/)(string, string, string, string) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. e.g.: document1 has 5 pages: p1, p2, p3, p4, p5. document2 has 3 pages: p1', p2', p3'. Merging the two Pdf document will produce the result document with pages:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryDelete](./trydelete/)(Stream, int[], Stream) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [TryDelete](./trydelete/)(string, int[], string) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [TryExtract](./tryextract/)(Stream, int[], Stream) | Extracts pages specified by number array, saves as a new Pdf file. |
| [TryExtract](./tryextract/)(string, int[], string) | Extracts pages specified by number array, saves as a new PDF file. |
| [TryExtract](./tryextract/)(string, int, int, string) | Extracts pages from input file,saves as a new Pdf file. |
| [TryInsert](./tryinsert/)(Stream, int, Stream, int[], Stream) | Inserts pages from an other file into the input Pdf file. |
| [TryInsert](./tryinsert/)(string, int, string, int[], string) | Inserts pages from an other file into the input Pdf file. |
| [TryMakeBooklet](./trymakebooklet/)(Stream, Stream) | Makes booklet from the InputStream to outputStream. |
| [TryMakeBooklet](./trymakebooklet/)(string, string) | Makes booklet from the input file to output file. |
| [TryMakeBooklet](./trymakebooklet/)(Stream, Stream, PageSize) | Makes booklet from the input stream and save result into output stream. |
| [TryMakeBooklet](./trymakebooklet/)(string, string, PageSize) | Makes booklet from the inputFile to outputFile. |
| [TryMakeBooklet](./trymakebooklet/)(Stream, Stream, int[], int[]) | Makes customized booklet from the firstInputStream to outputStream. |
| [TryMakeBooklet](./trymakebooklet/)(string, string, int[], int[]) | Makes customized booklet from the firstInputFile to outputFile. |
| [TryMakeBooklet](./trymakebooklet/)(Stream, Stream, PageSize, int[], int[]) | Makes booklet from the firstInputStream to outputStream. |
| [TryMakeBooklet](./trymakebooklet/)(string, string, PageSize, int[], int[]) | Makes customized booklet from the firstInputFile to outputFile. |
| [TryMakeNUp](./trymakenup/)(Stream, Stream, Stream) | Makes N-Up document from the two input PDF streams to outputStream. |
| [TryMakeNUp](./trymakenup/)(Stream[], Stream, bool) | Makes N-Up document from the multi input PDF streams to outputStream. Each page of outputStream will contain multi pages, which are combination with pages in the input streams of the same page number. The multi-pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false. |
| [TryMakeNUp](./trymakenup/)(string, string, string) | Makes N-Up document from the two input PDF files to outputFile. Each page of outputFile will contain two pages, one page is from the first input file and another is from the second input file. The two pages are piled up horizontally. |
| [TryMakeNUp](./trymakenup/)(string[], string, bool) | Makes N-Up document from the multi input PDF files to outputFile. Each page of outputFile will contain multi pages, which are combination with pages in the input files of the same page number. The multi pages piled up horizontally if isSidewise is true and piled up vertically if isSidewise is false. |
| [TryMakeNUp](./trymakenup/)(Stream, Stream, int, int) | Makes N-Up document from the input stream and saves result into output stream. |
| [TryMakeNUp](./trymakenup/)(string, string, int, int) | Makes N-Up document from the firstInputFile to outputFile. |
| [TryMakeNUp](./trymakenup/)(Stream, Stream, int, int, PageSize) | Makes N-Up document from the first input stream to output stream. |
| [TryMakeNUp](./trymakenup/)(string, string, int, int, PageSize) | Makes N-Up document from the input file to outputFile. |
| [TryResizeContents](./tryresizecontents/)(Stream, Stream, int[], ContentsResizeParameters) | Resizes contents of pages of the document. |
| [TryResizeContents](./tryresizecontents/)(string, string, int[], ContentsResizeParameters) | Resizes contents of pages in document. If page is shrinked blank margins are added around the page. |
| [TryResizeContents](./tryresizecontents/)(Stream, Stream, int[], double, double) | Resizes contents of document pages. Shrinks contents of page and adds margins. New size of contents is specified in default space units. |
| [TrySplitFromFirst](./trysplitfromfirst/)(Stream, int, Stream) | Splits from start to specified location,and saves the front part in output Stream. |
| [TrySplitFromFirst](./trysplitfromfirst/)(string, int, string) | Splits Pdf file from first page to specified location,and saves the front part as a new file. |
| [TrySplitToEnd](./trysplittoend/)(Stream, int, Stream) | Splits from specified location, and saves the rear part as a new file Stream. |
| [TrySplitToEnd](./trysplittoend/)(string, int, string) | Splits from location, and saves the rear part as a new file. |

## Other Members

| Name | Description |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Action performed when corrupted file was met in concatenation process. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Class for specifing page resize parameters. Allow to set the following parameters: Size of result page (width, height) in default space units or in percents of initial pages size; Left, Top, Bottom and Right margins in default space units or in percents of initial page size; Some values may be left null for automatic calculation. These values will be calculated from rest of page size after calculation explicitly specified values. For example: if page width = 100 and new page width specified 60 units then left and right margins are automatically calculated: (100 - 60) / 2 = 15. This class is used in ResizeContents method. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Value of margin or content size specified in percents of default space units. This class is used in ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Class which provides information about corrupted files in time of concatenation. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Data of page break position. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

