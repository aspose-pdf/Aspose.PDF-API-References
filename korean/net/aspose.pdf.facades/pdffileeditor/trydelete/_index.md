---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새 Pdf 파일로 저장합니다.
type: docs
weight: 400
url: /ko/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새 Pdf 파일로 저장합니다.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 파일 경로. |
| pageNumber | Int32[] | 입력 파일의 페이지 인덱스. |
| outputFile | String | 출력 파일 경로. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false입니다.

## 비고

TryDelete 메서드는 Delete 메서드와 유사하지만, TryDelete 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새 Pdf 파일로 저장합니다.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 파일 스트림. |
| pageNumber | Int32[] | 입력 파일의 페이지 인덱스. |
| outputStream | Stream | 출력 파일 스트림. |

### 반환 값

성공하면 true, 실패하면 false입니다.

## 비고

TryDelete 메서드는 Delete 메서드와 유사하지만, TryDelete 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

문서에서 지정된 페이지를 삭제하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 원본 파일의 경로. |
| pageNumber | Int32[] | 삭제해야 할 페이지 번호 배열. |
| response | HttpResponse | 결과 문서가 저장될 응답 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false입니다.

## 비고

TryDelete 메서드는 Delete 메서드와 유사하지만, TryDelete 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

문서에서 지정된 페이지를 삭제하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 문서 스트림. |
| pageNumber | Int32[] | 삭제될 페이지 번호 배열. |
| response | HttpResponse | HttpResponse 객체 |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false입니다.

## 비고

TryDelete 메서드는 Delete 메서드와 유사하지만, TryDelete 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)