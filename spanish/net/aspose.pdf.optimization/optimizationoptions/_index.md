---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Optimization.OptimizationOptions. Clase que describe el algoritmo de optimización de documentos. Una instancia de esta clase puede ser utilizada como parámetro del método OptimizeResources.
type: docs
weight: 7980
url: /es/net/aspose.pdf.optimization/optimizationoptions/
---
## Clase OptimizationOptions

Clase que describe el algoritmo de optimización de documentos. Una instancia de esta clase puede ser utilizada como parámetro del método OptimizeResources().

```csharp
public class OptimizationOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | El constructor por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Si es verdadero, el contenido de las páginas se reutilizará cuando el documento sea optimizado para páginas iguales. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Si esta bandera está configurada en `true`, los objetos Pdf se empaquetarán en flujos de objetos y se comprimirán para reducir el tamaño del archivo pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Conjunto de opciones que describen si las imágenes en el documento serán comprimidas y los parámetros de la compresión. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Codificación de imagen que se utilizará. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Si esta bandera está configurada en verdadero, se analizarán los flujos de recursos. Si se encuentran flujos duplicados (es decir, si el contenido del flujo es igual), entonces estos flujos se almacenarán como un solo objeto. Esto permite disminuir el tamaño del documento en algunos casos (por ejemplo, cuando el mismo documento se ha concatenado múltiples veces). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | Nivel de escaneo. Escaneos más profundos (valor más alto) tardan más, pero pueden producir archivos de resultado más pequeños. Valor predeterminado: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Especifica la resolución máxima de las imágenes. Si la imagen tiene una resolución más alta, se escalará. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Eliminar información privada (información de piezas de página). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Si esta bandera está configurada en verdadero, se comprobarán todos los objetos del documento y se eliminarán los objetos no utilizados (es decir, objetos que no tienen ninguna referencia) del documento. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Si esta bandera está configurada en verdadero, se comprueba el uso de cada recurso. Si un recurso nunca se utiliza, entonces se elimina. Esto puede disminuir el tamaño del documento, por ejemplo, cuando se han extraído páginas del documento. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Las fuentes se convertirán en subconjuntos si se establece en verdadero. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Hacer que las fuentes no estén incrustadas si se establece en verdadero. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Crea una estrategia de optimización con todas las opciones activadas. Tenga en cuenta que solo se activan las opciones que no cambian ninguna funcionalidad del documento. Es decir, la compresión de imágenes y la desincrustación de fuentes no se habilitarán (y se pueden incrustar manualmente). |

### Ver También

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)