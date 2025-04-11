---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Esporta il contenuto dei campi del pdf nello stream xml. Il valore dei campi pulsante non sarà esportato
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/form/exportxml/
---
## Metodo Form.ExportXml

Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo pulsante non sarà esportato.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputXmlStream | Stream | Stream Xml di output. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)