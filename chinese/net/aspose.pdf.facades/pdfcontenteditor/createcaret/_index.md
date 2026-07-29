---
title: "PdfContentEditor.CreateCaret"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建光标注释。"
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret method

创建插入符号注释。

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | Int32 | 注释将被创建的原始页面编号。 |
| annotRect | Rectangle | 注释矩形定义了注释在页面上的位置。 |
| caretRect | Rectangle | 底层光标的实际边界。 |
| 符号 | String | 将为光标关联一个符号。取值可以是："P"（段落），"None"。 |
| annotContents | String | 注释的内容。 |
| 颜色 | Color | 注释的颜色。 |

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

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


