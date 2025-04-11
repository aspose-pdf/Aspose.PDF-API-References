---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。连接两个文件
type: docs
weight: 390
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

连接两个文件。

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | String | 第一个要连接的文件。 |
| secInputFile | String | 第二个要连接的文件。 |
| outputFile | String | 输出文件。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryConcatenate 方法类似于 Concatenate 方法，不同之处在于如果操作失败，TryConcatenate 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

连接文档。

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | Document[] | 源文档数组。 |
| dest | Document | 目标文档。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryConcatenate 方法类似于 Concatenate 方法，不同之处在于如果操作失败，TryConcatenate 方法不会抛出异常。

### 另请参见

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

将文件连接成一个文件。

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | String[] | 要连接的文件数组。 |
| outputFile | String | 输出文件的名称。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryConcatenate 方法类似于 Concatenate 方法，不同之处在于如果操作失败，TryConcatenate 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

连接文件

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream[] | 要连接的流数组。 |
| outputStream | Stream | 存储结果文件的流。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryConcatenate 方法类似于 Concatenate 方法，不同之处在于如果操作失败，TryConcatenate 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

将两个 Pdf 文档合并为一个新的 Pdf 文档，页面交替排列，并用空白页填充空白位置。例如：document1 有 5 页：p1, p2, p3, p4, p5。document2 有 3 页：p1', p2', p3'。合并这两个 Pdf 文档将生成结果文档，页面为：p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage。

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | String | 第一个文件。 |
| secInputFile | String | 第二个文件。 |
| blankPageFile | String | 带有空白页的 PDF 文件。 |
| outputFile | String | 结果文件。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryConcatenate 方法类似于 Concatenate 方法，不同之处在于如果操作失败，TryConcatenate 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

将两个 Pdf 文档合并为一个新的 Pdf 文档，页面交替排列，并用空白页填充空白位置。例如：document1 有 5 页：p1, p2, p3, p4, p5。document2 有 3 页：p1', p2', p3'。合并这两个 Pdf 文档将生成结果文档，页面为：p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage。

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputStream | Stream | 第一个 Pdf 流。 |
| secInputStream | Stream | 第二个 Pdf 流。 |
| blankPageStream | Stream | 带有空白页的 Pdf 流。 |
| outputStream | Stream | 输出 Pdf 流。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryConcatenate 方法类似于 Concatenate 方法，不同之处在于如果操作失败，TryConcatenate 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

连接文件并将结果保存到 HttpResponse 对象中。

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | String[] | 要连接的文件数组。 |
| response | HttpResponse | 响应对象。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryConcatenate 方法类似于 Concatenate 方法，不同之处在于如果操作失败，TryConcatenate 方法不会抛出异常。

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

连接文件并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream[] | 包含要连接的文件的流数组。 |
| response | HttpResponse | 响应对象。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryConcatenate 方法类似于 Concatenate 方法，不同之处在于如果操作失败，TryConcatenate 方法不会抛出异常。

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)