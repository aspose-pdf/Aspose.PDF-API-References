---
title: Aspose::Pdf::Annotations::XYZExplicitDestination class
linktitle: XYZExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::XYZExplicitDestination class. Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value in C++.'
type: docs
weight: 12000
url: /cpp/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class


Represents explicit destination that displays the page with the coordinates (left, top) positioned at the upper-left corner of the window and the contents of the page magnified by the factor zoom. A null value for any of the parameters left, top, or zoom specifies that the current value of that parameter is to be retained unchanged. A zoom value of 0 has the same meaning as a null value.

```cpp
class XYZExplicitDestination : public Aspose::Pdf::Annotations::ExplicitDestination
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateDestination](./createdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, double, double, double, bool) | Create destintion to specified location of the page considering page rotation if required. |
| static [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(System::SharedPtr\<Aspose::Pdf::Page\>, double) | Create destionation to upper left corner of the specifed page. |
| static [CreateDestinationToUpperLeftCorner](./createdestinationtoupperleftcorner/)(System::SharedPtr\<Aspose::Pdf::Page\>) | Create destination to specified page. |
| [get_Left](./get_left/)() | Gets left horizontal coordinate of the upper-left corner of the window. |
| [get_Top](./get_top/)() | Gets top vertical coordinate of the upper-left corner of the window. |
| [get_Zoom](./get_zoom/)() | Gets zoom factor. |
| [ToString](./tostring/)() const override | Converts the object state into string value. Example: "1 XYZ 100 200 3". |
| [XYZExplicitDestination](./xyzexplicitdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, double, double, double) | Creates local explicit destination. |
| [XYZExplicitDestination](./xyzexplicitdestination/)(System::SharedPtr\<Document\>, int32_t, double, double, double) | Creates remote explicit destination. |
| [XYZExplicitDestination](./xyzexplicitdestination/)(int32_t, double, double, double) | Creates remote explicit destination. |
## See Also

* Class [ExplicitDestination](../explicitdestination/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
