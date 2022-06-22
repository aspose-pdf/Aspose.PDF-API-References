---
title: MakeBooklet
second_title: Aspose.PDF for .NET API 参考
description: 从输入文件到输出文件制作小册子
type: docs
weight: 330
url: /zh/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_8}

从输入文件到输出文件制作小册子。

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入pdf文件路径和名称。 |
| outputFile | String | 输出pdf文件路径和名称。 |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet_2}

制作从 InputStream 到 outputStream 的小册子。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 pdf 流。 |
| outputStream | Stream | 输出pdf流。 |

### 返回值

如果操作成功则为真。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_9}

制作从 inputFile 到 outputFile 的小册子。

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入pdf文件路径和名称。 |
| outputFile | String | 输出pdf文件路径和名称。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |

### 返回值

如果操作成功，则为真。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_3}

从输入流制作小册子并将结果保存到输出流中。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入 PDF 流。 |
| outputStream | Stream | 输出pdf流。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |

### 返回值

如果操作成功则为真。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_11}

制作从 firstInputFile 到 outputFile 的自定义小册子。

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件。 |
| outputFile | String | 输出pdf文件路径和名称。 |
| leftPages | Int32[] | 小册子的左页。 |
| rightPages | Int32[] | 小册子的右页。 |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_5}

制作从 firstInputStream 到 outputStream 的自定义小册子。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| outputStream | Stream | 输出 pdf 流。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 正确的页面。 |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_10}

制作从 firstInputFile 到 outputFile 的自定义小册子。

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件。 |
| outputFile | String | 输出pdf文件路径和名称。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 正确的页面。 |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_4}

制作从 firstInputStream 到 outputStream 的小册子。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入流。 |
| outputStream | Stream | 输出 pdf 流。 |
| pageSize | PageSize | 输出 pdf 文件的页面大小。 |
| leftPages | Int32[] | 左侧页面。 |
| rightPages | Int32[] | 正确的页面。 |

### 返回值

boolean - True 表示成功，或 false。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

从源文件制作小册子并将结果存储到 HttpResponse 对象中。

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件路径。 |
| pageSize | PageSize | 所需的页面大小。 |
| leftPages | Int32[] | 要放置在左侧的页码数组。 |
| rightPages | Int32[] | 要放置在右侧的页码数组。 |
| response | HttpResponse | HttpResponse 对象将存储结果。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

从 PDF 文件制作小册子并将其存储到 HttpResponse 中。

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文档流。 |
| pageSize | PageSize | 所需的页面大小。 |
| leftPages | Int32[] | 将放置在左侧的页码数组。 |
| rightPages | Int32[] | 将被放在右边的页码数组。 |
| response | HttpResponse | HttpResponse 对象。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

从源文件制作小册子并将结果存储到 HttpResponse 对象中。

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件路径。 |
| pageSize | PageSize | 输出文件中所需的页面大小。 |
| response | HttpResponse | HttpResponse 对象将存储结果。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

从源文件制作小册子并将结果存储到 HttpResponse。

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文档流。 |
| pageSize | PageSize | 输出文件中所需的页面大小。 |
| response | HttpResponse | Respose 对象将保存resut。 |

### 返回值

如果小册子构建成功，则为 true。

### 也可以看看

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
