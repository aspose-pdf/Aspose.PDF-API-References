---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。调整文档页面内容的大小
type: docs
weight: 320
url: /zh/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

调整文档页面的内容大小。

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 包含源文档的流。 |
| destination | Stream | 目标文档的流。 |
| pages | Int32[] | 页面索引数组。 |
| parameters | ContentsResizeParameters | 调整大小的参数。 |

### 返回值

如果成功则返回 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### 另请参阅

* 类 [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

调整文档页面的内容大小。缩小页面内容并添加边距。内容的新大小以默认空间单位指定。

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 包含源文档的流。 |
| destination | Stream | 将保存结果文档的流。 |
| pages | Int32[] | 页面索引数组。如果为 null，则处理所有文档页面。 |
| newWidth | Double | 页面内容的新宽度，以默认空间单位表示。 |
| newHeight | Double | 页面内容的新高度，以默认空间单位表示。 |

### 返回值

如果调整大小成功则返回 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

调整文档页面的内容大小。缩小页面内容并添加边距。内容的新大小以默认空间单位指定。

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文档的路径。 |
| destination | String | 将保存结果文档的路径。 |
| pages | Int32[] | 页面索引数组。如果为 null，则处理所有文档页面。 |
| newWidth | Double | 页面内容的新宽度，以默认空间单位表示。 |
| newHeight | Double | 页面内容的新高度，以默认空间单位表示。 |

### 返回值

如果调整大小成功则返回 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

调整文档中页面的内容大小。如果页面被缩小，则在页面周围添加空白边距。

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文档路径。 |
| destination | String | 目标文档路径。 |
| pages | Int32[] | 页面索引数组（页面索引从 1 开始）。 |
| parameters | ContentsResizeParameters | 页面调整大小的参数。 |

### 返回值

如果调整大小成功则返回 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### 另请参阅

* 类 [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

调整文档的页面大小。在缩小的页面周围添加空白边距。

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | Document | 源文档。 |
| pages | Int32[] | 页面索引列表。 |
| parameters | ContentsResizeParameters | 调整大小的参数。 |

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### 另请参阅

* 类 [Document](../../../aspose.pdf/document/)
* 类 [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

调整文档的页面大小。在缩小的页面周围添加空白边距。

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | Document | 源文档。 |
| parameters | ContentsResizeParameters | 调整大小的参数。 |

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### 另请参阅

* 类 [Document](../../../aspose.pdf/document/)
* 类 [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)