---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 方法。调整页面内容并添加指定的边距。边距以初始页面大小的百分比指定
type: docs
weight: 230
url: /zh/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

调整页面内容并添加指定的边距。边距以初始页面大小的百分比指定。

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 包含源文档的流。 |
| destination | Stream | 结果文档将保存到的流。 |
| pages | Int32[] | 页面索引数组。如果为 null，则将处理所有文档页面。 |
| leftMargin | Double | 左边距，以初始页面大小的百分比表示。 |
| rightMargin | Double | 右边距，以初始页面大小的百分比表示。 |
| topMargin | Double | 上边距，以初始页面大小的百分比表示。 |
| bottomMargin | Double | 下边距，以初始页面大小的百分比表示。 |

### 返回值

如果操作成功执行，则返回 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

调整页面内容并添加指定的边距。边距以初始页面大小的百分比指定。

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文档的路径。 |
| destination | String | 结果文档将保存到的路径。 |
| pages | Int32[] | 页面索引数组。如果为 null，则将处理所有文档页面。 |
| leftMargin | Double | 左边距，以初始页面大小的百分比表示。 |
| rightMargin | Double | 右边距，以初始页面大小的百分比表示。 |
| topMargin | Double | 上边距，以初始页面大小的百分比表示。 |
| bottomMargin | Double | 下边距，以初始页面大小的百分比表示。 |

### 返回值

如果调整大小成功，则返回 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### 另请参阅

* 类 [PdfFileEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)