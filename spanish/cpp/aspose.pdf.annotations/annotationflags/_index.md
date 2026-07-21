---
title: "Aspose::Pdf::Annotations::AnnotationFlags enumeración"
linktitle: "AnnotationFlags"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Annotations::AnnotationFlags enumeración. Un conjunto de indicadores que especifica varias características de la anotación en C++."
type: docs
weight: 12100
url: /es/cpp/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enum


Un conjunto de indicadores que especifican diversas características de la anotación.

```cpp
enum class AnnotationFlags
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Predeterminado | 0 | Valor predeterminado. |
| Invisible | 1 | Si está activado, no muestre la anotación si no pertenece a uno de los tipos de anotación estándar y no hay un controlador de anotaciones disponible. Si está desactivado, muestre dicha anotación desconocida utilizando un flujo de apariencia especificado por su diccionario de apariencia, si lo hay. |
| Oculto | 2 | Si está activado, no muestre ni imprima la anotación ni permita que interactúe con el usuario, independientemente de su tipo de anotación o de si hay un controlador de anotaciones disponible. En casos donde el espacio en pantalla es limitado, la capacidad de ocultar y mostrar anotaciones de forma selectiva puede usarse en combinación con flujos de apariencia para mostrar información auxiliar emergente similar en función a los sistemas de ayuda en línea. |
| Print | 4 | Si está activado, imprima la anotación cuando se imprima la página. Si está desactivado, nunca imprima la anotación, independientemente de si se muestra en pantalla. Esto puede ser útil, por ejemplo, para anotaciones que representan botones pulsables interactivos, los cuales no tendrían un propósito significativo en la página impresa. |
| NoZoom | 8 | Si está activado, no escale la apariencia de la anotación para que coincida con la ampliación de la página. La ubicación de la anotación en la página (definida por la esquina superior izquierda de su rectángulo de anotación) permanece fija, independientemente de la ampliación de la página. |
| NoRotate | 16 | Si está activado, no rote la apariencia de la anotación para que coincida con la rotación de la página. La esquina superior izquierda del rectángulo de anotación permanece en una posición fija en la página, independientemente de la rotación de la página. |
| NoView | 32 | Si está activado, no muestre la anotación en la pantalla ni permita que interactúe con el usuario. La anotación puede imprimirse (según la configuración de la bandera Print) pero debe considerarse oculta a efectos de la visualización en pantalla y la interacción del usuario. |
| ReadOnly | 64 | Si está activado, no permita que la anotación interactúe con el usuario. La anotación puede mostrarse o imprimirse (según la configuración de las banderas NoView y Print) pero no debe responder a clics del ratón ni cambiar su apariencia en respuesta a movimientos del ratón. Esta bandera se ignora para anotaciones de tipo widget; su función está subsumida por la bandera ReadOnly del campo de formulario asociado. |
| Locked | 128 | Si está activado, no permita que la anotación sea eliminada ni que sus propiedades (incluyendo posición y tamaño) sean modificadas por el usuario. Sin embargo, esta bandera no restringe los cambios en el contenido de la anotación, como el valor de un campo de formulario. |
| ToggleNoView | 256 | Si está activado, invierta la interpretación de la bandera NoView para ciertos eventos. Un uso típico es tener una anotación que aparece solo cuando el cursor del ratón se mantiene sobre ella. |
| LockedContents | 512 | Si está establecido, no permita que el contenido de la anotación sea modificado por el usuario. Esta bandera no restringe la eliminación de la anotación ni los cambios en otras propiedades de la anotación, como la posición y el tamaño. |

## Ver también

* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
