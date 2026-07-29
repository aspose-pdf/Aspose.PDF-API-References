---
title: "PdfPageEditor.Save"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfPageEditor. تحفظ المستند المعدل إلى ملف"
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

يحفظ المستند المعدل إلى ملف.

```csharp
public override void Save(string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | المسار إلى الملف حيث سيتم حفظ المستند. |

## أمثلة

العينة التالية توضح كيفية حفظ مستند PDF المعدل

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### انظر أيضًا

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

يحفظ المستند المعدل إلى تدفق.

```csharp
public override void Save(Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق حيث سيتم حفظ مستند PDF المعدل. |

## أمثلة

العينة التالية توضح كيفية حفظ مستند PDF المعدل في الدفق.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### انظر أيضًا

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


