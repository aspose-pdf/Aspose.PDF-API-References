---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Alanın gönderim eylemini kaldır
type: docs
weight: 220
url: /tr/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction metodu

Alanın gönderim eylemini kaldır.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Alanın adı. |

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)