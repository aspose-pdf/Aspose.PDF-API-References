---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Método do formulário. Preencha um campo de código de barras de acordo com seu nome de campo totalmente qualificado
type: docs
weight: 120
url: /pt/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Método Form.FillBarcodeField

Preencha um campo de código de barras de acordo com seu nome de campo totalmente qualificado.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | O nome de campo totalmente qualificado. |
| data | String | O novo valor do código de barras. |

### Valor de Retorno

Se o preenchimento for bem-sucedido, retorna verdadeiro; caso contrário, falso.

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)