---
title: "Aspose::Pdf::Annotations::PolyAnnotation clase"
linktitle: "PolyAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Annotations::PolyAnnotation. Clase base abstracta para anotaciones poligonales en C++."
type: docs
weight: 8400
url: /es/cpp/aspose.pdf.annotations/polyannotation/
---
## PolyAnnotation class


Clase base abstracta para anotaciones poligonales.

```cpp
class PolyAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Actualiza los puntos en Vertices, de acuerdo con la transformación matricial. |
| [get_EndingStyle](./get_endingstyle/)() | Obtiene el estilo del final de línea secundario. |
| [get_Intent](./get_intent/)() | Obtiene la intención de la anotación de polígono o polilínea. |
| [get_InteriorColor](./get_interiorcolor/)() | Obtiene el color interior con el que rellenar los finales de línea de la anotación. |
| [get_Measure](./get_measure/)() | [Measure](../measure/) unidades especificadas para esta anotación. |
| [get_StartingStyle](./get_startingstyle/)() | Obtiene el estilo del final de línea primario. |
| [get_Vertices](./get_vertices/)() | Obtiene una matriz de puntos que representa las coordenadas horizontales y verticales de cada vértice. |
| [set_EndingStyle](./set_endingstyle/)(LineEnding) | Establece el estilo del final de línea secundario. |
| [set_Intent](./set_intent/)(PolyIntent) | Establece la intención de la anotación de polígono o polilínea. |
| [set_InteriorColor](./set_interiorcolor/)(const System::SharedPtr\<Aspose::Pdf::Color\>\&) | Establece el color interior con el que rellenar los finales de línea de la anotación. |
| [set_Measure](./set_measure/)(const System::SharedPtr\<Aspose::Pdf::Annotations::Measure\>\&) | [Measure](../measure/) unidades especificadas para esta anotación. |
| [set_StartingStyle](./set_startingstyle/)(LineEnding) | Establece el estilo del final de línea primario. |
| [set_Vertices](./set_vertices/)(const System::ArrayPtr\<System::SharedPtr\<Point\>\>\&) | Establece una matriz de puntos que representa las coordenadas horizontales y verticales de cada vértice. |
## Ver también

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
