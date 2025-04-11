---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Metodo WidgetAnnotation. Esporta il campo modulo PDF specificato in formato JSON e scrive il risultato nello stream fornito
type: docs
weight: 120
url: /it/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Esporta il campo modulo PDF specificato in formato JSON e scrive il risultato nello stream fornito.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream su cui scrivere l'output JSON. |
| options | ExportFieldsToJsonOptions | Impostazioni opzionali per esportare il campo modulo in JSON. |

### Valore di Ritorno

Una collezione di [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) che indica il risultato dell'operazione di esportazione per il campo modulo specificato e i suoi elementi figli, se presenti.

## Esempi

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### Vedi Anche

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Esporta il campo modulo PDF specificato in formato JSON e scrive il risultato nel file specificato.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Il nome del file su cui scrivere l'output JSON. |
| options | ExportFieldsToJsonOptions | Impostazioni opzionali per esportare il campo modulo in JSON. |

### Valore di Ritorno

Una collezione di [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) che indica il risultato dell'operazione di esportazione per il campo modulo specificato e i suoi elementi figli, se presenti.

## Esempi

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### Vedi Anche

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)