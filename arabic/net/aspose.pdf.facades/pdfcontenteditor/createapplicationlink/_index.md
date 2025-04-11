---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ رابطًا لتشغيل تطبيق في مستند PDF
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

تنشئ رابطًا لتشغيل تطبيق في مستند PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| application | String | مسار التطبيق الذي سيتم تشغيله. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط. |
| clr | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | مصفوفة من الإجراءات (أعضاء من تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

تنشئ رابطًا لتشغيل تطبيق في مستند PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| application | String | مسار التطبيق الذي سيتم تشغيله. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط. |
| clr | Color | لون المستطيل للنقر النشط. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

تنشئ رابطًا لتشغيل تطبيق في مستند PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| application | String | مسار التطبيق الذي سيتم تشغيله. |
| page | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)