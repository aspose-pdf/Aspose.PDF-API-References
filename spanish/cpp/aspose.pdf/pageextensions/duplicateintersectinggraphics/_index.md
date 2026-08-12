---
title: "Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics método"
linktitle: "DuplicateIntersectingGraphics"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics método. Encuentra todos los elementos gráficos vectoriales que intersectan con la región especificada y crea sus copias con desplazamiento respecto a las posiciones originales en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf/pageextensions/duplicateintersectinggraphics/
---
## PageExtensions::DuplicateIntersectingGraphics method


Encuentra todos los elementos gráficos vectoriales que intersectan con la región especificada y crea sus copias con desplazamiento respecto a las posiciones originales.

```cpp
static void Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics(const System::SharedPtr<Page> &page, const System::SharedPtr<Rectangle> &region, double deltaX, double deltaY)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| página | const System::SharedPtr\<Page\>\& | La página donde se buscan y copian los elementos gráficos. |
| región | const System::SharedPtr\<Rectangle\>\& | La región rectangular para buscar elementos intersectantes. |
| deltaX | double | Desplazamiento a lo largo del eje X para los elementos copiados. |
| deltaY | double | Desplazamiento a lo largo del eje Y para los elementos copiados. |
## Observaciones



Este método funciona solo con gráficos vectoriales (líneas, formas, curvas de Bézier, etc.). Las imágenes rasterizadas y otros tipos de elementos no se procesan. Cada elemento copiado se desplazará por los valores dx y dy especificados respecto a su posición original. Los elementos originales permanecen sin cambios.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [Rectangle](../../rectangle/)
* Class [PageExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
