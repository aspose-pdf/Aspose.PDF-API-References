---
title: Save
second_title: Aspose.PDF لمرجع .NET API
description: يحفظ المستند الذي تم تغييره إلى ملف.
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

يحفظ المستند الذي تم تغييره إلى ملف.

```csharp
public override void Save(string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | مسار الملف حيث سيتم حفظ المستند. |

### أمثلة

يوضح النموذج التالي كيفية حفظ ملف PDF الذي تم تغييره document

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### أنظر أيضا

* class [PdfPageEditor](../../pdfpageeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfpageeditor)
* المجسم [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

يحفظ المستند الذي تم تغييره إلى دفق.

```csharp
public override void Save(Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | دفق حيث سيتم حفظ مستند PDF الذي تم تغييره. |

### أمثلة

يوضح النموذج التالي كيفية حفظ مستند PDF الذي تم تغييره في الدفق.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### أنظر أيضا

* class [PdfPageEditor](../../pdfpageeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfpageeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
