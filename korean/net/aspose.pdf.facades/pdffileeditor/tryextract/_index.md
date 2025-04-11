---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 입력 파일에서 페이지를 추출하여 새로운 Pdf 파일로 저장합니다.
type: docs
weight: 410
url: /ko/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

입력 파일에서 페이지를 추출하여 새로운 Pdf 파일로 저장합니다.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일 경로. |
| startPage | Int32 | 시작 페이지 번호. |
| endPage | Int32 | 끝 페이지 번호. |
| outputFile | String | 출력 Pdf 파일 경로. |

### 반환 값

성공 시 true, 실패 시 false.

## 비고

TryExtract 메서드는 Extract 메서드와 유사하지만, TryExtract 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

번호 배열로 지정된 페이지를 추출하여 새로운 PDF 파일로 저장합니다.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 파일 경로. |
| pageNumber | Int32[] | 입력 파일의 페이지 인덱스. |
| outputFile | String | 출력 파일 경로. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryExtract 메서드는 Extract 메서드와 유사하지만, TryExtract 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

번호 배열로 지정된 페이지를 추출하여 새로운 Pdf 파일로 저장합니다.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 파일 스트림. |
| pageNumber | Int32[] | 입력 파일의 페이지 인덱스. |
| outputStream | Stream | 출력 파일 스트림. |

### 반환 값

성공 시 true, 실패 시 false.

## 비고

TryExtract 메서드는 Extract 메서드와 유사하지만, TryExtract 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

소스 파일에서 지정된 페이지를 추출하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 소스 문서의 스트림. |
| pageNumber | Int32[] | 추출될 페이지 번호 배열. |
| response | HttpResponse | 결과가 저장될 HttpResponse 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryExtract 메서드는 Extract 메서드와 유사하지만, TryExtract 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

소스 파일에서 지정된 페이지를 추출하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 소스 파일 경로. |
| pageNumber | Int32[] | 추출될 페이지 번호 배열. |
| response | HttpResponse | 결과가 저장될 HttpResponse 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryExtract 메서드는 Extract 메서드와 유사하지만, TryExtract 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)