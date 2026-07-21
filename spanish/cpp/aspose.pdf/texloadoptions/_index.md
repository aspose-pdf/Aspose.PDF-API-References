---
title: "Aspose::Pdf::TeXLoadOptions clase"
linktitle: "TeXLoadOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::TeXLoadOptions clase. Representa opciones para cargar/importar archivos TeX en un documento PDF en C++."
type: docs
weight: 18100
url: /es/cpp/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class


Representa opciones para cargar/importar un archivo TeX en un documento PDF.

```cpp
class TeXLoadOptions : public Aspose::Pdf::LoadOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_DateTime](./get_datetime/)() | Obtiene/establece un valor determinado para primitivas de fecha/hora como año, mes, día y hora. |
| [get_InputDirectory](./get_inputdirectory/)() | Obtiene/establece el directorio de entrada de TeX. |
| [get_JobName](./get_jobname/)() const | Obtiene/establece el nombre del trabajo. |
| [get_NoLigatures](./get_noligatures/)() | Obtiene/establece una bandera que cancela ligaduras en todas las fuentes. |
| [get_OutputDirectory](./get_outputdirectory/)() | Obtiene/establece el directorio de salida de TeX. |
| [get_RasterizeFormulas](./get_rasterizeformulas/)() | Obtiene/establece una bandera que permite rasterizar fórmulas matemáticas. |
| [get_Repeat](./get_repeat/)() | Obtiene/establece la bandera que indica si es necesario ejecutar el trabajo TeX dos veces en caso, por ejemplo, de que haya referencias en los archivos TeX de entrada. En general, este comportamiento es útil cuando el motor recopila algunos datos durante el proceso de composición y los almacena en un archivo auxiliar, todo en la primera ejecución. Y en la segunda ejecución, el motor de alguna manera utiliza esos datos. |
| [get_RequiredInputDirectory](./get_requiredinputdirectory/)() | Obtiene/establece el directorio de entrada requerido por TeX. La entrada requerida son los archivos que de alguna manera se incluyen en el archivo .tex principal, p. ej., paquetes para los que no hay soporte incorporado. |
| [get_ShowTerminalOutput](./get_showterminaloutput/)() const | Obtiene/establece la bandera que indica si se muestra la salida del terminal en la consola. |
| [get_SubsetFonts](./get_subsetfonts/)() | Obtiene/establece la bandera que indica si se subestablecen fuentes en el archivo de salida o no. |
| [GetLoadResult](./getloadresult/)() | Obtiene el resultado de la carga y compilación de TeX: ¿todo se ejecutó sin problemas o hubo comentarios/errores? |
| [set_DateTime](./set_datetime/)(System::DateTime) | Obtiene/establece un valor determinado para primitivas de fecha/hora como año, mes, día y hora. |
| [set_InputDirectory](./set_inputdirectory/)(const System::SharedPtr\<ITeXInputDirectory\>\&) | Obtiene/establece el directorio de entrada de TeX. |
| [set_JobName](./set_jobname/)(const System::String\&) | Obtiene/establece el nombre del trabajo. |
| [set_NoLigatures](./set_noligatures/)(bool) | Obtiene/establece una bandera que cancela ligaduras en todas las fuentes. |
| [set_OutputDirectory](./set_outputdirectory/)(const System::SharedPtr\<ITeXOutputDirectory\>\&) | Obtiene/establece el directorio de salida de TeX. |
| [set_RasterizeFormulas](./set_rasterizeformulas/)(bool) | Obtiene/establece una bandera que permite rasterizar fórmulas matemáticas. |
| [set_Repeat](./set_repeat/)(bool) | Obtiene/establece la bandera que indica si es necesario ejecutar el trabajo TeX dos veces en caso, por ejemplo, de que haya referencias en los archivos TeX de entrada. En general, este comportamiento es útil cuando el motor recopila algunos datos durante el proceso de composición y los almacena en un archivo auxiliar, todo en la primera ejecución. Y en la segunda ejecución, el motor de alguna manera utiliza esos datos. |
| [set_RequiredInputDirectory](./set_requiredinputdirectory/)(const System::SharedPtr\<ITeXInputDirectory\>\&) | Obtiene/establece el directorio de entrada requerido por TeX. La entrada requerida son los archivos que de alguna manera se incluyen en el archivo .tex principal, p. ej., paquetes para los que no hay soporte incorporado. |
| [set_ShowTerminalOutput](./set_showterminaloutput/)(bool) | Obtiene/establece la bandera que indica si se muestra la salida del terminal en la consola. |
| [set_SubsetFonts](./set_subsetfonts/)(bool) | Obtiene/establece la bandera que indica si se subestablecen fuentes en el archivo de salida o no. |
| [TeXLoadOptions](./texloadoptions/)() | Crea opciones de carga predeterminadas para convertir un archivo TeX en documento PDF. |
## Ver también

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
