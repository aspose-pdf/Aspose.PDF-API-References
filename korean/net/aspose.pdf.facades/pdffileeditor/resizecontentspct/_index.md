---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. 문서 페이지의 내용을 크기 조정합니다. 페이지의 내용을 축소하고 여백을 추가합니다. 새로운 내용 크기는 백분율로 지정됩니다.
type: docs
weight: 330
url: /ko/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

문서 페이지의 내용을 크기 조정합니다. 페이지의 내용을 축소하고 여백을 추가합니다. 새로운 내용 크기는 백분율로 지정됩니다.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | Stream | 원본 문서를 포함하는 스트림입니다. |
| destination | Stream | 결과 문서가 저장될 스트림입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| newWidth | Double | 페이지 내용의 새로운 너비(백분율)입니다. |
| newHeight | Double | 페이지 내용의 새로운 높이(백분율)입니다. |

### 반환 값

성공적으로 크기 조정되면 true입니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

문서 페이지의 내용을 크기 조정합니다. 페이지의 내용을 축소하고 여백을 추가합니다. 새로운 내용 크기는 백분율로 지정됩니다.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | String | 원본 문서의 경로입니다. |
| destination | String | 결과 문서가 저장될 경로입니다. |
| pages | Int32[] | 페이지 인덱스 배열입니다. null인 경우 모든 문서 페이지가 처리됩니다. |
| newWidth | Double | 페이지 내용의 새로운 너비(백분율)입니다. |
| newHeight | Double | 페이지 내용의 새로운 높이(백분율)입니다. |

### 반환 값

크기 조정이 성공적이면 true입니다.

## 예제

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### 참조

* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)