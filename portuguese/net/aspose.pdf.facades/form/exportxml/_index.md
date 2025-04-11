---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Método do Form. Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor dos campos de botão não será exportado
type: docs
weight: 100
url: /pt/net/aspose.pdf.facades/form/exportxml/
---
## Método Form.ExportXml

Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor do campo de botão não será exportado.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputXmlStream | Stream | Fluxo Xml de saída. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)