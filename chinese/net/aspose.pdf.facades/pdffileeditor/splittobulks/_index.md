---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。将 Pdf 文件拆分为多个文档。文档可以是单页或多页
type: docs
weight: 350
url: /zh/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

将 Pdf 文件拆分为多个文档。文档可以是单页或多页。

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 PDF 文件。 |
| numberOfPage | Int32[][] | 包含双元素数组的数组，表示文档的起始页和结束页。 |

### 返回值

输出 PDF 流，每个流缓冲一个 PDF 文档。

### 另请参阅

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

将 Pdf 文件拆分为多个文档。文档可以是单页或多页。

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 PDF 流。 |
| numberOfPage | Int32[][] | 每个文档的起始页和结束页。 |

### 返回值

输出 PDF 流，每个流缓冲一个 PDF 文档。

### 另请参阅

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)