---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。将输入文件制作成输出文件的小册子
type: docs
weight: 300
url: /zh/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

将输入文件制作成输出文件的小册子。

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 pdf 文件路径和名称。 |
| outputFile | String | 输出 pdf 文件路径和名称。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### 另见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

将输入流制作成输出流的小册子。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出 pdf 流。 |

### 返回值

如果操作成功，则返回 true。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### 另见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

将输入文件制作成输出文件的小册子。

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 pdf 文件路径和名称。 |
| outputFile | String | 输出 pdf 文件路径和名称。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |

### 返回值

如果操作成功，则返回 true。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### 另见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

将输入流制作成小册子并将结果保存到输出流中。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 PDF 流。 |
| outputStream | Stream | 输出 pdf 流。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |

### 返回值

如果操作成功，则返回 true。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### 另见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

从 firstInputFile 制作自定义小册子到 outputFile。

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件。 |
| outputFile | String | 输出 pdf 文件路径和名称。 |
| leftPages | Int32[] | 小册子的左侧页面。 |
| rightPages | Int32[] | 小册子的右侧页面。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

从 firstInputStream 制作自定义小册子到 outputStream。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| outputStream | Stream | 输出 pdf 流。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 右侧页面。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

从 firstInputFile 制作自定义小册子到 outputFile。

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件。 |
| outputFile | String | 输出 pdf 文件路径和名称。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 右侧页面。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

从 firstInputStream 制作小册子到 outputStream。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| outputStream | Stream | 输出 pdf 流。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 右侧页面。 |

### 返回值

boolean - 成功返回 true，失败返回 false。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 另见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

从源文件制作小册子并将结果存储到 HttpResponse 对象中。

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
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

如果操作成功，则返回 true。

### 另见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

从 PDF 文件制作小册子并将其存储到 HttpResponse 中。

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文档流。 |
| pageSize | PageSize | 所需的页面大小。 |
| leftPages | Int32[] | 将放置在左侧的页面编号数组。 |
| rightPages | Int32[] | 将放置在右侧的页面编号数组。 |
| response | HttpResponse | HttpResponse 对象。 |

### 返回值

如果操作成功，则返回 true。

### 另见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

从源文件制作小册子并将结果存储到 HttpResponse 对象中。

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件路径。 |
| pageSize | PageSize | 输出文件中的所需页面大小。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功，则返回 true。

### 另见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

从源文件制作小册子并将结果存储到 HttpResponse。

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文档流。 |
| pageSize | PageSize | 输出文件中的所需页面大小。 |
| response | HttpResponse | 将保存结果的响应对象。 |

### 返回值

如果小册子成功构建，则返回 true。

### 另见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)