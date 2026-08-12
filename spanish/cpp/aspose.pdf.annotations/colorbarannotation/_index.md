---
title: "Aspose::Pdf::Annotations::ColorBarAnnotation class"
linktitle: "ColorBarAnnotation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::ColorBarAnnotation class. Clase que representa la anotación ColorBarAnnotation. La propiedad Color se ignora, en su lugar se usa el color ColorsOfCMYK. Al crearla, la proporción de ancho y alto determina la orientación de la anotación: horizontal o vertical. Luego, verifica que el rectángulo de la anotación esté fuera del TrimBox y, si no lo está, se desplaza a la ubicación más cercana fuera del TrimBox, teniendo en cuenta la orientación de la anotación. Es posible reducir el ancho (alto) para que la anotación quepa fuera del TrimBox. Si no hay espacio para el diseño, el ancho/alto puede establecerse en cero (en este caso, la anotación está presente en la página, pero no se muestra) en C++."
type: docs
weight: 1900
url: /es/cpp/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class


Clase que representa la anotación [ColorBarAnnotation](./). La propiedad [Color](../../aspose.pdf/color/) se ignora, en su lugar se usa el color [ColorsOfCMYK](../colorsofcmyk/). Al crearla, la proporción de ancho y alto determina la orientación de la anotación: horizontal o vertical. Luego, verifica que el rectángulo de la anotación esté fuera del TrimBox y, si no lo está, se desplaza a la ubicación más cercana fuera del TrimBox, teniendo en cuenta la orientación de la anotación. Es posible reducir el ancho (alto) para que la anotación quepa fuera del TrimBox. Si no hay espacio para el diseño, el ancho/alto puede establecerse en cero (en este caso, la anotación está presente en la página, pero no se muestra).

```cpp
class ColorBarAnnotation : public Aspose::Pdf::Annotations::PrinterMarkAnnotation
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Acepta un objeto visitante para procesar la anotación. |
| [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) override | Actualiza los parámetros y la apariencia, de acuerdo con la transformación de la matriz y moviendo fuera del TrimBox si es necesario. |
| [ColorBarAnnotation](./colorbarannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, ColorsOfCMYK) | Crea una nueva anotación ColorBar en la página especificada. |
| [get_AnnotationType](./get_annotationtype/)() override | Obtiene el tipo de anotación. |
| [get_ColorOfCMYK](./get_colorofcmyk/)() const | Obtiene el color (uno de cian, magenta, amarillo, negro) con el que se dibuja la anotación. |
| [set_ColorOfCMYK](./set_colorofcmyk/)(ColorsOfCMYK) | Establece el color (uno de cian, magenta, amarillo, negro) con el que se dibuja la anotación. |
## Ver también

* Class [PrinterMarkAnnotation](../printermarkannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
