---
title: Aspose::Pdf::Annotations::ColorBarAnnotation class
linktitle: ColorBarAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::ColorBarAnnotation class. Class representing ColorBarAnnotation annotation. Property Color ignored, instead used ColorsOfCMYK color. On creation, the ratio of width and height determines the orientation of the annotation - horizontal or vertical. Next, it checks that the annotation rectangle is outside the TrimBox, and if not, then it is shifted to the nearest location outside the TrimBox, taking into account the orientation of the annotation. It is possible to reduce the width (height) so that the annotation fits outside the TrimBox. If there is no space for the layout, the width/height can be set to zero (in this case, the annotation is present on the page, but not displayed) in C++.'
type: docs
weight: 1900
url: /cpp/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class


Class representing [ColorBarAnnotation](./) annotation. Property [Color](../../aspose.pdf/color/) ignored, instead used [ColorsOfCMYK](../colorsofcmyk/) color. On creation, the ratio of width and height determines the orientation of the annotation - horizontal or vertical. Next, it checks that the annotation rectangle is outside the TrimBox, and if not, then it is shifted to the nearest location outside the TrimBox, taking into account the orientation of the annotation. It is possible to reduce the width (height) so that the annotation fits outside the TrimBox. If there is no space for the layout, the width/height can be set to zero (in this case, the annotation is present on the page, but not displayed).

```cpp
class ColorBarAnnotation : public Aspose::Pdf::Annotations::PrinterMarkAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object to process the annotation. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Update parameters and appearance, according to the matrix transform and moving outside of TrimBox if nesseary. |
| [ColorBarAnnotation](./colorbarannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, ColorsOfCMYK) | Creates new ColorBar annotation on the specified page. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_ColorOfCMYK](./get_colorofcmyk/)() const | Gets color (one of cyan, magenta, yellow, black) for which the annotation is drawing. |
| [set_ColorOfCMYK](./set_colorofcmyk/)(ColorsOfCMYK) | Sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing. |
## See Also

* Class [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
