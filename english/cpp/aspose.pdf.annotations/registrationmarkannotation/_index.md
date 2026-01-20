---
title: Aspose::Pdf::Annotations::RegistrationMarkAnnotation class
linktitle: RegistrationMarkAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::RegistrationMarkAnnotation class. Represents a Registration Mark annotation in C++.'
type: docs
weight: 9300
url: /cpp/aspose.pdf.annotations/registrationmarkannotation/
---
## RegistrationMarkAnnotation class


Represents a Registration Mark annotation.

```cpp
class RegistrationMarkAnnotation : public Aspose::Pdf::Annotations::PrinterMarkAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor for annotation processing. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Position](./get_position/)() const | Gets the position of the registration mark on a page. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, PrinterMarkSidePosition) | Initializes a new instance of the [RegistrationMarkAnnotation](./) class on the given page in the given location. |
| [set_Position](./set_position/)(PrinterMarkSidePosition) | Sets the position of the registration mark on a page. |
## Remarks


Registration marks are symbols added to printing plates or screens to ensure proper alignment of colors during the printing process. 
## See Also

* Class [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
