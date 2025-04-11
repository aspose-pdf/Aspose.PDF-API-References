---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。附加从 portStreams 中选择的文档数组的页面。结果文档包括 firstInputFile 和所有 portStreams 文档在 startPage 到 endPage 范围内的页面
type: docs
weight: 250
url: /zh/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

附加从 portStreams 中选择的文档数组的页面。结果文档包括 firstInputFile 和所有 portStreams 文档在 startPage 到 endPage 范围内的页面。

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 Pdf 流。 |
| portStreams | Stream[] | 要复制页面的文档。 |
| startPage | Int32 | 在 portStreams 文档中开始的页面。 |
| endPage | Int32 | 在 portStreams 文档中结束的页面。 |
| outputStream | Stream | 输出 Pdf 流。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

附加从 portFiles 文档中选择的页面。结果文档包括 firstInputFile 和所有 portFiles 文档在 startPage 到 endPage 范围内的页面。

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| portFiles | String[] | 要复制页面的文档。 |
| startPage | Int32 | 在 portFiles 文档中开始的页面。 |
| endPage | Int32 | 在 portFiles 文档中结束的页面。 |
| outputFile | String | 输出 Pdf 文档。 |

### 返回值

操作成功返回 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

附加从 portFile 中选择的页面，范围从 startPage 到 endPage，在 firstInputFile 的末尾。

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| portFile | String | 来自 Pdf 文件的页面。 |
| startPage | Int32 | 在 portFile 中开始的页面。 |
| endPage | Int32 | 在 portFile 中结束的页面。 |
| outputFile | String | 输出 Pdf 文档。 |

### 返回值

操作成功返回 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

附加从 portStream 中选择的页面，范围从 startPage 到 endPage，在 firstInputStream 的末尾。

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文件流。 |
| portStream | Stream | 来自 Pdf 文件流的页面。 |
| startPage | Int32 | 在 portFile 流中开始的页面。 |
| endPage | Int32 | 在 portFile 流中结束的页面。 |
| outputStream | Stream | 输出 Pdf 文件流。 |

### 返回值

成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)