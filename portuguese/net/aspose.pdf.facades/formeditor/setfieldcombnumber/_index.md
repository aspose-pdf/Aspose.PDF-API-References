---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Define o número de divisões para um campo de texto simples regular, o campo é automaticamente dividido em tantas posições ou divisões igualmente espaçadas quanto o valor do parâmetro combNumber
type: docs
weight: 300
url: /pt/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## Método FormEditor.SetFieldCombNumber

Define o número de divisões para um campo de texto de linha única regular (o campo é automaticamente dividido em tantas posições igualmente espaçadas, ou divisões, quanto o valor do parâmetro combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome qualificado do campo. |
| combNumber | Int32 | O número de divisões para dividir o campo. |

### Valor de Retorno

Se for bem-sucedido, retorna true; caso contrário, false.

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)