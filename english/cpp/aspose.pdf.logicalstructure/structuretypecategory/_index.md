---
title: Aspose::Pdf::LogicalStructure::StructureTypeCategory class
linktitle: StructureTypeCategory
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::StructureTypeCategory class. Represents Categories of Standard Structure Types in C++.'
type: docs
weight: 5800
url: /cpp/aspose.pdf.logicalstructure/structuretypecategory/
---
## StructureTypeCategory class


Represents Categories of Standard [Structure](../../aspose.pdf.structure/) Types.

```cpp
class StructureTypeCategory : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [BLSEs](./blses/)() | Block-level structure elements (BLSEs) describe the overall layout of content on the page, proceeding in the block-progression direction. |
| static [GroupingElements](./groupingelements/)() | Grouping elements group other elements into sequences or hierarchies but hold no content directly and have no direct effect on layout. |
| static [IllustrationElements](./illustrationelements/)() | Illustration elements are compact sequences of content, in page content order, that are considered to be unitary objects with respect to page layout. An illustration can be treated as either a BLSE or an ILSE. |
| static [ILSEs](./ilses/)() | Inline-level structure elements (ILSEs) describe the layout of content within a BLSE, proceeding in the inline-progression direction. |
| static [to_StructureTypeCategory](./to_structuretypecategory/)(System::String) | Performs an explicit conversion from [System::String](../../system/string/) to [Aspose::Pdf::LogicalStructure::StructureTypeCategory](./). |
| [ToString](./tostring/)() const override | Returns a string that represents the current object. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
