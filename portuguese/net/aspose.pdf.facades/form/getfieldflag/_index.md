---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Retorna as flags do campo
type: docs
weight: 220
url: /pt/net/aspose.pdf.facades/form/getfieldflag/
---
## Método Form.GetFieldFlag

Retorna as flags do campo.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo |

### Valor de Retorno

Flag da propriedade (ReadOnly/ Required/NoExport

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### Veja Também

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)