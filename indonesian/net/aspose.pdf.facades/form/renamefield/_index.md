---
title: "Form.RenameField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengganti nama sebuah bidang. Baik bidang AcroForm maupun XFA diperbolehkan."
type: docs
weight: 330
url: /id/net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

Mengganti nama sebuah bidang. Baik bidang AcroForm maupun XFA diperbolehkan.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | nama bidang lama |
| newFieldName | String | nama bidang baru |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


