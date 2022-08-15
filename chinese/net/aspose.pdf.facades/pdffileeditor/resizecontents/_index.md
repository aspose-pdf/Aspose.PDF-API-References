---
title: ResizeContents
second_title: Aspose.PDF for .NET API 参考
description: 调整文档中页面内容的大小如果页面缩小则在页面周围添加空白边距
type: docs
weight: 350
url: /zh/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_4}

调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文档路径。 |
| destination | String | 目标文档路径。 |
| pages | Int32[] | 页面索引数组（页面索引从 1 开始）。 |
| parameters | ContentsResizeParameters | 页面大小调整参数。 |

### 返回值

如果调整大小成功，则为 true。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左边距=页面宽度的10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新内容宽度自动计算为宽度 - 左边距 - 右边距 (100% - 10% - 10% = 80%)
    null,
    //右边距是页面的10% 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上边距 = 高度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //自动计算新内容高度（类似于宽度）
    null,
    //下边距为10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### 也可以看看

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_7}

调整文档页面的大小。在缩小的页面周围添加空白边距。

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Document | 源文件。 |
| pages | Int32[] | 页面索引列表。 |
| parameters | ContentsResizeParameters | 调整参数大小。 |

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左边距=页面宽度的10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新内容宽度自动计算为宽度 - 左边距 - 右边距 (100% - 10% - 10% = 80%)
    null,
    //右边距是页面的10% 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上边距 = 高度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //自动计算新内容高度（类似于宽度）
    null,
    //下边距为10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### 也可以看看

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_6}

调整文档页面的大小。在缩小的页面周围添加空白边距。

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Document | 源文件。 |
| parameters | ContentsResizeParameters | 调整参数大小。 |

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左边距=页面宽度的10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新内容宽度自动计算为宽度 - 左边距 - 右边距 (100% - 10% - 10% = 80%)
    null,
    //右边距是页面的10% 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上边距 = 高度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //自动计算新内容高度（类似于宽度）
    null,
    //下边距为10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### 也可以看看

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents_1}

调整文档页面内容的大小。

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 使用源文档进行流式传输。 |
| destination | Stream | 与目标文档一起流式传输。 |
| pages | Int32[] | 页面索引数组。 |
| parameters | ContentsResizeParameters | 调整参数大小。 |

### 返回值

如果成功则返回真。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左边距=页面宽度的10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新内容宽度自动计算为宽度 - 左边距 - 右边距 (100% - 10% - 10% = 80%)
    null,
    //右边距是页面的10% 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上边距 = 高度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //自动计算新内容高度（类似于宽度）
    null,
    //下边距为10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### 也可以看看

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_2}

调整文档页面内容的大小。 缩小页面内容并添加边距。 以默认空间单位指定新的内容大小。

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 包含源文档的流。 |
| destination | Stream | 将保存结果文档的流。 |
| pages | Int32[] | 页面索引数组。如果为 null，则将处理所有文档页面。 |
| newWidth | Double | 默认空间单位中页面内容的新宽度。 |
| newHeight | Double | 默认空间单位中页面内容的新高度。 |

### 返回值

如果调整大小成功，则为真。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//调整文档所有页面的大小
null, 
//新内容宽度 = 200
200, 
//新内容高度 = 300
300);
// 页面的剩余区域为空
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_5}

调整文档页面内容的大小。 缩小页面内容并添加边距。 以默认空间单位指定新的内容大小。

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文档的路径。 |
| destination | String | 将保存结果文档的路径。 |
| pages | Int32[] | 页面索引数组。如果为 null，则将处理所有文档页面。 |
| newWidth | Double | 默认空间单位中页面内容的新宽度。 |
| newHeight | Double | 默认空间单位中页面内容的新高度。 |

### 返回值

如果调整大小成功，则为 true。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//调整文档所有页面的大小
null, 
//新内容宽度 = 200
200, 
//新内容高度 = 300
300);
// 页面的剩余区域为空
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## ResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#resizecontents_3}

调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。

```csharp
public bool ResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文件的路径。 |
| pages | Int32[] | 要调整大小的页面数组。 |
| parameters | ContentsResizeParameters | 调整参数大小。 |
| response | HttpResponse | 保存结果的 HttpResponse 对象。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## ResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#resizecontents}

调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。

```csharp
public bool ResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 源文件流。 |
| pages | Int32[] | 要调整大小的页面数组。 |
| parameters | ContentsResizeParameters | 调整参数大小。 |
| response | HttpResponse | 保存结果的 HttpResponse 对象。 |

### 返回值

如果操作成功则为真。

### 也可以看看

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
