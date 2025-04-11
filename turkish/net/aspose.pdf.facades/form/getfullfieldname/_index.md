---
title: Form.GetFullFieldName
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Kısa alan adına göre tam alan adını alır
type: docs
weight: 250
url: /tr/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName metodu

Kısa alan adına göre tam alan adını alır.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Tam nitelikli alan adı. |

### Dönüş Değeri

Tam alan adı.

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)