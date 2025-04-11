---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Imposta gli attributi del campo
type: docs
weight: 290
url: /it/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## Metodo FormEditor.SetFieldAttribute

Imposta gli attributi del campo.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo di cui devono essere impostati gli attributi. |
| flag | PropertyFlag | Flag (NoExport/ReadOnly/Required) |

### Valore di ritorno

true se l'attributo è stato impostato con successo.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Vedi anche

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)