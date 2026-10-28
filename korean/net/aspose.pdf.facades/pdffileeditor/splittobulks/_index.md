---
title: "PdfFileEditor.SplitToBulks"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 메서드. Pdf 파일을 여러 문서로 분할합니다. 문서는 단일 페이지이거나 다중 페이지일 수 있습니다."
type: docs
weight: 350
url: /ko/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Pdf 파일을 여러 문서로 분할합니다. 문서는 단일 페이지 또는 다중 페이지일 수 있습니다.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFile | String | 입력 PDF 파일. |
| numberOfPage | Int32[][] | 문서의 시작 페이지와 끝 페이지를 나타내는 double 요소 배열을 포함하는 배열. |

### 반환 값

출력 PDF 스트림, 각 스트림은 PDF 문서를 버퍼링합니다.

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Pdf 파일을 여러 문서로 분할합니다. 문서는 단일 페이지 또는 다중 페이지일 수 있습니다.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputStream | Stream | 입력 PDF 스트림. |
| numberOfPage | Int32[][] | 각 문서의 시작 페이지와 끝 페이지. |

### 반환 값

출력 PDF 스트림, 각 스트림은 PDF 문서를 버퍼링합니다.

### 또 보기

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


