---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase de opción de guardado de documento en formato markdown."
type: docs
weight: 60
url: /es/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Representa la clase de opción de guardado de documento en formato markdown.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Crea una opción de instancia para guardar un documento en formato markdown. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | Obtenga o establezca un área rectangular para extraer contenido a markdown. |
| [getEmphasisStyle](#getEmphasisStyle--) | Obtiene o establece el estilo de énfasis para el documento generado. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Obtiene y establece una propiedad que indica si se deben extraer los gráficos vectoriales. |
| [getHeadingLevels](#getHeadingLevels--) | Define los niveles de encabezado esperados para usar en la estrategia de reconocimiento de encabezados FontSize. Si el valor de esta propiedad está establecido, entonces la estrategia de reconocimiento de encabezados {@link HeadingRecognitionStrategy#Heuristic} se seleccionará cuando se establezcan las estrategias {@link HeadingRecognitionStrategy#Auto}, incluso si el documento contiene marcadores. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Obtiene o establece la estrategia de reconocimiento de encabezados. |
| [getHeadingStyle](#getHeadingStyle--) | Obtiene o establece el estilo de encabezado para el documento generado. |
| [getLineBreakStyle](#getLineBreakStyle--) | Obtiene o establece el estilo de salto de línea para el documento generado. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Obtiene y establece el nombre del directorio donde guardar los recursos del documento, como imágenes. Si no se especifica el valor, las imágenes se escribirán en el mismo directorio que el propio archivo markdown. ¡Esto no es una ruta, es solo un nombre! Este directorio se creará automáticamente en el directorio con el archivo markdown guardado. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Obtiene y establece el nombre del directorio donde guardar los recursos del documento, como imágenes. Este directorio se creará automáticamente en el directorio con el archivo markdown guardado. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Obtiene y establece la autorización para convertir subíndices y superíndices. Este valor es verdadero por defecto. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Obtiene y establece la autorización para usar una etiqueta img para insertar imágenes a la izquierda y derecha del texto. En este caso, en el visor markdown, el texto se ajustará alrededor de la imagen. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | Obtenga o establezca un área rectangular para extraer contenido a markdown. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Obtiene o establece el estilo de énfasis para el documento generado. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Obtiene y establece una propiedad que indica si se deben extraer los gráficos vectoriales. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Define los niveles de encabezado esperados para usar en la estrategia de reconocimiento de encabezados FontSize. Si el valor de esta propiedad está establecido, entonces la estrategia de reconocimiento de encabezados {@link HeadingRecognitionStrategy#Heuristic} se seleccionará cuando se establezcan las estrategias {@link HeadingRecognitionStrategy#Auto}, incluso si el documento contiene marcadores. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Obtiene o establece la estrategia de reconocimiento de encabezados. |
| [setHeadingStyle](#setHeadingStyle-int-) | Obtiene o establece el estilo de encabezado para el documento generado. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Obtiene o establece el estilo de salto de línea para el documento generado. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Obtiene y establece el nombre del directorio donde guardar los recursos del documento, como imágenes. Si no se especifica el valor, las imágenes se escribirán en el mismo directorio que el propio archivo markdown. ¡Esto no es una ruta, es solo un nombre! Este directorio se creará automáticamente en el directorio con el archivo markdown guardado. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Obtiene y establece el nombre del directorio donde guardar los recursos del documento, como imágenes. Este directorio se creará automáticamente en el directorio con el archivo markdown guardado. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Obtiene y establece la autorización para convertir subíndices y superíndices. Este valor es verdadero por defecto. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Obtiene y establece la autorización para usar una etiqueta img para insertar imágenes a la izquierda y derecha del texto. En este caso, en el visor markdown, el texto se ajustará alrededor de la imagen. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Crea una opción de instancia para guardar un documento en formato markdown.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

Obtenga o establezca un área rectangular para extraer contenido a markdown.

**Returns:**
Instancia de Rectangle

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Obtiene o establece el estilo de énfasis para el documento generado.

**Returns:**
Elemento EmphasisStyle

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Obtiene y establece una propiedad que indica si se deben extraer los gráficos vectoriales.

**Returns:**
valor booleano

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Define los niveles de encabezado esperados para usar en la estrategia de reconocimiento de encabezados FontSize. Si el valor de esta propiedad está establecido, entonces la estrategia de reconocimiento de encabezados {@link HeadingRecognitionStrategy#Heuristic} se seleccionará cuando se establezcan las estrategias {@link HeadingRecognitionStrategy#Auto}, incluso si el documento contiene marcadores.

**Returns:**
Instancia de HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Obtiene o establece la estrategia de reconocimiento de encabezados.

**Returns:**
Elemento HeadingRecognitionStrategy

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Obtiene o establece el estilo de encabezado para el documento generado.

**Returns:**
Elemento HeadingStyle

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Obtiene o establece el estilo de salto de línea para el documento generado.

**Returns:**
Elemento LineBreakStyle

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Obtiene y establece el nombre del directorio donde guardar los recursos del documento, como imágenes. Si no se especifica el valor, las imágenes se escribirán en el mismo directorio que el propio archivo markdown. ¡Esto no es una ruta, es solo un nombre! Este directorio se creará automáticamente en el directorio con el archivo markdown guardado.

**Returns:**
valor String

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Obtiene y establece el nombre del directorio donde guardar los recursos del documento, como imágenes. Este directorio se creará automáticamente en el directorio con el archivo markdown guardado.

**Returns:**
valor String

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Obtiene y establece la autorización para convertir subíndices y superíndices. Este valor es verdadero por defecto.

**Returns:**
valor booleano

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Obtiene y establece la autorización para usar una etiqueta img para insertar imágenes a la izquierda y derecha del texto. En este caso, en el visor markdown, el texto se ajustará alrededor de la imagen.

**Returns:**
valor booleano

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
Obtenga o establezca un área rectangular para extraer contenido a markdown.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Obtiene o establece el estilo de énfasis para el documento generado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento EmphasisStyle |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Obtiene y establece una propiedad que indica si se deben extraer los gráficos vectoriales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Define los niveles de encabezado esperados para usar en la estrategia de reconocimiento de encabezados FontSize. Si el valor de esta propiedad está establecido, entonces la estrategia de reconocimiento de encabezados {@link HeadingRecognitionStrategy#Heuristic} se seleccionará cuando se establezcan las estrategias {@link HeadingRecognitionStrategy#Auto}, incluso si el documento contiene marcadores.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Obtiene o establece la estrategia de reconocimiento de encabezados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento HeadingRecognitionStrategy |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Obtiene o establece el estilo de encabezado para el documento generado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento HeadingStyle |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Obtiene o establece el estilo de salto de línea para el documento generado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento LineBreakStyle |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Obtiene y establece el nombre del directorio donde guardar los recursos del documento, como imágenes. Si no se especifica el valor, las imágenes se escribirán en el mismo directorio que el propio archivo markdown. ¡Esto no es una ruta, es solo un nombre! Este directorio se creará automáticamente en el directorio con el archivo markdown guardado.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Obtiene y establece el nombre del directorio donde guardar los recursos del documento, como imágenes. Este directorio se creará automáticamente en el directorio con el archivo markdown guardado.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Obtiene y establece la autorización para convertir subíndices y superíndices. Este valor es verdadero por defecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Obtiene y establece la autorización para usar una etiqueta img para insertar imágenes a la izquierda y derecha del texto. En este caso, en el visor markdown, el texto se ajustará alrededor de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
