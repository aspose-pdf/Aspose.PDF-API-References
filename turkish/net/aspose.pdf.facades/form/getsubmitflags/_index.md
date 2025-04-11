---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Gönderim düğmelerinin gönderim bayraklarını döndürür
type: docs
weight: 270
url: /tr/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags metodu

Gönderim düğmesinin gönderim bayraklarını döndürür

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Nitelikli alan adı. |

### Dönüş Değeri

Düğmenin gönderim bayrakları.

## Örnekler

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Ayrıca Bakınız

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)