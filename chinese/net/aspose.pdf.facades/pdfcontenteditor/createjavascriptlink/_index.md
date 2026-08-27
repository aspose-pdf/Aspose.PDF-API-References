---
title: "PdfContentEditor.CreateJavaScriptLink"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建一个在 PDF 文档中指向 JavaScript 的链接"
type: docs
weight: 170
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink method

在 PDF 文档中创建指向 JavaScript 的链接。

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| `code` | String | 该 JavaScript 代码。 |
| rect | Rectangle | 用于激活点击的矩形。 |
| originalPage | Int32 | 将创建带链接矩形的原始页面的页码。 |
| 颜色 | Color | 用于激活点击的矩形颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


