---
title: PdfContentEditor.CreatePdfDocumentLink
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ رابطًا إلى صفحة مستند PDF آخر
type: docs
weight: 220
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## CreatePdfDocumentLink(Rectangle, string, int, int, Color, Enum[]) {#createpdfdocumentlink_2}

تنشئ رابطًا إلى صفحة مستند PDF آخر.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr, Enum[] actionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| remotePdf | String | مستند PDF الذي ستفتح صفحته. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط. |
| destinationPage | Int32 | الصفحة الوجهة. |
| clr | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | مصفوفة من الإجراءات (أعضاء من تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int, Color) {#createpdfdocumentlink_1}

تنشئ رابطًا إلى صفحة مستند PDF آخر.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| remotePdf | String | مستند PDF الذي ستفتح صفحته. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط. |
| destinationPage | Int32 | الصفحة الوجهة. |
| clr | Color | لون المستطيل للنقر النشط. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int) {#createpdfdocumentlink}

تنشئ رابطًا إلى صفحة مستند PDF آخر.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| remotePdf | String | مستند PDF الذي ستفتح صفحته. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط. |
| destinationPage | Int32 | الصفحة الوجهة. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)