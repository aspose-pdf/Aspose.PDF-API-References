---
title: "Form.ExportXml"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Esporta il contenuto dei campi del pdf nello stream xml. Il valore dei campi pulsante non verrà esportato"
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml method

Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo pulsante non verrà esportato.

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

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


