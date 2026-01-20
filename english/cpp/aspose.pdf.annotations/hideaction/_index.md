---
title: Aspose::Pdf::Annotations::HideAction class
linktitle: HideAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::HideAction class. Represents a hide action that hides or shows one or more annotations on the screen by setting or clearing their Hidden flags in C++.'
type: docs
weight: 4600
url: /cpp/aspose.pdf.annotations/hideaction/
---
## HideAction class


Represents a hide action that hides or shows one or more annotations on the screen by setting or clearing their Hidden flags.

```cpp
class HideAction : public Aspose::Pdf::Annotations::PdfAction
```

## Methods

| Method | Description |
| --- | --- |
| [get_IsHidden](./get_ishidden/)() | Gets status of the annotation(s) to hide/display. |
| [HideAction](./hideaction/)(System::SharedPtr\<Annotation\>) | Initializes a new instance of the [HideAction](./) class for the specified annotation. |
| [HideAction](./hideaction/)(System::SharedPtr\<Annotation\>, bool) | Initializes a new instance of the [HideAction](./) class for the specified annotation and invisibility flag. |
| [HideAction](./hideaction/)(System::String) | Initializes a new instance of the [HideAction](./) class for the specified field name. |
| [HideAction](./hideaction/)(System::String, bool) | Initializes a new instance of the [HideAction](./) class for the specified field name and invisibility flag. |
| [HideAction](./hideaction/)(System::ArrayPtr\<System::SharedPtr\<Annotation\>\>) | Initializes a new instance of the [HideAction](./) class for the specified annotations. |
| [HideAction](./hideaction/)(System::ArrayPtr\<System::SharedPtr\<Annotation\>\>, bool) | Initializes a new instance of the [HideAction](./) class for the specified annotations and for invisibility flag. |
| [HideAction](./hideaction/)(System::ArrayPtr\<System::String\>) | Initializes a new instance of the [HideAction](./) class for the specified field names. |
| [HideAction](./hideaction/)(System::ArrayPtr\<System::String\>, bool) | Initializes a new instance of the [HideAction](./) class for the specified field names and for invisibility flag. |
| [set_IsHidden](./set_ishidden/)(bool) | Sets status of the annotation(s) to hide/display. |
## See Also

* Class [PdfAction](../pdfaction/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
