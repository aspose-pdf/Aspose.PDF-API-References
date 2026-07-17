---
title: Aspose::Pdf::Comparison::GraphicalPdfComparer class
linktitle: GraphicalPdfComparer
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Comparison::GraphicalPdfComparer class. Represents a class for graphically comparing PDF documents. Should be used to search for small changes, mainly of a graphical nature. To compare text content changes, use other PDF comparison classes in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class


Represents a class for graphically comparing PDF documents. Should be used to search for small changes, mainly of a graphical nature. To compare text content changes, use other PDF comparison classes.

```cpp
class GraphicalPdfComparer : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [CompareDocumentsToImages](./comparedocumentstoimages/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&, const System::String\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Compares documents graphically. The comparison result is placed in images. |
| [CompareDocumentsToPdf](./comparedocumentstopdf/)(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&) | Compares documents graphically. The comparison result is placed in a PDF document. |
| [ComparePagesToImage](./comparepagestoimage/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Compares pages graphically. The comparison result is placed in a image. |
| [ComparePagesToPdf](./comparepagestopdf/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Compares pages graphically. The comparison result is placed in a PDF document. |
| [ComparePagesToPdf](./comparepagestopdf/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Document\>\&) | Compares pages graphically. The comparison result is placed in a PDF document. |
| [get_Color](./get_color/)() const | Gets and sets the change flag color. The default color is red. |
| [get_Resolution](./get_resolution/)() const | Gets and sets the resolution of the resulting images. The default value is 150dpi. |
| [get_Threshold](./get_threshold/)() const | Gets and sets the threshold value in percentage. This value allows you to ignore small changes if they are not significant to you. The default value is 0%. |
| [GetDifference](./getdifference/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&) | Gets differences between pages images. The result contains an image of the first page compared and an array of differences. |
| [GraphicalPdfComparer](./graphicalpdfcomparer/)() | Creates an instance of [GraphicalPdfComparer](./) class. |
| [set_Color](./set_color/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Gets and sets the change flag color. The default color is red. |
| [set_Resolution](./set_resolution/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Gets and sets the resolution of the resulting images. The default value is 150dpi. |
| [set_Threshold](./set_threshold/)(double) | Gets and sets the threshold value in percentage. This value allows you to ignore small changes if they are not significant to you. The default value is 0%. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
