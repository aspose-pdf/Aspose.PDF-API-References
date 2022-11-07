---
title: SignatureField
second_title: Aspose.PDF for Java API Reference
description: Represents signature form field.
type: docs
weight: 264
url: /java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field)
```
public final class SignatureField extends Field
```

Represents signature form field.
## Constructors

| Constructor | Description |
| --- | --- |
| [SignatureField(Page page, Rectangle rect)](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initializes new instance of the  SignatureField  class. |
## Methods

| Method | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Gets signature object. |
| [sign(Signature signature, InputStream pfx, String pass)](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Signs the document using this signature field. |
| [sign(Signature signature)](#sign-com.aspose.pdf.Signature-) | Sign the document using this signature field. |
| [clear()](#clear--) | Removes signature object from field. |
### SignatureField(Page page, Rectangle rect) {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public SignatureField(Page page, Rectangle rect)
```


Initializes new instance of the  SignatureField  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getSignature() {#getSignature--}
```
public Signature getSignature()
```


Gets signature object. This object contains signature data regarding public-key cryptographic standards. Classes  PKCS1 ,  PKCS7  and  PKCS7Detached  represent all supported types of signature objects.

**Returns:**
[Signature](../../com.aspose.pdf/signature)
### sign(Signature signature, InputStream pfx, String pass) {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
```
public void sign(Signature signature, InputStream pfx, String pass)
```


Signs the document using this signature field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | [Signature](../../com.aspose.pdf/signature) | Signature object, see  PKCS1 ,  PKCS7 ,  PKCS7Detached . |
| pfx | java.io.InputStream | Stream with certificate. |
| pass | java.lang.String | Password to access private in the  pfx . |

### sign(Signature signature) {#sign-com.aspose.pdf.Signature-}
```
public void sign(Signature signature)
```


Sign the document using this signature field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | [Signature](../../com.aspose.pdf/signature) | Signature object, see  PKCS1 ,  PKCS7  and  PKCS7Detached . |

### clear() {#clear--}
```
public void clear()
```


Removes signature object from field.

