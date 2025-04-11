---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Tam nitelikli alan adına göre bir barkod alanını doldurun
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField metodu

Tam nitelikli alan adına göre bir barkod alanını doldurun.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Tam nitelikli alan adı. |
| data | String | Yeni barkod değeri. |

### Dönüş Değeri

Doldurma başarılı olursa, true döner; aksi takdirde, false.

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)