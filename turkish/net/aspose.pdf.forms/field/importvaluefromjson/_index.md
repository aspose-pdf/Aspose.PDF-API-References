---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Alan yöntemi. Alanların tam adlarının tam eşleşmesine dayalı olarak bir JSON akışından belirtilen alanlara veri aktarır.
type: docs
weight: 210
url: /tr/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Belirtilen alanlara, alanların tam adlarının tam eşleşmesine dayalı olarak bir JSON akışından veri aktarır.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputJsonStream | Stream | Alana aktarılacak alan verilerini içeren giriş JSON akışı. |

### Dönüş Değeri

JSON akışında alan bulunduysa doğru; aksi takdirde - yanlış

## Örnekler

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### Ayrıca Bakınız

* sınıf [Field](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Belirtilen alana, eşleşme için 'fieldFullNameInJSON' değişkeninde belirtilen tam adı kullanarak bir JSON akışından veri aktarır.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputJsonStream | Stream | Alana aktarılacak alan verilerini içeren giriş JSON akışı. |
| fieldFullNameInJSON | String | Eşleşme için JSON akışındaki verinin adı. JSON akışındaki verinin iç içe bir yapısı varsa, tam ad tüm üst ve alt öğeler '.' ile ayrılarak belirtilmelidir. |

### Dönüş Değeri

JSON dosyasında alan bulunduysa doğru; aksi takdirde - yanlış

## Örnekler

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### Ayrıca Bakınız

* sınıf [Field](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)