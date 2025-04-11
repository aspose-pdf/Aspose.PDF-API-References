---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Alanın adını değiştir
type: docs
weight: 230
url: /tr/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField metodu

Alanın adını değiştir.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Alanın eski adı. |
| newFieldName | String | Alanın yeni adı. |

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Ayrıca Bakınız

* sınıf [FormEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)