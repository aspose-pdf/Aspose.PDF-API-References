---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Pdf'nin alanlarının içeriğini xml akışına aktarır. Buton alanlarının değeri aktarılmayacaktır.
type: docs
weight: 90
url: /tr/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf metodu

Pdf'nin alanlarının içeriğini xml akışına aktarır. Buton alanının değeri aktarılmayacaktır.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputXfdfStream | Akış | Çıktı xml akışı. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)