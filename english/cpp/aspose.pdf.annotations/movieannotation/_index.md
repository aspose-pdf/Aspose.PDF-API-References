---
title: Aspose::Pdf::Annotations::MovieAnnotation class
linktitle: MovieAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::MovieAnnotation class. Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the movie is played in C++.'
type: docs
weight: 6700
url: /cpp/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class


Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the movie is played.

```cpp
class MovieAnnotation : public Aspose::Pdf::Annotations::Annotation,
                        public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Aspect](./get_aspect/)() | Gets the width and height of the movie's bounding box, in pixels. |
| [get_File](./get_file/)() | Gets a file specification identifying a self-describing movie file. |
| [get_Poster](./get_poster/)() | Gets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. If true, the poster image shall be retrieved from the movie file; if it is false, no poster shall be displayed. |
| [get_Rotate](./get_rotate/)() | Gets the number of degrees by which the movie shall be rotated clockwise relative to the page. The value shall be a multiple of 90. |
| [get_Title](./get_title/)() override | Gets the title of the movie annotation. |
| [MovieAnnotation](./movieannotation/)(System::SharedPtr\<Document\>, System::String) | Constructor for using with Generator. |
| [MovieAnnotation](./movieannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::String) | Creates new Sound annotation on the specified page. |
| [set_Aspect](./set_aspect/)(System::SharedPtr\<Point\>) | Sets the width and height of the movie's bounding box, in pixels. |
| [set_File](./set_file/)(System::SharedPtr\<FileSpecification\>) | Sets a file specification identifying a self-describing movie file. |
| [set_Poster](./set_poster/)(bool) | Sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. If true, the poster image shall be retrieved from the movie file; if it is false, no poster shall be displayed. |
| [set_Rotate](./set_rotate/)(int32_t) | Sets the number of degrees by which the movie shall be rotated clockwise relative to the page. The value shall be a multiple of 90. |
| [set_Title](./set_title/)(System::String) override | Sets the title of the movie annotation. |
## See Also

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
