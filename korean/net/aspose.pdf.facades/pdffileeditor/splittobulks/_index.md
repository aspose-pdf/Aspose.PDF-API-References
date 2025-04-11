---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 메서드. Pdf 파일을 여러 문서로 분할합니다. 문서는 단일 페이지 또는 다중 페이지일 수 있습니다.
type: docs
weight: 350
url: /ko/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Pdf 파일을 여러 문서로 분할합니다. 문서는 단일 페이지 또는 다중 페이지일 수 있습니다.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | String | 입력 PDF 파일. |
| numberOfPage | Int32[][] | 문서의 시작 페이지와 끝 페이지를 포함하는 이중 요소 배열. |

### Return Value

출력 PDF 스트림, 각 스트림은 PDF 문서를 버퍼링합니다.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Pdf 파일을 여러 문서로 분할합니다. 문서는 단일 페이지 또는 다중 페이지일 수 있습니다.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | 입력 PDF 스트림. |
| numberOfPage | Int32[][] | 각 문서의 시작 페이지와 끝 페이지. |

### Return Value

출력 PDF 스트림, 각 스트림은 PDF 문서를 버퍼링합니다.

### See Also

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)