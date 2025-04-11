---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Metodo del form. Esporta i campi del form PDF in formato JSON e scrive il risultato nel flusso fornito.
type: docs
weight: 240
url: /it/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Esporta i campi del modulo PDF in formato JSON e scrive il risultato nello stream fornito.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Lo stream su cui scrivere l'output JSON. |
| options | ExportFieldsToJsonOptions | Impostazioni opzionali per esportare i campi del modulo in JSON. |

### Return Value

Una collezione di [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) che indica il risultato dell'operazione di esportazione per ciascun campo del modulo.

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Il nome del file su cui scrivere l'output JSON. |
| options | ExportFieldsToJsonOptions | Impostazioni opzionali per esportare i campi del modulo in JSON. |

### Return Value

Una collezione di [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) che indica il risultato dell'operazione di esportazione per ciascun campo del modulo.

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### See Also

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)