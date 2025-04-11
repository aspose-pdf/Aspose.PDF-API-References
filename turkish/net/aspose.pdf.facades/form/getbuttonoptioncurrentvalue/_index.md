---
title: Form.GetButtonOptionCurrentValue
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Radyo düğmesi seçenek alanları için mevcut değeri döndürür
type: docs
weight: 180
url: /tr/net/aspose.pdf.facades/form/getbuttonoptioncurrentvalue/
---
## Form.GetButtonOptionCurrentValue metodu

Radyo düğmesi seçenek alanları için mevcut değeri döndürür.

```csharp
public string GetButtonOptionCurrentValue(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Alan Adı |

### Dönüş Değeri

Mevcut radyo grubu seçeneği için String değeri. Ayrıca [`GetButtonOptionValues`](../getbuttonoptionvalues/) bakınız.

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetButtonOptionCurrentValue("btnField"));
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)