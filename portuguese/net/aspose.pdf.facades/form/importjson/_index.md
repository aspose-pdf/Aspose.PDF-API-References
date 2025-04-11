---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Método do Form. Importa todos os dados dos campos de um fluxo JSON para os campos do documento, correspondendo os campos pelos seus nomes completos
type: docs
weight: 290
url: /pt/net/aspose.pdf.facades/form/importjson/
---
## Método Form.ImportJson

Importa todos os dados dos campos de um fluxo JSON para os campos do documento, correspondendo os campos pelos seus nomes completos.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputJsonStream | Stream | O fluxo JSON de entrada contendo os dados dos campos a serem importados para os campos do documento. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)