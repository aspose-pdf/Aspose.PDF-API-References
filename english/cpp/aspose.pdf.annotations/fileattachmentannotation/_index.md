---
title: Aspose::Pdf::Annotations::FileAttachmentAnnotation class
linktitle: FileAttachmentAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::FileAttachmentAnnotation class. Class describes file attachment annotation in C++.'
type: docs
weight: 3000
url: /cpp/aspose.pdf.annotations/fileattachmentannotation/
---
## FileAttachmentAnnotation class


Class describes file attachment annotation.

```cpp
class FileAttachmentAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process annotation. |
| [FileAttachmentAnnotation](./fileattachmentannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::SharedPtr\<FileSpecification\>) | Creates new FileAttachment annotation on the specified page. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_File](./get_file/)() | The specification of the file associated with this annotation. |
| [get_Icon](./get_icon/)() | Gets icon that shall be used in displaying annotation. |
| [get_Opacity](./get_opacity/)() | Gets icon's opacity from 0 to 1: 0 - completely transparant, 1 - completely opaque. |
| [set_File](./set_file/)(System::SharedPtr\<FileSpecification\>) | The specification of the file associated with this annotation. |
| [set_Icon](./set_icon/)(FileIcon) | Sets icon that shall be used in displaying annotation. |
| [set_Opacity](./set_opacity/)(double) | Sets icon's opacity from 0 to 1: 0 - completely transparant, 1 - completely opaque. |
## See Also

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
