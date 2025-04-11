---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 다른 파일에서 페이지를 입력 Pdf 파일에 삽입합니다.
type: docs
weight: 420
url: /ko/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

다른 파일에서 페이지를 입력 Pdf 파일에 삽입합니다.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일. |
| insertLocation | Int32 | 입력 파일의 삽입 위치. |
| portFile | String | Pdf 파일의 페이지. |
| pageNumber | Int32[] | portFile에서 포팅된 페이지 번호. |
| outputFile | String | 출력 Pdf 파일. |

### 반환 값

성공 시 true, 실패 시 false.

## 비고

TryInsert 메서드는 Insert 메서드와 유사하지만, TryInsert 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

다른 파일에서 페이지를 입력 Pdf 파일에 삽입합니다.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | Pdf 파일의 입력 스트림. |
| insertLocation | Int32 | 입력 파일의 삽입 위치. |
| portStream | Stream | 페이지를 위한 Pdf 파일의 스트림. |
| pageNumber | Int32[] | portFile에서 포팅된 페이지 번호. |
| outputStream | Stream | 출력 스트림. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryInsert 메서드는 Insert 메서드와 유사하지만, TryInsert 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

파일의 내용을 소스 파일에 삽입하고 결과를 HttpResponse 객체에 저장합니다.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 소스 파일 이름. |
| insertLocation | Int32 | 두 번째 파일이 삽입될 페이지 번호. |
| portFile | String | 삽입될 파일의 경로. |
| pageNumber | Int32[] | 삽입될 소스 파일의 페이지 번호 배열. |
| response | HttpResponse | 결과가 저장될 응답 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryInsert 메서드는 Insert 메서드와 유사하지만, TryInsert 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

문서를 다른 문서에 삽입하고 결과를 응답 객체에 저장합니다.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 소스 문서가 있는 스트림 |
| insertLocation | Int32 | 다른 문서가 삽입될 위치. |
| portStream | Stream | 삽입될 문서. |
| pageNumber | Int32[] | 삽입될 두 번째 문서의 페이지 번호 배열. |
| response | HttpResponse | 결과가 저장될 응답 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TryInsert 메서드는 Insert 메서드와 유사하지만, TryInsert 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)