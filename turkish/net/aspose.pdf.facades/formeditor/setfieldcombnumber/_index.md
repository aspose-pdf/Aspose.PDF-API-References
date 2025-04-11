---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Bir normal tek satırlık metin alanı için tarama sayısını ayarlar, alan otomatik olarak combNumber parametresinin değeri kadar eşit aralıklı pozisyona veya taramaya bölünür.
type: docs
weight: 300
url: /tr/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber metodu

Bir normal tek satırlık metin alanı için tarama sayısını ayarlar (alan otomatik olarak combNumber parametresinin değeri kadar eşit aralıklı pozisyona veya taramaya bölünür).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Nitelikli alan adı. |
| combNumber | Int32 | Alanı bölmek için tarama sayısı. |

### Dönüş Değeri

Başarılıysa, true döner; aksi takdirde false.

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)