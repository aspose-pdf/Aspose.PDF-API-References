---
title: "Form.ImportXml"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تستورد محتوى الحقول من ملف xml وتضعه في ملف pdf الجديد."
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputXmlStream | Stream | الدفق الذي يُقرأ منه XML للاستيراد. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputXmlStream | Stream | دفق xml الإدخال. |
| IgnoreFormTemplateChanges | Boolean | إذا كان هذا المعامل صحيحًا، فلن يتم حفظ أي تغييرات في قالب نموذج XFA. |

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


