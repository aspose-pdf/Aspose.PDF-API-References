---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Define o número máximo de caracteres do campo de texto
type: docs
weight: 310
url: /pt/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## Método FormEditor.SetFieldLimit

Define o número máximo de caracteres do campo de texto.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo de texto. |
| fieldLimit | Int32 | Novo valor de limite para o campo. |

### Valor de Retorno

true se o limite do campo foi definido com sucesso.

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)