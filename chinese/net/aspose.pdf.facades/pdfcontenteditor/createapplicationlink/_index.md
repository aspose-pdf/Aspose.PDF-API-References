---
title: "PdfContentEditor.CreateApplicationLink"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。创建一个在 PDF 文档中启动应用程序的链接"
type: docs
weight: 110
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

在 PDF 文档中创建用于启动应用程序的链接。

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 用于激活点击的矩形。 |
| application | String | 要启动的应用程序的路径。 |
| 页面 | Int32 | 将创建带链接矩形的原始页面的页码。 |
| clr | Color | 用于激活点击的矩形颜色。 |
| actionName | Enum[] | 对应在 Acrobat 查看器中执行菜单项的操作数组（PredefinedAction 枚举的成员）。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

在 PDF 文档中创建用于启动应用程序的链接。

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 用于激活点击的矩形。 |
| application | String | 要启动的应用程序的路径。 |
| 页面 | Int32 | 将创建带链接矩形的原始页面的页码。 |
| clr | Color | 用于激活点击的矩形颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

在 PDF 文档中创建用于启动应用程序的链接。

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 用于激活点击的矩形。 |
| application | String | 要启动的应用程序的路径。 |
| 页面 | Int32 | 将创建带链接矩形的原始页面的页码。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


