---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Método do Formulário. Renomeia um campo. Tanto o campo AcroForm quanto o campo XFA são aceitos.
type: docs
weight: 330
url: /pt/net/aspose.pdf.facades/form/renamefield/
---
## Método Form.RenameField

Renomeia um campo. Tanto o campo AcroForm quanto o campo XFA são aceitos.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | o nome antigo do campo |
| newFieldName | String | o novo nome do campo |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)