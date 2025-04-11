---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicalPdfComparer. Compara documentos gráficamente. El resultado de la comparación se coloca en imágenes
type: docs
weight: 50
url: /es/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## Método GraphicalPdfComparer.CompareDocumentsToImages

Compara documentos gráficamente. El resultado de la comparación se coloca en imágenes.

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | Document | El primer documento a comparar. |
| document2 | Document | El segundo documento a comparar. |
| targetDirectory | String | El directorio para guardar los resultados de la comparación. |
| fileNamePrefix | String | El prefijo del nombre de las imágenes. |
| imageFormat | ImageFormat | El formato de imagen para guardar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Si las páginas que se comparan son de diferentes tamaños. Si targetDirectory es nulo o una cadena vacía. Si fileNamePrefix es nulo o una cadena vacía. |

### Ver También

* clase [Document](../../../aspose.pdf/document/)
* clase [GraphicalPdfComparer](../)
* espacio de nombres [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* ensamblado [Aspose.PDF](../../../)