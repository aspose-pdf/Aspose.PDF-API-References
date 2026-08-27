---
title: "PdfFileEditor.SplitFromFirst"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。从第一页到指定位置拆分 PDF 文件，并将前部保存为新文件"
type: docs
weight: 340
url: /zh/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

将 Pdf 文件从第一页拆分到指定位置，并将前半部分另存为新文件。

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源 Pdf 文件。 |
| 位置 | Int32 | 拆分点。 |
| outputFile | String | 输出 Pdf 文件。 |

### 返回值

成功返回 true，否则返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

从起始位置拆分到指定位置，并将前半部分保存到输出流。

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 源 Pdf 文件流。 |
| 位置 | Int32 | 拆分点。 |
| outputStream | Stream | 输出文件流。 |

### 返回值

成功返回 true，否则返回 false。

## 备注

此操作后流不会被关闭。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


