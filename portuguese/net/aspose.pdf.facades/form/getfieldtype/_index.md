---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Retorna o tipo de campo
type: docs
weight: 240
url: /pt/net/aspose.pdf.facades/form/getfieldtype/
---
## Método Form.GetFieldType

Retorna o tipo de campo.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo. |

### Valor de Retorno

Elemento da enumeração FileType correspondente ao tipo de campo.

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### Veja Também

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)