---
title: Aspose::Pdf::Annotations::RichMediaAnnotation class
linktitle: RichMediaAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::RichMediaAnnotation class. Class describes RichMediaAnnotation which allows embed video/audio data into PDF document in C++.'
type: docs
weight: 9700
url: /cpp/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class


Class describes [RichMediaAnnotation](./) which allows embed video/audio data into PDF document.

```cpp
class RichMediaAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Enums

| Enum | Description |
| --- | --- |
| [ActivationEvent](./activationevent/) | Event which activates annotation. |
| [ContentType](./contenttype/) | Type of the multimedia. |
## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor for this annotation. |
| [AddCustomData](./addcustomdata/)(System::String, System::SharedPtr\<System::IO::Stream\>) | Add custom named data (for example required for flash script). |
| [get_ActivateOn](./get_activateon/)() | Event which activates application. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Content](./get_content/)() | Data of the Rich Media content. |
| [get_CustomFlashVariables](./get_customflashvariables/)() const | Sets or gets flash variables which passed to player. |
| [get_CustomPlayer](./get_customplayer/)() const | Sets or gets custom flash player to play video/audio data. |
| [get_Type](./get_type/)() | Gets type of content. Possible values: Audio, Video. |
| [RichMediaAnnotation](./richmediaannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Initializes [RichMediaAnnotation](./). |
| [set_ActivateOn](./set_activateon/)(RichMediaAnnotation::ActivationEvent) | Event which activates application. |
| [set_CustomFlashVariables](./set_customflashvariables/)(System::String) | Sets or gets flash variables which passed to player. |
| [set_CustomPlayer](./set_customplayer/)(System::SharedPtr\<System::IO::Stream\>) | Sets or gets custom flash player to play video/audio data. |
| [set_Type](./set_type/)(RichMediaAnnotation::ContentType) | Sets type of content. Possible values: Audio, Video. |
| [SetContent](./setcontent/)(System::String, System::SharedPtr\<System::IO::Stream\>) | Set content stream. |
| [SetPoster](./setposter/)(System::SharedPtr\<System::IO::Stream\>) | Set poster of the annotation. |
| [Update](./update/)() | Updates data with specified parameters. |
## See Also

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
