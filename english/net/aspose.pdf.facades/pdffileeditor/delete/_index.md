---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor method. Deletes pages specified by number array from input file saves as a new Pdf file
type: docs
weight: 270
url: /net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

Deletes pages specified by number array from input file, saves as a new Pdf file.

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Input file path. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputFile | String | Output file path. |

### Return Value

True if operation was succeeded.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

Deletes pages specified by number array from input file, saves as a new Pdf file.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Input file Stream. |
| pageNumber | Int32[] | Index of page out of the input file. |
| outputStream | Stream | Output file stream. |

### Return Value

True for success, or false.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## Delete(string, int[], HttpResponse) {#delete_3}

Deletes specified pages from document and stores result into HttpResponse object.

```csharp
public bool Delete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Path of source file. |
| pageNumber | Int32[] | Array of page numbers which must be deleted. |
| response | HttpResponse | Response object where result document will be stored. |

### Return Value

True if operation was succeeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], HttpResponse) {#delete_1}

Deletes specified pages from document and saves result into HttpResponse object.

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Source document stream. |
| pageNumber | Int32[] | Array of page numbers which will be deleted. |
| response | HttpResponse | HttpResponse object |

### Return Value

True if operation succeded.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


