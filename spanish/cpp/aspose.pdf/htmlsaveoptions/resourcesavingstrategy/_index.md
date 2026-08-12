---
title: "Aspose::Pdf::HtmlSaveOptions::ResourceSavingStrategy typedef"
linktitle: "ResourceSavingStrategy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::HtmlSaveOptions::ResourceSavingStrategy typedef. A esta propiedad puede asignarse un delegado creado a partir de un método personalizado que implemente el procesamiento del recurso externo (Fuente o Imagen) que se extrajo del PDF y debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar en un flujo o en disco) puede realizarse en ese código personalizado y ese código debe devolver la ruta (o cualquier otra cadena sin comillas) que posteriormente se incorporará al HTML generado en lugar de la ruta original supuesta para ese recurso de imagen. En tal caso, todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del conversor no se utilizará. Si el procesamiento de este u otro archivo por alguna razón debe ser realizado por el código del conversor, no por el código personalizado, establezca en el código personalizado la bandera ''CustomProcessingCancelled'' de la variable del parámetro ''resourceSavingInfo''. Señala al conversor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio conversor como si no existiera ningún código personalizado externo en C++."
type: docs
weight: 5000
url: /es/cpp/aspose.pdf/htmlsaveoptions/resourcesavingstrategy/
---
## ResourceSavingStrategy typedef


A esta propiedad puede asignar un delegado creado a partir de un método personalizado que implemente el procesamiento de un recurso externo (fuente o imagen) que se extrajo del PDF y debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar en un flujo o en disco) puede realizarse en ese código personalizado y dicho código debe devolver la ruta (u otra cadena sin comillas) que posteriormente se incorporará al HTML generado en lugar de la ruta original supuesta del recurso de imagen. En tal caso, todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento para este u otro archivo, por alguna razón, debe ser realizado por el código del convertidor mismo, no en el código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'resourceSavingInfo'. Indica al convertidor que todos los pasos necesarios para procesar ese recurso deben realizarse en el propio convertidor como si no hubiera ningún código externo personalizado.

```cpp
using Aspose::Pdf::HtmlSaveOptions::ResourceSavingStrategy =  System::MulticastDelegate<System::String(const System::SharedPtr<Aspose::Pdf::SaveOptions::ResourceSavingInfo>&)>
```


## Ver también

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
