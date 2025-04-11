---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Define o estilo de alinhamento de um campo de texto
type: docs
weight: 260
url: /pt/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## Método FormEditor.SetFieldAlignment

Define o estilo de alinhamento de um campo de texto.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome qualificado do campo. |
| alignment | Int32 | A definição do estilo de alinhamento, incluindo FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter e FormFieldFacade.AlignRight. |

### Valor de Retorno

true se o campo foi encontrado e o alinhamento foi definido.

## Exemplos

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)