---
title: "PdfContentEditor.CreateLocalLink"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ ارتباطًا محليًا في مستند PDF"
type: docs
weight: 190
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

ينشئ رابطًا محليًا في مستند PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| desPage | Int32 | صفحة الوجهة. |
| originalPage | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط المحلي. |
| clr | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | المصفوفة التي تحتوي على الإجراءات (أعضاء تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

ينشئ رابطًا محليًا في مستند PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| desPage | Int32 | صفحة الوجهة. |
| originalPage | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط المحلي. |
| clr | Color | لون المستطيل للنقر النشط. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

ينشئ رابطًا محليًا في مستند PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| desPage | Int32 | صفحة الوجهة. |
| originalPage | Int32 | رقم الصفحة الأصلية التي سيُنشأ فيها المستطيل المرتبط بالارتباط المحلي. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


