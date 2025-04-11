---
title: FormEditor.ExportItems
second_title: Aspose.PDF for .NET API Reference
description: Propriedade FormEditor. Define opções para a caixa de combinação com valores de exportação
type: docs
weight: 30
url: /pt/net/aspose.pdf.facades/formeditor/exportitems/
---
## Propriedade FormEditor.ExportItems

Define opções para a caixa de combinação com valores de exportação.

```csharp
public string[][] ExportItems { get; set; }
```

## Exemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
formEditor.ExportItems = new string[][] 
{ 
    new string[] { "1", "Firs" }, 
    new string[] { "2", "Second" }, 
    new string[] { "3", "Third" } 
};
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
formEditor.Save();
```

### Veja Também

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)