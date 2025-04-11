---
title: PdfContentEditor.CreatePdfDocumentLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。创建指向另一个 PDF 文档页面的链接
type: docs
weight: 220
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## CreatePdfDocumentLink(Rectangle, string, int, int, Color, Enum[]) {#createpdfdocumentlink_2}

创建指向另一个 PDF 文档页面的链接。

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr, Enum[] actionName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 活动点击的矩形。 |
| remotePdf | String | 将要打开的 PDF 文档。 |
| originalPage | Int32 | 创建与链接绑定的矩形的原始页面编号。 |
| destinationPage | Int32 | 目标页面。 |
| clr | Color | 活动点击的矩形颜色。 |
| actionName | Enum[] | 对应于在 Acrobat 查看器中执行菜单项的操作数组（PredefinedAction 枚举的成员）。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int, Color) {#createpdfdocumentlink_1}

创建指向另一个 PDF 文档页面的链接。

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 活动点击的矩形。 |
| remotePdf | String | 将要打开的 PDF 文档。 |
| originalPage | Int32 | 创建与链接绑定的矩形的原始页面编号。 |
| destinationPage | Int32 | 目标页面。 |
| clr | Color | 活动点击的矩形颜色。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int) {#createpdfdocumentlink}

创建指向另一个 PDF 文档页面的链接。

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Rectangle | 活动点击的矩形。 |
| remotePdf | String | 将要打开的 PDF 文档。 |
| originalPage | Int32 | 创建与链接绑定的矩形的原始页面编号。 |
| destinationPage | Int32 | 目标页面。 |

## 示例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### 另请参阅

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)