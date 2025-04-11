---
title: PdfFileEditor.Concatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 두 파일을 연결합니다.
type: docs
weight: 260
url: /ko/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

두 파일을 연결합니다.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | 연결할 첫 번째 파일. |
| secInputFile | String | 연결할 두 번째 파일. |
| outputFile | String | 출력 파일. |

### Return Value

작업이 성공하면 True입니다.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

두 파일을 연결합니다.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | 첫 번째 파일의 스트림. |
| secInputStream | Stream | 두 번째 파일의 스트림. |
| outputStream | Stream | 결과 파일이 저장될 스트림. |

### Return Value

작업이 성공하면 True입니다.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

문서를 연결합니다.

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| Parameter | Type | Description |
| --- | --- | --- |
| src | Document[] | 소스 문서 배열. |
| dest | Document | 대상 문서. |

### Return Value

연결이 성공하면 True입니다.

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

파일을 하나의 파일로 연결합니다.

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | 연결할 파일 배열. |
| outputFile | String | 출력 파일의 이름. |

### Return Value

작업이 성공하면 True입니다.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

파일을 연결합니다.

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | 연결할 스트림 배열. |
| outputStream | Stream | 결과 파일이 저장될 스트림. |

### Return Value

작업이 성공하면 True입니다.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

두 개의 Pdf 문서를 새로운 Pdf 문서로 병합하며 페이지를 교대로 배치하고 빈 공간은 빈 페이지로 채웁니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고 있습니다. document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 페이지:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage가 됩니다.

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputFile | String | 첫 번째 파일. |
| secInputFile | String | 두 번째 파일. |
| blankPageFile | String | 빈 페이지가 있는 PDF 파일. |
| outputFile | String | 결과 파일. |

### Return Value

작업이 성공하면 True입니다.

## Examples

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

두 개의 Pdf 문서를 새로운 Pdf 문서로 병합하며 페이지를 교대로 배치하고 빈 공간은 빈 페이지로 채웁니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고 있습니다. document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 페이지:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage가 됩니다.

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| firstInputStream | Stream | 첫 번째 Pdf 스트림. |
| secInputStream | Stream | 두 번째 Pdf 스트림. |
| blankPageStream | Stream | 빈 페이지가 있는 Pdf 스트림. |
| outputStream | Stream | 출력 Pdf 스트림. |

### Return Value

작업이 성공하면 True입니다.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## Concatenate(string[], HttpResponse) {#concatenate_8}

파일을 연결하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFiles | String[] | 연결할 파일 배열. |
| response | HttpResponse | 응답 객체. |

### Return Value

연결이 성공하면 true입니다.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

파일을 연결하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream[] | 연결할 파일을 포함하는 스트림 배열. |
| response | HttpResponse | 응답 객체. |

### Return Value

작업이 성공하면 true입니다.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)