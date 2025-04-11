---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Metin alanının maksimum karakter sayısını ayarlar
type: docs
weight: 310
url: /tr/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit metodu

Metin alanının maksimum karakter sayısını ayarlar.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Metin alanının adı. |
| fieldLimit | Int32 | Alan için yeni limit değeri. |

### Dönüş Değeri

Alan limiti başarıyla ayarlandıysa true döner.

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)