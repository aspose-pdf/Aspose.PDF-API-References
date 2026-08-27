---
title: "PdfFileEditor.ResizeContentsPct"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。调整文档页面内容的大小。缩小页面内容并添加页边距。新的内容尺寸以百分比指定。"
type: docs
weight: 330
url: /zh/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

调整文档页面内容的大小。收缩页面内容并添加边距。内容的新大小以百分比指定。

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | Stream | 包含源文档的流。 |
| destination | Stream | 保存结果文档的流。 |
| 页面 | Int32[] | 页面索引数组。如果为 null，则处理所有文档页面。 |
| newWidth | Double | 页面内容的新宽度（百分比）。 |
| newHeight | Double | 页面内容的新高度（百分比）。 |

### 返回值

如果成功调整大小则为 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//调整文档的所有页面
null, 
//新内容宽度 = 初始尺寸的 60%
60, 
//新内容高度 = 初始尺寸的 60%
60);
// 页面其余区域将为空（页面边距）。左右边距的大小为 (100% - 60%) / 2 = 20%。
// 上下边距同理。
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

调整文档页面内容的大小。收缩页面内容并添加边距。内容的新大小以百分比指定。

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | String | 源文档的路径。 |
| destination | String | 结果文档将保存的路径。 |
| 页面 | Int32[] | 页面索引数组。如果为 null，则处理所有文档页面。 |
| newWidth | Double | 页面内容的新宽度（百分比）。 |
| newHeight | Double | 页面内容的新高度（百分比）。 |

### 返回值

如果调整成功则为 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//调整文档的所有页面
null, 
//新内容宽度 = 初始尺寸的 60%
60, 
//新内容高度 = 初始尺寸的 60%
60);
// 页面其余区域将为空（页面边距）。左右边距的大小为 (100% - 60%) / 2 = 20%。
// 上下边距同理。
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


