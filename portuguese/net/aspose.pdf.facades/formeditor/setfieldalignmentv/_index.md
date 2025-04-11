---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Define o estilo de alinhamento vertical de um campo de texto
type: docs
weight: 270
url: /pt/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## Método FormEditor.SetFieldAlignmentV

Define o estilo de alinhamento vertical de um campo de texto.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome qualificado do campo. |
| alignment | Int32 | A definição do estilo de alinhamento, incluindo FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle e FormFieldFacade.AlignRight. |

### Valor de Retorno

true se o campo foi encontrado e o alinhamento foi preenchido com sucesso.

## Exemplos

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)