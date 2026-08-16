---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa la anotación ColorBarAnnotation. La propiedad Color se ignora, en su lugar se usa el color ColorsOfCMYK. Al crearla, la relación entre ancho y alto determina la orientación."
type: docs
weight: 680
url: /es/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Clase que representa la anotación ColorBarAnnotation. La propiedad Color se ignora, en su lugar se utiliza el color ColorsOfCMYK. Al crearla, la proporción de ancho y alto determina la orientación de la anotación: horizontal o vertical. A continuación, verifica que el rectángulo de la anotación esté fuera del TrimBox y, si no lo está, se desplaza a la ubicación más cercana fuera del TrimBox, teniendo en cuenta la orientación de la anotación. Es posible reducir el ancho (alto) para que la anotación encaje fuera del TrimBox. Si no hay espacio para el diseño, el ancho/alto puede establecerse en cero (en este caso, la anotación está presente en la página, pero no se muestra).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nueva anotación ColorBar en la página especificada. Predeterminado ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Crea una nueva anotación ColorBar en la página especificada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepta un objeto visitante para procesar la anotación. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Actualiza los parámetros y la apariencia, de acuerdo con la transformación de la matriz y el desplazamiento fuera del TrimBox si es necesario. |
| [getAnnotationType](#getAnnotationType--) | Obtiene el tipo de anotación. |
| [getColorOfCMYK](#getColorOfCMYK--) | Obtiene o establece el color (uno de cian, magenta, amarillo, negro) con el que se dibuja la anotación. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Obtiene o establece el color (uno de cian, magenta, amarillo, negro) con el que se dibuja la anotación. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nueva anotación ColorBar en la página especificada. Predeterminado ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Crea una nueva anotación ColorBar en la página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepta un objeto visitante para procesar la anotación.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Actualiza los parámetros y la apariencia, de acuerdo con la transformación de la matriz y el desplazamiento fuera del TrimBox si es necesario.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtiene el tipo de anotación.

**Returns:**
valor int

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Obtiene o establece el color (uno de cian, magenta, amarillo, negro) con el que se dibuja la anotación.

**Returns:**
Elemento ColorsOfCMYK

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Obtiene o establece el color (uno de cian, magenta, amarillo, negro) con el que se dibuja la anotación.
