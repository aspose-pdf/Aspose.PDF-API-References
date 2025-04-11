---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。调整文档页面内容的大小
type: docs
weight: 450
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

调整文档中页面的内容大小。如果页面缩小，则在页面周围添加空白边距。结果存储在 HttpResponse 对象中。

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文件路径。 |
| pages | Int32[] | 要调整大小的页面数组。 |
| parameters | ContentsResizeParameters | 调整大小的参数。 |
| response | HttpResponse | 保存结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则返回 true；否则返回 false。

## 备注

TryResizeContents 方法类似于 ResizeContents 方法，不同之处在于 TryResizeContents 方法在操作失败时不会抛出异常。

### 另请参阅

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

调整文档中页面的内容大小。如果页面缩小，则在页面周围添加空白边距。结果存储在 HttpResponse 对象中。

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 源文件的流。 |
| pages | Int32[] | 要调整大小的页面数组。 |
| parameters | ContentsResizeParameters | 调整大小的参数。 |
| response | HttpResponse | 保存结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则返回 true；否则返回 false。

## 备注

TryResizeContents 方法类似于 ResizeContents 方法，不同之处在于 TryResizeContents 方法在操作失败时不会抛出异常。

### 另请参阅

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

调整文档页面的内容大小。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 包含源文档的流。 |
| destination | Stream | 包含目标文档的流。 |
| pages | Int32[] | 页面索引数组。 |
| parameters | ContentsResizeParameters | 调整大小的参数。 |

### 返回值

如果成功则返回 true。

## 备注

TryResizeContents 方法类似于 ResizeContents 方法，不同之处在于 TryResizeContents 方法在操作失败时不会抛出异常。

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
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### 另请参阅

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

调整文档页面的内容大小。缩小页面内容并添加边距。内容的新大小以默认空间单位指定。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

如果操作成功完成，则返回 true；否则返回 false。

## 备注

TryResizeContents 方法类似于 ResizeContents 方法，不同之处在于 TryResizeContents 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### 另请参阅

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

调整文档中页面的内容大小。如果页面缩小，则在页面周围添加空白边距。

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文档路径。 |
| destination | String | 目标文档路径。 |
| pages | Int32[] | 页面索引数组（页面索引从 1 开始）。 |
| parameters | ContentsResizeParameters | 页面调整大小的参数。 |

### 返回值

如果调整大小成功，则返回 true。

## 备注

TryResizeContents 方法类似于 ResizeContents 方法，不同之处在于 TryResizeContents 方法在操作失败时不会抛出异常。

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### 另请参阅

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)