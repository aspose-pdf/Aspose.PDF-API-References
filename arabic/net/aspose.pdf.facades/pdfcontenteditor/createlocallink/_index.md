---
title: PdfContentEditor.CreateLocalLink
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ رابطًا محليًا في مستند PDF
type: docs
weight: 190
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

تنشئ رابطًا محليًا في مستند PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| desPage | Int32 | الصفحة الوجهة. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط المحلي. |
| clr | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | مصفوفة الإجراءات (أعضاء من تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

تنشئ رابطًا محليًا في مستند PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| desPage | Int32 | الصفحة الوجهة. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط المحلي. |
| clr | Color | لون المستطيل للنقر النشط. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

تنشئ رابطًا محليًا في مستند PDF.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| desPage | Int32 | الصفحة الوجهة. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط بالرابط المحلي. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)