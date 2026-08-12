---
title: "Aspose::Pdf::Optimization::OptimizationOptions clase"
linktitle: "OptimizationOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Optimization::OptimizationOptions. Clase que describe el algoritmo de optimización de documentos. Una instancia de esta clase puede usarse como parámetro del método OptimizeResources() en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class


Clase que describe el algoritmo de optimización de documentos. Una instancia de esta clase puede usarse como parámetro del método OptimizeResources().

```cpp
class OptimizationOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [All](./all/)() | Crea una estrategia de optimización con todas las opciones activadas. Tenga en cuenta que solo se activan las opciones que no cambian ninguna funcionalidad del documento. Por ejemplo, la compresión de imágenes y la desincorporación de fuentes no se habilitarán (y pueden incorporarse manualmente). |
| [get_AllowReusePageContent](./get_allowreusepagecontent/)() const | Si es verdadero, el contenido de la página se reutilizará cuando el documento se optimice para páginas iguales. |
|  | [get_CompressAllContentStreams](./get_compressallcontentstreams/)() const | Si se establece en **true** |

, todos los flujos de contenido de página sin comprimir se comprimirán usando el filtro FlateDecode durante [Document::OptimizeResources()](../../aspose.pdf/document/optimizeresources/). El valor predeterminado es **false**

para preservar la compatibilidad hacia atrás. |
| [get_CompressImages](./get_compressimages/)() | Si esta bandera se establece en verdadero, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
|  | [get_CompressObjects](./get_compressobjects/)() const | Si esta bandera se establece en **true** |

, los objetos [Pdf](../../aspose.pdf/) se empaquetarán en flujos de objetos y se comprimirán para reducir el tamaño del archivo pdf. |
| [get_ImageCompressionOptions](./get_imagecompressionoptions/)() const | Conjunto de opciones que describen si las imágenes en el documento se comprimirán y los parámetros de la compresión. |
| [get_ImageEncoding](./get_imageencoding/)() const | [Image](../../aspose.pdf/image/) codificación que se utilizará. |
| [get_ImageQuality](./get_imagequality/)() | Especifica el nivel de compresión de imagen cuando se usa la bandera CompressIamges. |
| [get_LinkDuplicateStreams](./get_linkduplicatestreams/)() const | Si esta bandera se establece en verdadero, los flujos de recursos se analizarán. Si se encuentran flujos duplicados (p. ej., si el contenido del flujo es igual), entonces esos flujos se almacenarán como un solo objeto. Esto permite reducir el tamaño del documento en algunos casos (por ejemplo, cuando el mismo documento se concatenó varias veces). |
| [get_MaxResoultion](./get_maxresoultion/)() | Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, se escalará. |
| [get_RemovePrivateInfo](./get_removeprivateinfo/)() const | Eliminar información privada (información de fragmentos de página). |
| [get_RemoveUnusedObjects](./get_removeunusedobjects/)() const | Si esta bandera se establece en verdadero, todos los objetos del documento se comprobarán y los objetos no utilizados (p. ej., objetos que no tienen ninguna referencia) se eliminarán del documento. |
| [get_RemoveUnusedStreams](./get_removeunusedstreams/)() const | Si esta bandera se establece en verdadero, cada recurso se verifica en su uso. Si un recurso nunca se utiliza, entonces se elimina. Esto puede reducir el tamaño del documento, por ejemplo, cuando se extrajeron páginas del documento. |
| [get_ResizeImages](./get_resizeimages/)() | Si esta bandera se establece en verdadero y CompressImages es verdadero, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| [get_SubsetFonts](./get_subsetfonts/)() const | Las fuentes se convertirán en subconjuntos si se establece en verdadero. |
| [get_UnembedFonts](./get_unembedfonts/)() const | No incruste fuentes si se establece en verdadero. |
| [OptimizationOptions](./optimizationoptions/)() |  |
| [set_AllowReusePageContent](./set_allowreusepagecontent/)(bool) | Si es verdadero, el contenido de la página se reutilizará cuando el documento se optimice para páginas iguales. |
|  | [set_CompressAllContentStreams](./set_compressallcontentstreams/)(bool) | Si se establece en **true** |

, todos los flujos de contenido de página sin comprimir se comprimirán usando el filtro FlateDecode durante [Document::OptimizeResources()](../../aspose.pdf/document/optimizeresources/). El valor predeterminado es **false**

para preservar la compatibilidad hacia atrás. |
| [set_CompressImages](./set_compressimages/)(bool) | Si esta bandera se establece en verdadero, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
|  | [set_CompressObjects](./set_compressobjects/)(bool) | Si esta bandera se establece en **true** |

, los objetos [Pdf](../../aspose.pdf/) se empaquetarán en flujos de objetos y se comprimirán para reducir el tamaño del archivo pdf. |
| [set_ImageEncoding](./set_imageencoding/)(Aspose::Pdf::Optimization::ImageEncoding) | [Image](../../aspose.pdf/image/) codificación que se utilizará. |
| [set_ImageQuality](./set_imagequality/)(int32_t) | Especifica el nivel de compresión de imagen cuando se usa la bandera CompressIamges. |
| [set_LinkDuplicateStreams](./set_linkduplicatestreams/)(bool) | Si esta bandera se establece en verdadero, los flujos de recursos se analizarán. Si se encuentran flujos duplicados (p. ej., si el contenido del flujo es igual), entonces esos flujos se almacenarán como un solo objeto. Esto permite reducir el tamaño del documento en algunos casos (por ejemplo, cuando el mismo documento se concatenó varias veces). |
| [set_MaxResoultion](./set_maxresoultion/)(int32_t) | Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, se escalará. |
| [set_RemovePrivateInfo](./set_removeprivateinfo/)(bool) | Eliminar información privada (información de fragmentos de página). |
| [set_RemoveUnusedObjects](./set_removeunusedobjects/)(bool) | Si esta bandera se establece en verdadero, todos los objetos del documento se comprobarán y los objetos no utilizados (p. ej., objetos que no tienen ninguna referencia) se eliminarán del documento. |
| [set_RemoveUnusedStreams](./set_removeunusedstreams/)(bool) | Si esta bandera se establece en verdadero, cada recurso se verifica en su uso. Si un recurso nunca se utiliza, entonces se elimina. Esto puede reducir el tamaño del documento, por ejemplo, cuando se extrajeron páginas del documento. |
| [set_ResizeImages](./set_resizeimages/)(bool) | Si esta bandera se establece en verdadero y CompressImages es verdadero, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| [set_SubsetFonts](./set_subsetfonts/)(bool) | Las fuentes se convertirán en subconjuntos si se establece en verdadero. |
| [set_UnembedFonts](./set_unembedfonts/)(bool) | No incruste fuentes si se establece en verdadero. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Optimization](../)
* Library [Aspose.PDF for C++](../../)
