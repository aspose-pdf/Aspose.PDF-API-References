---
title: "Form.ImportFromJson"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form method. Importerar PDF-formulärfält från JSON-format som tillhandahålls i strömmen"
type: docs
weight: 310
url: /sv/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Importerar PDF-formulärfält från JSON-format som tillhandahålls i strömmen.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Strömmen att läsa JSON-indata från. |

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

### Se även

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Importerar PDF-formulärfält från JSON-format som tillhandahålls i den angivna filen.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| `fileName` | String | Namnet på filen att läsa JSON-indata från. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av importoperationen för varje formulärfält.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### Se även

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


