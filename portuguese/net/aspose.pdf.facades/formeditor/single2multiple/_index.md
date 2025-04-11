---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Muda um campo de texto de linha única para um de múltiplas linhas
type: docs
weight: 350
url: /pt/net/aspose.pdf.facades/formeditor/single2multiple/
---
## Método FormEditor.Single2Multiple

Muda um campo de texto de linha única para um de múltiplas linhas.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome qualificado do campo. |

### Valor de Retorno

Se for bem-sucedido, retorna verdadeiro; caso contrário, falso.

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)