---
title: Aspose::Pdf::Annotations::GoToRemoteAction class
linktitle: GoToRemoteAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::GoToRemoteAction class. Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file in C++.'
type: docs
weight: 4400
url: /cpp/aspose.pdf.annotations/gotoremoteaction/
---
## GoToRemoteAction class


Represents a remote go-to action that is similar to an ordinary go-to action but jumps to a destination in another PDF file instead of the current file.

```cpp
class GoToRemoteAction : public Aspose::Pdf::Annotations::GoToAction
```

## Methods

| Method | Description |
| --- | --- |
| [get_Destination](./get_destination/)() override | Gets the destination to jump to. |
| [get_File](./get_file/)() | Gets the specification of the file in which the destination is located. |
| [get_NewWindow](./get_newwindow/)() | Gets a flag specifying whether to open the destination document in a new window. |
| [get_Next](../pdfaction/get_next/)() | Next actions in sequence. |
| [GetECMAScriptString](../pdfaction/getecmascriptstring/)() | Gets string for ECMAScript Action. |
| [GoToAction](../gotoaction/gotoaction/)(int32_t) | Constructor for [GoToAction](../gotoaction/) class. |
| [GoToAction](../gotoaction/gotoaction/)(System::SharedPtr\<Page\>) | Constructor for [GoToAction](../gotoaction/) class. |
| [GoToAction](../gotoaction/gotoaction/)(System::SharedPtr\<Page\>, ExplicitDestinationType, const System::ArrayPtr\<double\>\&) | Constructor for [GoToAction](../gotoaction/) class. |
| [GoToAction](../gotoaction/gotoaction/)(System::SharedPtr\<ExplicitDestination\>) | Constructor. |
| [GoToAction](../gotoaction/gotoaction/)() | Constructor. |
| [GoToAction](../gotoaction/gotoaction/)(System::SharedPtr\<Document\>, System::String) | Action which linked with Named Destination. |
| [GoToRemoteAction](./gotoremoteaction/)(System::String, int32_t) | Initializes [GoToRemoteAction](./) object. |
| [GoToRemoteAction](./gotoremoteaction/)(System::String, System::SharedPtr\<ExplicitDestination\>) | Initializes [GoToRemoteAction](./) object. |
| [set_Destination](./set_destination/)(System::SharedPtr\<IAppointment\>) override | Sets the destination to jump to. |
| [set_File](./set_file/)(System::SharedPtr\<FileSpecification\>) | Sets the specification of the file in which the destination is located. |
| [set_NewWindow](./set_newwindow/)(ExtendedBoolean) | Sets a flag specifying whether to open the destination document in a new window. |
| [ToString](../pdfaction/tostring/)() const override | Returns string representation of [ExplicitDestination](../explicitdestination/) object. |
## See Also

* Class [GoToAction](../gotoaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
