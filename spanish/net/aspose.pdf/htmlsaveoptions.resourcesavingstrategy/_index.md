---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: A esta propiedad se le puede asignar un delegado creado a partir de un método personalizado que implementa el procesamiento de recursos externos que se extrajo de un PDF y debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento, como guardar en un flujo o disco, se puede realizar en ese código personalizado y ese código personalizado debe devolver una ruta que se incorporará posteriormente al HTML generado en lugar de la ruta original supuesta a ese recurso de imagen. En tal caso, todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método proporcionado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento de este o aquel archivo, por alguna razón, debe ser realizado por el propio código del convertidor, no en el código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable de parámetros 'resourceSavingInfo'. Esto le señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor como si no hubiera ningún código personalizado externo.
type: docs
weight: 5730
url: /es/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## Delegado HtmlSaveOptions.ResourceSavingStrategy

A esta propiedad se le puede asignar un delegado creado a partir de un método personalizado que implementa el procesamiento de recursos externos (fuente o imagen) que se extrajo de un PDF y debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar en un flujo o disco) se puede realizar en ese código personalizado y ese código personalizado debe devolver una ruta (o cualquier otra cadena sin comillas) que se incorporará posteriormente al HTML generado en lugar de la ruta original supuesta a ese recurso de imagen. En tal caso, todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método proporcionado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento de este o aquel archivo, por alguna razón, debe ser realizado por el propio código del convertidor, no en el código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable de parámetros 'resourceSavingInfo'. Esto le señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor como si no hubiera ningún código personalizado externo.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | representa un conjunto de datos para el guardado de recursos |

### Valor de Retorno

debe devolver la URL al recurso guardado que se utilizará durante la generación de HTML

### Véase También

* clase [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)