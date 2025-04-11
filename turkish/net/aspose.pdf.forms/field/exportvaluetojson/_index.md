---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: Field metodu. Belirtilen alanın içeriğini bir JSON akışına aktarır. Buton alanı değerleri aktarılmaz
type: docs
weight: 180
url: /tr/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson metodu

Belirtilen alanın içeriğini bir JSON akışına aktarır. Buton alanı değerleri aktarılmaz.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputJsonStream | Stream | Alan verilerinin yazılacağı çıkış JSON akışı. |
| indented | Boolean | İsteğe bağlı. JSON çıktısının daha iyi okunabilirlik için girintili olup olmayacağını belirtir. Varsayılan değer doğrudur. |

## Örnekler

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Ayrıca Bakınız

* sınıf [Field](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)