---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 위치에서 분할하고 뒷부분을 새 파일로 저장합니다.
type: docs
weight: 470
url: /ko/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

위치에서 분할하고 뒷부분을 새 파일로 저장합니다.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 원본 Pdf 파일. |
| location | Int32 | 분할 위치. |
| outputFile | String | 출력 Pdf 파일 경로. |

### 반환 값

성공 시 true, 실패 시 false.

## 비고

TrySplitToEnd 메서드는 SplitToEnd 메서드와 유사하지만, TrySplitToEnd 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

지정된 위치에서 분할하고 뒷부분을 새 파일 스트림으로 저장합니다.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 Pdf 파일 스트림. |
| location | Int32 | 분할 위치. |
| outputStream | Stream | 출력 Pdf 파일 스트림. |

### 반환 값

성공 시 true, 실패 시 false.

## 비고

이 작업 후 스트림은 CloseConcatedStreams가 지정되지 않는 한 닫히지 않습니다. TrySplitToEnd 메서드는 SplitToEnd 메서드와 유사하지만, TrySplitToEnd 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

지정된 위치에서 분할하고 뒷부분을 HttpResponse 객체에 저장합니다.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 문서 스트림. |
| location | Int32 | 분할 지점. |
| response | HttpResponse | HttpResponse 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TrySplitToEnd 메서드는 SplitToEnd 메서드와 유사하지만, TrySplitToEnd 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

지정된 위치에서 분할하고 뒷부분을 HttpResponse 객체에 저장합니다.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 원본 파일 이름. |
| location | Int32 | 분할 지점. |
| response | HttpResponse | HttpResponse 객체. |

### 반환 값

작업이 성공적으로 완료되면 true; 그렇지 않으면 false.

## 비고

TrySplitToEnd 메서드는 SplitToEnd 메서드와 유사하지만, TrySplitToEnd 메서드는 작업이 실패할 경우 예외를 발생시키지 않습니다.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)