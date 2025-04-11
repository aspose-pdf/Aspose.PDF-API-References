---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Definir atributos do campo
type: docs
weight: 290
url: /pt/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## Método FormEditor.SetFieldAttribute

Definir atributos do campo.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fieldName | String | Nome do campo cujos atributos devem ser definidos. |
| flag | PropertyFlag | Flag (NoExport/ReadOnly/Required) |

### Valor de Retorno

true se o atributo foi definido com sucesso.

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Veja Também

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)