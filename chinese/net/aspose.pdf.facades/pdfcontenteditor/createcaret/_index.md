---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建光标注释
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret 方法

创建光标注释。

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | Int32 | 注释将被创建的原始页面编号。 |
| annotRect | Rectangle | 定义注释在页面上位置的注释矩形。 |
| caretRect | Rectangle | 基础光标的实际边界。 |
| symbol | String | 将与光标关联的符号。值可以是：“P”（段落）、“None”。 |
| annotContents | String | 注释的内容。 |
| color | Color | 注释的颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)