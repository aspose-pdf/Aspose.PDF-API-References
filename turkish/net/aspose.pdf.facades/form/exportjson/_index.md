---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Form yöntemi. Belgedeki tüm alanların içeriğini bir JSON akışına aktarır. Buton alan değerleri aktarılmaz
type: docs
weight: 80
url: /tr/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson yöntemi

Belgedeki tüm alanların içeriğini bir JSON akışına aktarır. Buton alan değerleri aktarılmaz.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputJsonStream | Stream | Belgenin alan verilerinin yazılacağı çıkış JSON akışı. |
| indented | Boolean | Opsiyonel. JSON çıktısının daha iyi okunabilirlik için girintili olup olmayacağını belirtir. Varsayılan değer doğrudur. |

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)