---
title: PdfContentEditor.CreateWebLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。 在 PDF 文档中创建一个网页链接
type: docs
weight: 300
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

在 PDF 文档中创建一个网页链接。

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 活动点击的矩形。 |
| url | String | 网页链接的目标。 |
| originalPage | Int32 | 创建与网页链接绑定的矩形的原始页面编号。 |
| clr | Color | 活动点击的矩形的颜色。 |
| actionName | Enum[] | 与在 Acrobat 查看器中执行菜单项对应的操作数组（PredefinedAction 枚举的成员）。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

在 PDF 文档中创建一个网页链接。

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 活动点击的矩形。 |
| url | String | 网页链接的目标。 |
| originalPage | Int32 | 创建与网页链接绑定的矩形的原始页面编号。 |
| clr | Color | 活动点击的矩形的颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

在 PDF 文档中创建一个网页链接。

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 活动点击的矩形。 |
| url | String | 网页链接的目标。 |
| originalPage | Int32 | 创建与网页链接绑定的矩形的原始页面编号。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)