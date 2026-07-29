---
title: "Form.ExportJson"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تصدر محتويات جميع الحقول في المستند إلى تدفق JSON. لا يتم تصدير قيم حقول الأزرار"
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

يصدّر محتويات جميع الحقول في المستند إلى تدفق JSON. لا يتم تصدير قيم حقول الأزرار.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputJsonStream | Stream | تدفق JSON الناتج حيث سيتم كتابة بيانات حقول المستند. |
| مُسْتَفَصِل | Boolean | اختياري. يحدد ما إذا كان يجب أن يكون إخراج JSON مُستفصل لتحسين القابلية للقراءة. القيمة الافتراضية هي true. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


