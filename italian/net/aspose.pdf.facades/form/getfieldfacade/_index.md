---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Restituisce un oggetto FrofmFieldFacade contenente tutti gli attributi di aspetto
type: docs
weight: 210
url: /it/net/aspose.pdf.facades/form/getfieldfacade/
---
## Metodo Form.GetFieldFacade

Restituisce un oggetto FrofmFieldFacade contenente tutti gli attributi di aspetto.

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

Oggetto FormFieldFacade

### Vedi anche

* classe [FormFieldFacade](../../formfieldfacade/)
* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)