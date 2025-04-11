---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تحدد عدد المشط لحقول النص العادية ذات السطر الواحد، حيث يتم تقسيم الحقل تلقائيًا إلى عدد من المواقع المتساوية أو المشط كما هو محدد في قيمة معلمة combNumber
type: docs
weight: 300
url: /ar/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## طريقة FormEditor.SetFieldCombNumber

تحدد عدد المشط لحقول النص العادية ذات السطر الواحد (يتم تقسيم الحقل تلقائيًا إلى عدد من المواقع المتساوية، أو المشط، كما هو محدد في قيمة معلمة combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |
| combNumber | Int32 | عدد المشط لتقسيم الحقل إليه. |

### قيمة الإرجاع

إذا نجح، يرجع true؛ وإلا false.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)