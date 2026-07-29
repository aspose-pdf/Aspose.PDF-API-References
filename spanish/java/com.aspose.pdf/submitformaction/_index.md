---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que describe la acción submit-form."
type: docs
weight: 4690
url: /es/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

Clase que describe la acción submit-form.

## Campos

| Campo | Descripción |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | Si se establece, cualquier valor de campo enviado que represente fechas se convertirá al formato estándar. |
| [EMBED_FORM](#EMBED_FORM) | Si se establece, la entrada F del FDF enviado será una especificación de archivo que contiene un flujo de archivo incrustado que representa el archivo PDF del cual se envía el FDF. |
| [EXCL_F_KEY](#EXCL_F_KEY) | Si se establece, el FDF enviado excluirá la entrada F. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | Si se establece, solo incluirá aquellas anotaciones de marcado cuya entrada T coincida con el nombre del usuario actual. |
| [EXCLUDE](#EXCLUDE) | Si está vacío, la matriz Fields especifica qué campos incluir en el envío. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | Si se establece, los nombres y valores de los campos se enviarán en formato de formulario HTML. |
| [GET_METHOD](#GET_METHOD) | Si se establece, los nombres y valores de los campos se enviarán mediante una solicitud HTTP GET. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | Si se establece, el archivo FDF enviado incluirá todas las anotaciones de marcado del documento PDF subyacente. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | Si se establece, el archivo FDF enviado incluirá el contenido de todas las actualizaciones incrementales. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | Si se establece, todos los campos designados por la matriz Fields y la bandera Incluir/Excluir se enviarán. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | Si se establece, las coordenadas del clic del ratón que provocó la acción submit-form se transmitirán como parte de los datos del formulario. |
| [SUBMIT_PDF](#SUBMIT_PDF) | Si se establece, el documento se enviará como PDF, usando el tipo de contenido MIME application/pdf. |
| [XFDF](#XFDF) | Si se establece, los nombres y valores de los campos se enviarán como XFDF. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | Inicializa el objeto SubmitFormAction. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getFlags](#getFlags--) | Obtiene los indicadores de la acción de envío |
| [getUrl](#getUrl--) | URL de destino. |
| [setFlags](#setFlags-int-) | Establece los indicadores de la acción de envío |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | URL de destino. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

Si se establece, cualquier valor de campo enviado que represente fechas se convertirá al formato estándar.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

Si se establece, la entrada F del FDF enviado será una especificación de archivo que contiene un flujo de archivo incrustado que representa el archivo PDF del cual se envía el FDF.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

Si se establece, el FDF enviado excluirá la entrada F.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

Si se establece, solo incluirá aquellas anotaciones de marcado cuya entrada T coincida con el nombre del usuario actual.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

Si está vacío, la matriz Fields especifica qué campos incluir en el envío.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

Si se establece, los nombres y valores de los campos se enviarán en formato de formulario HTML.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

Si se establece, los nombres y valores de los campos se enviarán mediante una solicitud HTTP GET.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

Si se establece, el archivo FDF enviado incluirá todas las anotaciones de marcado del documento PDF subyacente.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

Si se establece, el archivo FDF enviado incluirá el contenido de todas las actualizaciones incrementales.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

Si se establece, todos los campos designados por la matriz Fields y la bandera Incluir/Excluir se enviarán.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

Si se establece, las coordenadas del clic del ratón que provocó la acción submit-form se transmitirán como parte de los datos del formulario.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

Si se establece, el documento se enviará como PDF, usando el tipo de contenido MIME application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```

Si se establece, los nombres y valores de los campos se enviarán como XFDF.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

Inicializa el objeto SubmitFormAction.

### getFlags {#getFlags--}
```
public int getFlags()
```

Obtiene los indicadores de la acción de envío

**Returns:**
valor int

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

URL de destino.

**Returns:**
Valor FileSpecification

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Establece los indicadores de la acción de envío

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
URL de destino.
