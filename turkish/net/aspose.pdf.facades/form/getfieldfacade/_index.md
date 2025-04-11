---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Tüm görünüm özelliklerini içeren FrofmFieldFacade nesnesini döndürür
type: docs
weight: 210
url: /tr/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade metodu

Tüm görünüm özelliklerini içeren FrofmFieldFacade nesnesini döndürür.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Okunacak alanın adı. |

### Dönüş Değeri

FormFieldFacade nesnesi

### Ayrıca Bakınız

* sınıf [FormFieldFacade](../../formfieldfacade/)
* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)