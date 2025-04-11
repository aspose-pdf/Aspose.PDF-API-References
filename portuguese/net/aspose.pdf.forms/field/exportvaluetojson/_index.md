---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: Método do campo. Exporta o conteúdo do campo especificado para um fluxo JSON. Os valores do campo de botão não são exportados
type: docs
weight: 180
url: /pt/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Método Field.ExportValueToJson

Exporta o conteúdo do campo especificado para um fluxo JSON. Os valores do campo de botão não são exportados.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputJsonStream | Stream | O fluxo JSON de saída onde os dados do campo serão escritos. |
| indented | Boolean | Opcional. Especifica se a saída JSON deve ser indentada para melhor legibilidade. O valor padrão é true. |

## Exemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Veja Também

* classe [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)