---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Alanın yeni konumunu ayarlayın
type: docs
weight: 200
url: /tr/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField metodu

Alanının yeni konumunu ayarlayın.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Taşınması gereken alanın adı. |
| llx | Single | Alanın sol alt köşesinin abscissası. |
| lly | Single | Alanın sol alt köşesinin ordinatı. |
| urx | Single | Alanın sağ üst köşesinin abscissası. |
| ury | Single | Alanın sağ üst köşesinin ordinatı. |

### Dönüş Değeri

Alan konumu başarıyla değiştirildiyse true döner.

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)