---
title: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El resultado de la conversión puede contener una o varias páginas HTML (que también pueden referenciar archivos externos como imágenes o fuentes). Puedes asignar a esta propiedad un delegado creado a partir de."
type: docs
weight: 2110
url: /es/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy

```
public abstract static class HtmlSaveOptions.HtmlPageMarkupSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

El resultado de la conversión puede contener una o varias páginas HTML (que también pueden referenciar archivos externos como imágenes o fuentes). Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente el procesamiento de la página HTML obtenida (el propio HTML) que se creó durante la conversión. En tal caso, el procesamiento (como guardar en un flujo o disco) puede realizarse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar el marcado de la página HTML deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del conversor no se utilizará. Si el procesamiento para este u otro caso, por alguna razón, debe ser realizado por el propio código del conversor y no por código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'htmlSavingInfo': indica al conversor que todos los pasos necesarios para procesar ese recurso deben realizarse en el conversor mismo, de la misma manera que si no hubiera ningún código externo de guardado personalizado.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlPageMarkupSavingStrategy](#HtmlPageMarkupSavingStrategy--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [beginInvoke](#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-) | Método interno beginInvoke |
| [endInvoke](#endInvoke-com.aspose.ms.System.IAsyncResult-) | Método interno endInvoke |
| [invoke](#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-) | Método invocado |

### HtmlPageMarkupSavingStrategy {#HtmlPageMarkupSavingStrategy--}
```
public HtmlPageMarkupSavingStrategy()
```



### beginInvoke {#beginInvoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
Método interno beginInvoke

### endInvoke {#endInvoke-com.aspose.ms.System.IAsyncResult-}
Método interno endInvoke

### invoke {#invoke-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo-}
Método invocado
