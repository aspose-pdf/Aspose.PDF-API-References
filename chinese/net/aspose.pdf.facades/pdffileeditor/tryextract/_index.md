---
title: TryExtract
second_title: Aspose.PDF for .NET API 参考
description: 从输入文件中提取页面另存为新的 Pdf 文件
type: docs
weight: 440
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_2}

从输入文件中提取页面，另存为新的 Pdf 文件。

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件路径。 |
| startPage | Int32 | 起始页码。 |
| endPage | Int32 | 结束页码。 |
| outputFile | String | 输出 Pdf 文件路径。 |

### 返回值

真为成功，或为假。

### 评论

TryExtract 方法与 Extract 方法类似，只是 TryExtract 方法在操作失败时不会抛出异常。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_3}

提取数字数组指定的页面，另存为新的 PDF 文件。

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件路径。 |
| pageNumber | Int32[] | 输入文件的页面索引。 |
| outputFile | String | 输出文件路径。 |

### 返回值

如果操作成功完成，则为 true；否则为假。

### 评论

TryExtract 方法与 Extract 方法类似，只是 TryExtract 方法在操作失败时不会抛出异常。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

提取数字数组指定的页面，另存为新的 Pdf 文件。

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文件流。 |
| pageNumber | Int32[] | 输入文件的页面索引。 |
| outputStream | Stream | 输出文件流。 |

### 返回值

真为成功，或为假。

### 评论

TryExtract 方法与 Extract 方法类似，只是 TryExtract 方法在操作失败时不会抛出异常。

### 例子

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 源文档流。 |
| pageNumber | Int32[] | 将被提取的页码数组。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则为 true；否则为假。

### 评论

TryExtract 方法与 Extract 方法类似，只是 TryExtract 方法在操作失败时不会抛出异常。

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

从源文件中提取指定页面并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件路径。 |
| pageNumber | Int32[] | 将被提取的页码数组。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则为 true；否则为假。

### 评论

TryExtract 方法与 Extract 方法类似，只是 TryExtract 方法在操作失败时不会抛出异常。

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->