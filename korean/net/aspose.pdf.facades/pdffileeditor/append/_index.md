---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. portStreams의 문서 배열에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage에서 endPage 범위의 모든 portStreams 문서 페이지가 포함됩니다.
type: docs
weight: 250
url: /ko/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

portStreams의 문서 배열에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage에서 endPage 범위의 모든 portStreams 문서 페이지가 포함됩니다.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | 입력 Pdf 스트림. |
| portStreams | Stream[] | 페이지를 복사할 문서. |
| startPage | Int32 | portStreams 문서에서 시작하는 페이지. |
| endPage | Int32 | portStreams 문서에서 끝나는 페이지. |
| outputStream | Stream | 출력 Pdf 스트림. |

### Return Value

성공 시 true, 실패 시 false.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

portFiles 문서에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage에서 endPage 범위의 모든 portFiles 문서 페이지가 포함됩니다.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일. |
| portFiles | String[] | 페이지를 복사할 문서. |
| startPage | Int32 | portFiles 문서에서 시작하는 페이지. |
| endPage | Int32 | portFiles 문서에서 끝나는 페이지. |
| outputFile | String | 출력 Pdf 문서. |

### Return Value

작업이 성공하면 true.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

startPage에서 endPage 범위 내의 portFile에서 선택된 페이지를 firstInputFile 끝에 추가합니다.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일. |
| portFile | String | Pdf 파일에서 페이지. |
| startPage | Int32 | portFile에서 시작하는 페이지. |
| endPage | Int32 | portFile에서 끝나는 페이지. |
| outputFile | String | 출력 Pdf 문서. |

### Return Value

작업이 성공하면 true.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

startPage에서 endPage 범위 내의 portStream에서 선택된 페이지를 firstInputStream 끝에 추가합니다.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | 입력 파일 스트림. |
| portStream | Stream | Pdf 파일 스트림에서 페이지. |
| startPage | Int32 | portFile 스트림에서 시작하는 페이지. |
| endPage | Int32 | portFile 스트림에서 끝나는 페이지. |
| outputStream | Stream | 출력 Pdf 파일 스트림. |

### Return Value

성공 시 true, 실패 시 false.

## Examples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)