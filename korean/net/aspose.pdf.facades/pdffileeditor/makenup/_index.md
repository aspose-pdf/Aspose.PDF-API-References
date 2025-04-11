---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 두 개의 입력 PDF 스트림에서 NUp 문서를 만들어 outputStream에 출력합니다.
type: docs
weight: 310
url: /ko/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

첫 번째 입력 파일에서 outputFile로 N-Up 문서를 만듭니다.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 PDF 파일 경로 및 이름. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

입력 스트림에서 N-Up 문서를 만들고 결과를 출력 스트림에 저장합니다.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 PDF 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

첫 번째 입력 스트림에서 출력 스트림으로 N-Up 문서를 만듭니다.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 PDF 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |
| pageSize | PageSize | 출력 PDF 파일의 페이지 크기. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

두 개의 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. outputFile의 각 페이지는 두 페이지를 포함하며, 한 페이지는 첫 번째 입력 파일에서, 다른 페이지는 두 번째 입력 파일에서 가져옵니다. 두 페이지는 수평으로 쌓입니다.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputFile | String | 첫 번째 입력 파일. |
| secondInputFile | String | 두 번째 입력 파일. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

두 개의 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputStream | Stream | 첫 번째 입력 스트림. |
| secondInputStream | Stream | 두 번째 입력 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

여러 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. outputFile의 각 페이지는 동일한 페이지 번호의 입력 파일에서 페이지를 조합한 여러 페이지를 포함합니다. isSidewise가 true이면 여러 페이지가 수평으로 쌓이고, false이면 수직으로 쌓입니다.

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFiles | String[] | 입력 PDF 파일. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |
| isSidewise | Boolean | 쌓는 방식, true는 수평, false는 수직. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

여러 입력 PDF 스트림에서 outputStream으로 N-Up 문서를 만듭니다. outputStream의 각 페이지는 동일한 페이지 번호의 입력 스트림에서 페이지를 조합한 여러 페이지를 포함합니다. isSidewise가 true이면 여러 페이지가 수평으로 쌓이고, false이면 수직으로 쌓입니다.

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStreams | Stream[] | 입력 PDF 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| isSidewise | Boolean | 쌓는 방식, true는 수평, false는 수직. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

입력 파일에서 outputFile로 N-Up 문서를 만듭니다.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 PDF 파일 경로 및 이름. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |
| pageSize | PageSize | 출력 PDF 파일의 페이지 크기. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

첫 번째 입력 파일에서 outputFile로 N-Up 문서를 만듭니다.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 PDF 파일 경로 및 이름. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

입력 스트림에서 N-Up 문서를 만들고 결과를 출력 스트림에 저장합니다.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 PDF 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

첫 번째 입력 스트림에서 출력 스트림으로 N-Up 문서를 만듭니다.

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 PDF 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| x | Int32 | 열의 수. |
| y | Int32 | 행의 수. |
| pageSize | PageSize | 출력 PDF 파일의 페이지 크기. |

### 반환 값

작업이 성공하면 true.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

두 개의 입력 PDF 파일에서 outputFile로 N-Up 문서를 만듭니다. outputFile의 각 페이지는 두 페이지를 포함하며, 한 페이지는 첫 번째 입력 파일에서, 다른 페이지는 두 번째 입력 파일에서 가져옵니다. 두 페이지는 수평으로 쌓입니다.

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstInputFile | String | 첫 번째 입력 파일. |
| secondInputFile | String | 두 번째 입력 파일. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |

### 반환 값

boolean - 성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)