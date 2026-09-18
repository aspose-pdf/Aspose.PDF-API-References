---
title: ListLIElement.AddRef
second_title: Aspose.PDF for .NET API Reference
description: ListLIElement method. Adds a reference to the specified StructureElement within this Table of Contents Item TOCI element. This is typically used when ListLIElement serves as a TOC header in nested tables of contents
type: docs
weight: 10
url: /net/aspose.pdf.logicalstructure/listlielement/addref/
---
## ListLIElement.AddRef method

Adds a reference to the specified [`StructureElement`](../../structureelement/) within this Table of Contents Item (TOCI) element. This is typically used when `ListLIElement` serves as a TOC header in nested tables of contents.

```csharp
public void AddRef(StructureElement referencedStructureElement)
```

| Parameter | Type | Description |
| --- | --- | --- |
| referencedStructureElement | StructureElement | The [`StructureElement`](../../structureelement/) to be referenced by this TOCI element. |

## Remarks

Associating a structure element, such as a header or another content section, with a TOCI element ensures correct logical structure and improves navigational behavior in tagged PDFs.

### See Also

* class [StructureElement](../../structureelement/)
* class [ListLIElement](../)
* namespace [Aspose.Pdf.LogicalStructure](../../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../../)


