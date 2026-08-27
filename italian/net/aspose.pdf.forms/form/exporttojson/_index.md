---
title: "Form.ExportToJson"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Esporta i campi del modulo PDF in formato JSON e scrive il risultato nello stream fornito"
type: docs
weight: 260
url: /it/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Esporta i campi del modulo PDF in formato JSON e scrive il risultato nello stream fornito.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream su cui scrivere l'output JSON. |
| options | ExportFieldsToJsonOptions | Impostazioni opzionali per l'esportazione dei campi del modulo in JSON. |

### Valore di ritorno

Una raccolta di [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) che indica il risultato dell'operazione di esportazione per ciascun campo del modulo.

## Esempi

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Vedi anche

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Esporta i campi del modulo PDF in formato JSON e scrive il risultato nel file specificato.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Il nome del file in cui scrivere l'output JSON. |
| options | ExportFieldsToJsonOptions | Impostazioni opzionali per l'esportazione dei campi del modulo in JSON. |

### Valore di ritorno

Una raccolta di [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) che indica il risultato dell'operazione di esportazione per ciascun campo del modulo.

## Esempi

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Vedi anche

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


