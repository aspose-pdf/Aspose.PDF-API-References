---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Form yöntemi. Metin kutusu alanlarını metin değerleri ile doldurur ve belgeyi kaydeder. İmzalı belgeler için geçerlidir. Not Sadece Metin Kutusuna uygulanır. Hem alanların adı hem de değerleri büyük/küçük harf duyarlıdır.
type: docs
weight: 140
url: /tr/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields yöntemi

Metin kutusu alanlarını metin değerleri ile doldurur ve belgeyi kaydeder. İmzalı belgeler için geçerlidir. Not: Sadece Metin Kutusuna uygulanır. Hem alanların adı hem de değerleri büyük/küçük harf duyarlıdır.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldNames | String[] | Alanların adları. |
| fieldValues | String[] | Alanların yeni değerleri. |
| output | Stream& | Belgenin kaydedileceği akış. |

### Dönüş Değeri

Alanlar bulunduysa ve başarıyla doldurulduysa true döner.

## Örnekler

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)