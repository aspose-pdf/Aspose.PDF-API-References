---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: Método do Form. Achata um campo especificado com o nome de campo totalmente qualificado. Qualquer outro campo permanecerá inalterado. Se o fieldName for inválido, todos os campos permanecerão inalterados.
type: docs
weight: 170
url: /pt/net/aspose.pdf.facades/form/flattenfield/
---
## Método Form.FlattenField

Achata um campo especificado com o nome de campo totalmente qualificado. Qualquer outro campo permanecerá inalterado. Se o fieldName for inválido, todos os campos permanecerão inalterados.

```csharp
public void FlattenField(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome do campo a ser achatado. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)