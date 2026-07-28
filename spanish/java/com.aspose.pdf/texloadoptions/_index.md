---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa opciones para cargar/importar un archivo TeX en un documento PDF."
type: docs
weight: 4870
url: /es/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

Representa opciones para cargar/importar un archivo TeX en un documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | Crea opciones de carga predeterminadas para convertir un archivo TeX en documento PDF. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getDateTime](#getDateTime--) | Obtiene/establece un valor determinado para primitivas de fecha/hora como año, mes, día y hora. |
| [getInputDirectory](#getInputDirectory--) | Obtiene/establece el directorio de entrada de TeX. |
| [getJobName](#getJobName--) | Obtiene/establece el nombre del trabajo. |
| [getLoadResult](#getLoadResult--) | Obtiene el resultado de la carga y compilación de TeX - ¿todo salió sin problemas o hubo comentarios/errores? |
| [getNoLigatures](#getNoLigatures--) | Obtiene/establece una bandera que cancela las ligaduras en todas las fuentes. |
| [getOutputDirectory](#getOutputDirectory--) | Obtiene/establece el directorio de salida de TeX. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | Obtiene/establece una bandera que permite rasterizar fórmulas matemáticas. |
| [getRepeat](#getRepeat--) | Obtiene/establece la bandera que indica si es necesario ejecutar el trabajo de TeX dos veces en caso, por ejemplo, de que haya referencias en los archivos TeX de entrada. En general, este comportamiento es útil cuando el motor recopila algunos datos durante el proceso de composición y los almacena en un archivo auxiliar, todo en la primera ejecución. Y en la segunda ejecución, el motor de alguna manera utiliza esos datos. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | Obtiene/establece el directorio de entrada requerido por TeX. La entrada requerida son los archivos que de alguna manera se incluyen en el archivo .tex principal, p. ej., paquetes para los que no hay soporte incorporado. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | Obtiene/establece la bandera que indica si se muestra la salida del terminal en la consola. |
| [getSubsetFonts](#getSubsetFonts--) | Obtiene/establece el indicador que indica si se deben subestablecer fuentes en el archivo de salida o no. |
| [setDateTime](#setDateTime-java.util.Date-) | Obtiene/establece un valor determinado para primitivas de fecha/hora como año, mes, día y hora. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Obtiene/establece el directorio de entrada de TeX. |
| [setJobName](#setJobName-java.lang.String-) | Obtiene/establece el nombre del trabajo. |
| [setNoLigatures](#setNoLigatures-boolean-) | Obtiene/establece una bandera que cancela las ligaduras en todas las fuentes. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | Obtiene/establece el directorio de salida de TeX. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | Obtiene/establece una bandera que permite rasterizar fórmulas matemáticas. |
| [setRepeat](#setRepeat-boolean-) | Obtiene/establece la bandera que indica si es necesario ejecutar el trabajo de TeX dos veces en caso, por ejemplo, de que haya referencias en los archivos TeX de entrada. En general, este comportamiento es útil cuando el motor recopila algunos datos durante el proceso de composición y los almacena en un archivo auxiliar, todo en la primera ejecución. Y en la segunda ejecución, el motor de alguna manera utiliza esos datos. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Obtiene/establece el directorio de entrada requerido por TeX. La entrada requerida son los archivos que de alguna manera se incluyen en el archivo .tex principal, p. ej., paquetes para los que no hay soporte incorporado. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | Obtiene/establece la bandera que indica si se muestra la salida del terminal en la consola. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Obtiene/establece el indicador que indica si se deben subestablecer fuentes en el archivo de salida o no. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

Crea opciones de carga predeterminadas para convertir un archivo TeX en documento PDF.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

Obtiene/establece un valor determinado para primitivas de fecha/hora como año, mes, día y hora.

**Returns:**
instancia de Date

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

Obtiene/establece el directorio de entrada de TeX.

**Returns:**
Instancia de ITeXInputDirectory

### getJobName {#getJobName--}
```
public final String getJobName()
```

Obtiene/establece el nombre del trabajo.

**Returns:**
valor String

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

Obtiene el resultado de la carga y compilación de TeX - ¿todo salió sin problemas o hubo comentarios/errores?

**Returns:**
Elemento TeXLoadResult

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

Obtiene/establece una bandera que cancela las ligaduras en todas las fuentes.

**Returns:**
valor booleano

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

Obtiene/establece el directorio de salida de TeX.

**Returns:**
Instancia de ITeXOutputDirectory

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

Obtiene/establece una bandera que permite rasterizar fórmulas matemáticas.

**Returns:**
valor booleano

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

Obtiene/establece la bandera que indica si es necesario ejecutar el trabajo de TeX dos veces en caso, por ejemplo, de que haya referencias en los archivos TeX de entrada. En general, este comportamiento es útil cuando el motor recopila algunos datos durante el proceso de composición y los almacena en un archivo auxiliar, todo en la primera ejecución. Y en la segunda ejecución, el motor de alguna manera utiliza esos datos.

**Returns:**
valor booleano

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

Obtiene/establece el directorio de entrada requerido por TeX. La entrada requerida son los archivos que de alguna manera se incluyen en el archivo .tex principal, p. ej., paquetes para los que no hay soporte incorporado.

**Returns:**
Instancia de ITeXInputDirectory

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

Obtiene/establece la bandera que indica si se muestra la salida del terminal en la consola.

**Returns:**
valor booleano

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

Obtiene/establece el indicador que indica si se deben subestablecer fuentes en el archivo de salida o no.

**Returns:**
valor booleano

### setDateTime {#setDateTime-java.util.Date-}
Obtiene/establece un valor determinado para primitivas de fecha/hora como año, mes, día y hora.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Obtiene/establece el directorio de entrada de TeX.

### setJobName {#setJobName-java.lang.String-}
Obtiene/establece el nombre del trabajo.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

Obtiene/establece una bandera que cancela las ligaduras en todas las fuentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
Obtiene/establece el directorio de salida de TeX.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

Obtiene/establece una bandera que permite rasterizar fórmulas matemáticas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

Obtiene/establece la bandera que indica si es necesario ejecutar el trabajo de TeX dos veces en caso, por ejemplo, de que haya referencias en los archivos TeX de entrada. En general, este comportamiento es útil cuando el motor recopila algunos datos durante el proceso de composición y los almacena en un archivo auxiliar, todo en la primera ejecución. Y en la segunda ejecución, el motor de alguna manera utiliza esos datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Obtiene/establece el directorio de entrada requerido por TeX. La entrada requerida son los archivos que de alguna manera se incluyen en el archivo .tex principal, p. ej., paquetes para los que no hay soporte incorporado.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

Obtiene/establece la bandera que indica si se muestra la salida del terminal en la consola.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Obtiene/establece el indicador que indica si se deben subestablecer fuentes en el archivo de salida o no.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
