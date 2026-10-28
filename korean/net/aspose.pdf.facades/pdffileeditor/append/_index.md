---
title: "PdfFileEditor.Append"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. portStreams에 있는 문서 배열에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 portStreams 문서들의 페이지가 startPage에서 endPage 범위에 포함됩니다."
type: docs
weight: 250
url: /ko/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

portStreams의 문서 배열에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage부터 endPage까지 범위에 해당하는 모든 portStreams 문서의 페이지가 포함됩니다.

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 Pdf 스트림. |
| portStreams | Stream[] | 페이지를 복사할 문서. |
| startPage | Int32 | 페이지 시작은 portStreams 문서에서. |
| endPage | Int32 | 페이지 종료는 portStreams 문서에서 . |
| outputStream | Stream | 출력 Pdf 스트림. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

portFiles 문서에서 선택된 페이지를 추가합니다. 결과 문서에는 firstInputFile과 startPage부터 endPage까지 범위에 해당하는 모든 portFiles 문서의 페이지가 포함됩니다.

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일. |
| portFiles | String[] | 페이지를 복사할 문서. |
| startPage | Int32 | 페이지 시작은 portFiles 문서에서. |
| endPage | Int32 | 페이지 종료는 portFiles 문서에서 . |
| outputFile | String | 출력 Pdf 문서. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

portFile에서 startPage부터 endPage까지의 범위에서 선택된 페이지를 firstInputFile의 끝에 있는 portFile에 추가합니다.

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일. |
| portFile | String | Pdf 파일의 페이지들. |
| startPage | Int32 | 페이지 시작은 portFile에서. |
| endPage | Int32 | 페이지 종료는 portFile에서. |
| outputFile | String | 출력 Pdf 문서. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

portStream에서 startPage부터 endPage까지의 범위에서 선택된 페이지를 firstInputStream의 끝에 있는 portStream에 추가합니다.

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 파일 스트림. |
| portStream | Stream | Pdf 파일 스트림의 페이지들. |
| startPage | Int32 | 페이지 시작은 portFile 스트림에서. |
| endPage | Int32 | 페이지 종료는 portFile 스트림에서. |
| outputStream | Stream | 출력 Pdf 파일 스트림. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


