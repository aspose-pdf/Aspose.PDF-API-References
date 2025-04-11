---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建 PDF 文档中的 JavaScript 链接
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink 方法

在 PDF 文档中创建一个指向 JavaScript 的链接。

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| code | 字符串 | JavaScript 代码。 |
| rect | 矩形 | 用于活动点击的矩形。 |
| originalPage | Int32 | 创建与链接绑定的矩形的原始页面编号。 |
| color | 颜色 | 用于活动点击的矩形的颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)