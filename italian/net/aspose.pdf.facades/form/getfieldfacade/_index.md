---
title: GetFieldFacade
second_title: Aspose.PDF per .NET API Reference
description: Restituisce loggetto FrofmFieldFacade contenente tutti gli attributi di aspetto.
type: docs
weight: 240
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

Oggetto FormFieldFacade

### Guarda anche

* class [FormFieldFacade](../../formfieldfacade)
* class [Form](../../form)
* spazio dei nomi [Aspose.Pdf.Facades](../../form)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
