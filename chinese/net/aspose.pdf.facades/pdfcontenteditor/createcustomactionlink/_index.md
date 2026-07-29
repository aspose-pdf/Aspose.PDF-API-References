---
title: "PdfContentEditor.CreateCustomActionLink"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。 创建指向 PDF 文档中自定义操作的链接。"
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink method

在 PDF 文档中创建指向自定义操作的链接。

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 用于激活点击的矩形。 |
| originalPage | Int32 | 将创建带链接矩形的原始页面的页码。 |
| 颜色 | Color | 用于激活点击的矩形颜色。 |
| actionName | Enum[] | 对应在 Acrobat 查看器中执行菜单项的操作数组（PredefinedAction 枚举的成员）。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


