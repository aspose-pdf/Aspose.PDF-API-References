---
title: SetSubmitUrl
second_title: Aspose.PDF for .NET API Referansı
description: Düğmenin URLsini ayarlar.
type: docs
weight: 380
url: /tr/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

Düğmenin URL'sini ayarlar.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Düğme adını gönder. |
| url | String | Tam nitelikli URL. |

### Geri dönüş değeri

düğmenin URL'si başarıyla ayarlanmışsa true .

### Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Ayrıca bakınız

* class [FormEditor](../../formeditor)
* ad alanı [Aspose.Pdf.Facades](../../formeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
