---
title: SignatureField
linktitle: SignatureField
second_title: Aspose.PDF for Java API Reference
description: Represents signature form field.
type: docs
weight: 4510
url: /java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

Represents signature form field.

## Constructors

| Constructor | Description |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Initializes new instance of the {@code SignatureField} class. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initializes new instance of the {@code SignatureField} class. |

## Methods

| Method | Description |
| --- | --- |
| [clear](#clear--) | Removes signature object from field. |
| [extractCertificate](#extractCertificate--) | Extracts the single X.509 certificate in DER format as a stream. |
| [extractCertificateObject](#extractCertificateObject--) | Extracts the single X.509 certificate object. |
| [extractImage](#extractImage--) | Extracts signature's image as jpeg encoded stream. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | Extracts signature's image as jpeg encoded stream. |
| [getSignature](#getSignature--) | Gets signature object. This object contains signature data regarding public-key cryptographic standards. Classes {@code PKCS1}, {@code PKCS7} and {@code PKCS7Detached} represent all supported types of signature objects. |
| [sign](#sign-com.aspose.pdf.Signature-) | Sign the document using this signature field. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Signs the document using this signature field. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Initializes new instance of the {@code SignatureField} class.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initializes new instance of the {@code SignatureField} class.

### clear {#clear--}
```
public void clear()
```

Removes signature object from field.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

Extracts the single X.509 certificate in DER format as a stream.

**Returns:**
If certificate was found returns X.509 single certificate; otherwise, null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

Extracts the single X.509 certificate object.

**Returns:**
If certificate was found returns X.509 single certificate; otherwise, null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

Extracts signature's image as jpeg encoded stream.

**Returns:**
If image was successfully found than returns jpeg encoded stream object; otherwise, null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
Extracts signature's image as jpeg encoded stream.

**Returns:**
If image was successfully found than returns jpeg encoded stream object; otherwise, null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

Gets signature object. This object contains signature data regarding public-key cryptographic standards. Classes {@code PKCS1}, {@code PKCS7} and {@code PKCS7Detached} represent all supported types of signature objects.

**Returns:**
Signature object

### sign {#sign-com.aspose.pdf.Signature-}
Sign the document using this signature field.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
Signs the document using this signature field.
