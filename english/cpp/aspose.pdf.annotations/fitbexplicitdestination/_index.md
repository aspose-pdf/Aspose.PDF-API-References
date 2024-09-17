---
title: Aspose::Pdf::Annotations::FitBExplicitDestination class
linktitle: FitBExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FitBExplicitDestination class. Represents explicit destination that displays the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the bounding box within the window in the other dimension in C++.'
type: docs
weight: 3200
url: /cpp/aspose.pdf.annotations/fitbexplicitdestination/
---
## FitBExplicitDestination class


Represents explicit destination that displays the page with its contents magnified just enough to fit its bounding box entirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the bounding box within the window in the other dimension.

```cpp
class FitBExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateDestination](../explicitdestination/createdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](../explicitdestination/) descendant classes. |
| static [CreateDestination](../explicitdestination/createdestination/)(System::SharedPtr\<Document\>, int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](../explicitdestination/) descendant classes. |
| static [CreateDestination](../explicitdestination/createdestination/)(int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](../explicitdestination/) descendant classes. |
| [FitBExplicitDestination](./fitbexplicitdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>) | Creates local explicit destination. |
| [FitBExplicitDestination](./fitbexplicitdestination/)(System::SharedPtr\<Document\>, int32_t) | Creates remote explicit destination. |
| [FitBExplicitDestination](./fitbexplicitdestination/)(int32_t) | Creates remote explicit destination. |
| [get_Page](../explicitdestination/get_page/)() const | Gets the destination page object. |
| [get_PageNumber](../explicitdestination/get_pagenumber/)() const | Gets the destination page number. |
| [ToString](./tostring/)() const override | Converts the object state into string value. Example: "1 FitB". |
## See Also

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
