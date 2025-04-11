---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Exporta o conteúdo de todos os campos no documento para um fluxo JSON. Os valores dos campos de botão não são exportados
type: docs
weight: 80
url: /pt/net/aspose.pdf.facades/form/exportjson/
---
## Método Form.ExportJson

Exporta o conteúdo de todos os campos no documento para um fluxo JSON. Os valores dos campos de botão não são exportados.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputJsonStream | Stream | O fluxo JSON de saída onde os dados dos campos do documento serão escritos. |
| indented | Boolean | Opcional. Especifica se a saída JSON deve ser indentada para melhor legibilidade. O valor padrão é true. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)