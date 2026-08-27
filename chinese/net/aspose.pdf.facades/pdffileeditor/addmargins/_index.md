---
title: "PdfFileEditor.AddMargins"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileEditor 方法。调整页面内容大小并添加指定的边距。边距以默认空间单位指定。"
type: docs
weight: 220
url: /zh/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

调整页面内容的大小并添加指定的边距。边距以默认空间单位指定。

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | Stream | 包含源文档的流。 |
| destination | Stream | 保存结果文档的流。 |
| 页面 | Int32[] | 页面索引数组。如果为 null，则处理所有文档页面。 |
| leftMargin | Double | 左边距。 |
| rightMargin | Double | 右边距。 |
| topMargin | Double | 上边距。 |
| bottomMargin | Double | 下边距。 |

### 返回值

如果操作成功，则为 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //处理页面 1、2、3
    new int[] { 1, 2, 3}, 
    //左边距为 10 单位
    10, 
    //右边距为 5 单位
    5, 
    //上边距为 5 单位
    5, 
    //下边距为 5 单位
    5);
    dest.Close();
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

调整页面内容的大小并添加指定的边距。边距以默认空间单位指定。

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 源 | String | 源文档的路径。 |
| destination | String | 结果文档将保存的路径。 |
| 页面 | Int32[] | 页面索引数组。如果为 null，则处理所有文档页面。 |
| leftMargin | Double | 左边距。 |
| rightMargin | Double | 右边距。 |
| topMargin | Double | 上边距。 |
| bottomMargin | Double | 下边距。 |

### 返回值

如果调整成功则为 true。

## 示例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //处理页面 1、2、3
    new int[] { 1, 2, 3}, 
    //左边距为 10 单位
    10, 
    //右边距为 5 单位
    5, 
    //上边距为 5 单位
    5, 
    //下边距为 5 单位
    5);
```

### 另请参见

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


