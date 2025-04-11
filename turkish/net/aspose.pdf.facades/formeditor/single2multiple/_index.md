---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Tek satırlık bir metin alanını çok satırlı bir alana dönüştür
type: docs
weight: 350
url: /tr/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple metodu

Tek satırlık bir metin alanını çok satırlı bir alana dönüştür.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Nitelikli alan adı. |

### Dönüş Değeri

Başarılıysa, true döner; aksi takdirde false.

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)