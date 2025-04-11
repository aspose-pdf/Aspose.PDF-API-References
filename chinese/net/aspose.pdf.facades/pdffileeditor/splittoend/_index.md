---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。从指定位置拆分并将后半部分保存为新文件
type: docs
weight: 360
url: /zh/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

从指定位置拆分，并将后半部分保存为新文件流。

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 源 Pdf 文件流。 |
| location | Int32 | 拆分位置。 |
| outputStream | Stream | 输出 Pdf 文件流。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

除非指定 CloseConcatedStreams，否则操作后流不会关闭。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

从位置拆分，并将后半部分保存为新文件。

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源 Pdf 文件。 |
| location | Int32 | 拆分位置。 |
| outputFile | String | 输出 Pdf 文件路径。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

从指定位置拆分，并将后半部分保存为新文件流。

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 源 Pdf 文件流。 |
| location | Int32 | 拆分位置。 |
| outputStream | Stream | 输出 Pdf 文件流。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

除非指定 CloseConcatedStreams，否则操作后流不会关闭。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)