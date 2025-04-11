---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Form yöntemi. xfdfxml dosyasındaki alanların içeriğini içe aktarır ve bunları yeni pdf'ye yerleştirir
type: docs
weight: 300
url: /tr/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf yöntemi

xfdf(xml) dosyasındaki alanların içeriğini içe aktarır ve bunları yeni pdf'ye yerleştirir.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputXfdfStream | Stream | Girdi xfdf(xml) akışı. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)