---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。从位置拆分并将后半部分保存为新文件
type: docs
weight: 470
url: /zh/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

从位置拆分，并将后半部分保存为新文件。

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 源 Pdf 文件。 |
| location | Int32 | 拆分位置。 |
| outputFile | 字符串 | 输出 Pdf 文件路径。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

TrySplitToEnd 方法类似于 SplitToEnd 方法，不同之处在于如果操作失败，TrySplitToEnd 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

从指定位置拆分，并将后半部分保存为新文件流。

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 源 Pdf 文件流。 |
| location | Int32 | 拆分位置。 |
| outputStream | 流 | 输出 Pdf 文件流。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

操作后流不会关闭，除非指定 CloseConcatedStreams。TrySplitToEnd 方法类似于 SplitToEnd 方法，不同之处在于如果操作失败，TrySplitToEnd 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

从指定位置拆分，并将后半部分保存到 HttpResponse 对象中。

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 源文档流。 |
| location | Int32 | 拆分点。 |
| response | HttpResponse | HttpResponse 对象。 |

### 返回值

如果操作成功完成则返回 true；否则返回 false。

## 备注

TrySplitToEnd 方法类似于 SplitToEnd 方法，不同之处在于如果操作失败，TrySplitToEnd 方法不会抛出异常。

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

从指定位置拆分，并将后半部分保存到 HttpResponse 对象中。

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 源文件名。 |
| location | Int32 | 拆分点。 |
| response | HttpResponse | HttpResponse 对象。 |

### 返回值

如果操作成功完成则返回 true；否则返回 false。

## 备注

TrySplitToEnd 方法类似于 SplitToEnd 方法，不同之处在于如果操作失败，TrySplitToEnd 方法不会抛出异常。

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)