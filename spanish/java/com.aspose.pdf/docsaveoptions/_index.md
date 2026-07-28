---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Opciones de guardado para exportar al formato Doc"
type: docs
weight: 1030
url: /es/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Opciones de guardado para exportar al formato Doc

## Constructores

| Constructor | Descripción |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Este controlador puede usarse para manejar eventos de progreso de conversión, p.e. puede usarse para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas; ejemplo del código del controlador que muestra el progreso en la consola: </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | Obtener formato de salida |
| [getImageResolutionX](#getImageResolutionX--) | Resolución X de imágenes convertidas. |
| [getImageResolutionY](#getImageResolutionY--) | Resolución Y de imágenes convertidas. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | Este parámetro se usa para agrupar líneas de texto en párrafos. Determina cuán separadas pueden estar dos líneas de texto relativas. Se especifica en cientos de por ciento de la altura de las líneas de texto. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | Define la ruta (nombre de archivo o nombre de directorio) para almacenar datos temporales al convertir en modo de guardado en memoria. |
| [getMode](#getMode--) | Modo de reconocimiento. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | En PDF, las palabras pueden estar representadas internamente con operadores que imprimen palabras al imprimir de forma independiente sus letras o sílabas. Por lo tanto, para detectar palabras a veces es necesario detectar grupos de caracteres independientes que en realidad son palabras. Esta configuración define el ancho del espacio entre los elementos de texto (letras, sílabas) que debe considerarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (La presencia de un espacio vacío al menos de este ancho entre letras indica que los elementos textuales pertenecen a palabras diferentes). Está normalizado al tamaño de fuente: 1.0 significa el 100 % del tamaño de fuente supuesto de la palabra. ¡ATENCIÓN! Se utiliza solo en casos en que el PDF de origen contiene fuentes específicas de uso raro para las que no se puede calcular un valor óptimo a partir de la fuente. Así, en la gran mayoría de los casos este parámetro no cambia nada en el documento resultante. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | Se usan saltos de párrafo o de línea. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Obtiene o establece la conversión para fuentes Type3. En fuentes Type 3, los glifos se definen mediante flujos de operadores gráficos. Esto significa que en la salida DOC/DOCX vemos imágenes en lugar de texto. Establezca este indicador en true para convertir fuentes Type3 a TTF y obtener texto en el archivo resultante. |
| [isRecognizeBullets](#isRecognizeBullets--) | Activar el reconocimiento de viñetas. |
| [isReSaveFonts](#isReSaveFonts--) | Obtiene o establece el procedimiento para volver a guardar fuentes. Si se establece en true, recargamos las fuentes en cada página para evitar la influencia de propiedades de fuentes anteriores y cargamos la fuente recién creada desde cero. Establezca esta opción en false si desea mejorar el rendimiento. El valor predeterminado es true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | Usar saltos de párrafo o de línea |
| [setBatchSize](#setBatchSize-int-) | Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Obtiene o establece la conversión para fuentes Type3. En fuentes Type 3, los glifos se definen mediante flujos de operadores gráficos. Esto significa que en la salida DOC/DOCX vemos imágenes en lugar de texto. Establezca este indicador en true para convertir fuentes Type3 a TTF y obtener texto en el archivo resultante. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Este manejador puede usarse para manejar eventos de progreso de conversión, p. ej. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | Establecer formato de salida |
| [setImageResolutionX](#setImageResolutionX-int-) | Resolución X de imágenes convertidas. |
| [setImageResolutionY](#setImageResolutionY-int-) | Resolución Y de imágenes convertidas. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | Este parámetro se usa para agrupar líneas de texto en párrafos. Determina cuán separadas pueden estar dos líneas de texto relativas. Se especifica en cientos de por ciento de la altura de las líneas de texto. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | Define la ruta (nombre de archivo o nombre de directorio) para almacenar datos temporales al convertir en modo de guardado en memoria. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | Modo de reconocimiento. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | Activar el reconocimiento de viñetas. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | En PDF, las palabras pueden estar representadas internamente con operadores que imprimen palabras al imprimir de forma independiente sus letras o sílabas. Por lo tanto, para detectar palabras a veces es necesario detectar grupos de caracteres independientes que en realidad son palabras. Esta configuración define el ancho del espacio entre los elementos de texto (letras, sílabas) que debe considerarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (La presencia de un espacio vacío al menos de este ancho entre letras indica que los elementos textuales pertenecen a palabras diferentes). Está normalizado al tamaño de fuente: 1.0 significa el 100 % del tamaño de fuente supuesto de la palabra. ¡ATENCIÓN! Se utiliza solo en casos en que el PDF de origen contiene fuentes específicas de uso raro para las que no se puede calcular un valor óptimo a partir de la fuente. Así, en la gran mayoría de los casos este parámetro no cambia nada en el documento resultante. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | Obtiene o establece el procedimiento para volver a guardar fuentes. Si se establece en true, recargamos las fuentes en cada página para evitar la influencia de propiedades de fuentes anteriores y cargamos la fuente recién creada desde cero. Establezca esta opción en false si desea mejorar el rendimiento. El valor predeterminado es true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

Constructor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino.

**Returns:**
valor int

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Este controlador puede ser utilizado para manejar eventos de progreso de conversión, p.ej. puede usarse para mostrar una barra de progreso o mensajes sobre la cantidad actual de páginas procesadas, ejemplo del código del controlador que muestra el progreso en la consola es : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
Instancia ConversionProgressEventHandler

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

Obtener formato de salida

**Returns:**
Elemento DocFormat @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

Resolución X de imágenes convertidas.

**Returns:**
valor int

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

Resolución Y de imágenes convertidas.

**Returns:**
valor int

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

Este parámetro se usa para agrupar líneas de texto en párrafos. Determina cuán separadas pueden estar dos líneas de texto relativas. Se especifica en cientos de por ciento de la altura de las líneas de texto.

**Returns:**
valor flotante

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

Define la ruta (nombre de archivo o nombre de directorio) para almacenar datos temporales al convertir en modo de guardado en memoria.

**Returns:**
valor String

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

Modo de reconocimiento.

**Returns:**
Valor RecognitionMode @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

En PDF, las palabras pueden estar representadas internamente con operadores que imprimen palabras al imprimir de forma independiente sus letras o sílabas. Por lo tanto, para detectar palabras a veces es necesario detectar grupos de caracteres independientes que en realidad son palabras. Esta configuración define el ancho del espacio entre los elementos de texto (letras, sílabas) que debe considerarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (La presencia de un espacio vacío al menos de este ancho entre letras indica que los elementos textuales pertenecen a palabras diferentes). Está normalizado al tamaño de fuente: 1.0 significa el 100 % del tamaño de fuente supuesto de la palabra. ¡ATENCIÓN! Se utiliza solo en casos en que el PDF de origen contiene fuentes específicas de uso raro para las que no se puede calcular un valor óptimo a partir de la fuente. Así, en la gran mayoría de los casos este parámetro no cambia nada en el documento resultante.

**Returns:**
Proximidad relativa

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

Se usan saltos de párrafo o de línea.

**Returns:**
valor booleano.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Obtiene o establece la conversión para fuentes Type3. En fuentes Type 3, los glifos se definen mediante flujos de operadores gráficos. Esto significa que en la salida DOC/DOCX vemos imágenes en lugar de texto. Establezca este indicador en true para convertir fuentes Type3 a TTF y obtener texto en el archivo resultante.

**Returns:**
valor booleano

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

Activar el reconocimiento de viñetas.

**Returns:**
valor booleano

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

Obtiene o establece el procedimiento para volver a guardar fuentes. Si se establece en true, recargamos las fuentes en cada página para evitar la influencia de propiedades de fuentes anteriores y cargamos la fuente recién creada desde cero. Establezca esta opción en false si desea mejorar el rendimiento. El valor predeterminado es true;

**Returns:**
valor booleano

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

Usar saltos de párrafo o de línea

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Define el tamaño del lote si la conversión por lotes es aplicable al par de formatos de origen y destino.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Obtiene o establece la conversión para fuentes Type3. En fuentes Type 3, los glifos se definen mediante flujos de operadores gráficos. Esto significa que en la salida DOC/DOCX vemos imágenes en lugar de texto. Establezca este indicador en true para convertir fuentes Type3 a TTF y obtener texto en el archivo resultante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Este manejador puede usarse para manejar eventos de progreso de conversión, p. ej.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
Establecer formato de salida

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

Resolución X de imágenes convertidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

Resolución Y de imágenes convertidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

Este parámetro se usa para agrupar líneas de texto en párrafos. Determina cuán separadas pueden estar dos líneas de texto relativas. Se especifica en cientos de por ciento de la altura de las líneas de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
Define la ruta (nombre de archivo o nombre de directorio) para almacenar datos temporales al convertir en modo de guardado en memoria.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
Modo de reconocimiento.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

Activar el reconocimiento de viñetas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

En PDF, las palabras pueden estar representadas internamente con operadores que imprimen palabras al imprimir de forma independiente sus letras o sílabas. Por lo tanto, para detectar palabras a veces es necesario detectar grupos de caracteres independientes que en realidad son palabras. Esta configuración define el ancho del espacio entre los elementos de texto (letras, sílabas) que debe considerarse como distancia entre palabras durante el reconocimiento de palabras en el PDF de origen. (La presencia de un espacio vacío al menos de este ancho entre letras indica que los elementos textuales pertenecen a palabras diferentes). Está normalizado al tamaño de fuente: 1.0 significa el 100 % del tamaño de fuente supuesto de la palabra. ¡ATENCIÓN! Se utiliza solo en casos en que el PDF de origen contiene fuentes específicas de uso raro para las que no se puede calcular un valor óptimo a partir de la fuente. Así, en la gran mayoría de los casos este parámetro no cambia nada en el documento resultante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Proximidad relativa |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

Obtiene o establece el procedimiento para volver a guardar fuentes. Si se establece en true, recargamos las fuentes en cada página para evitar la influencia de propiedades de fuentes anteriores y cargamos la fuente recién creada desde cero. Establezca esta opción en false si desea mejorar el rendimiento. El valor predeterminado es true;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
