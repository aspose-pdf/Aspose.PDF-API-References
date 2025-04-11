---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Form yöntemi. Fdf dosyasındaki alanların içeriğini içe aktarır ve bunları yeni pdf'ye yerleştirir.
type: docs
weight: 280
url: /tr/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf yöntemi

Fdf dosyasındaki alanların içeriğini içe aktarır ve bunları yeni pdf'ye yerleştirir.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFdfStream | Stream | Girdi fdf akışı. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)