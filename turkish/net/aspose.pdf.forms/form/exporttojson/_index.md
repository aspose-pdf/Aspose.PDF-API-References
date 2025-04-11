---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Form yöntemi. PDF form alanlarını JSON formatına aktarır ve sonucu sağlanan akışa yazar
type: docs
weight: 240
url: /tr/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

PDF form alanlarını JSON formatına aktarır ve sonucu sağlanan akışa yazar.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | JSON çıktısını yazmak için kullanılan akış. |
| options | ExportFieldsToJsonOptions | Form alanlarını JSON'a aktarmak için isteğe bağlı ayarlar. |

### Dönüş Değeri

Her form alanı için aktarım işleminin sonucunu belirten bir [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) koleksiyonu.

## Örnekler

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Ayrıca Bakınız

* sınıf [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* sınıf [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

PDF form alanlarını JSON formatına aktarır ve sonucu belirtilen dosyaya yazar.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | JSON çıktısını yazmak için kullanılan dosyanın adı. |
| options | ExportFieldsToJsonOptions | Form alanlarını JSON'a aktarmak için isteğe bağlı ayarlar. |

### Dönüş Değeri

Her form alanı için aktarım işleminin sonucunu belirten bir [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) koleksiyonu.

## Örnekler

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Ayrıca Bakınız

* sınıf [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* sınıf [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)