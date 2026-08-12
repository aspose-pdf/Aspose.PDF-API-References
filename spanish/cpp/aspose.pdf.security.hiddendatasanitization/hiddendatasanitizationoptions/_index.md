---
title: "Clase Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Security::HiddenDataSanitization::HiddenDataSanitizationOptions. Representa las opciones de configuración para la sanitización de datos ocultos dentro de un documento en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.security.hiddendatasanitization/hiddendatasanitizationoptions/
---
## HiddenDataSanitizationOptions class


Representa las opciones de configuración para sanitizar datos ocultos dentro de un documento.

```cpp
class HiddenDataSanitizationOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [All](./all/)() | Crea una nueva instancia de la clase [HiddenDataSanitizationOptions](./) con todas las opciones configuradas para la sanitización. Esto incluye habilitar la eliminación de anotaciones, JavaScript, metadatos, adjuntos, índice de búsqueda, información privada, aplanado de formularios y capas, mientras se deshabilita la opción de convertir páginas a imágenes. Configuraciones opcionales como [ImageCompressionOptions](../) o [ConvertPagesToImages](../) pueden modificarse manualmente después de obtener la instancia, ya que no están activas por defecto. |
| [get_ConvertPagesToImages](./get_convertpagestoimages/)() const | Obtiene la opción de convertir páginas a imágenes. Si esta opción está habilitada, la opción ImageCompressionOptions será ignorada. La opción debe habilitarse manualmente al usar el método [All](./all/) si es requerida. La conversión de páginas a imágenes se realizará después de limpiar los datos ocultos principales, lo cual está controlado por otras opciones. |
| [get_FlattenForms](./get_flattenforms/)() const | Obtiene un valor que indica si los formularios del documento deben aplanarse durante el proceso de sanitización. Aplanar formularios convierte los campos interactivos en contenido estático, haciéndolos no editables o rellenables. |
| [get_FlattenLayers](./get_flattenlayers/)() const | Obtiene la opción de aplanar las capas en el documento PDF. Cuando está habilitada, todas las capas del documento se fusionan en una sola capa, eliminando su estructura separada. Esta opción es útil para sanitizar documentos al simplificar su contenido y garantizar que no haya datos ocultos dentro de las capas. |
| [get_ImageCompressionOptions](./get_imagecompressionoptions/)() const | Obtiene la opción de conversión de imagen del documento. La opción debe habilitarse manualmente al usar el método [All](./all/) si es necesario. |
| [get_ImageDpi](./get_imagedpi/)() const | Obtiene la opción para resolver imágenes de página durante la conversión. |
| [get_RemoveAnnotations](./get_removeannotations/)() const | Obtiene un valor que indica si se deben eliminar las anotaciones del documento. Cuando está habilitado, todas las anotaciones presentes en el documento se eliminarán durante el proceso de sanitización. Se aplicarán anotaciones de redacción. |
| [get_RemoveAttachments](./get_removeattachments/)() const | Obtiene la opción para eliminar todos los archivos adjuntos del documento. Cuando está habilitado, garantiza que cualquier adjunto dentro del PDF sea eliminado durante el proceso de sanitización. |
| [get_RemoveJavaScriptsAndActions](./get_removejavascriptsandactions/)() const | Obtiene un valor que indica si JavaScript y las acciones asociadas deben eliminarse del documento. Esta opción es útil para eliminar posibles vulnerabilidades de seguridad introducidas por scripts incrustados. |
| [get_RemoveMetadata](./get_removemetadata/)() const | Obtiene una opción para eliminar los metadatos del documento. Si se establece en verdadero, los metadatos como propiedades del documento e información de metadatos incrustada adicional serán eliminados durante la sanitización. |
| [get_RemoveSearchIndexAndPrivateInfo](./get_removesearchindexandprivateinfo/)() const | Obtiene un valor que indica si el índice de búsqueda y la información privada deben eliminarse del documento. Habilita la eliminación de índices de búsqueda incrustados y datos privados para mejorar la seguridad y privacidad del documento. |
| [HiddenDataSanitizationOptions](./hiddendatasanitizationoptions/)() |  |
| [set_ConvertPagesToImages](./set_convertpagestoimages/)(bool) | Establece la opción para convertir páginas a imágenes. Si esta opción está habilitada, la opción ImageCompressionOptions será ignorada. La opción debe habilitarse manualmente al usar el método [All](./all/) si es necesario. La conversión de páginas a imágenes se realizará después de limpiar los datos ocultos principales, que son controlados por otras opciones. |
| [set_FlattenForms](./set_flattenforms/)(bool) | Establece un valor que indica si los formularios del documento deben aplanarse durante el proceso de sanitización. Aplanar formularios convierte los campos interactivos en contenido estático, haciéndolos no editables o rellenables. |
| [set_FlattenLayers](./set_flattenlayers/)(bool) | Establece la opción para aplanar las capas en el documento PDF. Cuando está habilitado, todas las capas del documento se fusionan en una sola capa, eliminando su estructura separada. Esta opción es útil para sanitizar documentos simplificando su contenido y asegurando que no haya datos ocultos dentro de las capas. |
| [set_ImageCompressionOptions](./set_imagecompressionoptions/)(const System::SharedPtr\<Aspose::Pdf::Optimization::ImageCompressionOptions\>\&) | Establece la opción de conversión de imagen del documento. La opción debe habilitarse manualmente al usar el método [All](./all/) si es necesario. |
| [set_ImageDpi](./set_imagedpi/)(int32_t) | Establece la opción para resolver imágenes de página durante la conversión. |
| [set_RemoveAnnotations](./set_removeannotations/)(bool) | Establece un valor que indica si se deben eliminar las anotaciones del documento. Cuando está habilitado, todas las anotaciones presentes en el documento se eliminarán durante el proceso de sanitización. Se aplicarán anotaciones de redacción. |
| [set_RemoveAttachments](./set_removeattachments/)(bool) | Establece la opción para eliminar todos los archivos adjuntos del documento. Cuando está habilitado, garantiza que cualquier adjunto dentro del PDF sea eliminado durante el proceso de sanitización. |
| [set_RemoveJavaScriptsAndActions](./set_removejavascriptsandactions/)(bool) | Establece un valor que indica si JavaScript y las acciones asociadas deben eliminarse del documento. Esta opción es útil para eliminar posibles vulnerabilidades de seguridad introducidas por scripts incrustados. |
| [set_RemoveMetadata](./set_removemetadata/)(bool) | Establece una opción para eliminar los metadatos del documento. Si se establece en verdadero, los metadatos como propiedades del documento e información de metadatos incrustada adicional serán eliminados durante la sanitización. |
| [set_RemoveSearchIndexAndPrivateInfo](./set_removesearchindexandprivateinfo/)(bool) | Establece un valor que indica si el índice de búsqueda y la información privada deben eliminarse del documento. Habilita la eliminación de índices de búsqueda incrustados y datos privados para mejorar la seguridad y privacidad del documento. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Security::HiddenDataSanitization](../)
* Library [Aspose.PDF for C++](../../)
