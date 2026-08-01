---
title: "PdfFileEditor.TrySplitFromFirst"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. PDF 파일을 첫 페이지부터 지정된 위치까지 분할하고 앞부분을 새 파일로 저장합니다"
type: docs
weight: 460
url: /ko/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

첫 페이지부터 지정된 위치까지 Pdf 파일을 분할하고, 앞부분을 새 파일로 저장합니다.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 원본 Pdf 파일. |
| 위치 | Int32 | 분할 지점. |
| outputFile | String | 출력 Pdf 파일. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 비고

TrySplitFromFirst 메서드는 SplitFromFirst 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

시작 위치에서 지정된 위치까지 분할하고, 앞부분을 출력 Stream에 저장합니다.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 Pdf 파일 스트림. |
| 위치 | Int32 | 분할 지점. |
| outputStream | Stream | 출력 파일 스트림. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 비고

이 작업 후에 스트림은 닫히지 않습니다. TrySplitFromFirst 메서드는 SplitFromFirst 메서드와 같지만, 작업이 실패해도 예외를 발생시키지 않습니다.

## 예제

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


