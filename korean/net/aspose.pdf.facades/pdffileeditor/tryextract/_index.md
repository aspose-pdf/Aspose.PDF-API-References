---
title: "PdfFileEditor.TryExtract"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. 입력 파일에서 pages를 추출하여 새로운 PDF 파일로 저장합니다."
type: docs
weight: 410
url: /ko/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

입력 파일에서 페이지를 추출하고 새로운 Pdf 파일로 저장합니다.

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 PDF 파일 경로. |
| startPage | Int32 | 시작 page 번호. |
| endPage | Int32 | 끝 page 번호. |
| outputFile | String | 출력 Pdf 파일 경로. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 비고

TryExtract 메서드는 Extract 메서드와 유사하지만, 작업이 실패해도 TryExtract 메서드는 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

번호 배열로 지정된 페이지를 추출하여 새로운 PDF 파일로 저장합니다.

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 파일 경로. |
| pageNumber | Int32[] | 입력 파일 내 페이지 인덱스. |
| outputFile | String | 출력 파일 경로. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryExtract 메서드는 Extract 메서드와 유사하지만, 작업이 실패해도 TryExtract 메서드는 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

번호 배열로 지정된 페이지를 추출하여 새로운 Pdf 파일로 저장합니다.

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 파일 스트림. |
| pageNumber | Int32[] | 입력 파일 내 페이지 인덱스. |
| outputStream | Stream | 출력 파일 스트림. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 비고

TryExtract 메서드는 Extract 메서드와 유사하지만, 작업이 실패해도 TryExtract 메서드는 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


