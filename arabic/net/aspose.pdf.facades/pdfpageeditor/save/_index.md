---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfPageEditor. تحفظ المستند المعدل في ملف
type: docs
weight: 180
url: /ar/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

تحفظ المستند المعدل في ملف.

```csharp
public override void Save(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | المسار إلى الملف الذي سيتم حفظ المستند فيه. |

## Examples

العينة التالية توضح كيفية حفظ مستند PDF المعدل

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### See Also

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

تحفظ المستند المعدل في دفق.

```csharp
public override void Save(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | الدفق الذي سيتم حفظ مستند PDF المعدل فيه. |

## Examples

العينة التالية توضح كيفية حفظ مستند PDF المعدل في دفق.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### See Also

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)