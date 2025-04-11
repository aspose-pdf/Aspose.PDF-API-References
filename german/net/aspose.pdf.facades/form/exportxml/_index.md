---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Exportiert den Inhalt der Felder des PDFs in den XML-Stream. Der Wert der Schaltflächenfelder wird nicht exportiert.
type: docs
weight: 100
url: /de/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml-Methode

Exportiert den Inhalt der Felder des PDFs in den XML-Stream. Der Wert des Schaltflächenfeldes wird nicht exportiert.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputXmlStream | Stream | Ausgabestream für XML. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)