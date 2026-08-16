---
title: "IDocument"
linktitle: "IDocument"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "interfaz que representa un documento PDF"
type: docs
weight: 2230
url: /es/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

interfaz que representa un documento PDF

## Métodos

| Método | Descripción |
| --- | --- |
| [afterImport](#afterImport--) | Enumere todas las anotaciones registradas y llame a AfterImport para cada una de ellas. |
| [bindXml](#bindXml-java.io.InputStream-) | Vincular xml al documento |
| [bindXml](#bindXml-java.lang.String-) | Vincular xml al documento |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Vincular xml/xsl al documento |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Cambia las contraseñas del documento. |
| [check](#check-boolean-) | Valida el documento. |
| [close](#close--) | Cierra todos los recursos utilizados por este documento. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir el documento a un documento buscable. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Convertir el documento y guardar los errores en el archivo especificado. <p> Esto permite mostrar/ocultar texto buscable en la página. El valor predeterminado es FALSE. Esto permite obtener la imagen original del pdf. El valor predeterminado es FALSE. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Convertir el documento y guardar los errores en el archivo especificado. <p> Esto permite mostrar/ocultar texto buscable en la página. El valor predeterminado es FALSE. Esto permite obtener la imagen original del pdf. El valor predeterminado es FALSE. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Convertir el documento usando opciones de conversión especificadas |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Convertir el documento y guardar los errores en el archivo especificado. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Método interno |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos. |
| [decrypt](#decrypt--) | Desencripta el documento. |
| [dispose](#dispose--) | Obsoleto. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encripta el documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Encripta el documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Encripta el documento. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exporta todas las anotaciones del documento a un archivo XFDF |
| [flatten](#flatten--) | Elimina todos los campos (y anotaciones) del documento y coloca sus valores en su lugar. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Elimina todos los campos del documento y coloca sus valores en su lugar. |
| [flattenTransparency](#flattenTransparency--) | Reemplaza el contenido transparente con gráficos raster y vectoriales no transparentes. |
| [freeMemory](#freeMemory--) | Limpia la memoria |
| [getActions](#getActions--) | Obtiene las acciones del documento. |
| [getBackground](#getBackground--) | Obtiene el color de fondo del documento. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Devuelve el valor del elemento del diccionario del catálogo. |
| [getCollection](#getCollection--) | Obtiene la colección del documento. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Obtiene la configuración de seguridad si el documento está cifrado. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Obtiene un controlador de seguridad personalizado. |
| [getDefaultCopier](#getDefaultCopier--) | Devuelve el copiado usado para copiar páginas a este documento. |
| [getDestinations](#getDestinations--) | Obtiene la colección de destinos. |
| [getDirection](#getDirection--) | Obtiene el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
| [getDuplex](#getDuplex--) | Obtiene o establece la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Obtiene la colección de archivos incrustados en el documento. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar cuyo indicador IsEmbedded está establecido en verdadero. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Obtiene o establece el indicador para gestionar la sanitización de campos de firma. |
| [getEngineDoc](#getEngineDoc--) | Instancia de IPdfDocument usada para acceder a la estructura interna del documento. |
| [getFileName](#getFileName--) | Nombre del archivo PDF que causó este documento |
| [getForm](#getForm--) | Obtiene el Acro Form del documento. |
| [getId](#getId--) | Obtiene el ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Obtiene o establece el indicador de ignorar errores en los archivos fuente. |
| [getInfo](#getInfo--) | Obtiene la información del documento. |
| [getLogicalStructure](#getLogicalStructure--) | Obtiene la estructura lógica del documento. |
| [getMetadata](#getMetadata--) | Metadatos del documento. |
| [getMetadataStream](#getMetadataStream--) | Devuelve el flujo de metadatos sin procesar |
| [getNamedDestinations](#getNamedDestinations--) | Colección de Destinos nombrados en el documento. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Obtiene el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
| [getObjectById](#getObjectById-java.lang.String-) | Obtiene un objeto con el ID especificado en el documento. |
| [getOpenAction](#getOpenAction--) | Obtiene la acción realizada al abrir el documento. |
| [getOptimizeSize](#getOptimizeSize--) | Obtiene la bandera de optimización. |
| [getOutlines](#getOutlines--) | Obtiene los contornos del documento. |
| [getPageInfo](#getPageInfo--) | Obtiene la información de la página.(solo para generador, no se completa al leer el documento) |
| [getPageLabels](#getPageLabels--) | Obtiene las etiquetas de página en el documento. |
| [getPageLayout](#getPageLayout--) | Obtiene el diseño de página que se utilizará cuando se abra el documento. |
| [getPageMode](#getPageMode--) | Obtiene el modo de página, especificando cómo debe mostrarse el documento al abrirse. |
| [getPages](#getPages--) | Obtiene la colección de páginas del documento. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | Obtiene los permisos del documento. |
| [getPrintScaling](#getPrintScaling--) | Obtiene la opción de manejo de escala de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [getTaggedContent](#getTaggedContent--) | Obtiene acceso al contenido TaggedPdf. |
| [getVersion](#getVersion--) | Obtiene una versión de PDF del encabezado del archivo PDF. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Obtener metadatos XMP del documento. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importa anotaciones del archivo XFDF al documento. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Notificación sobre fuentes faltantes al procesar documentos |
| [isCenterWindow](#isCenterWindow--) | Obtiene la bandera que especifica si la posición de la ventana del documento se centrará en la pantalla. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Obtiene la bandera que especifica si la barra de título de la ventana del documento debe mostrar el título del documento. |
| [isEncrypted](#isEncrypted--) | Obtiene el estado cifrado del documento. |
| [isFitWindow](#isFitWindow--) | Obtiene la bandera que especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. |
| [isHideMenubar](#isHideMenubar--) | Obtiene la bandera que indica si la barra de menús debe ocultarse cuando el documento está activo. |
| [isHideToolBar](#isHideToolBar--) | Obtiene la bandera que indica si la barra de herramientas debe ocultarse cuando el documento está activo. |
| [isHideWindowUI](#isHideWindowUI--) | Obtiene o establece la bandera que indica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. |
| [isLinearized](#isLinearized--) | Obtiene o establece un valor que indica si el documento está linealizado. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Por defecto, el método save cierra los flujos internos y libera los recursos de memoria. Podemos realizar algunas operaciones y continuar trabajando con el documento después del método save si el parámetro ManualDispose está habilitado. |
| [isPdfaCompliant](#isPdfaCompliant--) | Obtiene si el documento es compatible con pdf/a. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Obtiene si el documento es compatible con pdfua. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Obtiene una bandera que indica si el tamaño de página PDF debe usarse para seleccionar la bandeja de papel de entrada. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Obtiene o establece si el documento es compatible con pdfa. |
| [optimize](#optimize--) | Linealiza el documento con el fin de - abrir la primera página lo más rápido posible; - mostrar la página siguiente o seguir el enlace a la página siguiente lo más rápido posible; - mostrar la página de forma incremental a medida que llega cuando los datos de una página se entregan a través de un canal lento (mostrar primero los datos más útiles); - permitir que la interacción del usuario, como seguir un enlace, se realice incluso antes de que se haya recibido y mostrado la página completa. |
| [optimizeResources](#optimizeResources--) | Optimiza los recursos en el documento: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimiza los recursos en el documento según la estrategia de optimización definida. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organiza los nodos del árbol de páginas en un documento en un árbol balanceado. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organiza los nodos del árbol de páginas en un documento en un árbol balanceado. |
| [processParagraphs](#processParagraphs--) | Almacena el documento en un flujo. |
| [removeMetadata](#removeMetadata--) | Elimina los metadatos del documento. |
| [removePdfaCompliance](#removePdfaCompliance--) | Elimina la compatibilidad pdfa del documento |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Elimina la compatibilidad pdfUa del documento |
| [repair](#repair--) | Repara el documento dañado. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | Guardar documento de forma incremental (p.ej. |
| [save](#save-java.io.OutputStream-) | Almacena el documento en un flujo. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Guardar documento |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Guarda el documento con un nuevo nombre configurando sus opciones de guardado. |
| [save](#save-java.lang.String-) | Guarda el documento en el archivo especificado. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Guarda el documento con un nuevo nombre configurando sus opciones de guardado. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Guarda de forma incremental el Documento PDF en el flujo especificado. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Guarda de forma incremental el Documento PDF en el flujo especificado. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Guarda de forma incremental el Documento PDF en el flujo especificado. |
| [saveXml](#saveXml-java.lang.String-) | Guardar documento en XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Envía ciertas páginas del documento al dispositivo de documento para su procesamiento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Envía todo el documento al dispositivo de documento para su procesamiento. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Estableciendo la bandera para fijar la fuente determinada por el programa en caso de ausencia de fuente. |
| [setBackground](#setBackground-java.awt.Color-) | Establece el color de fondo del documento. |
| [setCenterWindow](#setCenterWindow-boolean-) | Establece la bandera que especifica si la posición de la ventana del documento se centrará en la pantalla. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Establece la colección del documento. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Obtiene el parámetro de conversión para el convertidor pdf/ua (Convierte solo Metadatos y Catálogo del Documento si se establece en verdadero). |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Establece la bandera que especifica si la barra de título de la ventana del documento debe mostrar el título del documento. |
| [setDuplex](#setDuplex-int-) | Obtiene o establece la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar cuyo indicador IsEmbedded está establecido en verdadero. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Obtiene o establece el indicador para gestionar la sanitización de campos de firma. |
| [setFitWindow](#setFitWindow-boolean-) | Establece la bandera que especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada. |
| [setHideMenubar](#setHideMenubar-boolean-) | Establece la bandera que especifica si la barra de menú debe ocultarse cuando el documento está activo. |
| [setHideToolBar](#setHideToolBar-boolean-) | Establece la bandera que especifica si la barra de herramientas debe ocultarse cuando el documento está activo. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Establece la bandera que especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | Establece un valor que indica si el documento está linealizado. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Por defecto, el método save cierra los flujos internos y libera los recursos de memoria. Podemos realizar algunas operaciones y continuar trabajando con el documento después de que se llame al método save si este parámetro ManualDispose está habilitado. Pero se recomienda encarecidamente llamar al método dispose cuando la instancia Document ya no sea necesaria. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Establece la acción que se realiza al abrir el documento. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Establece la bandera de optimización. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Establece la información de la página (solo para generador, no se completa al leer el documento). |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Establece el diseño de página que se utilizará cuando se abra el documento. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Establece el modo de página, especificando cómo debe mostrarse el documento al abrirse. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Establece una bandera que especifica si el tamaño de página PDF debe usarse para seleccionar la bandeja de papel de entrada. |
| [setPrintScaling](#setPrintScaling-int-) | Establece la opción de manejo de escalado de impresión que se usará al imprimir el archivo desde el cuadro de diálogo de impresión. |
| [setTitle](#setTitle-java.lang.String-) | Establecer título para el documento PDF |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Establecer metadatos XMP del documento. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Obtiene o establece si el documento es compatible con pdfa. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validar el documento en el archivo especificado. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validar el documento en el archivo especificado. |

### afterImport {#afterImport--}
```
void afterImport()
```

Enumere todas las anotaciones registradas y llame a AfterImport para cada una de ellas.

### bindXml {#bindXml-java.io.InputStream-}
Vincular xml al documento

### bindXml {#bindXml-java.lang.String-}
Vincular xml al documento

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Vincular xml/xsl al documento

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Cambia las contraseñas del documento.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
```

Valida el documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| doRepair |  | Si true, los problemas encontrados serán reparados. |

**Returns:**
valor booleano

### close {#close--}
```
void close()
```

Cierra todos los recursos utilizados por este documento.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir el documento a un documento buscable.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Convertir el documento y guardar los errores en el archivo especificado. <p> Esto permite mostrar/ocultar texto buscable en la página. El valor predeterminado es FALSE. Esto permite obtener la imagen original del pdf. El valor predeterminado es FALSE.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Convertir el documento y guardar los errores en el archivo especificado. <p> Esto permite mostrar/ocultar texto buscable en la página. El valor predeterminado es FALSE. Esto permite obtener la imagen original del pdf. El valor predeterminado es FALSE.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Convertir el documento usando opciones de conversión especificadas

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convertir el documento y guardar los errores en el archivo especificado.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Convertir el documento y guardar los errores en el archivo especificado.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Método interno

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir el documento a un documento buscable y omitir los errores de hochr que no pueden ser convertidos.

### decrypt {#decrypt--}
```
void decrypt()
```

Desencripta el documento.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Obsoleto.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Encripta el documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Encripta el documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Encripta el documento.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exporta todas las anotaciones del documento a un archivo XFDF

### flatten {#flatten--}
```
void flatten()
```

Elimina todos los campos (y anotaciones) del documento y coloca sus valores en su lugar.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Elimina todos los campos del documento y coloca sus valores en su lugar.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

Reemplaza el contenido transparente con gráficos raster y vectoriales no transparentes.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

Limpia la memoria

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

Obtiene las acciones del documento.

**Returns:**
DocumentActionCollection objeto

### getBackground {#getBackground--}
```
Color getBackground()
```

Obtiene el color de fondo del documento.

**Returns:**
java.awt.Color objeto

### getCatalogValue {#getCatalogValue-java.lang.String-}
Devuelve el valor del elemento del diccionario del catálogo.

### getCollection {#getCollection--}
```
Collection getCollection()
```

Obtiene la colección del documento.

**Returns:**
Collection objeto

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

Obtiene la configuración de seguridad si el documento está cifrado.

**Returns:**
CryptoAlgorithm elemento o null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Obtiene un controlador de seguridad personalizado.

**Returns:**
ICustomSecurityHandler instancia

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

Devuelve el copiado usado para copiar páginas a este documento.

**Returns:**
Copier objeto

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

Obtiene la colección de destinos.

**Returns:**
DestinationCollection objeto

### getDirection {#getDirection--}
```
Direction getDirection()
```

Obtiene el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda).

**Returns:**
Direction elemento

### getDuplex {#getDuplex--}
```
int getDuplex()
```

Obtiene o establece la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión.

**Returns:**
PrintDuplex elemento

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

Obtiene la colección de archivos incrustados en el documento.

**Returns:**
EmbeddedFileCollection objeto

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar cuyo indicador IsEmbedded está establecido en verdadero.

**Returns:**
valor booleano

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

Obtiene o establece el indicador para gestionar la sanitización de campos de firma.

**Returns:**
valor booleano

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instancia de IPdfDocument usada para acceder a la estructura interna del documento.

**Returns:**
IPdfDocument objeto

### getFileName {#getFileName--}
```
String getFileName()
```

Nombre del archivo PDF que causó este documento

**Returns:**
Objeto String

### getForm {#getForm--}
```
Form getForm()
```

Obtiene el Acro Form del documento.

**Returns:**
Form objeto

### getId {#getId--}
```
Id getId()
```

Obtiene el ID.

**Returns:**
Id objeto

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

Obtiene o establece el indicador de ignorar errores en los archivos fuente.

**Returns:**
valor booleano

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

Obtiene la información del documento.

**Returns:**
DocumentInfo objeto

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

Obtiene la estructura lógica del documento.

**Returns:**
RootElement objeto

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

Metadatos del documento.

**Returns:**
Metadata objeto

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Devuelve el flujo de metadatos sin procesar

**Returns:**
IPdfStreamAccessor objeto

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

Colección de Destinos nombrados en el documento.

**Returns:**
NamedDestinationCollection instancia

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

Obtiene el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa.

**Returns:**
PageMode elemento

### getObjectById {#getObjectById-java.lang.String-}
Obtiene un objeto con el ID especificado en el documento.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

Obtiene la acción realizada al abrir el documento.

**Returns:**
IAppointment objeto

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

Obtiene la bandera de optimización.

**Returns:**
valor booleano

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

Obtiene los contornos del documento.

**Returns:**
Objeto OutlineCollection

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

Obtiene la información de la página.(solo para generador, no se completa al leer el documento)

**Returns:**
La información de la página.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

Obtiene las etiquetas de página en el documento.

**Returns:**
Objeto PageLabelCollection

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

Obtiene el diseño de página que se utilizará cuando se abra el documento.

**Returns:**
Elemento PageLayout

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

Obtiene el modo de página, especificando cómo debe mostrarse el documento al abrirse.

**Returns:**
PageMode elemento

### getPages {#getPages--}
```
PageCollection getPages()
```

Obtiene la colección de páginas del documento.

**Returns:**
valor booleano

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
Elemento PdfFormat

### getPermissions {#getPermissions--}
```
int getPermissions()
```

Obtiene los permisos del documento.

**Returns:**
valor int

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

Obtiene la opción de manejo de escala de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión.

**Returns:**
Elemento PrintScaling

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

Obtiene acceso al contenido TaggedPdf.

**Returns:**
Instancia ITaggedContent

### getVersion {#getVersion--}
```
String getVersion()
```

Obtiene una versión de PDF del encabezado del archivo PDF.

**Returns:**
Objeto String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Obtener metadatos XMP del documento.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importa anotaciones del archivo XFDF al documento.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

Notificación sobre fuentes faltantes al procesar documentos

**Returns:**
valor booleano

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

Obtiene la bandera que especifica si la posición de la ventana del documento se centrará en la pantalla.

**Returns:**
valor booleano

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente.

**Returns:**
Valor booleano por defecto falso.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

Obtiene la bandera que especifica si la barra de título de la ventana del documento debe mostrar el título del documento.

**Returns:**
valor booleano

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

Obtiene el estado cifrado del documento.

**Returns:**
valor booleano

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

Obtiene la bandera que especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada.

**Returns:**
valor booleano

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

Obtiene la bandera que indica si la barra de menús debe ocultarse cuando el documento está activo.

**Returns:**
valor booleano

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

Obtiene la bandera que indica si la barra de herramientas debe ocultarse cuando el documento está activo.

**Returns:**
valor booleano

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

Obtiene o establece la bandera que indica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo.

**Returns:**
valor booleano

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

Obtiene o establece un valor que indica si el documento está linealizado.

**Returns:**
valor booleano

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

Por defecto, el método save cierra los flujos internos y libera los recursos de memoria. Podemos realizar algunas operaciones y continuar trabajando con el documento después del método save si el parámetro ManualDispose está habilitado.

**Returns:**
Valor booleano. (Valor predeterminado == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

Obtiene si el documento es compatible con pdf/a.

**Returns:**
valor booleano

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

Obtiene si el documento es compatible con pdfua.

**Returns:**
valor booleano

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

Obtiene una bandera que indica si el tamaño de página PDF debe usarse para seleccionar la bandeja de papel de entrada.

**Returns:**
valor booleano

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

Obtiene o establece si el documento es compatible con pdfa.

**Returns:**
valor booleano

### optimize {#optimize--}
```
void optimize()
```

Linealiza el documento con el fin de - abrir la primera página lo más rápido posible; - mostrar la página siguiente o seguir el enlace a la página siguiente lo más rápido posible; - mostrar la página de forma incremental a medida que llega cuando los datos de una página se entregan a través de un canal lento (mostrar primero los datos más útiles); - permitir que la interacción del usuario, como seguir un enlace, se realice incluso antes de que se haya recibido y mostrado la página completa.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

Optimiza los recursos en el documento: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimiza los recursos en el documento según la estrategia de optimización definida.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

Organiza los nodos del árbol de páginas en un documento en un árbol balanceado.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organiza los nodos del árbol de páginas en un documento en un árbol balanceado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodesNumInSubtrees |  | Número deseado de subnodos. El valor predeterminado es diez. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

Almacena el documento en un flujo.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

Elimina los metadatos del documento.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

Elimina la compatibilidad pdfa del documento

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

Elimina la compatibilidad pdfUa del documento

### repair {#repair--}
```
void repair()
```

Repara el documento dañado.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

Guardar documento de forma incremental (p.ej.

### save {#save-java.io.OutputStream-}
Almacena el documento en un flujo.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Guardar documento

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Guarda el documento con un nuevo nombre configurando sus opciones de guardado.

### save {#save-java.lang.String-}
Guarda el documento en el archivo especificado.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
Guarda el documento con un nuevo nombre configurando sus opciones de guardado.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
Guarda de forma incremental el Documento PDF en el flujo especificado.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
Guarda de forma incremental el Documento PDF en el flujo especificado.

### saveIncrementally {#saveIncrementally-java.lang.String-}
Guarda de forma incremental el Documento PDF en el flujo especificado.

### saveXml {#saveXml-java.lang.String-}
Guardar documento en XML.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Envía ciertas páginas del documento al dispositivo de documento para su procesamiento.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Envía todo el documento al dispositivo de documento para su procesamiento.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Envía todo el documento al dispositivo de documento para su procesamiento.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Envía todo el documento al dispositivo de documento para su procesamiento.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Estableciendo la bandera para fijar la fuente determinada por el programa en caso de ausencia de fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | valor booleano |

### setBackground {#setBackground-java.awt.Color-}
Establece el color de fondo del documento.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

Establece la bandera que especifica si la posición de la ventana del documento se centrará en la pantalla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Establece la colección del documento.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

Obtiene el parámetro de conversión para el convertidor pdf/ua (Convierte solo Metadatos y Catálogo del Documento si se establece en verdadero).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Establece el orden de lectura del texto: L2R (de izquierda a derecha) o R2L (de derecha a izquierda).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor booleano por defecto falso. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

Establece la bandera que especifica si la barra de título de la ventana del documento debe mostrar el título del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

Obtiene o establece la opción de manejo del modo dúplex de impresión para usar al imprimir el archivo desde el cuadro de diálogo de impresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | PrintDuplex elemento |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar cuyo indicador IsEmbedded está establecido en verdadero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

Obtiene o establece el indicador para gestionar la sanitización de campos de firma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

Establece la bandera que especifica si la ventana del documento debe redimensionarse para ajustarse a la primera página mostrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

Establece la bandera que especifica si la barra de menú debe ocultarse cuando el documento está activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

Establece la bandera que especifica si la barra de herramientas debe ocultarse cuando el documento está activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

Establece la bandera que especifica si los elementos de la interfaz de usuario deben ocultarse cuando el documento está activo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

Establece un valor que indica si el documento está linealizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Por defecto, el método save cierra los flujos internos y libera los recursos de memoria. Podemos realizar algunas operaciones y continuar trabajando con el documento después de que se llame al método save si este parámetro ManualDispose está habilitado. Pero se recomienda encarecidamente llamar al método dispose cuando la instancia Document ya no sea necesaria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| manualDisposeEnabled |  | Valor booleano. (Valor predeterminado == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Establece el modo de página, especificando cómo mostrar el documento al salir del modo de pantalla completa.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
Establece la acción que se realiza al abrir el documento.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
void setOptimizeSize(boolean value)
```

Establece la bandera de optimización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Establece la información de la página (solo para generador, no se completa al leer el documento).

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Establece el diseño de página que se utilizará cuando se abra el documento.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Establece el modo de página, especificando cómo debe mostrarse el documento al abrirse.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
void setPickTrayByPdfSize(boolean value)
```

Establece una bandera que especifica si el tamaño de página PDF debe usarse para seleccionar la bandeja de papel de entrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

Establece la opción de manejo de escalado de impresión que se usará al imprimir el archivo desde el cuadro de diálogo de impresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | PrintDuplex elemento |

### setTitle {#setTitle-java.lang.String-}
Establecer título para el documento PDF

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Establecer metadatos XMP del documento.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

Obtiene o establece si el documento es compatible con pdfa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validar el documento en el archivo especificado.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validar el documento en el archivo especificado.
