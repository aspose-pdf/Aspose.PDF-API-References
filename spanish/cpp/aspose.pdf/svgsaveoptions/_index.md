---
title: "Clase Aspose::Pdf::SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::SvgSaveOptions. Opciones de guardado para exportar al formato SVG en C++."
type: docs
weight: 17600
url: /es/cpp/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class


Opciones de guardado para exportar al formato SVG.

```cpp
class SvgSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Nested classes

* Class [SvgImageSavingInfo](./svgimagesavinginfo/)
## Enums

| Enumeración | Descripción |
| --- | --- |
| [SvgExternalImageType](./svgexternalimagetype/) | Enumera los tipos posibles de archivos de imagen que pueden guardarse como recursos externos durante la conversión de [Pdf](../) a SVG. |
## Métodos

| Método | Descripción |
| --- | --- |
| [SvgSaveOptions](./svgsaveoptions/)() | Constructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [EmbeddedImagesSavingStrategy](./embeddedimagessavingstrategy/) | Para una propiedad de este tipo puedes asignar un delegado creado a partir de un método personalizado que implemente el procesamiento del guardado externo de la imagen extraída del SVG generado a partir del PDF y que debe guardarse como recurso externo durante la conversión de PDF a HTML. En tal caso, el procesamiento (como el guardado propio en un flujo o en disco) puede realizarse en ese código personalizado y ese código debe devolver una ruta (o cualquier otra cadena sin comillas) que luego se incorporará al SVG generado en lugar de la ruta original supuesta para ese recurso de imagen. En este caso, todas las acciones necesarias para guardar la imagen deben llevarse a cabo en el código del método suministrado, porque el guardado del resultado en el código del convertidor no se utilizará. Si el procesamiento de este o aquel archivo por alguna razón debe ser realizado por el código del convertidor mismo, no en el código personalizado, por favor establece en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo'. Señala al convertidor que todos los pasos necesarios para procesar ese recurso deben realizarse en el propio convertidor como si no existiera ningún código personalizado externo. |
## Ver también

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
