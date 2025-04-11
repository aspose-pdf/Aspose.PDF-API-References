---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. PDF 파일을 단일 페이지 문서로 분할합니다.
type: docs
weight: 370
url: /ko/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

PDF 파일을 단일 페이지 문서로 분할합니다.

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 PDF 파일 이름. |

### 반환 값

각 스트림이 단일 페이지 PDF 문서를 버퍼링하는 출력 PDF 스트림.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

PDF 파일을 단일 페이지 문서로 분할합니다.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 PDF 스트림. |

### 반환 값

문서의 페이지를 포함하는 메모리 스트림 배열.

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

PDF 파일을 단일 페이지 문서로 분할하고 지정된 경로에 저장합니다. 경로는 필드 이름 템플릿으로 지정됩니다.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 파일 이름. |
| fileNameTemplate | String | 결과 파일 이름의 템플릿. 페이지 번호로 대체되는 %NUM%을 포함해야 합니다. 예를 들어, c:/dir/page%NUM%.pdf가 지정되면 결과 파일 이름은 다음과 같습니다: c:/dir/page1.pdf, c:/dir/page2.pdf 등. |

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

PDF 파일을 단일 페이지 문서로 분할하고 지정된 경로에 저장합니다. 경로는 필드 이름 템플릿으로 지정됩니다.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 문서의 스트림. |
| fileNameTemplate | String | 결과 파일 이름의 템플릿. 페이지 번호로 대체되는 %NUM%을 포함해야 합니다. 예를 들어, c:/dir/page%NUM%.pdf가 지정되면 결과 파일 이름은 다음과 같습니다: c:/dir/page1.pdf, c:/dir/page2.pdf 등. |

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)