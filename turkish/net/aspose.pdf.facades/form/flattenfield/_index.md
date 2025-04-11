---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Belirtilen alanı tam nitelikli alan adı ile düzleştirir. Diğer tüm alanlar değişmez kalacaktır. Eğer fieldName geçersizse, tüm alanlar değişmez kalacaktır.
type: docs
weight: 170
url: /tr/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField metodu

Belirtilen alanı tam nitelikli alan adı ile düzleştirir. Diğer tüm alanlar değişmez kalacaktır. Eğer fieldName geçersizse, tüm alanlar değişmez kalacaktır.

```csharp
public void FlattenField(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Düzleştirilecek alanın adı. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)