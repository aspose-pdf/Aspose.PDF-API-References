---
title: "OptimizationOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que describe el algoritmo de optimización de documentos.<br/>            Una instancia de esta clase puede usarse como parámetro del método OptimizeResources()."
type: docs
weight: 20
url: /es/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

Clase que describe el algoritmo de optimización de documentos.<br/>            Una instancia de esta clase puede usarse como parámetro del método OptimizeResources().

El tipo OptimizationOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| OptimizationOptions() | Inicializa una nueva instancia de la clase OptimizationOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| link_duplcate_streams | Si esta bandera está establecida en true, se analizarán los flujos de recursos. Si se encuentran flujos duplicados (p. ej., si el contenido del flujo es igual), entonces esos flujos se almacenarán como un solo objeto. <br/>            Esto permite reducir el tamaño del documento en algunos casos (por ejemplo, cuando el mismo documento se concatenó varias veces). |
| allow_reuse_page_content | Si es true, el contenido de la página se reutilizará cuando el documento se optimice para páginas iguales. |
| remove_unused_streams | Si esta bandera está establecida en true, se verifica cada recurso en su uso. Si un recurso nunca se utiliza, entonces se elimina.<br/>            Esto puede reducir el tamaño del documento, por ejemplo cuando se extrajeron páginas del documento. |
| remove_unused_objects | Si esta bandera está establecida en true, se verificarán todos los objetos del documento y los objetos no utilizados (p. ej., objetos que no tienen ninguna referencia) se eliminarán del documento. |
| image_compression_options | Conjunto de opciones que describen si las imágenes en el documento serán comprimidas y los parámetros de la compresión. |
| compress_images | Si esta bandera se establece en true, las imágenes serán comprimidas en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
| resize_images | Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| image_quality | Especifica el nivel de compresión de la imagen cuando se usa la bandera CompressIamges. |
| max_resoultion | Especifica la resolución máxima de las imágenes. Si la imagen tiene una resolución más alta, será escalada. |
| unembed_fonts | Hacer que las fuentes no se incrusten si se establece en true. |
| subset_fonts | Las fuentes se convertirán en subconjuntos si se establece en true. |
| remove_private_info | Eliminar información privada (información de pieza de página). |
| image_encoding | Codificación de imagen que se utilizará. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| all() | Crea una estrategia de optimización con todas las opciones activadas.<br/>            Tenga en cuenta que solo se activan las opciones que no cambian ninguna funcionalidad del documento.<br/>            Por ejemplo, la compresión de imágenes y la desincrustación de fuentes no estarán habilitadas (y pueden incrustarse manualmente). |

### Ver también

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

