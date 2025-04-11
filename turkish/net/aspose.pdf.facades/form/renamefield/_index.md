---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Bir alanın adını değiştirir. AcroForm alanı veya XFA alanı uygundur.
type: docs
weight: 330
url: /tr/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField metodu

Bir alanın adını değiştirir. AcroForm alanı veya XFA alanı uygundur.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | eski alan adı |
| newFieldName | String | yeni alan adı |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)