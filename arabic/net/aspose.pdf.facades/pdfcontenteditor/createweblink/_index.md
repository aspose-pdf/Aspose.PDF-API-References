---
title: PdfContentEditor.CreateWebLink
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تنشئ رابط ويب في مستند PDF
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

تنشئ رابط ويب في مستند PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| url | String | وجهة رابط الويب. |
| originalPage | Int32 | رقم الصفحة الأصلية التي سيتم إنشاء المستطيل المرتبط برابط الويب عليها. |
| clr | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | مصفوفة من الإجراءات (أعضاء من تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

تنشئ رابط ويب في مستند PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| url | String | وجهة رابط الويب. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط برابط الويب. |
| clr | Color | لون المستطيل للنقر النشط. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

تنشئ رابط ويب في مستند PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| url | String | وجهة رابط الويب. |
| originalPage | Int32 | رقم الصفحة الأصلية حيث سيتم إنشاء المستطيل المرتبط برابط الويب. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)