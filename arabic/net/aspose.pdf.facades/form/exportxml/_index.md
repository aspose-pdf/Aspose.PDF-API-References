---
title: "Form.ExportXml"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تصدر محتوى حقول الـ pdf إلى تدفق xml. لن يتم تصدير قيمة حقول الأزرار"
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml method

يصدّر محتوى حقول الـ pdf إلى تدفق XML. لن يتم تصدير قيمة حقل الزر.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| معامل | النوع | الوصف |
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


