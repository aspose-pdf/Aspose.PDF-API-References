---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Butonun URL'sini ayarlar
type: docs
weight: 340
url: /tr/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl metodu

Butonun URL'sini ayarlar.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Gönder butonu adı. |
| url | String | Tam nitelikli URL. |

### Dönüş Değeri

Buton için URL başarıyla ayarlandıysa true döner.

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)