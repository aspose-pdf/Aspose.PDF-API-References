---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تصدر محتوى حقول pdf إلى تدفق xml. لن يتم تصدير قيمة حقول الأزرار
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/form/exportxml/
---
## طريقة Form.ExportXml

تصدر محتوى حقول pdf إلى تدفق xml. لن يتم تصدير قيمة حقل الزر.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputXmlStream | Stream | تدفق Xml الناتج. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)