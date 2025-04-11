---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。将 Pdf 文件从第一页拆分到指定位置，并将前半部分保存为新文件
type: docs
weight: 460
url: /zh/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

将 Pdf 文件从第一页拆分到指定位置，并将前半部分保存为新文件。

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 源 Pdf 文件。 |
| location | Int32 | 拆分点。 |
| outputFile | 字符串 | 输出 Pdf 文件。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

TrySplitFromFirst 方法类似于 SplitFromFirst 方法，不同之处在于如果操作失败，TrySplitFromFirst 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

从开始拆分到指定位置，并将前半部分保存到输出流中。

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 源 Pdf 文件流。 |
| location | Int32 | 拆分点。 |
| outputStream | 流 | 输出文件流。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

操作后流不会关闭。TrySplitFromFirst 方法类似于 SplitFromFirst 方法，不同之处在于如果操作失败，TrySplitFromFirst 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

从第一页拆分文档到指定位置，并将结果保存到 HttpResponse 对象中。

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 源文件名。 |
| location | Int32 | 拆分点。 |
| response | HttpResponse | HttpResponse 对象。 |

### 返回值

如果操作成功完成则返回 true；否则返回 false。

## 备注

TrySplitFromFirst 方法类似于 SplitFromFirst 方法，不同之处在于如果操作失败，TrySplitFromFirst 方法不会抛出异常。

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

从开始拆分文档到指定位置，并将结果存储到 HttpResponse 对象中。

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | 流 | 源文档的流。 |
| location | Int32 | 拆分点。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成则返回 true；否则返回 false。

## 备注

TrySplitFromFirst 方法类似于 SplitFromFirst 方法，不同之处在于如果操作失败，TrySplitFromFirst 方法不会抛出异常。

### 另见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)