---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 첫 번째 입력 파일에서 출력 파일로 NUp 문서를 만듭니다.
type: docs
weight: 440
url: /ko/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

N-up 문서를 만들고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 원본 파일의 경로. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |
| pageSize | PageSize | 결과 파일의 페이지 크기. |
| response | HttpResponse | 결과가 저장될 HttpResponse 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

N-up 문서를 만들고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 문서의 스트림. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |
| pageSize | PageSize | 결과 파일의 페이지 크기. |
| response | HttpResponse | 결과가 저장될 HttpResponse 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

N-up 문서를 만들고 결과를 HttpResponse에 저장합니다.

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 원본 파일 이름. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |
| response | HttpResponse | 결과가 저장될 HttpResponse 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

N-up 문서를 만들고 결과를 HttpResponse에 저장합니다.

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 문서의 스트림. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |
| response | HttpResponse | 결과가 저장될 HttpResponse. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

첫 번째 입력 파일에서 출력 파일로 N-Up 문서를 만듭니다.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 pdf 파일 경로 및 이름. |
| outputFile | String | 출력 pdf 파일 경로 및 이름. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

입력 스트림에서 N-Up 문서를 만들고 결과를 출력 스트림에 저장합니다.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 pdf 스트림. |
| outputStream | Stream | 출력 pdf 스트림. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

첫 번째 입력 스트림에서 출력 스트림으로 N-Up 문서를 만듭니다.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 pdf 스트림. |
| outputStream | Stream | 출력 pdf 스트림. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |
| pageSize | PageSize | 출력 pdf 파일의 페이지 크기. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

두 개의 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. outputFile의 각 페이지는 첫 번째 입력 파일의 한 페이지와 두 번째 입력 파일의 한 페이지를 포함합니다. 두 페이지는 수평으로 쌓입니다.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputFile | String | 첫 번째 입력 파일. |
| secondInputFile | String | 두 번째 입력 파일. |
| outputFile | String | 출력 pdf 파일 경로 및 이름. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

두 개의 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다.

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputStream | Stream | 첫 번째 입력 스트림. |
| secondInputStream | Stream | 두 번째 입력 스트림. |
| outputStream | Stream | 출력 pdf 스트림. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

여러 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. outputFile의 각 페이지는 동일한 페이지 번호의 입력 파일에서 페이지를 조합한 여러 페이지를 포함합니다. isSidewise가 true이면 여러 페이지가 수평으로 쌓이고, false이면 수직으로 쌓입니다.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFiles | String[] | 입력 Pdf 파일. |
| outputFile | String | 출력 pdf 파일 경로 및 이름. |
| isSidewise | Boolean | 쌓는 방식, true는 수평, false는 수직. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

여러 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다. outputStream의 각 페이지는 동일한 페이지 번호의 입력 스트림에서 페이지를 조합한 여러 페이지를 포함합니다. isSidewise가 true이면 여러 페이지가 수평으로 쌓이고, false이면 수직으로 쌓입니다.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStreams | Stream[] | 입력 Pdf 스트림. |
| outputStream | Stream | 출력 pdf 스트림. |
| isSidewise | Boolean | 쌓는 방식, true는 수평, false는 수직. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

입력 파일에서 outputFile로 N-Up 문서를 만듭니다.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 pdf 파일 경로 및 이름. |
| outputFile | String | 출력 pdf 파일 경로 및 이름. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |
| pageSize | PageSize | 출력 pdf 파일의 페이지 크기. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 유사하지만, TryMakeNUp 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### 참조

* 클래스 [PageSize](../../../aspose.pdf/pagesize/)
* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)