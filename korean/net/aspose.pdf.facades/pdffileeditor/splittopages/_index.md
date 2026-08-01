---
title: "PdfFileEditor.SplitToPages"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. PDF 파일을 단일 page 문서로 분할합니다."
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

출력 PDF 스트림, 각 스트림은 단일 page PDF document를 버퍼링합니다.

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Pdf 파일을 단일 페이지 문서로 분할합니다.

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 Pdf 스트림. |

### 반환 값

document의 pages를 포함하는 메모리 스트림 배열.

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Pdf 파일을 단일 페이지 문서로 분할하고 지정된 경로에 저장합니다. 경로는 템플릿 필드 이름으로 지정됩니다.

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 파일 이름. |
| fileNameTemplate | String | 결과 파일 이름의 템플릿. page 번호로 대체되는 %NUM%를 포함해야 합니다. 예를 들어 c:/dir/page%NUM%.pdf를 지정하면, 결과 파일은 다음과 같은 이름을 갖게 됩니다: c:/dir/page1.pdf, c:/dir/page2.pdf 등. |

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Pdf 파일을 단일 페이지 문서로 분할하고 지정된 경로에 저장합니다. 경로는 템플릿 필드 이름으로 지정됩니다.

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 원본 document의 스트림. |
| fileNameTemplate | String | 결과 파일 이름의 템플릿. page 번호로 대체되는 %NUM%를 포함해야 합니다. 예를 들어 c:/dir/page%NUM%.pdf를 지정하면, 결과 파일은 다음과 같은 이름을 갖게 됩니다: c:/dir/page1.pdf, c:/dir/page2.pdf 등. |

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


