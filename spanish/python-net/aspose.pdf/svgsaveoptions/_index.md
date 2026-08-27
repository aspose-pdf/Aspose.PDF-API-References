---
title: "SvgSaveOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Opciones de guardado para exportar al formato SVG"
type: docs
weight: 1460
url: /es/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

Opciones de guardado para exportar al formato SVG

El tipo SvgSaveOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| SvgSaveOptions() | Inicializa una nueva instancia de la clase SvgSaveOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Función de devolución de llamada para manejar cualquier advertencia generada. <br/>            El WarningHandler devuelve el elemento enum ReturnAction que especifica Continuar o Abort. <br/>            Continuar es la acción predeterminada y la operación Guardar continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación Guardar debe detenerse. |
| save_format | Formato de guardado de datos. |
| close_response | Obtiene o establece un valor booleano que indica si el objeto Response se cerrará después de que el documento se guarde en la respuesta. |
| extract_ocr_sublayer_only | Ninguno |
| try_merge_adjacent_same_background_images | Ninguno |
| treat_target_file_name_as_directory | Esta opción define si se creará el directorio de destino<br/>             (si aún no existe) con el mismo nombre que el archivo de salida solicitado <br/>             en lugar del propio archivo de salida.<br/>             De esta forma, el directorio contendrá todas las imágenes SVG de salida de las páginas (como se describe a continuación).<br/>               Si no, los archivos de salida de las páginas distintas a la primera se crearán exactamente en el directorio solicitado<br/>            como archivo de salida principal, pero contendrán en el nombre del archivo el sufijo _[2...n], que<br/>             se define por el número de página, p. ej. si define el archivo de salida "C:\\AsposeTests\\output.svg"<br/>             y la salida contendrá varios archivos svg de páginas,<br/>             entonces los archivos de las páginas también se crearán en el directorio "C:\\AsposeTests\\" y tendrán nombres 'output.svg', 'output_2.svg', 'output_3.svg' etc. |
| compress_output_to_zip_archive | Especifica si la salida se creará como un único archivo zip.<br/>             Consulte el comentario de la opción 'TreatTargetFileNameAsDirectory' para ver las reglas de nombrado<br/>             de los archivos svg de las páginas para un documento fuente multipágina, que también se aplican al conjunto comprimido de archivos de salida. |
| scale_to_pixels | Especifica si se debe escalar el documento de salida de puntos tipográficos a píxeles. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

