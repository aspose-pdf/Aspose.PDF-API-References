---
title: MakeNUp
second_title: Aspose.PDF for .NET API 参考
description: 使 N-Up 文档从 firstInputFile 到 outputFile.
type: docs
weight: 340
url: /zh/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(string, string, int, int) {#makenup_8}

使 N-Up 文档从 firstInputFile 到 outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入pdf文件路径和名称. |
| outputFile | String | 输出pdf文件路径和名称. |
| x | Int32 | 列数. |
| y | Int32 | 行数。 |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

从输入流生成 N-Up 文档并将结果保存到输出流中。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入pdf流. |
| outputStream | Stream | 输出pdf流. |
| x | Int32 | 列数. |
| y | Int32 | 行数。 |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

将 N-Up 文档从第一个输入流转换为输出流。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入pdf流. |
| outputStream | Stream | 输出pdf流. |
| x | Int32 | 列数. |
| y | Int32 | 行数。 |
| pageSize | PageSize | 输出pdf文件的页面大小. |

### 返回值

如果操作成功则为真。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

将两个输入 PDF 文件中的 N-Up 文档制作成 outputFile。 outputFile 的每一页将包含两页，一页来自第一个输入文件 ，另一页来自第二个输入文件。这两页是水平堆积的。

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | String | 第一个输入文件. |
| secondInputFile | String | 第二个输入文件. |
| outputFile | String | 输出pdf文件路径和名称. |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

从两个输入 PDF 流生成 N-Up 文档到 outputStream.

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstInputStream | Stream | 第一个输入流. |
| secondInputStream | Stream | 第二个输入流. |
| outputStream | Stream | 输出pdf流. |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_11}

从多输入 PDF 文件制作 N-Up 文档到 outputFile。 outputFile 的每一页将包含多页，这些页与相同页码的输入文件中的 页组合。如果 isSidewise 为 true，则多页水平堆积 ，如果 isSidewise 为 false，则垂直堆积。

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | String[] | 输入 PDF 文件。 |
| outputFile | String | 输出pdf文件路径和名称. |
| isSidewise | Boolean | 堆积方式，水平为真，垂直为假。 |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_5}

将多输入 PDF 流中的 N-Up 文档制作成 outputStream。 outputStream 的每一页将包含多个页面，这些页面与相同页码的输入流中的页面 组合。如果isSidewise为真，多页横向堆积 ，如果isSidewise为假，多页垂直堆积。

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStreams | Stream[] | 输入 PDF 流。 |
| outputStream | Stream | 输出pdf流。 |
| isSidewise | Boolean | 堆积方式，水平为真，垂直为假。 |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_9}

将输入文件中的 N-Up 文档制作为 outputFile.

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入pdf文件路径和名称. |
| outputFile | String | 输出pdf文件路径和名称. |
| x | Int32 | 列数. |
| y | Int32 | 行数。 |
| pageSize | PageSize | 输出pdf文件的页面大小. |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, PageSize, HttpResponse) {#makenup}

制作 N-up 文档并将结果存储到 HttpResponse 对象中。

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 源文档流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 结果文件中的页面大小。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, PageSize, HttpResponse) {#makenup_6}

制作 N-up 文档并将结果存储到 HttpResponse 对象中。

```csharp
public bool MakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件的路径。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 结果文件中的页面大小。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(string, int, int, HttpResponse) {#makenup_7}

制作 N-up 文档并将结果存储到 HttpResponse.

```csharp
public bool MakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件名。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, int, int, HttpResponse) {#makenup_1}

制作 N-up 文档并将结果存储到 HttpResponse。

```csharp
public bool MakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文档流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| response | HttpResponse | 将存储结果的 HttpResponse。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
