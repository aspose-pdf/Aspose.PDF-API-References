---
title: "Field.ExportValueToJson"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Field. Esporta il contenuto del campo specificato in un flusso JSON. I valori dei campi pulsante non vengono esportati"
type: docs
weight: 180
url: /it/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson method

Esporta il contenuto del campo specificato in uno stream JSON. I valori dei campi pulsante non sono esportati.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputJsonStream | Stream | Il flusso JSON di output in cui verranno scritti i dati del campo. |
| indentato | Boolean | Opzionale. Specifica se l'output JSON deve essere indentato per una migliore leggibilità. Il valore predefinito è true. |

## Esempi

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Vedi anche

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


