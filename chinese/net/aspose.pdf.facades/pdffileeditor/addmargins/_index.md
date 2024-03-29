---
title: AddMargins
second_title: Aspose.PDF for .NET API 参考
description: 调整页面内容的大小并添加指定的边距 以默认空间单位指定边距
type: docs
weight: 250
url: /zh/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

调整页面内容的大小并添加指定的边距。 以默认空间单位指定边距。

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | String | 源文档的路径。 |
| destination | String | 将保存结果文档的路径。 |
| pages | Int32[] | 页面索引数组。如果为 null，则将处理所有文档页面。 |
| leftMargin | Double | 左边距。 |
| rightMargin | Double | 右边距。 |
| topMargin | Double | 上边距。 |
| bottomMargin | Double | 下边距。 |

### 返回值

如果调整大小成功，则为 true。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //处理第1、2、3页
    new int[] { 1, 2, 3}, 
    //左边距为10个单位
    10, 
    //右边距为5个单位
    5, 
    //上边距为5个单位
    5, 
    //下边距为5个单位
    5);
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

---

## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

调整页面内容的大小并添加指定的边距。 以默认空间单位指定边距。

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| source | Stream | 包含源文档的流。 |
| destination | Stream | 将保存结果文档的流。 |
| pages | Int32[] | 页面索引数组。如果为 null，则将处理所有文档页面。 |
| leftMargin | Double | 左边距。 |
| rightMargin | Double | 右边距。 |
| topMargin | Double | 上边距。 |
| bottomMargin | Double | 下边距。 |

### 返回值

如果操作成功，则为 true。

### 例子

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //处理第1、2、3页
    new int[] { 1, 2, 3}, 
    //左边距为10个单位
    10, 
    //右边距为5个单位
    5, 
    //上边距为5个单位
    5, 
    //下边距为5个单位
    5);
    dest.Close();
```

### 也可以看看

* class [PdfFileEditor](../../pdffileeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdffileeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
