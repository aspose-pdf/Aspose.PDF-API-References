---
title: "PdfFileEditor.TryMakeNUp"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. firstInputFile에서 outputFile로 NUp 문서를 만듭니다."
type: docs
weight: 440
url: /ko/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

firstInputFile에서 N-Up 문서를 만들어 outputFile에 저장합니다.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 pdf 파일 경로 및 이름. |
| outputFile | String | 출력 pdf 파일 경로 및 이름. |
| x | Int32 | 열 수. |
| y | Int32 | 행 수. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

입력 스트림에서 N-Up 문서를 만들어 결과를 출력 스트림에 저장합니다.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 pdf 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| x | Int32 | 열 수. |
| y | Int32 | 행 수. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

첫 번째 입력 스트림에서 N-Up 문서를 만들어 출력 스트림에 저장합니다.

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 pdf 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| x | Int32 | 열 수. |
| y | Int32 | 행 수. |
| pageSize | PageSize | 출력 pdf 파일의 페이지 크기. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 또 보기

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

두 개의 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. outputFile의 각 페이지는 두 페이지를 포함하며, 하나는 첫 번째 입력 파일에서, 다른 하나는 두 번째 입력 파일에서 가져옵니다. 두 페이지는 가로로 쌓입니다.

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputFile | String | 첫 입력 파일. |
| secondInputFile | String | 두 번째 입력 파일. |
| outputFile | String | 출력 pdf 파일 경로 및 이름. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

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
| outputStream | Stream | 출력 PDF 스트림. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

다중 입력 PDF 파일에서 N-Up 문서를 만들어 outputFile에 저장합니다. outputFile의 각 페이지는 동일한 페이지 번호의 입력 파일 페이지와 결합된 여러 페이지를 포함합니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓입니다.

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFiles | String[] | 입력 Pdf 파일. |
| outputFile | String | 출력 pdf 파일 경로 및 이름. |
| isSidewise | Boolean | 쌓는 방식, 가로 방향이면 true, 세로 방향이면 false. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

다중 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다. outputStream의 각 페이지는 동일한 페이지 번호를 가진 입력 스트림들의 페이지를 조합한 여러 페이지를 포함합니다. isSidewise가 true이면 다중 페이지가 가로로 쌓이고, false이면 세로로 쌓입니다.

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStreams | Stream[] | 입력 Pdf 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| isSidewise | Boolean | 쌓는 방식, 가로 방향이면 true, 세로 방향이면 false. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

입력 파일에서 N-Up 문서를 만들어 outputFile에 저장합니다.

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 pdf 파일 경로 및 이름. |
| outputFile | String | 출력 pdf 파일 경로 및 이름. |
| x | Int32 | 열 수. |
| y | Int32 | 행 수. |
| pageSize | PageSize | 출력 pdf 파일의 페이지 크기. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryMakeNUp 메서드는 MakeNUp 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### 또 보기

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


