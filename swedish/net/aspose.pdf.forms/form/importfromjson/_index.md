---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Importerar PDF-formulärfält från JSON-format som tillhandahålls i strömmen
type: docs
weight: 290
url: /sv/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Importerar PDF-formulärfält från JSON-format som tillhandahålls i strömmen.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att läsa JSON-inmatningen från. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av importoperationen för varje formulärfält.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### Se Även

* klass [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Importerar PDF-formulärfält från JSON-format som tillhandahålls i den angivna filen.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Namnet på filen att läsa JSON-inmatningen från. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av importoperationen för varje formulärfält.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### Se Även

* klass [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)