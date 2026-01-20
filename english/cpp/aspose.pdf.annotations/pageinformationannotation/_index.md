---
title: Aspose::Pdf::Annotations::PageInformationAnnotation class
linktitle: PageInformationAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PageInformationAnnotation class. Represents a Page Information annotation in a PDF document. This annotation contains the file name, page number, and the date and time of the annotation creation in C++.'
type: docs
weight: 7000
url: /cpp/aspose.pdf.annotations/pageinformationannotation/
---
## PageInformationAnnotation class


Represents a [Page](../../aspose.pdf/page/) Information annotation in a PDF document. This annotation contains the file name, page number, and the date and time of the annotation creation.

```cpp
class PageInformationAnnotation : public Aspose::Pdf::Annotations::PrinterMarkAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor for annotation processing. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [PageInformationAnnotation](./pageinformationannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Initializes a new instance of the [PageInformationAnnotation](./) class on the given page in the given location. |
## Remarks


This class is primarily used to add metadata to a specific page in the PDF document, which can be useful for tracking and referencing purposes. For instance, it can be used to mark pages during the printing process or to provide additional information about the page when viewing the document. 
## See Also

* Class [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
