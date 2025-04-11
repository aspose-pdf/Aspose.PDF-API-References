---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。从第一页开始将 Pdf 文件拆分到指定位置，并将前半部分保存为新文件
type: docs
weight: 340
url: /zh/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

从第一页开始将 Pdf 文件拆分到指定位置，并将前半部分保存为新文件。

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 源 Pdf 文件。 |
| location | Int32 | 拆分点。 |
| outputFile | 字符串 | 输出 Pdf 文件。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

从开始到指定位置拆分，并将前半部分保存到输出流中。

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 源 Pdf 文件流。 |
| location | Int32 | 拆分点。 |
| outputStream | 流 | 输出文件流。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

此操作后流不会关闭。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)