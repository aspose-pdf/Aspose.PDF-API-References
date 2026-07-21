---
title: "Aspose::Pdf::Text::ParagraphAbsorber::set_SectionsSearchDepth método"
linktitle: "set_SectionsSearchDepth"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::ParagraphAbsorber::set_SectionsSearchDepth método. Establece el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos más finos de la estructura. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas) en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.text/paragraphabsorber/set_sectionssearchdepth/
---
## ParagraphAbsorber::set_SectionsSearchDepth method


Establece el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos de estructura más finos. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas).

```cpp
void Aspose::Pdf::Text::ParagraphAbsorber::set_SectionsSearchDepth(int32_t value)
```

## Observaciones


Incrementar este valor puede provocar una ligera disminución del rendimiento sin cambios visibles en el resultado de la búsqueda. Disminuir este valor puede conducir a una determinación incorrecta de los párrafos en las secciones. No recomendamos establecer un valor inferior al predeterminado si no desea obtener solo los elementos 'básicos' de la estructura de la página.
## Ver también

* Class [ParagraphAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
