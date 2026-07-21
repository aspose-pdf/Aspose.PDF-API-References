---
title: "Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth método"
linktitle: "get_SectionsSearchDepth"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth método. Obtiene el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos más finos de la estructura. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas de secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas de secciones divididas verticalmente (columnas) en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf.text/paragraphabsorber/get_sectionssearchdepth/
---
## ParagraphAbsorber::get_SectionsSearchDepth method


Obtiene el valor que indica cuántas veces se realizarán búsquedas secuenciales de elementos de estructura más finos. La profundidad de búsqueda predeterminada es 3. Significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas).

```cpp
int32_t Aspose::Pdf::Text::ParagraphAbsorber::get_SectionsSearchDepth() const
```

## Observaciones


Incrementar este valor puede provocar una ligera disminución del rendimiento sin cambios visibles en el resultado de la búsqueda. Disminuir este valor puede conducir a una determinación incorrecta de los párrafos en las secciones. No recomendamos establecer un valor inferior al predeterminado si no desea obtener solo los elementos 'básicos' de la estructura de la página.
## Ver también

* Class [ParagraphAbsorber](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
