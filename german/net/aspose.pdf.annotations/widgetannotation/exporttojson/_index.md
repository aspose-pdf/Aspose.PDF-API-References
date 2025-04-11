---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: WidgetAnnotation-Methode. Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream
type: docs
weight: 120
url: /de/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in den die JSON-Ausgabe geschrieben wird. |
| options | ExportFieldsToJsonOptions | Optionale Einstellungen für den Export des Formularfelds in JSON. |

### Rückgabewert

Eine Sammlung von [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), die das Ergebnis der Exportoperation für das angegebene Formularfeld und seine untergeordneten Elemente, falls vorhanden, angibt.

## Beispiele

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### Siehe auch

* Klasse [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* Klasse [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* Klasse [WidgetAnnotation](../)
* Namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exportiert das angegebene PDF-Formularfeld in das JSON-Format und schreibt das Ergebnis in die angegebene Datei.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Name der Datei, in die die JSON-Ausgabe geschrieben wird. |
| options | ExportFieldsToJsonOptions | Optionale Einstellungen für den Export des Formularfelds in JSON. |

### Rückgabewert

Eine Sammlung von [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/), die das Ergebnis der Exportoperation für das angegebene Formularfeld und seine untergeordneten Elemente, falls vorhanden, angibt.

## Beispiele

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### Siehe auch

* Klasse [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* Klasse [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* Klasse [WidgetAnnotation](../)
* Namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../../)