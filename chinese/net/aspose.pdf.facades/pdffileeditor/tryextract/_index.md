---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。 从输入文件中提取页面并保存为新的 Pdf 文件
type: docs
weight: 410
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

从输入文件中提取页面，保存为新的 Pdf 文件。

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入 Pdf 文件路径。 |
| startPage | Int32 | 起始页码。 |
| endPage | Int32 | 结束页码。 |
| outputFile | String | 输出 Pdf 文件路径。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

TryExtract 方法类似于 Extract 方法，不同之处在于如果操作失败，TryExtract 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

提取由数字数组指定的页面，保存为新的 PDF 文件。

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 输入文件路径。 |
| pageNumber | Int32[] | 输入文件中页面的索引。 |
| outputFile | String | 输出文件路径。 |

### 返回值

如果操作成功完成，则返回 true；否则返回 false。

## 备注

TryExtract 方法类似于 Extract 方法，不同之处在于如果操作失败，TryExtract 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

提取由数字数组指定的页面，保存为新的 Pdf 文件。

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 输入文件流。 |
| pageNumber | Int32[] | 输入文件中页面的索引。 |
| outputStream | Stream | 输出文件流。 |

### 返回值

成功返回 true，失败返回 false。

## 备注

TryExtract 方法类似于 Extract 方法，不同之处在于如果操作失败，TryExtract 方法不会抛出异常。

## 示例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

从源文件中提取指定页面，并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | Stream | 源文档的流。 |
| pageNumber | Int32[] | 将要提取的页面号码数组。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则返回 true；否则返回 false。

## 备注

TryExtract 方法类似于 Extract 方法，不同之处在于如果操作失败，TryExtract 方法不会抛出异常。

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

从源文件中提取指定页面，并将结果存储到 HttpResponse 对象中。

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | String | 源文件路径。 |
| pageNumber | Int32[] | 将要提取的页面号码数组。 |
| response | HttpResponse | 将存储结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则返回 true；否则返回 false。

## 备注

TryExtract 方法类似于 Extract 方法，不同之处在于如果操作失败，TryExtract 方法不会抛出异常。

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)