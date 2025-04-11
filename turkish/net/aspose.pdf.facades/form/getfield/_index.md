---
title: Form.GetField
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Alan adına göre alanın değerini alır
type: docs
weight: 200
url: /tr/net/aspose.pdf.facades/form/getfield/
---
## Form.GetField metodu

Alan adına göre alanın değerini alır.

```csharp
public string GetField(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Tam nitelikli alan adı. |

### Dönüş Değeri

Alanın değeri.

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Field value = " + form.GetField("Field1"));
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)