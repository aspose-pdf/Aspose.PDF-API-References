---
title: Aspose::Pdf::Annotations::FitRExplicitDestination class
linktitle: FitRExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FitRExplicitDestination class. Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior in C++.'
type: docs
weight: 3700
url: /cpp/aspose.pdf.annotations/fitrexplicitdestination/
---
## FitRExplicitDestination class


Represents explicit destination that displays the page with its contents magnified just enough to fit the rectangle specified by the coordinates left, bottom, right, and topentirely within the window both horizontally and vertically. If the required horizontal and vertical magnification factors are different, use the smaller of the two, centering the rectangle within the window in the other dimension. A null value for any of the parameters may result in unpredictable behavior.

```cpp
class FitRExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Methods

| Method | Description |
| --- | --- |
| [FitRExplicitDestination](./fitrexplicitdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, double, double, double, double) | Creates local explicit destination. |
| [FitRExplicitDestination](./fitrexplicitdestination/)(System::SharedPtr\<Document\>, int32_t, double, double, double, double) | Creates remote explicit destination. |
| [FitRExplicitDestination](./fitrexplicitdestination/)(int32_t, double, double, double, double) | Creates remote explicit destination. |
| [get_Bottom](./get_bottom/)() | Gets bottom vertical coordinate of visible rectangle. |
| [get_Left](./get_left/)() | Gets left horizontal coordinate of visible rectangle. |
| [get_Right](./get_right/)() | Gets right horizontal coordinate of visible rectangle. |
| [get_Top](./get_top/)() | Gets top vertical coordinate of visible rectangle. |
| [ToString](./tostring/)() const override | Converts the object state into string value. Example: "1 FitR 100 200 300 400". |
## See Also

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
