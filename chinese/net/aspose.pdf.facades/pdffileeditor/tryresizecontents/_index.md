---
title: "PdfFileEditor.TryResizeContents"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。调整文档页面的内容大小。"
type: docs
weight: 450
url: /zh/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

调整文档页面内容的大小。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | Stream | 包含源文档的流。 |
| destination | Stream | 包含目标文档的流。 |
| 页面 | Int32[] | 页面索引数组。 |
| 参数 | ContentsResizeParameters | 调整参数。 |

### 返回值

如果成功则返回 true。

## 备注

TryResizeContents 方法类似于 ResizeContents 方法，但 TryResizeContents 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左边距 = 页面宽度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新内容宽度自动计算为 width - left margin - right margin（100% - 10% - 10% = 80%）
    null,
    //右边距是页面的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上边距 = 高度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新内容高度自动计算（类似于宽度）
    null,
    //下边距是 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### 另请参见

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

调整文档页面内容的大小。收缩页面内容并添加边距。内容的新大小以默认空间单位指定。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | Stream | 包含源文档的流。 |
| destination | Stream | 保存结果文档的流。 |
| 页面 | Int32[] | 页面索引数组。如果为 null，则处理所有文档页面。 |
| newWidth | Double | 页面内容的新宽度（使用默认空间单位）。 |
| newHeight | Double | 页面内容的新高度（使用默认空间单位）。 |

### 返回值

如果操作成功完成则为 true；否则为 false。

## 备注

TryResizeContents 方法类似于 ResizeContents 方法，但 TryResizeContents 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//调整文档的所有页面
null, 
//新内容宽度 = 200
200, 
//新内容高度 = 300
300);
// 页面的其余区域将为空
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

调整文档中页面内容的大小。如果页面被收缩，页面周围会添加空白边距。

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | String | 源文档路径。 |
| destination | String | 目标文档路径。 |
| 页面 | Int32[] | 页面索引数组（页面索引从 1 开始）。 |
| 参数 | ContentsResizeParameters | 页面调整大小的参数。 |

### 返回值

如果调整成功则为 true。

## 备注

TryResizeContents 方法类似于 ResizeContents 方法，但 TryResizeContents 方法在操作失败时不会抛出异常。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左边距 = 页面宽度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新内容宽度自动计算为 width - left margin - right margin（100% - 10% - 10% = 80%）
    null,
    //右边距是页面的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上边距 = 高度的 10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新内容高度自动计算（类似于宽度）
    null,
    //下边距是 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### 另请参见

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


