---
title: Aspose::Pdf::Text::AbsorbedCell class
linktitle: AbsorbedCell
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::AbsorbedCell class. Represents cell of table that exist on the page in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.text/absorbedcell/
---
## AbsorbedCell class


Represents cell of table that exist on the page.

```cpp
class AbsorbedCell : public Aspose::Pdf::Text::ITableElement,
                     public System::IComparable<System::SharedPtr<AbsorbedCell>>
```

## Methods

| Method | Description |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<AbsorbedCell\>) override | Compares the current [AbsorbedCell](./) object with another [AbsorbedCell](./) object and returns an integer that indicates whether the current object precedes, follows, or occurs in the same position in the sort order as the other object. |
| [get_BorderInfo](./get_borderinfo/)() const | Return the border information for the cell when the FlowEngine.TableAbsorber.UseFlowEngine property is set to true. |
| [get_ColSpan](./get_colspan/)() const | Return the number of columns the cell should span when TableAbsorber.UseFlowEngine property is set to true. |
| [get_Rectangle](./get_rectangle/)() override | Gets rectangle that describes position of the cell on page. |
| [get_TextFragments](./get_textfragments/)() const | Gets collection of [TextFragment](../textfragment/) objects that describes text containing in the cell. |
## See Also

* Class [ITableElement](../itableelement/)
* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
