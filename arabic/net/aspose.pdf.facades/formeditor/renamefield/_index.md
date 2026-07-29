---
title: "FormEditor.RenameField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تغيير اسم الحقل"
type: docs
weight: 230
url: /ar/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

غيّر اسم الحقل.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | الاسم القديم للحقل. |
| newFieldName | String | الاسم الجديد للحقل. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


