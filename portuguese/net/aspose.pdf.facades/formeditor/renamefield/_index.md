---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Mudar o nome do campo
type: docs
weight: 230
url: /pt/net/aspose.pdf.facades/formeditor/renamefield/
---
## Método FormEditor.RenameField

Mudar o nome do campo.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome antigo do campo. |
| newFieldName | String | Novo nome do campo. |

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)