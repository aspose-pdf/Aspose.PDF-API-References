---
title: Aspose::Pdf::Annotations::Measure class
linktitle: Measure
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::Measure class. Class which describes Measure coordinate system in C++.'
type: docs
weight: 6200
url: /cpp/aspose.pdf.annotations/measure/
---
## Measure class


Class which describes [Measure](./) coordinate system.

```cpp
class Measure : public System::Object
```

## Nested classes

* Class [NumberFormat](./numberformat/)
* Class [NumberFormatList](./numberformatlist/)
## Methods

| Method | Description |
| --- | --- |
| [get_AngleFormat](./get_angleformat/)() | A number format array for measurement of angles. |
| [get_AreaFormat](./get_areaformat/)() | A number format array for measurement of area. |
| [get_DistanceFormat](./get_distanceformat/)() | A number format array for measurement of distance in any direction. |
| [get_Origin](./get_origin/)() | [Point](../../aspose.pdf/point/) that shall specify the origin of the measurement coordinate system in default user space coordinates. |
| [get_ScaleRatio](./get_scaleratio/)() | A text string expressing the scale ratio of the drawing. |
| [get_SlopeFormat](./get_slopeformat/)() | A number format array for measurement of the slope of a line. |
| [get_XFormat](./get_xformat/)() | A number format array for measurement of change along the xaxis and, if Y is not present, along the y axis as well. |
| [get_XYFactor](./get_xyfactor/)() | A factor that shall be used to convert the largest units along the y axis to the largest units along the x axis. |
| [get_YFormat](./get_yformat/)() | A number format array for measurement of change along the y axis. |
| [Measure](./measure/)(System::SharedPtr\<Annotation\>) | Creates [Measure](./) object for measure annotations. |
| [set_AngleFormat](./set_angleformat/)(System::SharedPtr\<Measure::NumberFormatList\>) | A number format array for measurement of angles. |
| [set_AreaFormat](./set_areaformat/)(System::SharedPtr\<Measure::NumberFormatList\>) | A number format array for measurement of area. |
| [set_DistanceFormat](./set_distanceformat/)(System::SharedPtr\<Measure::NumberFormatList\>) | A number format array for measurement of distance in any direction. |
| [set_Origin](./set_origin/)(System::SharedPtr\<Point\>) | [Point](../../aspose.pdf/point/) that shall specify the origin of the measurement coordinate system in default user space coordinates. |
| [set_ScaleRatio](./set_scaleratio/)(System::String) | A text string expressing the scale ratio of the drawing. |
| [set_SlopeFormat](./set_slopeformat/)(System::SharedPtr\<Measure::NumberFormatList\>) | A number format array for measurement of the slope of a line. |
| [set_XFormat](./set_xformat/)(System::SharedPtr\<Measure::NumberFormatList\>) | A number format array for measurement of change along the xaxis and, if Y is not present, along the y axis as well. |
| [set_XYFactor](./set_xyfactor/)(double) | A factor that shall be used to convert the largest units along the y axis to the largest units along the x axis. |
| [set_YFormat](./set_yformat/)(System::SharedPtr\<Measure::NumberFormatList\>) | A number format array for measurement of change along the y axis. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
