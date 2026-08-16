---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para acceder a la meta información de un documento PDF."
type: docs
weight: 490
url: /es/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

Representa una clase para acceder a la meta información de un documento PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados. |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Inicializa la fachada. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Inicializa la fachada. |
| [clearInfo](#clearInfo--) | Borra toda la información meta del documento PDF. |
| [close](#close--) | Cierra todos los recursos utilizados por este documento. |
| [dispose](#dispose--) | Cierra todos los recursos utilizados por esta instancia. Este método está obsoleto, use close() en su lugar. |
| [getAuthor](#getAuthor--) | Obtiene la información del Autor del documento PDF. |
| [getCreationDate](#getCreationDate--) | Obtiene la información de CreationDate del documento PDF. |
| [getCreator](#getCreator--) | Obtiene la información del Creator del documento PDF. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | Obtiene la configuración de privilegios del documento PDF. |
| [getHeader](#getHeader--) | <p> Obtiene la información personalizada del documento PDF. </p> |
| [getInputFile](#getInputFile--) | Obtiene el archivo de entrada. |
| [getInputStream](#getInputStream--) | Obtiene el flujo de entrada. |
| [getKeywords](#getKeywords--) | Obtiene la información de palabras clave del documento PDF. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | Obtiene información personalizada del documento PDF con el nombre de la propiedad. Si no hay ninguna propiedad que coincida con el nombre, devolverá una cadena vacía. |
| [getModDate](#getModDate--) | Obtiene la información de fecha ModDate del documento PDF. |
| [getNumberOfPages](#getNumberOfPages--) | Obtiene el número de páginas del documento. |
| [getPageHeight](#getPageHeight-int-) | Obtiene la altura de la página especificada. |
| [getPageRotation](#getPageRotation-int-) | Obtiene la rotación de la página especificada. |
| [getPageWidth](#getPageWidth-int-) | Obtiene el ancho de la página especificada. |
| [getPageXOffset](#getPageXOffset-int-) | Obtiene el desplazamiento horizontal del área de visualización de la página especificada. |
| [getPageYOffset](#getPageYOffset-int-) | Obtiene el desplazamiento vertical del área de visualización de la página especificada. |
| [getPasswordType](#getPasswordType--) | Devuelve el tipo de contraseña que se pasó para crear la instancia de PdfFileInfo. Consulte los valores posibles en {@code PasswordType}. Tenga en cuenta que el documento PDF puede abrirse usando tanto la contraseña de usuario (o apertura) como la contraseña de propietario (o permisos, edición). |
| [getPdfVersion](#getPdfVersion--) | Obtiene la información de versión del documento PDF. |
| [getProducer](#getProducer--) | Obtiene la información del productor del documento PDF. |
| [getSubject](#getSubject--) | Obtiene la información del asunto del documento PDF. |
| [getTitle](#getTitle--) | Obtiene la información del título del documento PDF. |
| [getUseStrictValidation](#getUseStrictValidation--) | Utiliza reglas de validación estrictas mediante la propiedad {@code IsPdfFile}({@link #isPdfFile}). |
| [hasCollection](#hasCollection--) | Devuelve true si el archivo de entrada actual es un archivo 'Portfolio' que contiene una colección de archivos PDF. |
| [hasEditPassword](#hasEditPassword--) | Devuelve true si se necesita una contraseña para modificar los permisos o la propiedad de seguridad del documento. Tenga en cuenta que esta propiedad solo se puede leer si se proporcionó una contraseña válida en el constructor {@code PdfFileInfo}. En caso de que PasswordType sea Inaccessible (significa que se proporcionó una contraseña inválida), la lectura de esta propiedad fallará con {@code InvalidPasswordException}. |
| [hasOpenPassword](#hasOpenPassword--) | Devuelve true si se necesita una contraseña para abrir un documento PDF protegido con contraseña. |
| [isEncrypted](#isEncrypted--) | Comprueba si el documento PDF está encriptado. |
| [isPdfFile](#isPdfFile--) | Comprueba si la entrada fuente es un archivo PDF válido. |
| [save](#save-java.io.OutputStream-) | Guarda el documento PDF en el archivo especificado. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | Guardar el documento PDF actualizado en el flujo especificado. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | Guardar el documento PDF actualizado en el archivo especificado. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | Cambia las propiedades especificadas explícitamente estableciendo la información del archivo, las demás propiedades permanecen. |
| [setAuthor](#setAuthor-java.lang.String-) | Establece la información del Autor del documento PDF. |
| [setCreationDate](#setCreationDate-java.lang.String-) | Establece la información de CreationDate del documento PDF. |
| [setCreator](#setCreator-java.lang.String-) | Establece la información de Creator del documento PDF. |
| [setHeader](#setHeader-java.util.Map-) | Establece la información personalizada del documento PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Establece el archivo de entrada. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Establece el flujo de entrada. |
| [setKeywords](#setKeywords-java.lang.String-) | Establece la información de Keywords del documento PDF. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | Establece información personalizada del documento PDF. |
| [setModDate](#setModDate-java.lang.String-) | Establece la información de fecha ModDate del documento PDF. |
| [setSubject](#setSubject-java.lang.String-) | Establece la información de Subject del documento PDF. |
| [setTitle](#setTitle-java.lang.String-) | Establece la información de Title del documento PDF. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | Utiliza reglas de validación estrictas mediante la propiedad {@code IsPdfFile}({@link #isPdfFile}). |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Inicializa una nueva instancia de la clase com.aspose.pdf.facades.PdfFileInfo con valores predeterminados.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Inicializa la fachada.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Inicializa la fachada.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

Borra toda la información meta del documento PDF.

### close {#close--}
```
public void close()
```

Cierra todos los recursos utilizados por este documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Cierra todos los recursos utilizados por esta instancia. Este método está obsoleto, use close() en su lugar.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Obtiene la información del Autor del documento PDF.

**Returns:**
valor String

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

Obtiene la información de CreationDate del documento PDF.

**Returns:**
valor String

### getCreator {#getCreator--}
```
public String getCreator()
```

Obtiene la información del Creator del documento PDF.

**Returns:**
valor String

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

Obtiene la configuración de privilegios del documento PDF.

**Returns:**
La configuración de privilegios del documento PDF.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> Obtiene la información personalizada del documento PDF. </p>

**Returns:**
{@code Map<String, String>} objeto

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Obtiene el archivo de entrada.

**Returns:**
valor String

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Obtiene el flujo de entrada.

**Returns:**
Objeto InputStream

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Obtiene la información de palabras clave del documento PDF.

**Returns:**
valor String

### getMetaInfo {#getMetaInfo-java.lang.String-}
Obtiene información personalizada del documento PDF con el nombre de la propiedad. Si no hay ninguna propiedad que coincida con el nombre, devolverá una cadena vacía.

### getModDate {#getModDate--}
```
public String getModDate()
```

Obtiene la información de fecha ModDate del documento PDF.

**Returns:**
valor String

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

Obtiene el número de páginas del documento.

**Returns:**
valor int

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

Obtiene la altura de la página especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNum |  | Número de página. |

**Returns:**
La altura de la página.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

Obtiene la rotación de la página especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNum |  | Número de página. |

**Returns:**
La rotación de la página. El valor puede ser 0,90,180,270.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

Obtiene el ancho de la página especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNum |  | Número de página. |

**Returns:**
El ancho de la página.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

Obtiene el desplazamiento horizontal del área de visualización de la página especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNum |  | Número de página. |

**Returns:**
El desplazamiento horizontal desde el lado izquierdo de la página.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

Obtiene el desplazamiento vertical del área de visualización de la página especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNum |  | Número de página. |

**Returns:**
El desplazamiento vertical del área de visualización de la página.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

Devuelve el tipo de contraseña que se pasó para crear la instancia de PdfFileInfo. Consulte los valores posibles en {@code PasswordType}. Tenga en cuenta que el documento PDF puede abrirse usando tanto la contraseña de usuario (o apertura) como la contraseña de propietario (o permisos, edición).

**Returns:**
Elemento PasswordType @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

Obtiene la información de versión del documento PDF.

**Returns:**
La cadena de versión.

### getProducer {#getProducer--}
```
public String getProducer()
```

Obtiene la información del productor del documento PDF.

**Returns:**
valor String

### getSubject {#getSubject--}
```
public String getSubject()
```

Obtiene la información del asunto del documento PDF.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtiene la información del título del documento PDF.

**Returns:**
valor String

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

Utiliza reglas de validación estrictas mediante la propiedad {@code IsPdfFile}({@link #isPdfFile}).

**Returns:**
valor booleano

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

Devuelve true si el archivo de entrada actual es un archivo 'Portfolio' que contiene una colección de archivos PDF.

**Returns:**
valor booleano

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

Devuelve true si se necesita una contraseña para modificar los permisos o la propiedad de seguridad del documento. Tenga en cuenta que esta propiedad solo se puede leer si se proporcionó una contraseña válida en el constructor {@code PdfFileInfo}. En caso de que PasswordType sea Inaccessible (significa que se proporcionó una contraseña inválida), la lectura de esta propiedad fallará con {@code InvalidPasswordException}.

**Returns:**
valor booleano

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

Devuelve true si se necesita una contraseña para abrir un documento PDF protegido con contraseña.

**Returns:**
valor booleano

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Comprueba si el documento PDF está encriptado.

**Returns:**
valor booleano

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

Comprueba si la entrada fuente es un archivo PDF válido.

**Returns:**
valor booleano

### save {#save-java.io.OutputStream-}
Guarda el documento PDF en el archivo especificado.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
Guardar el documento PDF actualizado en el flujo especificado.

### saveNewInfo {#saveNewInfo-java.lang.String-}
Guardar el documento PDF actualizado en el archivo especificado.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
Cambia las propiedades especificadas explícitamente estableciendo la información del archivo, las demás propiedades permanecen.

### setAuthor {#setAuthor-java.lang.String-}
Establece la información del Autor del documento PDF.

### setCreationDate {#setCreationDate-java.lang.String-}
Establece la información de CreationDate del documento PDF.

### setCreator {#setCreator-java.lang.String-}
Establece la información de Creator del documento PDF.

### setHeader {#setHeader-java.util.Map-}
Establece la información personalizada del documento PDF.

### setInputFile {#setInputFile-java.lang.String-}
Establece el archivo de entrada.

### setInputStream {#setInputStream-java.io.InputStream-}
Establece el flujo de entrada.

### setKeywords {#setKeywords-java.lang.String-}
Establece la información de Keywords del documento PDF.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
Establece información personalizada del documento PDF.

### setModDate {#setModDate-java.lang.String-}
Establece la información de fecha ModDate del documento PDF.

### setSubject {#setSubject-java.lang.String-}
Establece la información de Subject del documento PDF.

### setTitle {#setTitle-java.lang.String-}
Establece la información de Title del documento PDF.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

Utiliza reglas de validación estrictas mediante la propiedad {@code IsPdfFile}({@link #isPdfFile}).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
