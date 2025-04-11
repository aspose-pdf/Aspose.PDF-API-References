---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建指向 PDF 文档中自定义操作的链接
type: docs
weight: 140
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink 方法

创建指向 PDF 文档中自定义操作的链接。

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | 矩形 | 活动点击的矩形。 |
| originalPage | Int32 | 创建与链接绑定的矩形的原始页面编号。 |
| color | 颜色 | 活动点击的矩形的颜色。 |
| actionName | Enum[] | 对应于在 Acrobat 查看器中执行菜单项的操作数组（PredefinedAction 枚举的成员）。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)