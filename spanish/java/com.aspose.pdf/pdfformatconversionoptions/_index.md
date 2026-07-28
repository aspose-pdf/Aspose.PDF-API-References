---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "representa un conjunto de opciones para convertir un documento PDF"
type: docs
weight: 3730
url: /es/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

representa un conjunto de opciones para convertir un documento PDF

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Constructor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | Estrategia para alinear texto. Este parámetro tiene sentido solo cuando la bandera {@code AlignText} está establecida en true. |
| [getAlignText](#getAlignText--) | Esta bandera controla la alineación del texto en el documento convertido. Por defecto, la conversión de documentos no afecta la alineación del texto y lo deja tal como está. Pero en algunos casos la sustitución de fuentes provoca solapamiento de texto o espacios extra en el documento convertido. Cuando esta bandera está activada se realizarán operaciones especiales de alineación. Esta bandera debe activarse solo para documentos que tengan problemas de texto superpuesto o espacios de texto extra, ya que su uso disminuye el rendimiento y, en algunos casos, podría corromper el contenido del texto. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | Obtiene o establece la configuración para el etiquetado automático durante la conversión de formato PDF. Los ajustes de etiquetado automático se utilizan para configurar el comportamiento del proceso de autoetiquetado, que normalmente se emplea para mejorar la accesibilidad y la estructura de un documento PDF durante la conversión a un formato PDF específico. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | Acción para imágenes con máscara suave. |
| [getDefault](#getDefault--) | Obtiene el objeto PdfFormatConversionOptions con los parámetros predeterminados. |
| [getErrorAction](#getErrorAction--) | Acción para objetos que no pueden convertirse. |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | Estrategia(s) para excluir fuentes superfluas y reducir el tamaño del archivo del documento. Este parámetro tiene sentido solo cuando la bandera {@code OptimizeFileSize} está establecida en true. Por defecto se utiliza la combinación de estrategias {@code SubsetFonts} y {@code RemoveDuplicatedFonts}. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | Opciones para los casos en que no es posible incrustar algunas fuentes en el documento PDF. |
| [getFormat](#getFormat--) | Formato PDF. |
| [getIccProfileFileName](#getIccProfileFileName--) | Obtiene el nombre de archivo del perfil icc. En caso de null se utiliza el perfil icc predeterminado. |
| [getLogFileName](#getLogFileName--) | Ruta al archivo donde se almacenarán los comentarios. |
| [getLogStream](#getLogStream--) | Flujo donde se almacenarán los comentarios. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | Contiene banderas para controlar el proceso de conversión PDF/A en casos en que el documento fuente no corresponde a la especificación PDF/A. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | Esta propiedad es out-property. Contiene todas las fuentes (nombres de fuentes) que no se encontraron en el equipo en la última conversión PDF/A. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | Obtiene una bandera que habilita/deshabilita el modo de conversión especial para obtener un documento PDF/A con tamaño de archivo reducido. Actualmente esta bandera afecta la optimización de fuentes usadas en el documento PDF; posiblemente, en el futuro, también se usará para activar la optimización de otras estructuras de datos, como gráficos. El conjunto de esta bandera y modo podría reducir significativamente el tamaño del archivo, pero al mismo tiempo podría disminuir notablemente el rendimiento de la conversión. |
| [getOutputIntent](#getOutputIntent--) | Obtiene o establece el {@link OutputIntent} para la conversión de formato PDF. El {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) especifica el dispositivo de salida o condición prevista para la cual se está preparando el documento PDF. Se utiliza para garantizar que los colores del documento se rendericen correctamente en el dispositivo de destino. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Estrategia para procesar símbolos del Área de Uso Privado (PUA) de Unicode. |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | Estrategia para copiar datos de codificación para fuentes simbólicas si la fuente TrueType simbólica tiene más de una subtabla de codificación. |
| [getTransparencyAction](#getTransparencyAction--) | Acción para objetos de imagen enmascarados |
| [getTransparencyResolution](#getTransparencyResolution--) | Establece la resolución durante la conversión de imágenes transparentes. A mayor resolución, menor velocidad de conversión. El valor predeterminado es 300. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Reglas para resolver problemas con el mapeo Unicode. Puede ser null. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | Obtiene/establece la ejecución de flujos de imagen en modo asíncrono. |
| [isLowMemoryMode](#isLowMemoryMode--) | ¿Está habilitado el modo de conversión de bajo consumo de memoria? |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | ¿Está habilitado el modo de análisis de fuentes por página? Valor predeterminado = false |
| [isTransferInfo](#isTransferInfo--) | Obtiene o establece si se deben pasar datos de Info a Metadata al convertir a PDF 2.0. Verdadero por defecto. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | Valor predeterminado FALSE y el color de transparencia se mantendrá para conservar la apariencia del documento. Con valor TRUE el color de transparencia se convertirá en opaco, pudiendo cubrir algunos objetos. |
| [setAlignStrategy](#setAlignStrategy-byte-) | Estrategia para alinear texto. Este parámetro tiene sentido solo cuando la bandera {@code AlignText} está establecida en true. |
| [setAlignText](#setAlignText-boolean-) | Esta bandera controla la alineación del texto en el documento convertido. Por defecto, la conversión de documentos no afecta la alineación del texto y lo deja tal como está. Pero en algunos casos la sustitución de fuentes provoca solapamiento de texto o espacios extra en el documento convertido. Cuando esta bandera está activada se realizarán operaciones especiales de alineación. Esta bandera debe activarse solo para documentos que tengan problemas de texto superpuesto o espacios de texto extra, ya que su uso disminuye el rendimiento y, en algunos casos, podría corromper el contenido del texto. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | Obtiene/establece la ejecución de flujos de imagen en modo asíncrono. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | Obtiene o establece la configuración para el etiquetado automático durante la conversión de formato PDF. Los ajustes de etiquetado automático se utilizan para configurar el comportamiento del proceso de autoetiquetado, que normalmente se emplea para mejorar la accesibilidad y la estructura de un documento PDF durante la conversión a un formato PDF específico. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | Acción para imágenes con máscara suave. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | Acción para objetos que no pueden convertirse. |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | Estrategia(s) para excluir fuentes superfluas y reducir el tamaño del archivo del documento. Este parámetro tiene sentido solo cuando la bandera {@code OptimizeFileSize} está establecida en true. Por defecto se utiliza la combinación de estrategias {@code SubsetFonts} y {@code RemoveDuplicatedFonts}. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | Formato PDF. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | Establece el nombre de archivo del perfil icc. En caso de null se utiliza el perfil icc predeterminado. |
| [setLogFileName](#setLogFileName-java.lang.String-) | Ruta al archivo donde se almacenarán los comentarios. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | Flujo donde se almacenarán los comentarios. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | ¿Está habilitado el modo de conversión de bajo consumo de memoria? |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | Establece una bandera que habilita/deshabilita el modo de conversión especial para obtener un documento PDF/A con tamaño de archivo reducido. Actualmente esta bandera afecta la optimización de fuentes usadas en el documento PDF; posiblemente, en el futuro, también se usará para activar la optimización de otras estructuras de datos, como gráficos. El conjunto de esta bandera y modo podría reducir significativamente el tamaño del archivo, pero al mismo tiempo podría disminuir notablemente el rendimiento de la conversión. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | Obtiene o establece el {@link OutputIntent} para la conversión de formato PDF. El {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) especifica el dispositivo de salida o condición prevista para la cual se está preparando el documento PDF. Se utiliza para garantizar que los colores del documento se rendericen correctamente en el dispositivo de destino. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | Establece el modo de análisis de fuentes por página habilitado. Valor predeterminado = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Estrategia para procesar símbolos del Área de Uso Privado (PUA) de Unicode. |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Estrategia para copiar datos de codificación para fuentes simbólicas si la fuente TrueType simbólica tiene más de una subtabla de codificación. |
| [setTransferInfo](#setTransferInfo-boolean-) | Obtiene o establece si se deben pasar datos de Info a Metadata al convertir a PDF 2.0. Verdadero por defecto. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | Acción para objetos de imagen enmascarados |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | Valor predeterminado FALSE y el color de transparencia se mantendrá para conservar la apariencia del documento. Con valor TRUE el color de transparencia se convertirá en opaco, pudiendo cubrir algunos objetos. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | Establece la resolución durante la conversión de imágenes transparentes. A mayor resolución, menor velocidad de conversión. El valor predeterminado es 300. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Reglas para resolver problemas con el mapeo Unicode. Puede ser null. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Constructor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Constructor

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

Estrategia para alinear texto. Este parámetro tiene sentido solo cuando la bandera {@code AlignText} está establecida en true.

**Returns:**
Elemento SegmentAlignStrategy @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

Esta bandera controla la alineación del texto en el documento convertido. Por defecto, la conversión de documentos no afecta la alineación del texto y lo deja tal como está. Pero en algunos casos la sustitución de fuentes provoca solapamiento de texto o espacios extra en el documento convertido. Cuando esta bandera está activada se realizarán operaciones especiales de alineación. Esta bandera debe activarse solo para documentos que tengan problemas de texto superpuesto o espacios de texto extra, ya que su uso disminuye el rendimiento y, en algunos casos, podría corromper el contenido del texto.

**Returns:**
valor booleano

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

Obtiene o establece la configuración para el etiquetado automático durante la conversión de formato PDF. Los ajustes de etiquetado automático se utilizan para configurar el comportamiento del proceso de autoetiquetado, que normalmente se emplea para mejorar la accesibilidad y la estructura de un documento PDF durante la conversión a un formato PDF específico.

**Returns:**
Instancia de AutoTaggingSettings

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

Acción para imágenes con máscara suave.

**Returns:**
valor int

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

Obtiene el objeto PdfFormatConversionOptions con los parámetros predeterminados.

**Returns:**
Objeto PdfFormatConversionOptions

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

Acción para objetos que no pueden convertirse.

**Returns:**
Elemento ConvertErrorAction @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

Estrategia(s) para excluir fuentes superfluas y reducir el tamaño del archivo del documento. Este parámetro tiene sentido solo cuando la bandera {@code OptimizeFileSize} está establecida en true. Por defecto se utiliza la combinación de estrategias {@code SubsetFonts} y {@code RemoveDuplicatedFonts}.

**Returns:**
Valor byte @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

Opciones para los casos en que no es posible incrustar algunas fuentes en el documento PDF.

**Returns:**
Objeto FontEmbeddingOptions

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

Formato PDF.

**Returns:**
Elemento PdfFormat @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

Obtiene el nombre de archivo del perfil icc. En caso de null se utiliza el perfil icc predeterminado.

**Returns:**
Objeto String

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

Ruta al archivo donde se almacenarán los comentarios.

**Returns:**
Objeto String

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

Flujo donde se almacenarán los comentarios.

**Returns:**
Objeto OutputStream

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

Contiene banderas para controlar el proceso de conversión PDF/A en casos en que el documento fuente no corresponde a la especificación PDF/A.

**Returns:**
Objeto PdfANonSpecificationFlags

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

Esta propiedad es out-property. Contiene todas las fuentes (nombres de fuentes) que no se encontraron en el equipo en la última conversión PDF/A.

**Returns:**
Matriz de cadenas

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

Obtiene una bandera que habilita/deshabilita el modo de conversión especial para obtener un documento PDF/A con tamaño de archivo reducido. Actualmente esta bandera afecta la optimización de fuentes usadas en el documento PDF; posiblemente, en el futuro, también se usará para activar la optimización de otras estructuras de datos, como gráficos. El conjunto de esta bandera y modo podría reducir significativamente el tamaño del archivo, pero al mismo tiempo podría disminuir notablemente el rendimiento de la conversión.

**Returns:**
valor booleano

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

Obtiene o establece el {@link OutputIntent} para la conversión de formato PDF. El {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) especifica el dispositivo de salida o condición prevista para la cual se está preparando el documento PDF. Se utiliza para garantizar que los colores del documento se rendericen correctamente en el dispositivo de destino.

**Returns:**
Instancia OutputIntent

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Estrategia para procesar símbolos del Área de Uso Privado (PUA) de Unicode.

**Returns:**
Elemento PuaProcessingStrategy @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

Estrategia para copiar datos de codificación para fuentes simbólicas si la fuente TrueType simbólica tiene más de una subtabla de codificación.

**Returns:**
Objeto PdfASymbolicFontEncodingStrategy

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

Acción para objetos de imagen enmascarados

**Returns:**
Elemento ConvertTransparencyAction @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

Establece la resolución durante la conversión de imágenes transparentes. A mayor resolución, menor velocidad de conversión. El valor predeterminado es 300.

**Returns:**
Valor de resolución

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Reglas para resolver problemas con el mapeo Unicode. Puede ser null.

**Returns:**
Objeto ToUnicodeProcessingRules

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

Obtiene/establece la ejecución de flujos de imagen en modo asíncrono.

**Returns:**
valor booleano

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

¿Está habilitado el modo de conversión de bajo consumo de memoria?

**Returns:**
valor booleano

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

¿Está habilitado el modo de análisis de fuentes por página? Valor predeterminado = false

**Returns:**
valor booleano

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

Obtiene o establece si se deben pasar datos de Info a Metadata al convertir a PDF 2.0. Verdadero por defecto.

**Returns:**
valor booleano

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

Valor predeterminado FALSE y el color de transparencia se mantendrá para conservar la apariencia del documento. Con valor TRUE el color de transparencia se convertirá en opaco, pudiendo cubrir algunos objetos.

**Returns:**
valor booleano

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

Estrategia para alinear texto. Este parámetro tiene sentido solo cuando la bandera {@code AlignText} está establecida en true.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignStrategy |  | Elemento SegmentAlignStrategy @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

Esta bandera controla la alineación del texto en el documento convertido. Por defecto, la conversión de documentos no afecta la alineación del texto y lo deja tal como está. Pero en algunos casos la sustitución de fuentes provoca solapamiento de texto o espacios extra en el documento convertido. Cuando esta bandera está activada se realizarán operaciones especiales de alineación. Esta bandera debe activarse solo para documentos que tengan problemas de texto superpuesto o espacios de texto extra, ya que su uso disminuye el rendimiento y, en algunos casos, podría corromper el contenido del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

Obtiene/establece la ejecución de flujos de imagen en modo asíncrono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
Obtiene o establece la configuración para el etiquetado automático durante la conversión de formato PDF. Los ajustes de etiquetado automático se utilizan para configurar el comportamiento del proceso de autoetiquetado, que normalmente se emplea para mejorar la accesibilidad y la estructura de un documento PDF durante la conversión a un formato PDF específico.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
Acción para imágenes con máscara suave.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
Acción para objetos que no pueden convertirse.

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

Estrategia(s) para excluir fuentes superfluas y reducir el tamaño del archivo del documento. Este parámetro tiene sentido solo cuando la bandera {@code OptimizeFileSize} está establecida en true. Por defecto se utiliza la combinación de estrategias {@code SubsetFonts} y {@code RemoveDuplicatedFonts}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
Formato PDF.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
Establece el nombre de archivo del perfil icc. En caso de null se utiliza el perfil icc predeterminado.

### setLogFileName {#setLogFileName-java.lang.String-}
Ruta al archivo donde se almacenarán los comentarios.

### setLogStream {#setLogStream-java.io.OutputStream-}
Flujo donde se almacenarán los comentarios.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

¿Está habilitado el modo de conversión de bajo consumo de memoria?

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

Establece una bandera que habilita/deshabilita el modo de conversión especial para obtener un documento PDF/A con tamaño de archivo reducido. Actualmente esta bandera afecta la optimización de fuentes usadas en el documento PDF; posiblemente, en el futuro, también se usará para activar la optimización de otras estructuras de datos, como gráficos. El conjunto de esta bandera y modo podría reducir significativamente el tamaño del archivo, pero al mismo tiempo podría disminuir notablemente el rendimiento de la conversión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
Obtiene o establece el {@link OutputIntent} para la conversión de formato PDF. El {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) especifica el dispositivo de salida o condición prevista para la cual se está preparando el documento PDF. Se utiliza para garantizar que los colores del documento se rendericen correctamente en el dispositivo de destino.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

Establece el modo de análisis de fuentes por página habilitado. Valor predeterminado = false

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| b |  | valor booleano |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Estrategia para procesar símbolos del Área de Uso Privado (PUA) de Unicode.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento PuaProcessingStrategy @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
Estrategia para copiar datos de codificación para fuentes simbólicas si la fuente TrueType simbólica tiene más de una subtabla de codificación.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

Obtiene o establece si se deben pasar datos de Info a Metadata al convertir a PDF 2.0. Verdadero por defecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
Acción para objetos de imagen enmascarados

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

Valor predeterminado FALSE y el color de transparencia se mantendrá para conservar la apariencia del documento. Con valor TRUE el color de transparencia se convertirá en opaco, pudiendo cubrir algunos objetos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

Establece la resolución durante la conversión de imágenes transparentes. A mayor resolución, menor velocidad de conversión. El valor predeterminado es 300.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpi |  | Valor de resolución |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Reglas para resolver problemas con el mapeo Unicode. Puede ser null.
