---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Importa i campi del form PDF dal formato JSON forniti nel flusso.
type: docs
weight: 290
url: /it/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Importa i campi del modulo PDF dal formato JSON fornito nello stream.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream da cui leggere l'input JSON. |

### Valore di Ritorno

Una collezione di [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) che indica il risultato dell'operazione di importazione per ciascun campo del modulo.

## Esempi

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### Vedi Anche

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Importa i campi del modulo PDF dal formato JSON fornito nel file specificato.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Il nome del file da cui leggere l'input JSON. |

### Valore di Ritorno

Una collezione di [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) che indica il risultato dell'operazione di importazione per ciascun campo del modulo.

## Esempi

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### Vedi Anche

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)