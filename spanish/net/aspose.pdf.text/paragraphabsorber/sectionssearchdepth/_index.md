---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de ParagraphAbsorber. Obtiene o establece el valor que indica cuántas veces se realizarán búsquedas secuenciales para elementos más finos de la estructura. La profundidad de búsqueda predeterminada es 3. Esto significa tres búsquedas para secciones divididas horizontalmente y tres búsquedas para las divididas verticalmente.
type: docs
weight: 50
url: /es/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## Propiedad ParagraphAbsorber.SectionsSearchDepth

Obtiene o establece el valor que indica cuántas veces se realizarán búsquedas secuenciales para elementos más finos de la estructura. La profundidad de búsqueda predeterminada es 3. Esto significa tres búsquedas para secciones divididas horizontalmente (encabezados, párrafos, etc.) y tres búsquedas para las divididas verticalmente (columnas).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Observaciones

Aumentar este valor puede llevar a una ligera disminución del rendimiento sin cambios visibles en el resultado de la búsqueda. Disminuir este valor puede llevar a una determinación incorrecta de los párrafos en las secciones. No recomendamos establecer un valor menor que el predeterminado si no desea obtener solo elementos 'toscos' de la estructura de la página.

### Véase también

* clase [ParagraphAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblado [Aspose.PDF](../../../)