---
title: Form.ImportXml
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تستورد محتوى الحقول من ملف xml وتضعها في ملف pdf الجديد
type: docs
weight: 310
url: /ar/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

تستورد محتوى الحقول من ملف xml وتضعها في ملف pdf الجديد.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | Stream | التدفق الذي يتم قراءة XML منه للاستيراد. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

تستورد محتوى الحقول من ملف xml وتضعها في ملف pdf الجديد.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | Stream | تدفق xml المدخل. |
| IgnoreFormTemplateChanges | Boolean | إذا كانت هذه المعلمة صحيحة، فلن يتم حفظ أي تغييرات في قالب نموذج XFA |

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)