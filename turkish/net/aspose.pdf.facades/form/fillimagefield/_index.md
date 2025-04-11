---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Mevcut buton alanına, tam nitelikli alan adıyla görünümü olarak bir resim yapıştırır.
type: docs
weight: 150
url: /tr/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Mevcut buton alanına, tam nitelikli alan adıyla görünümü olarak bir resim yapıştırır.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Resim buton alanının tam nitelikli alan adı. |
| imageFileName | String | Resim dosyasının yolu, hem göreceli hem de mutlak geçerlidir. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

FillImageField fonksiyonunun aşırı yüklenmesi. Girdi bir resim akışıdır.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Tam nitelikli alan adı. |
| imageStream | Stream | Resmin akışı. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)