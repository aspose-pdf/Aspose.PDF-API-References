---
title: Aspose::Pdf::Annotations::GoToAction class
linktitle: GoToAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::GoToAction class. Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor) in C++.'
type: docs
weight: 4300
url: /cpp/aspose.pdf.annotations/gotoaction/
---
## GoToAction class


Represents a go-to action that changes the view to a specified destination (page, location, and magnification factor).

```cpp
class GoToAction : public Aspose::Pdf::Annotations::PdfAction
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_Destination](./get_destination/)() | Gets the destination to jump to. |
| [GoToAction](./gotoaction/)(int32_t) | Constructor for [GoToAction](./) class. |
| [GoToAction](./gotoaction/)(System::SharedPtr\<Page\>) | Constructor for [GoToAction](./) class. |
| [GoToAction](./gotoaction/)(System::SharedPtr\<Page\>, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Constructor for [GoToAction](./) class. |
| [GoToAction](./gotoaction/)(System::SharedPtr\<ExplicitDestination\>) | Constructor. |
| [GoToAction](./gotoaction/)() | Constructor. |
| [GoToAction](./gotoaction/)(System::SharedPtr\<Document\>, System::String) | Action which linked with Named Destination. |
| virtual [set_Destination](./set_destination/)(System::SharedPtr\<IAppointment\>) | Sets the destination to jump to. |
## See Also

* Class [PdfAction](../pdfaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
