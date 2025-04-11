---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Retorna o objeto FrofmFieldFacade contendo todos os atributos de aparência
type: docs
weight: 210
url: /pt/net/aspose.pdf.facades/form/getfieldfacade/
---
## Método Form.GetFieldFacade

Retorna o objeto FrofmFieldFacade contendo todos os atributos de aparência.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo a ser lido. |

### Valor de Retorno

Objeto FormFieldFacade

### Veja Também

* classe [FormFieldFacade](../../formfieldfacade/)
* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)