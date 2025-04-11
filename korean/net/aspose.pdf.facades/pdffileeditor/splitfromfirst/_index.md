---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. Pdf 파일을 첫 페이지에서 지정된 위치로 분할하고 앞부분을 새 파일로 저장합니다.
type: docs
weight: 340
url: /ko/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Pdf 파일을 첫 페이지에서 지정된 위치로 분할하고, 앞부분을 새 파일로 저장합니다.

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 원본 Pdf 파일. |
| location | Int32 | 분할 지점. |
| outputFile | String | 출력 Pdf 파일. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

시작에서 지정된 위치로 분할하고, 앞부분을 출력 스트림에 저장합니다.

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 Pdf 파일 스트림. |
| location | Int32 | 분할 지점. |
| outputStream | Stream | 출력 파일 스트림. |

### 반환 값

성공 시 true, 실패 시 false.

## 비고

이 작업 후 스트림은 닫히지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)