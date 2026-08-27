---
title: "PdfContentEditor.CreateApplicationLink"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تُنشئ رابطًا لتشغيل تطبيق في مستند PDF."
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

ينشئ رابطًا لتشغيل تطبيق في مستند PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| التطبيق | String | مسار التطبيق الذي سيتم تشغيله. |
| صفحة | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط. |
| clr | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | المصفوفة التي تحتوي على الإجراءات (أعضاء تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

ينشئ رابطًا لتشغيل تطبيق في مستند PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| التطبيق | String | مسار التطبيق الذي سيتم تشغيله. |
| صفحة | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط. |
| clr | Color | لون المستطيل للنقر النشط. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

ينشئ رابطًا لتشغيل تطبيق في مستند PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| التطبيق | String | مسار التطبيق الذي سيتم تشغيله. |
| صفحة | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


