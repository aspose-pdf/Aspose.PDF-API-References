---
title: "Enumeración System::Drawing::CopyPixelOperation"
linktitle: "CopyPixelOperation"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Enumeración System::Drawing::CopyPixelOperation. Especifica cómo se combina el color de origen en una operación de copia de píxeles con el color de destino para obtener un color final en C++."
type: docs
weight: 3000
url: /es/cpp/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum


Especifica cómo se combina el color de origen en una operación de copia de píxeles con el color de destino para obtener un color final.

```cpp
enum class CopyPixelOperation
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NoMirrorBitmap | n/a | El mapa de bits no está reflejado. |
| Blackness | 66 | La región de destino se rellena usando el color con índice 0 en la paleta física. |
| NotSourceErase | 1114278 | Los colores de origen y destino se combinan con OR y el color resultante se invierte. |
| NotSourceCopy | 3342344 | La región de origen se invierte y luego se copia al destino. |
| SourceErase | 4457256 | Los colores invertidos de la región de destino se combinan mediante AND con los colores de la región de origen. |
| DestinationInvert | 5570569 | La región de destino se invierte. |
| PatInvert | 5898313 | Los colores del pincel actualmente seleccionado en el contexto del dispositivo de destino se combinan mediante XOR con los colores del destino. |
| SourceInvert | 6684742 | Los colores de las regiones de origen y destino se combinan mediante XOR. |
| SourceAnd | 8913094 | Los colores de las regiones de origen y destino se combinan mediante AND. |
| MergePaint | 12255782 | Los colores de la región de origen invertida se combinan mediante OR con los colores de la región de destino. |
| MergeCopy | 12583114 | Los colores de la región de origen se combinan mediante AND con los colores del pincel seleccionado del contexto del dispositivo de destino. |
| SourceCopy | 13369376 | La región de origen se copia directamente a la región de destino. |
| SourcePaint | 15597702 | Los colores de las regiones de origen y destino se combinan mediante OR. |
| PatCopy | 15728673 | El pincel actualmente seleccionado en el contexto de dispositivo de destino se copia al mapa de bits de destino. |
| PatPaint | 16452105 | Los colores del pincel actualmente seleccionado en el contexto de dispositivo de destino se combinan mediante OR con los colores de la región de origen invertida. El resultado de esta operación se combina mediante OR con los colores de la región de destino. |
| Whiteness | 16711778 | La región de destino se rellena usando el color con índice 1 en la paleta física. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) que están superpuestos sobre la ventana de la aplicación se incluyen en la imagen resultante. |

## Ver también

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
