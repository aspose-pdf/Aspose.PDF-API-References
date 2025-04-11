---
title: GraphicalPdfComparer.ComparePagesToImage
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Compara páginas gráficamente. El resultado de la comparación se coloca en una imagen
type: docs
weight: 70
url: /es/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## Método GraphicalPdfComparer.ComparePagesToImage

Compara páginas gráficamente. El resultado de la comparación se coloca en una imagen.

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page1 | Page | La primera página a comparar. |
| page2 | Page | La segunda página a comparar. |
| resultImagePath | String | La ruta al archivo de imagen de destino. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Si las páginas que se comparan son de diferentes tamaños. Si resultImagePath es nulo o una cadena vacía. Hay un formato de imagen de guardado desconocido. |

### Ver También

* clase [Page](../../../aspose.pdf/page/)
* clase [GraphicalPdfComparer](../)
* espacio de nombres [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* ensamblaje [Aspose.PDF](../../../)