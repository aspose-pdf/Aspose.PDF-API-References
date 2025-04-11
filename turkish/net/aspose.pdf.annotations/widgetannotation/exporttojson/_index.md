---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: WidgetAnnotation metodu. Belirtilen PDF form alanını JSON formatına aktarır ve sonucu sağlanan akışa yazar
type: docs
weight: 120
url: /tr/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Belirtilen PDF form alanını JSON formatına aktarır ve sonucu sağlanan akışa yazar.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | JSON çıktısını yazmak için kullanılan akış. |
| options | ExportFieldsToJsonOptions | Form alanını JSON'a aktarmak için isteğe bağlı ayarlar. |

### Dönüş Değeri

Belirtilen form alanı ve varsa alt öğeleri için aktarım işleminin sonucunu belirten bir [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) koleksiyonu.

## Örnekler

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### Ayrıca Bakınız

* sınıf [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* sınıf [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* sınıf [WidgetAnnotation](../)
* ad alanı [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Belirtilen PDF form alanını JSON formatına aktarır ve sonucu belirtilen dosyaya yazar.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | String | JSON çıktısını yazmak için kullanılan dosyanın adı. |
| options | ExportFieldsToJsonOptions | Form alanını JSON'a aktarmak için isteğe bağlı ayarlar. |

### Dönüş Değeri

Belirtilen form alanı ve varsa alt öğeleri için aktarım işleminin sonucunu belirten bir [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) koleksiyonu.

## Örnekler

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### Ayrıca Bakınız

* sınıf [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* sınıf [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* sınıf [WidgetAnnotation](../)
* ad alanı [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../../)