---
title: "PdfContentEditor.CreateWebLink"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تنشئ رابط ويب في مستند PDF"
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

ينشئ رابط ويب في مستند PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| عنوان URL | String | وجهة رابط الويب. |
| originalPage | Int32 | عدد الصفحة الأصلية التي سيتم إنشاء المستطيل المرتبط بالرابط الويب عليها. |
| clr | Color | لون المستطيل للنقر النشط. |
| actionName | Enum[] | المصفوفة التي تحتوي على الإجراءات (أعضاء تعداد PredefinedAction) المقابلة لتنفيذ عناصر القائمة في عارض Acrobat. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

ينشئ رابط ويب في مستند PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| عنوان URL | String | وجهة رابط الويب. |
| originalPage | Int32 | عدد الصفحة الأصلية التي سيتم إنشاء المستطيل المرتبط بالرابط الويب عليها. |
| clr | Color | لون المستطيل للنقر النشط. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

ينشئ رابط ويب في مستند PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | المستطيل للنقر النشط. |
| عنوان URL | String | وجهة رابط الويب. |
| originalPage | Int32 | عدد الصفحة الأصلية التي سيتم إنشاء المستطيل المرتبط بالرابط الويب عليها. |

## أمثلة

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


