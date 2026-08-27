---
title: "Form.GetFieldFacade"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Restituisce l'oggetto FrofmFieldFacade contenente tutti gli attributi di aspetto"
type: docs
weight: 210
url: /it/net/aspose.pdf.facades/form/getfieldfacade/
---
## Form.GetFieldFacade method

Restituisce l'oggetto FrofmFieldFacade contenente tutti gli attributi di aspetto.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo da leggere. |

### Valore di ritorno

oggetto FormFieldFacade

### Vedi anche

* class [FormFieldFacade](../../formfieldfacade/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


