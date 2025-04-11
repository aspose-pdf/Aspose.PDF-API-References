---
title: Form.GetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Metin alanının sınırlamasını al
type: docs
weight: 230
url: /tr/net/aspose.pdf.facades/form/getfieldlimit/
---
## Form.GetFieldLimit metodu

Metin alanının sınırlamasını al.

```csharp
public int GetFieldLimit(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Nitelikli alan adı. |

### Dönüş Değeri

Bir metin alanının doldurulabileceği karakter sayısının sınırlama numarasını döndürür. Ayarlanmamışsa, 0 döndürür.

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetFieldLimit("textfieldBox"));
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)