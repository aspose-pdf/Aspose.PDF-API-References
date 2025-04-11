---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Form yöntemi. Akışta sağlanan JSON formatındaki PDF form alanlarını içe aktarır
type: docs
weight: 290
url: /tr/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Akışta sağlanan JSON formatındaki PDF form alanlarını içe aktarır.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | JSON girdi verilerini okumak için akış. |

### Dönüş Değeri

Her form alanı için içe aktarma işleminin sonucunu belirten bir [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) koleksiyonu.

## Örnekler

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### Ayrıca Bakınız

* sınıf [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Belirtilen dosyada sağlanan JSON formatındaki PDF form alanlarını içe aktarır.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | JSON girdi verilerini okumak için dosya adı. |

### Dönüş Değeri

Her form alanı için içe aktarma işleminin sonucunu belirten bir [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) koleksiyonu.

## Örnekler

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### Ayrıca Bakınız

* sınıf [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)