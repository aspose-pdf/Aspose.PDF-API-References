---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un campo de formulario de firma."
type: docs
weight: 4510
url: /es/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

Representa un campo de formulario de firma.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Inicializa una nueva instancia de la clase {@code SignatureField}. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inicializa una nueva instancia de la clase {@code SignatureField}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [clear](#clear--) | Elimina el objeto de firma del campo. |
| [extractCertificate](#extractCertificate--) | Extrae el único certificado X.509 en formato DER como un flujo. |
| [extractCertificateObject](#extractCertificateObject--) | Extrae el objeto del único certificado X.509. |
| [extractImage](#extractImage--) | Extrae la imagen de la firma como un flujo codificado en JPEG. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | Extrae la imagen de la firma como un flujo codificado en JPEG. |
| [getSignature](#getSignature--) | Obtiene el objeto de firma. Este objeto contiene datos de firma relativos a los estándares criptográficos de clave pública. Las clases {@code PKCS1}, {@code PKCS7} y {@code PKCS7Detached} representan todos los tipos de objetos de firma compatibles. |
| [sign](#sign-com.aspose.pdf.Signature-) | Firme el documento usando este campo de firma. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Firma el documento usando este campo de firma. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Inicializa una nueva instancia de la clase {@code SignatureField}.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inicializa una nueva instancia de la clase {@code SignatureField}.

### clear {#clear--}
```
public void clear()
```

Elimina el objeto de firma del campo.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

Extrae el único certificado X.509 en formato DER como un flujo.

**Returns:**
Si se encontró el certificado, devuelve el único certificado X.509; de lo contrario, null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

Extrae el objeto del único certificado X.509.

**Returns:**
Si se encontró el certificado, devuelve el único certificado X.509; de lo contrario, null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

Extrae la imagen de la firma como un flujo codificado en JPEG.

**Returns:**
Si la imagen se encontró correctamente, devuelve el objeto de flujo codificado en JPEG; de lo contrario, null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
Extrae la imagen de la firma como un flujo codificado en JPEG.

**Returns:**
Si la imagen se encontró correctamente, devuelve el objeto de flujo codificado en JPEG; de lo contrario, null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

Obtiene el objeto de firma. Este objeto contiene datos de firma relativos a los estándares criptográficos de clave pública. Las clases {@code PKCS1}, {@code PKCS7} y {@code PKCS7Detached} representan todos los tipos de objetos de firma compatibles.

**Returns:**
Objeto de firma

### sign {#sign-com.aspose.pdf.Signature-}
Firme el documento usando este campo de firma.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
Firma el documento usando este campo de firma.
