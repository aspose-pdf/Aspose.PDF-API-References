---
title: "PdfContentEditor.CreateMarkup"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。 在 PDF 文档中创建标记注释。"
type: docs
weight: 200
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

在 PDF 文档中创建标记注释。

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 定义注释在页面上位置的矩形。 |
| 内容 | String | 注释的内容。 |
| 类型 | Int32 | 标记注释的类型。 可以是 0（Highlight）、1（Underline）、2（StrikeOut）、3（Squiggly）。 |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |
| clr | Color | 标记的颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


