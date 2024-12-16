---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor method. Appends pages which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage
type: docs
weight: 380
url: /net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

Appends pages, which are chosen from array of documents in portStreams. The result document includes firstInputFile and all portStreams documents pages in the range startPage to endPage.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input Pdf stream. |
| portStreams | Stream[] | Documents to copy pages from. |
| startPage | Int32 | Page starts in portStreams documents. |
| endPage | Int32 | Page ends in portStreams documents . |
| outputStream | Stream | Output Pdf stream. |

### Return Value

True for success, or false.

## Remarks

The TryAppend method is like the Append method, except the TryAppend method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

Appends pages, which are chosen from portFiles documents. The result document includes firstInputFile and all portFiles documents pages in the range startPage to endPage.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input Pdf file. |
| portFiles | String[] | Documents to copy pages from. |
| startPage | Int32 | Page starts in portFiles documents. |
| endPage | Int32 | Page ends in portFiles documents . |
| outputFile | String | Output Pdf document. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryAppend method is like the Append method, except the TryAppend method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

Appends documents to source document and saves result into response object.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream which contains source document. |
| portStreams | Stream[] | Array of streams with documents to be appended. |
| startPage | Int32 | Start page of appended page. |
| endPage | Int32 | End page of appended pages. |
| response | HttpResponse | Response object where document will be saved. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryAppend method is like the Append method, except the TryAppend method does not throw an exception if the operation fails.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

Appends documents to source document and saves result into HttpResponse object.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Name of file containing source document. |
| portFiles | String[] | Array of file names containing appended documents. |
| startPage | Int32 | Start page of appended pages. |
| endPage | Int32 | End page of appended pages. |
| response | HttpResponse | Response object where document will be saved. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TryAppend method is like the Append method, except the TryAppend method does not throw an exception if the operation fails.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


