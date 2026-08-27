---
title: "PdfContentEditor.CreateLocalLink"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建 PDF Document 中的本地链接"
type: docs
weight: 190
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

在 PDF 文档中创建本地链接。

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 用于激活点击的矩形。 |
| desPage | Int32 | 目标页面 |
| originalPage | Int32 | 将创建绑定本地链接的矩形的原始页码 |
| clr | Color | 用于激活点击的矩形颜色。 |
| actionName | Enum[] | 对应在 Acrobat 查看器中执行菜单项的操作数组（PredefinedAction 枚举的成员）。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

在 PDF 文档中创建本地链接。

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 用于激活点击的矩形。 |
| desPage | Int32 | 目标页面 |
| originalPage | Int32 | 将创建绑定本地链接的矩形的原始页码 |
| clr | Color | 用于激活点击的矩形颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

在 PDF 文档中创建本地链接。

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 用于激活点击的矩形。 |
| desPage | Int32 | 目标页面 |
| originalPage | Int32 | 将创建绑定本地链接的矩形的原始页码 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


