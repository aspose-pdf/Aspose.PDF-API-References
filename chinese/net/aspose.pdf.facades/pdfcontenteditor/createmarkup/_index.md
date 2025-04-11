---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建 PDF 文档中的标记注释
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup 方法

在 PDF 文档中创建标记注释。

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | 矩形 | 定义注释在页面上位置的矩形。 |
| contents | 字符串 | 注释的内容。 |
| type | Int32 | 标记注释的类型。可以是 0（高亮），1（下划线），2（删除线），3（波浪线）。 |
| page | Int32 | 注释将被创建的原始页面编号。 |
| clr | 颜色 | 标记的颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 另请参见

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)