---
title: "Aspose::Pdf::Annotations::Measure class"
linktitle: "Measure"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::Measure class. Clase que describe el sistema de coordenadas Measure en C++."
type: docs
weight: 6200
url: /es/cpp/aspose.pdf.annotations/measure/
---
## Measure class


Clase que describe el sistema de coordenadas [Measure](./).

```cpp
class Measure : public System::Object
```

## Nested classes

* Class [NumberFormat](./numberformat/)
* Class [NumberFormatList](./numberformatlist/)
## Métodos

| Método | Descripción |
| --- | --- |
| [get_AngleFormat](./get_angleformat/)() | Una matriz de formato numérico para la medición de ángulos. |
| [get_AreaFormat](./get_areaformat/)() | Una matriz de formato numérico para la medición de áreas. |
| [get_DistanceFormat](./get_distanceformat/)() | Una matriz de formato numérico para la medición de distancia en cualquier dirección. |
| [get_Origin](./get_origin/)() | [Point](../../aspose.pdf/point/) que especificará el origen del sistema de coordenadas de medida en coordenadas del espacio de usuario predeterminado. |
| [get_ScaleRatio](./get_scaleratio/)() | Una cadena de texto que expresa la razón de escala del dibujo. |
| [get_SlopeFormat](./get_slopeformat/)() | Una matriz de formato numérico para la medición de la pendiente de una línea. |
| [get_XFormat](./get_xformat/)() | Una matriz de formato numérico para la medición del cambio a lo largo del eje x y, si Y no está presente, también a lo largo del eje y. |
| [get_XYFactor](./get_xyfactor/)() | Un factor que se utilizará para convertir las unidades más grandes a lo largo del eje y a las unidades más grandes a lo largo del eje x. |
| [get_YFormat](./get_yformat/)() | Una matriz de formato numérico para la medición del cambio a lo largo del eje y. |
| [Measure](./measure/)(const System::SharedPtr\<Annotation\>\&) | Crea el objeto [Measure](./) para anotaciones de medida. |
| [set_AngleFormat](./set_angleformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Una matriz de formato numérico para la medición de ángulos. |
| [set_AreaFormat](./set_areaformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Una matriz de formato numérico para la medición de áreas. |
| [set_DistanceFormat](./set_distanceformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Una matriz de formato numérico para la medición de distancia en cualquier dirección. |
| [set_Origin](./set_origin/)(const System::SharedPtr\<Point\>\&) | [Point](../../aspose.pdf/point/) que especificará el origen del sistema de coordenadas de medida en coordenadas del espacio de usuario predeterminado. |
| [set_ScaleRatio](./set_scaleratio/)(const System::String\&) | Una cadena de texto que expresa la razón de escala del dibujo. |
| [set_SlopeFormat](./set_slopeformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Una matriz de formato numérico para la medición de la pendiente de una línea. |
| [set_XFormat](./set_xformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Una matriz de formato numérico para la medición del cambio a lo largo del eje x y, si Y no está presente, también a lo largo del eje y. |
| [set_XYFactor](./set_xyfactor/)(double) | Un factor que se utilizará para convertir las unidades más grandes a lo largo del eje y a las unidades más grandes a lo largo del eje x. |
| [set_YFormat](./set_yformat/)(const System::SharedPtr\<Measure::NumberFormatList\>\&) | Una matriz de formato numérico para la medición del cambio a lo largo del eje y. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
