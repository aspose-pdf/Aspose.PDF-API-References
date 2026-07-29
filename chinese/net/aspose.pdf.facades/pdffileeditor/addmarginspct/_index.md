---
title: "PdfFileEditor.AddMarginsPct"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。调整页面内容大小并添加指定的边距。边距以初始页面尺寸的百分比指定。"
type: docs
weight: 230
url: /zh/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

调整页面内容的大小并添加指定的边距。边距以初始页面尺寸的百分比指定。

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | Stream | 包含源文档的流。 |
| destination | Stream | 保存结果文档的流。 |
| 页面 | Int32[] | 页面索引数组。如果为 null，则处理所有文档页面。 |
| leftMargin | Double | 左边距以初始页面尺寸的百分比表示。 |
| rightMargin | Double | 右边距以初始页面尺寸的百分比表示。 |
| topMargin | Double | 上边距以初始页面尺寸的百分比表示。 |
| bottomMargin | Double | 下边距以初始页面尺寸的百分比表示。 |

### 返回值

如果操作成功执行，则为 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //处理页面 1、2、3
    new int[] { 1, 2, 3}, 
    //左边距为页面宽度的 15%。
    15, 
    //右边距为页面宽度的 10%。
    10, 
    //上边距为页面宽度的 20%。
    20, 
    //下边距为页面宽度的 5%。
    5);
    dest.Close();
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

调整页面内容的大小并添加指定的边距。边距以初始页面尺寸的百分比指定。

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | String | 源文档的路径。 |
| destination | String | 结果文档将保存的路径。 |
| 页面 | Int32[] | 页面索引数组。如果为 null，则处理所有文档页面。 |
| leftMargin | Double | 左边距以初始页面尺寸的百分比表示。 |
| rightMargin | Double | 右边距以初始页面尺寸的百分比表示。 |
| topMargin | Double | 上边距以初始页面尺寸的百分比表示。 |
| bottomMargin | Double | 下边距以初始页面尺寸的百分比表示。 |

### 返回值

如果调整大小成功，则为 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //处理页面 1、2、3
    new int[] { 1, 2, 3}, 
    //左边距为页面宽度的 15%。
    15, 
    //右边距为页面宽度的 10%。
    10, 
    //上边距为页面宽度的 20%。
    20, 
    //下边距为页面宽度的 5%。
    5);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


