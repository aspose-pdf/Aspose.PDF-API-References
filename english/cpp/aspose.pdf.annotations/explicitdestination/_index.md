---
title: Aspose::Pdf::Annotations::ExplicitDestination class
linktitle: ExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::ExplicitDestination class. Represents the base class for explicit destinations in PDF document in C++.'
type: docs
weight: 2700
url: /cpp/aspose.pdf.annotations/explicitdestination/
---
## ExplicitDestination class


Represents the base class for explicit destinations in PDF document.

```cpp
class ExplicitDestination : public Aspose::Pdf::Annotations::IAppointment
```

## Methods

| Method | Description |
| --- | --- |
| static [CreateDestination](./createdestination/)(System::SharedPtr\<Aspose::Pdf::Page\>, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](./) descendant classes. |
| static [CreateDestination](./createdestination/)(System::SharedPtr\<Document\>, int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](./) descendant classes. |
| static [CreateDestination](./createdestination/)(int32_t, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Creates instances of [ExplicitDestination](./) descendant classes. |
| [get_Page](./get_page/)() const | Gets the destination page object. |
| [get_PageNumber](./get_pagenumber/)() const | Gets the destination page number. |
| virtual [ToString](./tostring/)() const | Returns string representation of [ExplicitDestination](./) object. |
## See Also

* Class [IAppointment](../iappointment/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
