---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 입력 파일에서 출력 파일로 북릿을 만듭니다.
type: docs
weight: 430
url: /ko/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

소스 파일에서 북릿을 만들고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 소스 파일 경로. |
| pageSize | PageSize | 원하는 페이지 크기. |
| leftPages | Int32[] | 왼쪽에 배치할 페이지 번호 배열. |
| rightPages | Int32[] | 오른쪽에 배치할 페이지 번호 배열. |
| response | HttpResponse | 결과가 저장될 HttpResponse 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

PDF 파일에서 북릿을 만들고 HttpResponse에 저장합니다.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 문서 스트림. |
| pageSize | PageSize | 원하는 페이지 크기. |
| leftPages | Int32[] | 왼쪽에 배치할 페이지 번호 배열. |
| rightPages | Int32[] | 오른쪽에 배치할 페이지 번호 배열. |
| response | HttpResponse | HttpResponse 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

소스 파일에서 북릿을 만들고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 소스 파일 경로. |
| pageSize | PageSize | 출력 파일의 원하는 페이지 크기. |
| response | HttpResponse | 결과가 저장될 HttpResponse 객체. |

### 반환 값

작업이 성공하면 true.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

소스 파일에서 북릿을 만들고 결과를 HttpResponse에 저장합니다.

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 문서 스트림. |
| pageSize | PageSize | 출력 파일의 원하는 페이지 크기. |
| response | HttpResponse | 결과가 저장될 객체. |

### 반환 값

북릿이 성공적으로 생성되면 true.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

입력 파일에서 출력 파일로 북릿을 만듭니다.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 PDF 파일 경로 및 이름. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

InputStream에서 outputStream으로 북릿을 만듭니다.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 PDF 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

입력 파일에서 출력 파일로 북릿을 만듭니다.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 PDF 파일 경로 및 이름. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |
| pageSize | PageSize | 출력 PDF 파일의 페이지 크기. |

### 반환 값

작업이 성공하면 true.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

입력 스트림에서 북릿을 만들고 결과를 출력 스트림에 저장합니다.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 PDF 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| pageSize | PageSize | 출력 PDF 파일의 페이지 크기. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

첫 번째 입력 파일에서 출력 파일로 사용자 정의 북릿을 만듭니다.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 파일. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |
| leftPages | Int32[] | 북릿의 왼쪽 페이지. |
| rightPages | Int32[] | 북릿의 오른쪽 페이지. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

첫 번째 입력 스트림에서 출력 스트림으로 사용자 정의 북릿을 만듭니다.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| leftPages | Int32[] | 왼쪽 페이지. |
| rightPages | Int32[] | 오른쪽 페이지. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 참조

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

첫 번째 입력 파일에서 출력 파일로 사용자 정의 북릿을 만듭니다.

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 파일. |
| outputFile | String | 출력 PDF 파일 경로 및 이름. |
| pageSize | PageSize | 출력 PDF 파일의 페이지 크기. |
| leftPages | Int32[] | 왼쪽 페이지. |
| rightPages | Int32[] | 오른쪽 페이지. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

첫 번째 입력 스트림에서 출력 스트림으로 북릿을 만듭니다.

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 스트림. |
| outputStream | Stream | 출력 PDF 스트림. |
| pageSize | PageSize | 출력 PDF 파일의 페이지 크기. |
| leftPages | Int32[] | 왼쪽 페이지. |
| rightPages | Int32[] | 오른쪽 페이지. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryMakeBooklet 메서드는 MakeBooklet 메서드와 유사하지만, TryMakeBooklet 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 참조

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)