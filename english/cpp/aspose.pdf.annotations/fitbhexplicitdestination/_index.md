---
title: Aspose::Pdf::Annotations::FitBHExplicitDestination class
linktitle: FitBHExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FitBHExplicitDestination class. Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged in C++.'
type: docs
weight: 3300
url: /cpp/aspose.pdf.annotations/fitbhexplicitdestination/
---
## FitBHExplicitDestination class


Represents explicit destination that displays the page with the vertical coordinate top positioned at the top edge of the window and the contents of the page magnified just enough to fit the entire width of its bounding box within the window. A null value for top specifies that the current value of that parameter is to be retained unchanged.

```cpp
class FitBHExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Methods

| Method | Description |
| --- | --- |
| [FitBHExplicitDestination](./fitbhexplicitdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, double) | Creates local explicit destination. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/)(System::SharedPtr\<Document\>, int32_t, double) | Creates remote explicit destination. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/)(int32_t, double) | Creates remote explicit destination. |
| [get_Top](./get_top/)() | Gets the vertical coordinate top positioned at the top edge of the window. |
| [ToString](./tostring/)() const override | Converts the object state into string value. Example: "1 FitBH 100". |
## See Also

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
