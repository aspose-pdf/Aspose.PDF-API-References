---
title: Aspose::Pdf::Annotations::FitHExplicitDestination class
linktitle: FitHExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FitHExplicitDestination class. Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of the page within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged in C++.'
type: docs
weight: 3600
url: /cpp/aspose.pdf.annotations/fithexplicitdestination/
---
## FitHExplicitDestination class


Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of the page within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged.

```cpp
class FitHExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateDestination](../explicitdestination/createdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](../explicitdestination/) descendant classes. |
| static [CreateDestination](../explicitdestination/createdestination/)(System::SharedPtr\<Document\>, int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](../explicitdestination/) descendant classes. |
| static [CreateDestination](../explicitdestination/createdestination/)(int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](../explicitdestination/) descendant classes. |
| [FitHExplicitDestination](./fithexplicitdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, double) | Creates local explicit destination. |
| [FitHExplicitDestination](./fithexplicitdestination/)(System::SharedPtr\<Document\>, int32_t, double) | Creates remote explicit destination. |
| [FitHExplicitDestination](./fithexplicitdestination/)(int32_t, double) | Creates remote explicit destination. |
| [get_Page](../explicitdestination/get_page/)() const | Gets the destination page object. |
| [get_PageNumber](../explicitdestination/get_pagenumber/)() const | Gets the destination page number. |
| [get_Top](./get_top/)() | Gets the vertical coordinate top positioned at the top edge of the window. |
| [ToString](./tostring/)() const override | Converts the object state into string value. Example: "1 FitH 100". |
## See Also

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
