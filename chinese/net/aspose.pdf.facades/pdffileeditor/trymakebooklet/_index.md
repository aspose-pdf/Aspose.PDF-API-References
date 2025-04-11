---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。将输入文件制作成小册子并输出到文件
type: docs
weight: 430
url: /zh/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

从源文件制作小册子并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件路径。 |
| pageSize | PageSize | 所需的页面大小。 |
| leftPages | Int32[] | 要放置在左侧的页面编号数组。 |
| rightPages | Int32[] | 要放置在右侧的页面编号数组。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

从 PDF 文件制作小册子并将其存储到 HttpResponse 中。

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文档流。 |
| pageSize | PageSize | 所需的页面大小。 |
| leftPages | Int32[] | 将放置在左侧的页面编号数组。 |
| rightPages | Int32[] | 将放置在右侧的页面编号数组。 |
| response | HttpResponse | HttpResponse 对象。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

从源文件制作小册子并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件路径。 |
| pageSize | PageSize | 输出文件中所需的页面大小。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功，则为 true。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

从源文件制作小册子并将结果存储到 HttpResponse。

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文档流。 |
| pageSize | PageSize | 输出文件中所需的页面大小。 |
| response | HttpResponse | 将保存结果的响应对象。 |

### 返回值

如果小册子成功构建，则为 true。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

将输入文件制作成输出文件的小册子。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 PDF 文件路径和名称。 |
| outputFile | String | 输出 PDF 文件路径和名称。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

从 InputStream 制作小册子到 outputStream。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 PDF 流。 |
| outputStream | Stream | 输出 PDF 流。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

将 inputFile 制作成 outputFile 的小册子。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 PDF 文件路径和名称。 |
| outputFile | String | 输出 PDF 文件路径和名称。 |
| pageSize | PageSize | 输出 PDF 文件的页面大小。 |

### 返回值

如果操作成功，则为 true。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

从输入流制作小册子并将结果保存到输出流。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 PDF 流。 |
| outputStream | Stream | 输出 PDF 流。 |
| pageSize | PageSize | 输出 PDF 文件的页面大小。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

从 firstInputFile 制作自定义小册子到 outputFile。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件。 |
| outputFile | String | 输出 PDF 文件路径和名称。 |
| leftPages | Int32[] | 小册子的左侧页面。 |
| rightPages | Int32[] | 小册子的右侧页面。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

从 firstInputStream 制作自定义小册子到 outputStream。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| outputStream | Stream | 输出 PDF 流。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 右侧页面。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

从 firstInputFile 制作自定义小册子到 outputFile。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件。 |
| outputFile | String | 输出 PDF 文件路径和名称。 |
| pageSize | PageSize | 输出 PDF 文件的页面大小。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 右侧页面。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

从 firstInputStream 制作小册子到 outputStream。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| outputStream | Stream | 输出 PDF 流。 |
| pageSize | PageSize | 输出 PDF 文件的页面大小。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 右侧页面。 |

### 返回值

如果操作成功完成，则为 true；否则为 false。

## 备注

TryMakeBooklet 方法类似于 MakeBooklet 方法，不同之处在于 TryMakeBooklet 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)