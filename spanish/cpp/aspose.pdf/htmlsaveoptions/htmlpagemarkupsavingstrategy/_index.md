---
title: "Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingStrategy typedef"
linktitle: "HtmlPageMarkupSavingStrategy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingStrategy typedef. El resultado de la conversión puede contener una o varias páginas HTML (que también pueden referenciar archivos externos como imágenes o fuentes). Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente el procesamiento de la página HTML obtenida (el propio HTML) que se creó durante la conversión. En tal caso, el procesamiento (como guardar en un flujo o en disco) puede realizarse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar el marcado de la página HTML deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento para este u otro caso, por alguna razón, debe ser realizado por el código del convertidor mismo, no en código personalizado, establezca en el código personalizado la bandera ''CustomProcessingCancelled'' de la variable del parámetro ''htmlSavingInfo'': indica al convertidor que todos los pasos necesarios para procesar ese recurso deben realizarse en el propio convertidor de la misma manera que si no hubiera ningún código de guardado personalizado externo en C++."
type: docs
weight: 4900
url: /es/cpp/aspose.pdf/htmlsaveoptions/htmlpagemarkupsavingstrategy/
---
## HtmlPageMarkupSavingStrategy typedef


El resultado de la conversión puede contener una o varias páginas HTML (que también pueden referenciar archivos externos como imágenes o fuentes). Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implemente el procesamiento de la página HTML obtenida (el propio HTML) que se creó durante la conversión. En tal caso, el procesamiento (como guardar en un flujo o en disco) puede realizarse en ese código personalizado. En tal caso, todas las acciones necesarias para guardar el marcado de la página HTML deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento para este u otro caso, por alguna razón, debe ser realizado por el código del convertidor mismo, no en el código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'htmlSavingInfo': indica al convertidor que todos los pasos necesarios para procesar ese recurso deben realizarse en el propio convertidor de la misma manera que si no hubiera ningún código de guardado externo personalizado.

```cpp
using Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingStrategy =  System::MulticastDelegate<void(const System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::HtmlPageMarkupSavingInfo>&)>
```


## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
