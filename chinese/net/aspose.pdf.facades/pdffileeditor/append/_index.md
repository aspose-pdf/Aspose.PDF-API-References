---
title: Append
second_title: Aspose.PDF for .NET API 参考
description: 附加页面这些页面是从 portStreams 中的文档数组中选择的 结果文档包括 firstInputFile 和所有 portStreams 文档页面在 startPage 到 endPage 范围内
type: docs
weight: 280
url: /zh/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

附加页面，这些页面是从 portStreams 中的文档数组中选择的。 结果文档包括 firstInputFile 和所有 portStreams 文档页面在 startPage 到 endPage 范围内。

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 Pdf 流。 |
| portStreams | Stream[] | 要从中复制页面的文档。 |
| startPage | Int32 | 页面在 portStreams 文档中开始。 |
| endPage | Int32 | 页面以 portStreams 文档结尾。 |
| outputStream | Stream | 输出 Pdf 流。 |

### 返回值

成功则为真，否则为假。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_4}

附加页面，这些页面是从 portFiles 文档中选择的。 结果文档包括 firstInputFile 和所有 portFiles 文档页面在 startPage 到 endPage 范围内。

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| portFiles | String[] | 要从中复制页面的文档。 |
| startPage | Int32 | 页面在 portFiles 文档中开始。 |
| endPage | Int32 | 页面以 portFiles 文档结尾。 |
| outputFile | String | 输出 Pdf 文档。 |

### 返回值

如果操作成功则为真。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_3}

将在 startPage 到 endPage 范围内从 portFile 中选择的页面附加到 portFile 中 firstInputFile 的末尾。

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| portFile | String | Pdf 文件中的页面。 |
| startPage | Int32 | 页面从 portFile 开始。 |
| endPage | Int32 | 页面以 portFile 结尾。 |
| outputFile | String | 输出 Pdf 文档。 |

### 返回值

如果操作成功则为真。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

在 firstInputStream 末尾的 portStream 中追加从 startPage 到 endPage 范围内的 portStream 的页面。

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文件流。 |
| portStream | Stream | Pdf 文件流中的页面。 |
| startPage | Int32 | 页面在 portFile 流中开始。 |
| endPage | Int32 | 页面在 portFile 流中结束。 |
| outputStream | Stream | 输出 Pdf 文件流。 |

### 返回值

成功则为真，否则为假。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Append(Stream, Stream[], int, int, HttpResponse) {#append_2}

将文档附加到源文档并将结果保存到响应对象中。

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 包含源文档的流。 |
| portStreams | Stream[] | 要附加文档的流数组。 |
| startPage | Int32 | 附加页的起始页。 |
| endPage | Int32 | 附加页的结束页。 |
| response | HttpResponse | 将保存文档的响应对象。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, HttpResponse) {#append_5}

将文档附加到源文档并将结果保存到 HttpResponse 对象中。

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 包含源文档的文件名。 |
| portFiles | String[] | 包含附加文档的文件名数组。 |
| startPage | Int32 | 附加页的起始页。 |
| endPage | Int32 | 附加页的结束页。 |
| response | HttpResponse | 将保存文档的响应对象。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
