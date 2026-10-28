---
title: "PdfFileEditor.ResizeContentsPct"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. 문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 새로운 내용 크기는 백분율로 지정됩니다."
type: docs
weight: 330
url: /ko/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 새로운 내용 크기는 퍼센트로 지정됩니다.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | Stream | 원본 문서를 포함하는 스트림. |
| 대상 | Stream | 결과 문서가 저장될 스트림. |
| 페이지 | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| newWidth | Double | 페이지 내용의 새로운 너비(백분율). |
| newHeight | Double | 페이지 내용의 새로운 높이(백분율). |

### 반환 값

크기 조정에 성공하면 true.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//문서의 모든 페이지를 크기 조정합니다.
null, 
//새 내용 너비 = 초기 크기의 60%
60, 
//새 내용 높이 = 초기 크기의 60%
60);
// 페이지의 나머지 영역은 비어 있게 됩니다(페이지 여백). 좌우 여백의 크기는 (100% - 60%) / 2 = 20% 입니다.
// 상하 여백도 동일합니다.
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

문서 페이지의 내용을 크기 조정합니다. 페이지 내용을 축소하고 여백을 추가합니다. 새로운 내용 크기는 퍼센트로 지정됩니다.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 소스 | String | 원본 문서의 경로입니다. |
| 대상 | String | 결과 문서가 저장될 경로입니다. |
| 페이지 | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| newWidth | Double | 페이지 내용의 새로운 너비(백분율). |
| newHeight | Double | 페이지 내용의 새로운 높이(백분율). |

### 반환 값

크기 조정이 성공하면 true입니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//문서의 모든 페이지를 크기 조정합니다.
null, 
//새 내용 너비 = 초기 크기의 60%
60, 
//새 내용 높이 = 초기 크기의 60%
60);
// 페이지의 나머지 영역은 비어 있게 됩니다(페이지 여백). 좌우 여백의 크기는 (100% - 60%) / 2 = 20% 입니다.
// 상하 여백도 동일합니다.
```

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


