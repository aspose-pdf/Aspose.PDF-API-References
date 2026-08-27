---
title: "FormEditor.SetFieldCombNumber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تحدد عدد الفواصل (combs) لحقل نص أحادي السطر عادي؛ يتم تقسيم الحقل تلقائياً إلى عدد من المواقع المتساوية أو الفواصل حسب قيمة معامل combNumber."
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

يحدد عدد الأعمدة لحقل نص أحادي السطر عادي (يتم تقسيم الحقل تلقائيًا إلى عدد من المواقع المتساوية المسافة، أو الأعمدة، وفقًا لقيمة معامل combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |
| combNumber | Int32 | عدد الفواصل (combs) لتقسيم الحقل إليها. |

### قيمة الإرجاع

إذا نجح، إرجاع true؛ وإلا false.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


