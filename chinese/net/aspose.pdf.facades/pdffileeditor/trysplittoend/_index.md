---
title: "PdfFileEditor.TrySplitToEnd"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。从 location 分割并将后半部分保存为新文件"
type: docs
weight: 470
url: /zh/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

从指定位置拆分，并将后半部分保存为新文件。

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源 Pdf 文件。 |
| 位置 | Int32 | 分割位置。 |
| outputFile | String | 输出 Pdf 文件路径。 |

### 返回值

成功返回 true，否则返回 false。

## 备注

TrySplitToEnd 方法类似于 SplitToEnd 方法，但如果操作失败，TrySplitToEnd 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

从指定位置拆分，并将后半部分保存为新文件流。

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 源 Pdf 文件流。 |
| 位置 | Int32 | 分割位置。 |
| outputStream | Stream | 输出 Pdf 文件流。 |

### 返回值

成功返回 true，否则返回 false。

## 备注

除非指定了 CloseConcatedStreams，否则此操作后流不会被关闭。TrySplitToEnd 方法类似于 SplitToEnd 方法，但如果操作失败，TrySplitToEnd 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


