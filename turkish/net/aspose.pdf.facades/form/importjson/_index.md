---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Form yöntemi. Tüm alan verilerini bir JSON akışından, alanları tam adlarıyla eşleştirerek belge alanlarına aktarır.
type: docs
weight: 290
url: /tr/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson yöntemi

Tüm alan verilerini bir JSON akışından belge alanlarına aktarır, alanları tam adlarıyla eşleştirir.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputJsonStream | Stream | Belge alanlarına aktarılacak alan verilerini içeren giriş JSON akışı. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)