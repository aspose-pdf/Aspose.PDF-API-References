---
title: CreateMarkup
second_title: Aspose.PDF لمرجع .NET API
description: ينشئ تعليقًا توضيحيًا لوثيقة PDF.
type: docs
weight: 200
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

ينشئ تعليقًا توضيحيًا لوثيقة PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل الذي يحدد مكان التعليق التوضيحي على الصفحة. |
| contents | String | محتويات الشرح. |
| type | Int32 | نوع التعليق التوضيحي للترميز. يمكن أن يكون 0 (تمييز) ، 1 (تسطير) ، 2 (StrikeOut) ، 3 (متعرج). |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء التعليق التوضيحي. |
| clr | Color | لون الترميز. |

### أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->