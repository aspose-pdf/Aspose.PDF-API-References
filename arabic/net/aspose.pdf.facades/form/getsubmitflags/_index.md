---
title: "Form.GetSubmitFlags"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تُعيد أعلام إرسال أزرار الإرسال"
type: docs
weight: 270
url: /ar/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags method

يعيد أعلام الإرسال لزر الإرسال

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل. |

### قيمة الإرجاع

أعلام الإرسال للزر.

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


