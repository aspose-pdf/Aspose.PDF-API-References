---
title: "TeXLoadOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa opciones para cargar/importar un archivo TeX en un documento PDF."
type: docs
weight: 1520
url: /es/python-net/aspose.pdf/texloadoptions/
---

## TeXLoadOptions class

Representa opciones para cargar/importar un archivo TeX en un documento PDF.

El tipo TeXLoadOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| TeXLoadOptions() | Inicializa una nueva instancia de la clase TeXLoadOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| warning_handler | Función de devolución de llamada para manejar cualquier advertencia generada. <br/>            El WarningHandler devuelve el elemento enum ReturnAction que especifica Continuar o Abort. <br/>            Continuar es la acción predeterminada y la operación de Carga continúa, sin embargo el usuario también puede devolver Abort, en cuyo caso la operación de Carga debe detenerse. |
| load_format | Representa el formato de archivo que describe [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/). |
| job_name | Obtiene/establece el nombre del trabajo. |
| input_directory | Obtiene/establece el directorio de entrada de TeX. |
| output_directory | Obtiene/establece el directorio de salida de TeX. |
| repeat | Obtiene/establece la bandera que indica si es necesario ejecutar el trabajo de TeX dos veces en caso,<br/>            por ejemplo, de que haya referencias en los archivos de TeX de entrada. En general, este comportamiento es útil cuando<br/>            el motor recopila algunos datos durante el proceso de composición y los almacena en un archivo auxiliar,<br/>            todo en la primera ejecución. Y en la segunda ejecución, el motor de alguna manera utiliza esos datos. |
| subset_fonts | Obtiene/establece la bandera que indica si se deben crear subconjuntos de fuentes en el archivo de salida o no. |
| show_terminal_output | Obtiene/establece la bandera que indica si se muestra la salida del terminal en la consola. |
| date_time | Obtiene/establece un valor determinado para los primitivos de fecha/hora como \year, \month, \day y \time. |
| no_ligatures | Obtiene/establece una bandera que cancela las ligaduras en todas las fuentes. |
| rasterize_formulas | Obtiene/establece una bandera que permite rasterizar fórmulas matemáticas. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

