---
title: "PdfFileEditor.TryInsert"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. 다른 파일에서 페이지를 입력 Pdf 파일에 삽입합니다."
type: docs
weight: 420
url: /ko/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

다른 파일에서 페이지를 삽입하여 입력 Pdf 파일에 넣습니다.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 Pdf 파일. |
| insertLocation | Int32 | 입력 파일의 삽입 위치. |
| portFile | String | Pdf 파일의 페이지들. |
| pageNumber | Int32[] | 포트 파일에 포팅된 페이지 번호. |
| outputFile | String | 출력 Pdf 파일. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 비고

TryInsert 메서드는 Insert 메서드와 유사하지만, TryInsert 메서드는 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

다른 파일에서 페이지를 삽입하여 입력 Pdf 파일에 넣습니다.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | Pdf 파일의 입력 스트림. |
| insertLocation | Int32 | 입력 파일의 삽입 위치. |
| portStream | Stream | 페이지용 Pdf 파일 스트림. |
| pageNumber | Int32[] | 포트 파일에 포팅된 페이지 번호. |
| outputStream | Stream | 출력 스트림. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryInsert 메서드는 Insert 메서드와 유사하지만, TryInsert 메서드는 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


