---
title: "PdfFileEditor.Append"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。追加从 portStreams 中的文档数组中选择的页面。结果文档包括 firstInputFile 和所有 portStreams 文档中位于 startPage 到 endPage 范围的页面。"
type: docs
weight: 250
url: /zh/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

追加从 portStreams 中的文档数组中选取的页面。结果文档包括 firstInputFile 以及所有 portStreams 文档中位于 startPage 到 endPage 范围的页面。

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 Pdf 流。 |
| portStreams | Stream[] | 要复制页面的文档。 |
| startPage | Int32 | 页面在 portStreams 文档中开始。 |
| endPage | Int32 | 页面在 portStreams 文档中结束。 |
| outputStream | Stream | 输出 Pdf 流。 |

### 返回值

成功返回 true，否则返回 false。

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

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

追加从 portFiles 文档中选取的页面。结果文档包括 firstInputFile 以及所有 portFiles 文档中位于 startPage 到 endPage 范围的页面。

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| portFiles | String[] | 要复制页面的文档。 |
| startPage | Int32 | 页面在 portFiles 文档中开始。 |
| endPage | Int32 | 页面在 portFiles 文档中结束。 |
| outputFile | String | 输出 Pdf 文档。 |

### 返回值

如果操作成功则为 True。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

在 firstInputFile 末尾追加从 portFile 中选取的页面，范围为 startPage 到 endPage。

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件。 |
| portFile | String | Pdf 文件中的页面。 |
| startPage | Int32 | 页面在 portFile 中开始。 |
| endPage | Int32 | 页面在 portFile 中结束。 |
| outputFile | String | 输出 Pdf 文档。 |

### 返回值

如果操作成功则为 True。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

在 firstInputStream 末尾追加从 portStream 中选取的页面，范围为 startPage 到 endPage。

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文件流。 |
| portStream | Stream | Pdf 文件流中的页面。 |
| startPage | Int32 | 页面在 portFile 流中开始。 |
| endPage | Int32 | 页面在 portFile 流中结束。 |
| outputStream | Stream | 输出 Pdf 文件流。 |

### 返回值

成功返回 true，否则返回 false。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


