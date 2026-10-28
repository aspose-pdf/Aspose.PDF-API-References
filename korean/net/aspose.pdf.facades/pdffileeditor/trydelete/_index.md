---
title: "PdfFileEditor.TryDelete"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. 입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새 Pdf 파일로 저장합니다."
type: docs
weight: 400
url: /ko/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새로운 Pdf 파일로 저장합니다.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 파일 경로. |
| pageNumber | Int32[] | 입력 파일 내 페이지 인덱스. |
| outputFile | String | 출력 파일 경로. |

### 반환 값

작업이 성공적으로 완료되면 true, 그렇지 않으면 false.

## 비고

TryDelete 메서드는 Delete 메서드와 유사하지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

입력 파일에서 번호 배열로 지정된 페이지를 삭제하고 새로운 Pdf 파일로 저장합니다.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 파일 스트림. |
| pageNumber | Int32[] | 입력 파일 내 페이지 인덱스. |
| outputStream | Stream | 출력 파일 스트림. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 비고

TryDelete 메서드는 Delete 메서드와 유사하지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


