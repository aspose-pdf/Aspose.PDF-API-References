---
title: Aspose::Pdf::Annotations::MovieAnnotation::MovieAnnotation constructor
linktitle: MovieAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::MovieAnnotation::MovieAnnotation constructor. Creates new Sound annotation on the specified page in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.annotations/movieannotation/movieannotation/
---
## MovieAnnotation::MovieAnnotation(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) constructor


Creates new Sound annotation on the specified page.

```cpp
Aspose::Pdf::Annotations::MovieAnnotation::MovieAnnotation(const System::SharedPtr<Aspose::Pdf::Page> &page, const System::SharedPtr<Rectangle> &rect, const System::String &movieFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| page | const System::SharedPtr\<Aspose::Pdf::Page\>\& | The document's page where annotation should be created. |
| rect | const System::SharedPtr\<Rectangle\>\& | The annotation rectangle, defining the location of the annotation on the page. |
| movieFile | const System::String\& | A movie file to be played when the annotation is activated. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [String](../../../system/string/)
* Class [MovieAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## MovieAnnotation::MovieAnnotation(const System::SharedPtr\<Document\>\&, const System::String\&) constructor


Constructor for using with Generator.

```cpp
Aspose::Pdf::Annotations::MovieAnnotation::MovieAnnotation(const System::SharedPtr<Document> &document, const System::String &movieFile)
```


| Parameter | Type | Description |
| --- | --- | --- |
| document | const System::SharedPtr\<Document\>\& | [Document](../../../aspose.pdf/document/) where movie annotation will be created. |
| movieFile | const System::String\& | Name of movie file. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [MovieAnnotation](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
