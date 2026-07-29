---
title: "PdfFileEditor.TryAppend"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。追加从 portStreams 中的文档数组中选择的页面。结果文档包括 firstInputFile 和所有 portStreams 文档中位于 startPage 到 endPage 范围的页面。"
type: docs
weight: 380
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

追加从 portStreams 中的文档数组中选取的页面。结果文档包括 firstInputFile 以及所有 portStreams 文档中位于 startPage 到 endPage 范围的页面。

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

## 备注

TryAppend 方法类似于 Append 方法，但如果操作失败，TryAppend 方法不会抛出异常。

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

追加从 portFiles 文档中选取的页面。结果文档包括 firstInputFile 以及所有 portFiles 文档中位于 startPage 到 endPage 范围的页面。

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

如果操作成功完成则为 true；否则为 false。

## 备注

TryAppend 方法类似于 Append 方法，但如果操作失败，TryAppend 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


