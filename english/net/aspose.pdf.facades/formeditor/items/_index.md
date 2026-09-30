---
title: "FormEditor.Items"
linktitle: "Items"
articleTitle: "Items"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor property. Sets items which will be added t onewly created list box or combo box. formEditor = new Aspose.Pdf.Facades.FormEditor(\"input.pdf\", \"outp..."
type: docs
weight: 370
url: "/net/aspose.pdf.facades/formeditor/items/"
product_version: "26.9.0"
---
## FormEditor.Items property

Sets items which will be added t onewly created list box or combo box. 
 
 formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
 formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
 formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
 formEditor.Save();

```csharp
public string[] Items { get; set; }
```

## Examples

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

