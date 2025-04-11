---
title: Form.GetButtonOptionValues
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Alan adına dayalı olarak radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. Bu metod, radyo düğmesi grupları için anlam taşır.
type: docs
weight: 190
url: /tr/net/aspose.pdf.facades/form/getbuttonoptionvalues/
---
## Form.GetButtonOptionValues metodu

Alan adına dayalı olarak radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. Bu metod, radyo düğmesi grupları için anlam taşır.

```csharp
public Dictionary<string, string> GetButtonOptionValues(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Alan Adı |

### Dönüş Değeri

Form öğesi adıyla anahtarlanan seçenek değerlerinin hash tablosu

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
Hashtable values = form.GetButtonOptionValues("Color");
Console.WriteLine(values["White"].ToString());
Console.WriteLine(values["Black"].ToString());
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)