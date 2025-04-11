---
title: FormEditor.Items
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de FormEditor. Establece los elementos que se agregarán a la lista o cuadro combinado recién creado
type: docs
weight: 50
url: /es/net/aspose.pdf.facades/formeditor/items/
---
## Propiedad FormEditor.Items

Establece los elementos que se agregarán a la lista o cuadro combinado recién creado.

```csharp
formEditor = new Aspose.Pdf.Facades.FormEditor("input.pdf", "output.pdf");
formEditor.Items = new string[] { "AAA", "BBB", "CCC" };
formEditor.AddField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
formEditor.Save();
```

```csharp
public string[] Items { get; set; }
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)