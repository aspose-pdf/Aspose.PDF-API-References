---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。附加从 portStreams 中选择的文档数组的页面。结果文档包括 firstInputFile 和所有 portStreams 文档在 startPage 到 endPage 范围内的页面
type: docs
weight: 380
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

附加从 portStreams 中选择的文档数组的页面。结果文档包括 firstInputFile 和所有 portStreams 文档在 startPage 到 endPage 范围内的页面。

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

## 备注

TryAppend 方法类似于 Append 方法，不同之处在于 TryAppend 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

附加从 portFiles 文档中选择的页面。结果文档包括 firstInputFile 和所有 portFiles 文档在 startPage 到 endPage 范围内的页面。

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

操作成功完成返回 true；否则返回 false。

## 备注

TryAppend 方法类似于 Append 方法，不同之处在于 TryAppend 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

将文档附加到源文档并将结果保存到响应对象中。

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 包含源文档的流。 |
| portStreams | Stream[] | 要附加的文档流数组。 |
| startPage | Int32 | 附加页面的起始页面。 |
| endPage | Int32 | 附加页面的结束页面。 |
| response | HttpResponse | 文档将保存到的响应对象。 |

### 返回值

操作成功完成返回 true；否则返回 false。

## 备注

TryAppend 方法类似于 Append 方法，不同之处在于 TryAppend 方法在操作失败时不会抛出异常。

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

将文档附加到源文档并将结果保存到 HttpResponse 对象中。

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 包含源文档的文件名。 |
| portFiles | String[] | 包含附加文档的文件名数组。 |
| startPage | Int32 | 附加页面的起始页面。 |
| endPage | Int32 | 附加页面的结束页面。 |
| response | HttpResponse | 文档将保存到的响应对象。 |

### 返回值

操作成功完成返回 true；否则返回 false。

## 备注

TryAppend 方法类似于 Append 方法，不同之处在于 TryAppend 方法在操作失败时不会抛出异常。

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)