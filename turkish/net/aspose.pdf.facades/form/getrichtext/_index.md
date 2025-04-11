---
title: Form.GetRichText
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Her karakterin biçimlendirme bilgilerini içeren bir Zengin Metin alanının değerini alın
type: docs
weight: 260
url: /tr/net/aspose.pdf.facades/form/getrichtext/
---
## Form.GetRichText metodu

Bir Zengin Metin alanının değerini alın, her karakterin biçimlendirme bilgilerini de dahil edin.

```csharp
public string GetRichText(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Zengin Metin alanının tam nitelikli alan adı. |

### Dönüş Değeri

Zengin Metin alanının biçimlendirme bilgilerini içeren bir dize döndürün.

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine(form.GetRichText("txtDescriptionRTF"));
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)