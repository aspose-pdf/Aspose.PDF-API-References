---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Pdf'nin alanlarının içeriğini xml akışına aktarır. Buton alanlarının değeri aktarılmayacaktır.
type: docs
weight: 100
url: /tr/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml metodu

Pdf'nin alanlarının içeriğini xml akışına aktarır. Buton alanının değeri aktarılmayacaktır.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputXmlStream | Stream | Çıktı Xml akışı. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)