---
title: "ListLIElement.AddRef"
linktitle: "AddRef"
articleTitle: "AddRef"
second_title: "Aspose.PDF for .NET"
description: "Adds a reference to the specified within this Table of Contents Item (TOCI) element. This is typically used when `ListLIElement` serves as a TOC header in ne..."
type: docs
weight: 10
url: "/net/aspose.pdf.logicalstructure/listlielement/addref/"
product_version: "26.9.0"
---
## AddRef([StructureElement](../../../aspose.pdf.logicalstructure/structureelement/)) {#addref}

Adds a reference to the specified [`StructureElement`](../../../aspose.pdf.logicalstructure/structureelement/) within this Table of Contents Item (TOCI) element.
 This is typically used when `ListLIElement` serves as a TOC header in nested tables of contents.

Associating a structure element, such as a header or another content section, with a TOCI element
 ensures correct logical structure and improves navigational behavior in tagged PDFs.

```csharp
public void AddRef(StructureElement referencedStructureElement)
```

| Parameter | Type | Description |
| --- | --- | --- |
| referencedStructureElement | StructureElement | The <see cref="T:Aspose.Pdf.LogicalStructure.StructureElement" /> to be referenced by this TOCI element. |

### See Also

* class [ListLIElement](../)
* namespace [Aspose.Pdf.LogicalStructure](../../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../../)

