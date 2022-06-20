---
title: TryInsert
second_title: Aspose.PDF for .NET API Reference
description: Inserts pages from an other file into the input Pdf file.
type: docs
weight: 450
url: /net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_2}

Inserts pages from an other file into the input Pdf file.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input Pdf file. |
| insertLocation | Int32 | Insert position in input file. |
| portFile | String | Pages from the Pdf file. |
| pageNumber | Int32[] | The page number of the ported in portFile. |
| outputFile | String | Output Pdf file. |

### Return Value

True for success, or false.

### Remarks

The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Inserts pages from an other file into the input Pdf file.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input Stream of Pdf file. |
| insertLocation | Int32 | Insert position in input file. |
| portStream | Stream | Stream of Pdf file for pages. |
| pageNumber | Int32[] | The page number of the ported in portFile. |
| outputStream | Stream | Output Stream. |

### Return Value

true if operation completed successfully; otherwise, false.

### Remarks

The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails.

### Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Inserts contents of file into source file and stores result into HttpResponse object.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source file name. |
| insertLocation | Int32 | Page number where second file will be inserted. |
| portFile | String | Path to file which will be inserted. |
| pageNumber | Int32[] | Array of page numbers in source file wihich will be inserted. |
| response | HttpResponse | Response object where result will be stored. |

### Return Value

true if operation completed successfully; otherwise, false.

### Remarks

The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails.

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Inserts document into other document and stores result into response object.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream with source document |
| insertLocation | Int32 | Location where other document will be inserted. |
| portStream | Stream | Document to be inserted. |
| pageNumber | Int32[] | Array of page numbers in second document which will be inserted. |
| response | HttpResponse | Response object where result will be stored. |

### Return Value

true if operation completed successfully; otherwise, false.

### Remarks

The TryInsert method is like the Insert method, except the TryInsert method does not throw an exception if the operation fails.

### See Also

* class [PdfFileEditor](../../pdffileeditor)
* namespace [Aspose.Pdf.Facades](../../pdffileeditor)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
