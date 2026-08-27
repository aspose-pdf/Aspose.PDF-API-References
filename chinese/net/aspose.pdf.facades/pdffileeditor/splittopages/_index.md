---
title: "PdfFileEditor.SplitToPages"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。将 PDF 文件拆分为单页文档"
type: docs
weight: 370
url: /zh/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

将 PDF 文件拆分为单页文档。

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入的 PDF 文件名。 |

### 返回值

输出的 PDF 流，每个流缓冲一个单页 PDF 文档。

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

将 Pdf 文件拆分为单页文档。

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 Pdf 流。 |

### 返回值

包含文档页面的内存流数组。

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名 temaplate 指定。

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件名。 |
| fileNameTemplate | String | 结果文件名的模板。必须包含 %NUM%，该占位符将在运行时被页码替换。例如，如果指定 c:/dir/page%NUM%.pdf，则生成的文件名将为：c:/dir/page1.pdf、c:/dir/page2.pdf 等。 |

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

将 Pdf 文件拆分为单页文档并保存到指定路径。路径由字段名 temaplate 指定。

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 源文档的流。 |
| fileNameTemplate | String | 结果文件名的模板。必须包含 %NUM%，该占位符将在运行时被页码替换。例如，如果指定 c:/dir/page%NUM%.pdf，则生成的文件名将为：c:/dir/page1.pdf、c:/dir/page2.pdf 等。 |

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


