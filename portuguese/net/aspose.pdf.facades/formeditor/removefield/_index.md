---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Remove campo do formulário
type: docs
weight: 210
url: /pt/net/aspose.pdf.facades/formeditor/removefield/
---
## Método FormEditor.RemoveField

Remove campo do formulário.

```csharp
public void RemoveField(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo que deve ser removido. |

## Exemplos

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)