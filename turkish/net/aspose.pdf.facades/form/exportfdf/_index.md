---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Pdf alanlarının içeriğini fdf akışına aktarır
type: docs
weight: 70
url: /tr/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf metodu

Pdf alanlarının içeriğini fdf akışına aktarır.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFdfStream | Stream | Çıktı fdf akışı. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)