---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. portStreams의 문서 배열에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage에서 endPage 범위의 모든 portStreams 문서 페이지가 포함됩니다.
type: docs
weight: 380
url: /ko/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

portStreams의 문서 배열에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage에서 endPage 범위의 모든 portStreams 문서 페이지가 포함됩니다.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

## Remarks

TryAppend 메서드는 Append 메서드와 유사하지만, TryAppend 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

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

portFiles 문서에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage에서 endPage 범위의 모든 portFiles 문서 페이지가 포함됩니다.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## Remarks

TryAppend 메서드는 Append 메서드와 유사하지만, TryAppend 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

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

소스 문서에 문서를 추가하고 결과를 응답 객체에 저장합니다.

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | 소스 문서를 포함하는 스트림. |
| portStreams | Stream[] | 추가할 문서가 있는 스트림 배열. |
| startPage | Int32 | 추가된 페이지의 시작 페이지. |
| endPage | Int32 | 추가된 페이지의 끝 페이지. |
| response | HttpResponse | 문서가 저장될 응답 객체. |

### Return Value

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## Remarks

TryAppend 메서드는 Append 메서드와 유사하지만, TryAppend 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

소스 문서에 문서를 추가하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | 소스 문서를 포함하는 파일의 이름. |
| portFiles | String[] | 추가된 문서를 포함하는 파일 이름 배열. |
| startPage | Int32 | 추가된 페이지의 시작 페이지. |
| endPage | Int32 | 추가된 페이지의 끝 페이지. |
| response | HttpResponse | 문서가 저장될 응답 객체. |

### Return Value

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## Remarks

TryAppend 메서드는 Append 메서드와 유사하지만, TryAppend 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)