---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor method. Splits Pdf file from first page to specified locationand saves the front part as a new file
type: docs
weight: 460
url: /net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Splits Pdf file from first page to specified location,and saves the front part as a new file.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source Pdf file. |
| location | Int32 | The splitting point. |
| outputFile | String | Output Pdf file. |

### Return Value

True for success, or false.

## Remarks

The TrySplitFromFirst method is like the SplitFromFirst method, except the TrySplitFromFirst method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Splits from start to specified location,and saves the front part in output Stream.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Source Pdf file Stream. |
| location | Int32 | The splitting point. |
| outputStream | Stream | Output file Stream. |

### Return Value

True for success, or false.

## Remarks

The streams are NOT closed after this operation. The TrySplitFromFirst method is like the SplitFromFirst method, except the TrySplitFromFirst method does not throw an exception if the operation fails.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Splits document from first page to location and saves result into HttpResponse objects.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | Source file name. |
| location | Int32 | Split point. |
| response | HttpResponse | HttpResponse objects. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TrySplitFromFirst method is like the SplitFromFirst method, except the TrySplitFromFirst method does not throw an exception if the operation fails.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Splits document from start to specified location and stores result into HttpResponse object.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Stream of source document. |
| location | Int32 | The splitting point. |
| response | HttpResponse | HttpResponse object where result will be stored. |

### Return Value

true if operation completed successfully; otherwise, false.

## Remarks

The TrySplitFromFirst method is like the SplitFromFirst method, except the TrySplitFromFirst method does not throw an exception if the operation fails.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


