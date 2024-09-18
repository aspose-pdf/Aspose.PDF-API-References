---
title: Aspose::Pdf::Annotations::FitVExplicitDestination class
linktitle: FitVExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FitVExplicitDestination class. Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged in C++.'
type: docs
weight: 3800
url: /cpp/aspose.pdf.annotations/fitvexplicitdestination/
---
## FitVExplicitDestination class


Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of the page within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged.

```cpp
class FitVExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateDestination](../explicitdestination/createdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](../explicitdestination/) descendant classes. |
| static [CreateDestination](../explicitdestination/createdestination/)(System::SharedPtr\<Document\>, int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](../explicitdestination/) descendant classes. |
| static [CreateDestination](../explicitdestination/createdestination/)(int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](../explicitdestination/) descendant classes. |
| [FitVExplicitDestination](./fitvexplicitdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, double) | Creates local explicit destination. |
| [FitVExplicitDestination](./fitvexplicitdestination/)(System::SharedPtr\<Document\>, int32_t, double) | Creates remote explicit destination. |
| [FitVExplicitDestination](./fitvexplicitdestination/)(int32_t, double) | Creates remote explicit destination. |
| [get_Left](./get_left/)() | Gets the horizontal coordinate left positioned at the left edge of the window. |
| [get_Page](../explicitdestination/get_page/)() const | Gets the destination page object. |
| [get_PageNumber](../explicitdestination/get_pagenumber/)() const | Gets the destination page number. |
| [ToString](./tostring/)() const override | Converts the object state into string value. Example: "1 FitV 100". |
## See Also

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
