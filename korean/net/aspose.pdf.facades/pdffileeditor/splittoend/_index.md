---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 지정된 위치에서 분할하고 뒷부분을 새 파일로 저장합니다.
type: docs
weight: 360
url: /ko/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

지정된 위치에서 분할하고 뒷부분을 새 파일 스트림으로 저장합니다.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 Pdf 파일 스트림. |
| location | Int32 | 분할 위치. |
| outputStream | Stream | 출력 Pdf 파일 스트림. |

### 반환 값

성공 시 true, 실패 시 false.

## 비고

이 작업 후 스트림은 CloseConcatedStreams가 지정되지 않는 한 닫히지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

위치에서 분할하고 뒷부분을 새 파일로 저장합니다.

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 원본 Pdf 파일. |
| location | Int32 | 분할 위치. |
| outputFile | String | 출력 Pdf 파일 경로. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

지정된 위치에서 분할하고 뒷부분을 새 파일 스트림으로 저장합니다.

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 Pdf 파일 스트림. |
| location | Int32 | 분할 위치. |
| outputStream | Stream | 출력 Pdf 파일 스트림. |

### 반환 값

성공 시 true, 실패 시 false.

## 비고

이 작업 후 스트림은 CloseConcatedStreams가 지정되지 않는 한 닫히지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)