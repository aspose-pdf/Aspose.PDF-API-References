---
title: "Typedef Aspose::Pdf::SvgSaveOptions::EmbeddedImagesSavingStrategy"
linktitle: "EmbeddedImagesSavingStrategy"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::SvgSaveOptions::EmbeddedImagesSavingStrategy typedef. En una propiedad de este tipo puedes asignar un delegado creado a partir de un método personalizado que implemente el procesamiento del guardado externo de la imagen extraída del SVG generado a partir de PDF y que debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar manualmente en un flujo o en disco) puede realizarse en ese código personalizado y ese código debe devolver la ruta (o cualquier otra cadena sin comillas) que será incorporada posteriormente en el SVG generado en lugar de la ruta original supuesta para ese recurso de imagen. En tal caso, todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento de este u otro archivo por alguna razón debe ser realizado por el propio código del convertidor, no por el código personalizado, por favor establece en el código personalizado la bandera ''CustomProcessingCancelled'' de la variable del parámetro ''imageSavingInfo''. Señala al convertidor que todos los pasos necesarios para procesar ese recurso deben realizarse en el propio convertidor como si no existiera ningún código personalizado externo en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/svgsaveoptions/embeddedimagessavingstrategy/
---
## EmbeddedImagesSavingStrategy typedef


Para una propiedad de este tipo puedes asignar un delegado creado a partir de un método personalizado que implemente el procesamiento del guardado externo de la imagen extraída del SVG generado a partir del PDF y que debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como el guardado propio en un flujo o en disco) puede realizarse en ese código personalizado y ese código debe devolver una ruta (o cualquier otra cadena sin comillas) que luego se incorporará al SVG generado en lugar de la ruta original supuesta para ese recurso de imagen. En este caso, todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento de este o aquel archivo por alguna razón debe ser realizado por el código del convertidor mismo, no en el código personalizado, por favor establece en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo'. Señala al convertidor que todos los pasos necesarios para procesar ese recurso deben realizarse en el propio convertidor como si no existiera ningún código personalizado externo.

```cpp
using Aspose::Pdf::SvgSaveOptions::EmbeddedImagesSavingStrategy =  System::MulticastDelegate<System::String(const System::SharedPtr<Aspose::Pdf::SvgSaveOptions::SvgImageSavingInfo>&)>
```

## Ver también

* Class [SvgSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
