---
title: Aspose::Pdf::HtmlFragment class
linktitle: HtmlFragment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlFragment class. Represents html fragment in C++.'
type: docs
weight: 7300
url: /cpp/aspose.pdf/htmlfragment/
---
## HtmlFragment class


Represents html fragment.

```cpp
class HtmlFragment : public Aspose::Pdf::FormattedFragment
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clones html fragment. |
| [get_HtmlLoadOptions](./get_htmlloadoptions/)() const | Gets [HtmlLoadOptions](../htmlloadoptions/) that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used. |
| [get_IsBreakWords](./get_isbreakwords/)() const | Gets words break. |
| [get_IsParagraphHasMargin](./get_isparagraphhasmargin/)() const | Gets is paragraph has default margin otherwise margin is 0. |
| [get_Rectangle](./get_rectangle/)() const | Gets rectangle of the [HtmlFragment](./). |
| [get_TextState](./get_textstate/)() const | Gets font. |
| [HtmlFragment](./htmlfragment/)(System::String) | Initializes a new instance of the [HtmlFragment](./) class. |
| [set_HtmlLoadOptions](./set_htmlloadoptions/)(System::SharedPtr\<Aspose::Pdf::HtmlLoadOptions\>) | Sets [HtmlLoadOptions](../htmlloadoptions/) that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used. |
| [set_IsBreakWords](./set_isbreakwords/)(bool) | Sets words break. |
| [set_IsParagraphHasMargin](./set_isparagraphhasmargin/)(bool) | Sets is paragraph has default margin otherwise margin is 0. |
| [set_TextState](./set_textstate/)(System::SharedPtr\<Aspose::Pdf::Text::TextState\>) | Sets font. |
## See Also

* Class [FormattedFragment](../formattedfragment/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
