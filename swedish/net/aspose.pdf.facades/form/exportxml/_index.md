---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Formulärmetod. Exporterar innehållet i fälten i pdfen till xml-strömmen. Värdet av knappfälten kommer inte att exporteras
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml metod

Exporterar innehållet i fälten i pdf:en till xml-strömmen. Värdet av knappfältet kommer inte att exporteras.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputXmlStream | Stream | Utdata Xml-ström. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)