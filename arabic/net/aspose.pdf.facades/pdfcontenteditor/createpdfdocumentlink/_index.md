---
title: "PdfContentEditor.CreatePdfDocumentLink"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ ارتباطًا إلى صفحة مستند PDF آخر"
type: docs
weight: 220
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## CreatePdfDocumentLink(Rectangle, string, int, int, Color, Enum[]) {#createpdfdocumentlink_2}

ينشئ رابطًا إلى صفحة مستند PDF آخر.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr, Enum[] actionName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| remotePdf | String | مستند PDF الذي ستُفتح صفحته. |
| originalPage | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط. |
| destinationPage | Int32 | صفحة الوجهة. |
| clr | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | المصفوفة التي تحتوي على الإجراءات (أعضاء تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int, Color) {#createpdfdocumentlink_1}

ينشئ رابطًا إلى صفحة مستند PDF آخر.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| remotePdf | String | مستند PDF الذي ستُفتح صفحته. |
| originalPage | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط. |
| destinationPage | Int32 | صفحة الوجهة. |
| clr | Color | لون المستطيل للنقر النشط. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int) {#createpdfdocumentlink}

ينشئ رابطًا إلى صفحة مستند PDF آخر.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| remotePdf | String | مستند PDF الذي ستُفتح صفحته. |
| originalPage | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط. |
| destinationPage | Int32 | صفحة الوجهة. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


