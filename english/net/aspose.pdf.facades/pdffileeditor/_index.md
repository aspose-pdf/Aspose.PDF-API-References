---
title: "PdfFileEditor Class"
linktitle: "PdfFileEditor"
articleTitle: "PdfFileEditor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileEditor class. Implements operations with PDF file: concatenation, splitting, extracting pages, making booklet, etc."
type: docs
weight: 350
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
| [PdfFileEditor](./pdffileeditor/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AllowConcatenateExceptions](./allowconcatenateexceptions/) { get; set; } | If set to true, exceptions are thrown if error occured. Else excetion are not thrown and methods return false if failed. |
| [CloseConcatenatedStreams](./closeconcatenatedstreams/) { get; set; } | If set to true, streams are closed after operation. |
| [ConcatenationPacketSize](./concatenationpacketsize/) { get; set; } | Number of documents concatenated before new incremental update was made during concatenation when UseDiskBuffer is set to true. |
| [ConversionLog](./conversionlog/) { get; } | Gets log of conversion process. |
| [ConvertTo](./convertto/) { set; } | Sets PDF file format. Result file will be saved in specified file format. |
| [CopyLogicalStructure](./copylogicalstructure/) { get; set; } | If true then logical structure of the file is copied when concatenation is performed. |
| [CopyOutlines](./copyoutlines/) { get; set; } | If true then outlines will be copied. |
| [CorruptedFileAction](./corruptedfileaction/) { get; set; } | This property defines behavior when concatenating process met corrupted file. |
| [CorruptedItems](./corrupteditems/) { get; } | Array of encountered problems when concatenation was performed. For every corrupted document from passed to Concatenate(). |
| [IncrementalUpdates](./incrementalupdates/) { get; set; } | If true, incremental updates are made during concatenation. |
| [KeepActions](./keepactions/) { get; set; } | If true actions will be copied from source documents. Defaulkt value : true. |
| [KeepFieldsUnique](./keepfieldsunique/) { get; set; } | If true then field names will be made unique when forms are concatenated. |
| [LastException](./lastexception/) { get; } | Gets last occured exception. May be used to check the reason of failure. |
| [MergeDuplicateLayers](./mergeduplicatelayers/) { get; set; } | Optional contents of concatentated documents with equal names will be merged into one layer in resulstant document if this property is true. |
| [MergeDuplicateOutlines](./mergeduplicateoutlines/) { get; set; } | If true, duplicate outlines are merged. |
| [OptimizeSize](./optimizesize/) { get; set; } | Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. |
| [OwnerPassword](./ownerpassword/) { get; set; } | Sets owner's password if the source input Pdf file is encrypted. |
| [PreserveUserRights](./preserveuserrights/) { get; set; } | If true, user rights of first document are applied to concatenated document. User rights of all other documents are ignored. |
| [RemoveSignatures](./removesignatures/) { get; set; } | If true, all signatures will be removed from fields (fields will remain); otherwise, you can get invalid signatures. |
| [UniqueSuffix](./uniquesuffix/) { get; set; } | Format of the suffix which is added to field name to make it unique when forms are concatenated. |
| [UseDiskBuffer](./usediskbuffer/) { get; set; } | If this option used then destination document will be saved on disk periodically and further concatenation will appllied to it as incremental updates. |

## Methods

| Name | Description |
| --- | --- |
| [AddMargins](./addmargins/)(*Stream, Stream, int[], double, double, double, double*) | Resizes page contents and add specifed margins. |
| [AddMargins](./addmargins/)(*string, string, int[], double, double, double, double*) | Resizes page contents and add specifed margins. |
| [AddMarginsPct](./addmarginspct/)(*Stream, Stream, int[], double, double, double, double*) | Resizes page contents and add specified margins. |
| [AddMarginsPct](./addmarginspct/)(*string, string, int[], double, double, double, double*) | Resizes page contents and add specified margins. |
| [AddPageBreak](./addpagebreak/)(*Document, Document, PageBreak[]*) |  |
| [AddPageBreak](./addpagebreak/)(*string, string, PageBreak[]*) |  |
| [AddPageBreak](./addpagebreak/)(*Stream, Stream, PageBreak[]*) |  |
| [Append](./append/)(*Stream, Stream[], int, int, Stream*) | Appends pages, which are chosen from array of documents in portStreams. |
| [Append](./append/)(*string, string[], int, int, string*) | Appends pages, which are chosen from portFiles documents. |
| [Append](./append/)(*string, string, int, int, string*) | Appends pages, which are chosen from portFile within the range from startPage to endPage, in portFile at the end of firstInputFile. |
| [Append](./append/)(*Stream, Stream, int, int, Stream*) | Appends pages,which are chosen from portStream within the range from startPage to endPage, in portStream at the end of firstInputStream. |
| [Concatenate](./concatenate/)(*Document[], Document*) | Concatenates documents. |
| [Concatenate](./concatenate/)(*string[], string*) | Concatenates files into one file. |
| [Concatenate](./concatenate/)(*Stream[], Stream*) | Concatenates files. |
| [Concatenate](./concatenate/)(*string, string, string*) | Concatenates two files. |
| [Concatenate](./concatenate/)(*Stream, Stream, Stream*) | Concatenates two files. |
| [Concatenate](./concatenate/)(*string, string, string, string*) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. |
| [Concatenate](./concatenate/)(*Stream, Stream, Stream, Stream*) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. |
| [Delete](./delete/)(*string, int[], string*) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [Delete](./delete/)(*Stream, int[], Stream*) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [Extract](./extract/)(*string, int[], string*) | Extracts pages specified by number array, saves as a new PDF file. |
| [Extract](./extract/)(*Stream, int[], Stream*) | Extracts pages specified by number array, saves as a new Pdf file. |
| [Extract](./extract/)(*string, int, int, string*) | Extracts pages from input file,saves as a new Pdf file. |
| [Extract](./extract/)(*Stream, int, int, Stream*) | Extracts pages from input file,saves as a new Pdf file. |
| [Insert](./insert/)(*string, int, string, int[], string*) | Inserts pages from an other file into the input Pdf file. |
| [Insert](./insert/)(*Stream, int, Stream, int[], Stream*) | Inserts pages from an other file into the input Pdf file. |
| [Insert](./insert/)(*string, int, string, int, int, string*) | Inserts pages from an other file into the Pdf file at a position. |
| [Insert](./insert/)(*Stream, int, Stream, int, int, Stream*) | Inserts pages from an other file into the input Pdf file. |
| [MakeBooklet](./makebooklet/)(*string, string*) | Makes booklet from the input file to output file. |
| [MakeBooklet](./makebooklet/)(*Stream, Stream*) | Makes booklet from the InputStream to outputStream. |
| [MakeBooklet](./makebooklet/)(*string, string, PageSize*) | Makes booklet from the inputFile to outputFile. |
| [MakeBooklet](./makebooklet/)(*Stream, Stream, PageSize*) | Makes booklet from the input stream and save result into output stream. |
| [MakeBooklet](./makebooklet/)(*string, string, int[], int[]*) | Makes customized booklet from the firstInputFile to outputFile. |
| [MakeBooklet](./makebooklet/)(*Stream, Stream, int[], int[]*) | Makes customized booklet from the firstInputStream to outputStream. |
| [MakeBooklet](./makebooklet/)(*string, string, PageSize, int[], int[]*) | Makes customized booklet from the firstInputFile to outputFile. |
| [MakeBooklet](./makebooklet/)(*Stream, Stream, PageSize, int[], int[]*) | Makes booklet from the firstInputStream to outputStream. |
| [MakeNUp](./makenup/)(*string, string, string*) | Makes N-Up document from the two input PDF files to outputFile. |
| [MakeNUp](./makenup/)(*Stream, Stream, Stream*) | Makes N-Up document from the two input PDF streams to outputStream. |
| [MakeNUp](./makenup/)(*string[], string, bool*) | Makes N-Up document from the multi input PDF files to outputFile. |
| [MakeNUp](./makenup/)(*Stream[], Stream, bool*) | Makes N-Up document from the multi input PDF streams to outputStream. |
| [MakeNUp](./makenup/)(*string, string, int, int*) | Makes N-Up document from the firstInputFile to outputFile. |
| [MakeNUp](./makenup/)(*Stream, Stream, int, int*) | Makes N-Up document from the input stream and saves result into output stream. |
| [MakeNUp](./makenup/)(*Stream, Stream, int, int, PageSize*) | Makes N-Up document from the first input stream to output stream. |
| [MakeNUp](./makenup/)(*string, string, int, int, PageSize*) | Makes N-Up document from the input file to outputFile. |
| [ResizeContents](./resizecontents/)(*Document, ContentsResizeParameters*) |  |
| [ResizeContents](./resizecontents/)(*Document, int[], ContentsResizeParameters*) |  |
| [ResizeContents](./resizecontents/)(*Stream, Stream, int[], ContentsResizeParameters*) |  |
| [ResizeContents](./resizecontents/)(*string, string, int[], ContentsResizeParameters*) |  |
| [ResizeContents](./resizecontents/)(*Stream, Stream, int[], double, double*) | Resizes contents of document pages. |
| [ResizeContents](./resizecontents/)(*string, string, int[], double, double*) | Resizes contents of document pages. |
| [ResizeContentsPct](./resizecontentspct/)(*Stream, Stream, int[], double, double*) | Resizes contents of document pages. |
| [ResizeContentsPct](./resizecontentspct/)(*string, string, int[], double, double*) | Resizes contents of document pages. |
| [SplitFromFirst](./splitfromfirst/)(*string, int, string*) | Splits Pdf file from first page to specified location,and saves the front part as a new file. |
| [SplitFromFirst](./splitfromfirst/)(*Stream, int, Stream*) | Splits from start to specified location,and saves the front part in output Stream. |
| [SplitToBulks](./splittobulks/)(*string, int[][]*) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [SplitToBulks](./splittobulks/)(*Stream, int[][]*) | Splits the Pdf file into several documents.The documents can be single-page or multi-pages. |
| [SplitToEnd](./splittoend/)(*string, int, string*) | Splits from location, and saves the rear part as a new file. |
| [SplitToEnd](./splittoend/)(*Stream, int, Stream*) | Splits from specified location, and saves the rear part as a new file Stream. |
| [SplitToPages](./splittopages/)(*string*) | Splits the PDF file into single-page documents. |
| [SplitToPages](./splittopages/)(*Stream*) | Splits the Pdf file into single-page documents. |
| [SplitToPages](./splittopages/)(*string, string*) | Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate. |
| [SplitToPages](./splittopages/)(*Stream, string*) | Split the Pdf file into single-page documents and saves it into specified path. Path is specifield by field name temaplate. |
| [TryAppend](./tryappend/)(*Stream, Stream[], int, int, Stream*) | Appends pages, which are chosen from array of documents in portStreams. |
| [TryAppend](./tryappend/)(*string, string[], int, int, string*) | Appends pages, which are chosen from portFiles documents. |
| [TryConcatenate](./tryconcatenate/)(*Document[], Document*) | Concatenates documents. |
| [TryConcatenate](./tryconcatenate/)(*string[], string*) | Concatenates files into one file. |
| [TryConcatenate](./tryconcatenate/)(*Stream[], Stream*) | Concatenates files. |
| [TryConcatenate](./tryconcatenate/)(*string, string, string*) | Concatenates two files. |
| [TryConcatenate](./tryconcatenate/)(*string, string, string, string*) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. |
| [TryConcatenate](./tryconcatenate/)(*Stream, Stream, Stream, Stream*) | Merges two Pdf documents into a new Pdf document with pages in alternate ways and fill the blank places with blank pages. |
| [TryDelete](./trydelete/)(*string, int[], string*) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [TryDelete](./trydelete/)(*Stream, int[], Stream*) | Deletes pages specified by number array from input file, saves as a new Pdf file. |
| [TryExtract](./tryextract/)(*string, int[], string*) | Extracts pages specified by number array, saves as a new PDF file. |
| [TryExtract](./tryextract/)(*Stream, int[], Stream*) | Extracts pages specified by number array, saves as a new Pdf file. |
| [TryExtract](./tryextract/)(*string, int, int, string*) | Extracts pages from input file,saves as a new Pdf file. |
| [TryInsert](./tryinsert/)(*string, int, string, int[], string*) | Inserts pages from an other file into the input Pdf file. |
| [TryInsert](./tryinsert/)(*Stream, int, Stream, int[], Stream*) | Inserts pages from an other file into the input Pdf file. |
| [TryMakeBooklet](./trymakebooklet/)(*string, string*) | Makes booklet from the input file to output file. |
| [TryMakeBooklet](./trymakebooklet/)(*Stream, Stream*) | Makes booklet from the InputStream to outputStream. |
| [TryMakeBooklet](./trymakebooklet/)(*string, string, PageSize*) | Makes booklet from the inputFile to outputFile. |
| [TryMakeBooklet](./trymakebooklet/)(*Stream, Stream, PageSize*) | Makes booklet from the input stream and save result into output stream. |
| [TryMakeBooklet](./trymakebooklet/)(*string, string, int[], int[]*) | Makes customized booklet from the firstInputFile to outputFile. |
| [TryMakeBooklet](./trymakebooklet/)(*Stream, Stream, int[], int[]*) | Makes customized booklet from the firstInputStream to outputStream. |
| [TryMakeBooklet](./trymakebooklet/)(*string, string, PageSize, int[], int[]*) | Makes customized booklet from the firstInputFile to outputFile. |
| [TryMakeBooklet](./trymakebooklet/)(*Stream, Stream, PageSize, int[], int[]*) | Makes booklet from the firstInputStream to outputStream. |
| [TryMakeNUp](./trymakenup/)(*string, string, string*) | Makes N-Up document from the two input PDF files to outputFile. |
| [TryMakeNUp](./trymakenup/)(*Stream, Stream, Stream*) | Makes N-Up document from the two input PDF streams to outputStream. |
| [TryMakeNUp](./trymakenup/)(*string[], string, bool*) | Makes N-Up document from the multi input PDF files to outputFile. |
| [TryMakeNUp](./trymakenup/)(*Stream[], Stream, bool*) | Makes N-Up document from the multi input PDF streams to outputStream. |
| [TryMakeNUp](./trymakenup/)(*string, string, int, int*) | Makes N-Up document from the firstInputFile to outputFile. |
| [TryMakeNUp](./trymakenup/)(*Stream, Stream, int, int*) | Makes N-Up document from the input stream and saves result into output stream. |
| [TryMakeNUp](./trymakenup/)(*Stream, Stream, int, int, PageSize*) | Makes N-Up document from the first input stream to output stream. |
| [TryMakeNUp](./trymakenup/)(*string, string, int, int, PageSize*) | Makes N-Up document from the input file to outputFile. |
| [TryResizeContents](./tryresizecontents/)(*Stream, Stream, int[], ContentsResizeParameters*) |  |
| [TryResizeContents](./tryresizecontents/)(*string, string, int[], ContentsResizeParameters*) |  |
| [TryResizeContents](./tryresizecontents/)(*Stream, Stream, int[], double, double*) | Resizes contents of document pages. |
| [TrySplitFromFirst](./trysplitfromfirst/)(*string, int, string*) | Splits Pdf file from first page to specified location,and saves the front part as a new file. |
| [TrySplitFromFirst](./trysplitfromfirst/)(*Stream, int, Stream*) | Splits from start to specified location,and saves the front part in output Stream. |
| [TrySplitToEnd](./trysplittoend/)(*string, int, string*) | Splits from location, and saves the rear part as a new file. |
| [TrySplitToEnd](./trysplittoend/)(*Stream, int, Stream*) | Splits from specified location, and saves the rear part as a new file Stream. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

