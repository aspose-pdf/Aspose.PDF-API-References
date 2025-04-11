---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Formdan alanı kaldır
type: docs
weight: 210
url: /tr/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField metodu

Formdan alanı kaldır.

```csharp
public void RemoveField(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Kaldırılması gereken alanın adı. |

## Örnekler

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)