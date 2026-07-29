---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Opciones de guardado para exportar al formato SVG"
type: docs
weight: 4720
url: /es/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

Opciones de guardado para exportar al formato SVG

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión para el manejo personalizado de los archivos de imágenes externas referenciadas creadas (como BMP o JPEG incrustados) incorporados en el SVG guardado. Esa estrategia debe procesar los recursos y devolver una cadena que represente la URI deseada del recurso guardado en el SVG generado. Si el procesamiento de este u otro archivo, por alguna razón, debe ser realizado por el propio código del convertidor y no por código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo'. Esto indica al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor como si no existiera ningún código personalizado externo. |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | Especifica si la salida se creará como un único archivo zip. Consulte el comentario de la opción 'TreatTargetFileNameAsDirectory' para ver las reglas de nombrado de los archivos svg de las páginas del documento fuente multipágina, que también se aplican al conjunto comprimido de archivos de salida. |
| [isScaleToPixels](#isScaleToPixels--) | Especifica si se debe escalar el documento de salida de puntos tipográficos a píxeles. |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | Esta opción define si se creará un directorio de destino (si aún no existe) con el mismo nombre que el archivo de salida solicitado en lugar del propio archivo de salida. De esta forma, ese directorio contendrá todas las imágenes SVG de salida de las páginas (como se describe a continuación). Si no, los archivos de salida de las páginas, excepto la primera, se crearán exactamente en el directorio solicitado como archivo de salida principal, pero contendrán en el nombre del archivo el sufijo _[2...n], que se define por el número de página, por ejemplo, si defines el archivo de salida "C:\\AsposeTests\\output.svg" y la salida contendrá varios archivos svg de páginas, entonces los archivos de las páginas también se crearán en el directorio "C:\\AsposeTests\\" y tendrán nombres 'output.svg', 'output_2.svg', 'output_3.svg', etc. |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | Especifica si la salida se creará como un único archivo zip. Consulte el comentario de la opción 'TreatTargetFileNameAsDirectory' para ver las reglas de nombrado de los archivos svg de las páginas del documento fuente multipágina, que también se aplican al conjunto comprimido de archivos de salida. |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión para el manejo personalizado de los archivos de imágenes externas referenciadas creadas (como BMP o JPEG incrustados) incrustados en el SVG guardado. |
| [setScaleToPixels](#setScaleToPixels-boolean-) | Especifica si se debe escalar el documento de salida de puntos tipográficos a píxeles. |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | Esta opción define si se creará un directorio de destino (si aún no existe) con el mismo nombre que el archivo de salida solicitado en lugar del propio archivo de salida. De esta forma, ese directorio contendrá todas las imágenes SVG de salida de las páginas (como se describe a continuación). Si no, los archivos de salida de las páginas, excepto la primera, se crearán exactamente en el directorio solicitado como archivo de salida principal, pero contendrán en el nombre del archivo el sufijo _[2...n], que se define por el número de página, por ejemplo, si defines el archivo de salida "C:\\AsposeTests\\output.svg" y la salida contendrá varios archivos svg de páginas, entonces los archivos de las páginas también se crearán en el directorio "C:\\AsposeTests\\" y tendrán nombres 'output.svg', 'output_2.svg', 'output_3.svg', etc. |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

Constructor

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión para el manejo personalizado de los archivos de imágenes externas referenciadas creadas (como BMP o JPEG incrustados) incorporados en el SVG guardado. Esa estrategia debe procesar los recursos y devolver una cadena que represente la URI deseada del recurso guardado en el SVG generado. Si el procesamiento de este u otro archivo, por alguna razón, debe ser realizado por el propio código del convertidor y no por código personalizado, establezca en el código personalizado la bandera 'CustomProcessingCancelled' de la variable del parámetro 'imageSavingInfo'. Esto indica al convertidor que todos los pasos necesarios para el procesamiento de ese recurso deben realizarse en el propio convertidor como si no existiera ningún código personalizado externo.

**Returns:**
Instancia de EmbeddedImagesSavingStrategy

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

Especifica si la salida se creará como un único archivo zip. Consulte el comentario de la opción 'TreatTargetFileNameAsDirectory' para ver las reglas de nombrado de los archivos svg de las páginas del documento fuente multipágina, que también se aplican al conjunto comprimido de archivos de salida.

**Returns:**
valor booleano

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

Especifica si se debe escalar el documento de salida de puntos tipográficos a píxeles.

**Returns:**
valor booleano

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

Esta opción define si se creará un directorio de destino (si aún no existe) con el mismo nombre que el archivo de salida solicitado en lugar del propio archivo de salida. De esta forma, ese directorio contendrá todas las imágenes SVG de salida de las páginas (como se describe a continuación). Si no, los archivos de salida de las páginas, excepto la primera, se crearán exactamente en el directorio solicitado como archivo de salida principal, pero contendrán en el nombre del archivo el sufijo _[2...n], que se define por el número de página, por ejemplo, si defines el archivo de salida "C:\AsposeTests\output.svg" y la salida contendrá varios archivos svg de páginas, entonces los archivos de las páginas también se crearán en el directorio "C:\AsposeTests\" y tendrán nombres 'output.svg', 'output_2.svg', 'output_3.svg', etc.

**Returns:**
valor booleano

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

Especifica si la salida se creará como un único archivo zip. Consulte el comentario de la opción 'TreatTargetFileNameAsDirectory' para ver las reglas de nombrado de los archivos svg de las páginas del documento fuente multipágina, que también se aplican al conjunto comprimido de archivos de salida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| compressOutputToZipArchive |  | valor booleano |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
Este campo puede contener la estrategia de guardado que debe usarse (si está presente) durante la conversión para el manejo personalizado de los archivos de imágenes externas referenciadas creadas (como BMP o JPEG incrustados) incrustados en el SVG guardado.

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

Especifica si se debe escalar el documento de salida de puntos tipográficos a píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleToPixels |  | valor booleano |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

Esta opción define si se creará un directorio de destino (si aún no existe) con el mismo nombre que el archivo de salida solicitado en lugar del propio archivo de salida. De esta forma, ese directorio contendrá todas las imágenes SVG de salida de las páginas (como se describe a continuación). Si no, los archivos de salida de las páginas, excepto la primera, se crearán exactamente en el directorio solicitado como archivo de salida principal, pero contendrán en el nombre del archivo el sufijo _[2...n], que se define por el número de página, por ejemplo, si defines el archivo de salida "C:\AsposeTests\output.svg" y la salida contendrá varios archivos svg de páginas, entonces los archivos de las páginas también se crearán en el directorio "C:\AsposeTests\" y tendrán nombres 'output.svg', 'output_2.svg', 'output_3.svg', etc.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | valor booleano |
