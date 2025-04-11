---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengganti nama sebuah field. Baik field AcroForm atau field XFA diperbolehkan
type: docs
weight: 330
url: /id/net/aspose.pdf.facades/form/renamefield/
---
## Metode Form.RenameField

Mengganti nama sebuah field. Baik field AcroForm atau field XFA diperbolehkan.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | nama field lama |
| newFieldName | String | nama field baru |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)