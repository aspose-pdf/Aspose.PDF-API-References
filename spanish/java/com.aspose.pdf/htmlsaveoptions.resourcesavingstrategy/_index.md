---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "En esta propiedad puedes asignar un delegado creado a partir de un método personalizado que implemente el procesamiento del recurso externo (Fuente o Imagen) que fue extraído del PDF y debe guardarse."
type: docs
weight: 2150
url: /es/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

A esta propiedad puedes asignar un delegado creado a partir de un método personalizado que implementa el procesamiento de un recurso externo (Fuente o Imagen) que fue extraído del PDF y debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar en un flujo o en disco) puede realizarse en ese código personalizado y ese código personalizado debe devolver una ruta (o cualquier otra cadena sin comillas) que luego se incorporará al HTML generado en lugar de la ruta original supuesta para ese recurso de imagen. En tal caso, todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método suministrado, porque guardar el resultado en el código del convertidor no se utilizará. Si el procesamiento de este u otro archivo por alguna razón debe ser realizado por el código del convertidor mismo, no en el código personalizado, por favor establece en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'resourceSavingInfo'. Señala al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor como si no hubiera ningún código personalizado externo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | Método invocado |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
Método invocado
