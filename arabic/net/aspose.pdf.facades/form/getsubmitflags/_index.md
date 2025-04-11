---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تعيد علامات تقديم أزرار الإرسال
type: docs
weight: 270
url: /ar/net/aspose.pdf.facades/form/getsubmitflags/
---
## طريقة Form.GetSubmitFlags

تعيد علامات تقديم زر الإرسال

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم الحقل المؤهل. |

### قيمة الإرجاع

علامات تقديم الزر.

## أمثلة

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### انظر أيضًا

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)