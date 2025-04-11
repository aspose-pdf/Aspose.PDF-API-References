---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。从 firstInputFile 制作 NUp 文档到 outputFile
type: docs
weight: 440
url: /zh/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

制作 N-up 文档并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 源文件路径。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 结果文件中的页面大小。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

### 另请参阅

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

制作 N-up 文档并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 源文档的流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 结果文件中的页面大小。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

### 另请参阅

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

制作 N-up 文档并将结果存储到 HttpResponse。

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 源文件名。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

制作 N-up 文档并将结果存储到 HttpResponse。

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文档的流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| response | HttpResponse | 将存储结果的 HttpResponse。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

从 firstInputFile 制作 N-Up 文档到 outputFile。

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入 pdf 文件路径和名称。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

从输入流制作 N-Up 文档并将结果保存到输出流。

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

从第一个输入流制作 N-Up 文档到输出流。

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 另请参阅

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

从两个输入 PDF 文件制作 N-Up 文档到 outputFile。每个 outputFile 的页面将包含两个页面，一个页面来自第一个输入文件，另一个页面来自第二个输入文件。这两个页面水平堆叠。

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | 字符串 | 第一个输入文件。 |
| secondInputFile | 字符串 | 第二个输入文件。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

从两个输入 PDF 流制作 N-Up 文档到 outputStream。

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputStream | Stream | 第一个输入流。 |
| secondInputStream | Stream | 第二个输入流。 |
| outputStream | Stream | 输出 pdf 流。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

从多个输入 PDF 文件制作 N-Up 文档到 outputFile。每个 outputFile 的页面将包含多个页面，这些页面是输入文件中相同页码的组合。如果 isSidewise 为 true，则多个页面水平堆叠；如果 isSidewise 为 false，则垂直堆叠。

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | 字符串[] | 输入 Pdf 文件。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |
| isSidewise | 布尔值 | 堆叠方式，true 为水平，false 为垂直。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

从多个输入 PDF 流制作 N-Up 文档到 outputStream。每个 outputStream 的页面将包含多个页面，这些页面是输入流中相同页码的组合。如果 isSidewise 为 true，则多个页面水平堆叠；如果 isSidewise 为 false，则垂直堆叠。

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStreams | Stream[] | 输入 Pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| isSidewise | 布尔值 | 堆叠方式，true 为水平，false 为垂直。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

从输入文件制作 N-Up 文档到 outputFile。

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | 字符串 | 输入 pdf 文件路径和名称。 |
| outputFile | 字符串 | 输出 pdf 文件路径和名称。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，不同之处在于 TryMakeNUp 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### 另请参阅

* 类 [PageSize](../../../aspose.pdf/pagesize/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)