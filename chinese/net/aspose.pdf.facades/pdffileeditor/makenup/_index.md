---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。从两个输入 PDF 流创建 NUp 文档到 outputStream
type: docs
weight: 310
url: /zh/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

从 firstInputFile 创建 N-Up 文档到 outputFile。

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入 pdf 文件路径和名称。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

从输入流创建 N-Up 文档并将结果保存到输出流。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

从第一个输入流创建 N-Up 文档到输出流。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |

### 返回值

如果操作成功则返回 true。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 另请参见

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

从两个输入 PDF 文件创建 N-Up 文档到 outputFile。每个 outputFile 的页面将包含两个页面，一个来自第一个输入文件，另一个来自第二个输入文件。这两个页面水平堆叠。

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | 字符串 | 第一个输入文件。 |
| secondInputFile | 字符串 | 第二个输入文件。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

从两个输入 PDF 流创建 N-Up 文档到 outputStream。

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputStream | Stream | 第一个输入流。 |
| secondInputStream | Stream | 第二个输入流。 |
| outputStream | Stream | 输出 pdf 流。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

从多个输入 PDF 文件创建 N-Up 文档到 outputFile。每个 outputFile 的页面将包含多个页面，这些页面是来自输入文件中相同页码的组合。如果 isSidewise 为 true，则多个页面水平堆叠；如果 isSidewise 为 false，则垂直堆叠。

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | 字符串[] | 输入 Pdf 文件。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |
| isSidewise | 布尔值 | 堆叠方式，true 为水平，false 为垂直。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

从多个输入 PDF 流创建 N-Up 文档到 outputStream。每个 outputStream 的页面将包含多个页面，这些页面是来自输入流中相同页码的组合。如果 isSidewise 为 true，则多个页面水平堆叠；如果 isSidewise 为 false，则垂直堆叠。

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStreams | Stream[] | 输入 Pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| isSidewise | 布尔值 | 堆叠方式，true 为水平，false 为垂直。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

从输入文件创建 N-Up 文档到 outputFile。

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入 pdf 文件路径和名称。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### 另请参见

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

从 firstInputFile 创建 N-Up 文档到 outputFile。

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入 pdf 文件路径和名称。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

从输入流创建 N-Up 文档并将结果保存到输出流。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

从第一个输入流创建 N-Up 文档到输出流。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |

### 返回值

如果操作成功则返回 true。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 另请参见

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

从两个输入 PDF 文件创建 N-Up 文档到 outputFile。每个 outputFile 的页面将包含两个页面，一个来自第一个输入文件，另一个来自第二个输入文件。这两个页面水平堆叠。

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | 字符串 | 第一个输入文件。 |
| secondInputFile | 字符串 | 第二个输入文件。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 另请参见

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)