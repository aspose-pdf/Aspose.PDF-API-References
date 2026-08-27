---
title: "PdfContentEditor.CreatePopup"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建 PDF 文档中的弹出注释"
type: docs
weight: 250
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

在 PDF 文档中创建弹出注释。

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| 内容 | String | 注释的内容。 |
| 打开 | Boolean | 一个标志，指定弹出注释是否应初始显示为打开状态。 |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


