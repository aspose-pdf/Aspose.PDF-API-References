---
title: TryResizeContents
second_title: Aspose.PDF for .NET API 参考
description: 调整文档中页面内容的大小如果页面缩小则在页面周围添加空白边距结果存储到 HttpResponse 对象中
type: docs
weight: 480
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents_3}

调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文件的路径。 |
| pages | Int32[] | 要调整大小的页面数组。 |
| parameters | ContentsResizeParameters | 调整参数大小。 |
| response | HttpResponse | 保存结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则为真；否则为假。

### 评论

TryResizeContents 方法类似于 ResizeContents 方法，除了 TryResizeContents 方法不会抛出异常，如果操作失败。

### 也可以看看

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。结果存储到 HttpResponse 对象中。

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 源文件流。 |
| pages | Int32[] | 要调整大小的页面数组。 |
| parameters | ContentsResizeParameters | 调整参数大小。 |
| response | HttpResponse | 保存结果的 HttpResponse 对象。 |

### 返回值

如果操作成功完成，则为真；否则为假。

### 评论

TryResizeContents 方法类似于 ResizeContents 方法，除了 TryResizeContents 方法不会抛出异常，如果操作失败。

### 也可以看看

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

调整文档页面内容的大小。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 流与源文档。 |
| destination | Stream | 与目标文档一起流式传输。 |
| pages | Int32[] | 页面索引数组。 |
| parameters | ContentsResizeParameters | 调整参数大小。 |

### 返回值

如果成功则返回真。

### 评论

TryResizeContents 方法类似于 ResizeContents 方法，除了 TryResizeContents 方法不会抛出异常，如果操作失败。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左边距=页面宽度的10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
      //新内容的宽度自动计算为宽度 - 左边距 - 右边距 (100% - 10% - 10% = 80%)
    null,
      //右边距是页面

    PdfFileEditor.ContentsResizeValue.Percents(10),
      //上边距 = 高度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
      //自动计算新内容高度（类似于宽度）
    null,
      //下边距为10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### 也可以看看

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_2}

调整文档页面内容的大小。 缩小页面内容并添加边距。 新的内容大小以默认空间单位指定。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 包含源文档的流。 |
| destination | Stream | 将保存结果文档的流。 |
| pages | Int32[] | 页面索引数组。如果为 null，则将处理所有文档页面。 |
| newWidth | Double | 以默认空间单位表示的页面内容的新宽度。 |
| newHeight | Double | 以默认空间单位表示的页面内容的新高度。 |

### 返回值

如果操作成功完成，则为真；否则为假。

### 评论

TryResizeContents 方法类似于 ResizeContents 方法，除了 TryResizeContents 方法不会抛出异常，如果操作失败。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
  //调整document

null, 
//新内容宽度= 200
200, 
  //新内容高度= 300
300);
  // 页面的剩余区域为空
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_4}

调整文档中页面内容的大小。如果页面缩小，则在页面周围添加空白边距。

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文档路径。 |
| destination | String | 目标文档路径。 |
| pages | Int32[] | 页面索引数组（页面索引从 1 开始）。 |
| parameters | ContentsResizeParameters | 页面调整大小的参数。 |

### 返回值

如果调整大小成功，则为真。

### 评论

TryResizeContents 方法类似于 ResizeContents 方法，除了 TryResizeContents 方法不会抛出异常，如果操作失败。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左边距=页面宽度的10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
      //新内容的宽度自动计算为宽度 - 左边距 - 右边距 (100% - 10% - 10% = 80%)
    null,
      //右边距是页面

    PdfFileEditor.ContentsResizeValue.Percents(10),
      //上边距 = 高度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
      //自动计算新内容高度（类似于宽度）
    null,
      //下边距为10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### 也可以看看

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
