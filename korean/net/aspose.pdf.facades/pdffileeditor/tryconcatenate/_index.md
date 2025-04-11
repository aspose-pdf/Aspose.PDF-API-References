---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 두 파일을 연결합니다.
type: docs
weight: 390
url: /ko/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

두 파일을 연결합니다.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputFile | String | 연결할 첫 번째 파일. |
| secInputFile | String | 연결할 두 번째 파일. |
| outputFile | String | 출력 파일. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryConcatenate 메서드는 Concatenate 메서드와 유사하지만, TryConcatenate 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

문서를 연결합니다.

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| src | Document[] | 소스 문서 배열. |
| dest | Document | 대상 문서. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryConcatenate 메서드는 Concatenate 메서드와 유사하지만, TryConcatenate 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

파일을 하나의 파일로 연결합니다.

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFiles | String[] | 연결할 파일 배열. |
| outputFile | String | 출력 파일 이름. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryConcatenate 메서드는 Concatenate 메서드와 유사하지만, TryConcatenate 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

파일을 연결합니다.

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream[] | 연결할 스트림 배열. |
| outputStream | Stream | 결과 파일이 저장될 스트림. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryConcatenate 메서드는 Concatenate 메서드와 유사하지만, TryConcatenate 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

두 개의 Pdf 문서를 새로운 Pdf 문서로 병합하며, 페이지를 교대로 배치하고 빈 공간은 빈 페이지로 채웁니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고 있고, document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 페이지:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage를 생성합니다.

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputFile | String | 첫 번째 파일. |
| secInputFile | String | 두 번째 파일. |
| blankPageFile | String | 빈 페이지가 있는 PDF 파일. |
| outputFile | String | 결과 파일. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryConcatenate 메서드는 Concatenate 메서드와 유사하지만, TryConcatenate 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

두 개의 Pdf 문서를 새로운 Pdf 문서로 병합하며, 페이지를 교대로 배치하고 빈 공간은 빈 페이지로 채웁니다. 예: document1은 5페이지(p1, p2, p3, p4, p5)를 가지고 있고, document2는 3페이지(p1', p2', p3')를 가지고 있습니다. 두 Pdf 문서를 병합하면 결과 문서는 페이지:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage를 생성합니다.

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputStream | Stream | 첫 번째 Pdf 스트림. |
| secInputStream | Stream | 두 번째 Pdf 스트림. |
| blankPageStream | Stream | 빈 페이지가 있는 Pdf 스트림. |
| outputStream | Stream | 출력 Pdf 스트림. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryConcatenate 메서드는 Concatenate 메서드와 유사하지만, TryConcatenate 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

파일을 연결하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFiles | String[] | 연결할 파일 배열. |
| response | HttpResponse | 응답 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryConcatenate 메서드는 Concatenate 메서드와 유사하지만, TryConcatenate 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

파일을 연결하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream[] | 연결할 파일을 포함하는 스트림 배열. |
| response | HttpResponse | 응답 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryConcatenate 메서드는 Concatenate 메서드와 유사하지만, TryConcatenate 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)