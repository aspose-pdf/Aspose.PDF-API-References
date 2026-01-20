---
title: Aspose::Pdf::Annotations::FitBVExplicitDestination class
linktitle: FitBVExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FitBVExplicitDestination class. Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of its bounding box within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged in C++.'
type: docs
weight: 3400
url: /cpp/aspose.pdf.annotations/fitbvexplicitdestination/
---
## FitBVExplicitDestination class


Represents explicit destination that displays the page with the horizontal coordinate left positioned at the left edge of the window and the contents of the page magnified just enough to fit the entire height of its bounding box within the window. A null value for left specifies that the current value of that parameter is to be retained unchanged.

```cpp
class FitBVExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Methods

| Method | Description |
| --- | --- |
| [FitBVExplicitDestination](./fitbvexplicitdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, double) | Creates local explicit destination. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/)(System::SharedPtr\<Document\>, int32_t, double) | Creates remote explicit destination. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/)(int32_t, double) | Creates remote explicit destination. |
| [get_Left](./get_left/)() | Gets the horizontal coordinate left positioned at the left edge of the window. |
| [ToString](./tostring/)() const override | Converts the object state into string value. Example: "1 FitBV 100". |
## See Also

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
