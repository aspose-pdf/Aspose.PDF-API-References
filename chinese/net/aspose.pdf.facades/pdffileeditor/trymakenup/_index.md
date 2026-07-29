---
title: "PdfFileEditor.TryMakeNUp"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。将 firstInputFile 制作为 NUp 文档并保存到 outputFile"
type: docs
weight: 440
url: /zh/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

从 firstInputFile 生成 N‑Up 文档到 outputFile。

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 pdf 文件的路径和名称。 |
| outputFile | String | 输出 pdf 文件的路径和名称。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，但如果操作失败，TryMakeNUp 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

从输入流生成 N‑Up 文档并将结果保存到输出流。

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 PDF 流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，但如果操作失败，TryMakeNUp 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

从第一个输入流生成 N‑Up 文档并保存到输出流。

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 PDF 流。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 输出 pdf 文件的页面尺寸。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，但如果操作失败，TryMakeNUp 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

从两个输入 PDF 文件创建 N-Up 文档并输出到 outputFile。outputFile 的每一页将包含两页，一页来自第一个输入文件，另一页来自第二个输入文件。这两页水平堆叠。

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputFile | String | 第一个输入文件。 |
| secondInputFile | String | 第二个输入文件。 |
| outputFile | String | 输出 pdf 文件的路径和名称。 |

### 返回值

如果操作成功完成则为 true；否则为 false

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，但如果操作失败，TryMakeNUp 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

从两个输入 PDF 流创建 N-Up 文档并输出到 outputStream。

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstInputStream | Stream | 第一个输入流。 |
| secondInputStream | Stream | 第二个输入流。 |
| outputStream | Stream | 输出 PDF 流。 |

### 返回值

如果操作成功完成则为 true；否则为 false

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，但如果操作失败，TryMakeNUp 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

从多个输入 PDF 文件生成 N‑Up 文档到 outputFile。outputFile 的每一页将包含多页，这些多页是来自输入文件中相同页码的页面的组合。如果 isSidewise 为 true，则多页水平堆叠；如果 isSidewise 为 false，则垂直堆叠。

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFiles | String[] | 输入的 Pdf 文件。 |
| outputFile | String | 输出 pdf 文件的路径和名称。 |
| isSidewise | Boolean | 堆叠方式，水平为 true，垂直为 false。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，但如果操作失败，TryMakeNUp 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

从多个输入 PDF 流创建 N-Up 文档并输出到 outputStream。outputStream 的每一页将包含多页，这些页面是来自相同页码的输入流页面的组合。如果 isSidewise 为 true，则多页水平堆叠；如果为 false，则垂直堆叠。

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStreams | Stream[] | 输入的 Pdf 流。 |
| outputStream | Stream | 输出 PDF 流。 |
| isSidewise | Boolean | 堆叠方式，水平为 true，垂直为 false。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，但如果操作失败，TryMakeNUp 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

从输入文件生成 N‑Up 文档到 outputFile。

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 pdf 文件的路径和名称。 |
| outputFile | String | 输出 pdf 文件的路径和名称。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 输出 pdf 文件的页面尺寸。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryMakeNUp 方法类似于 MakeNUp 方法，但如果操作失败，TryMakeNUp 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


