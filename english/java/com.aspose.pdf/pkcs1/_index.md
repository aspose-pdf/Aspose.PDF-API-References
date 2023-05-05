---
title: PKCS1
second_title: Aspose.PDF for Java API Reference
description: Represents signature object regarding PKCS1 standard.
type: docs
weight: 253
url: /java/com.aspose.pdf/pkcs1/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Signature](../../com.aspose.pdf/signature)
```
public final class PKCS1 extends Signature
```

Represents signature object regarding PKCS\#1 standard. RSA encryption algorithm and SHA-1 digest method are used for signing.
## Constructors

| Constructor | Description |
| --- | --- |
| [PKCS1(InputStream image)](#PKCS1-java.io.InputStream-) | Initializes new instance of the  PKCS1  class. |
| [PKCS1()](#PKCS1--) | Inititalizes new instance of the  PKCS1  class. |
| [PKCS1(String pfx, String password)](#PKCS1-java.lang.String-java.lang.String-) | Inititalizes new instance of the  PKCS1  class. |
| [PKCS1(InputStream pfx, String password)](#PKCS1-java.io.InputStream-java.lang.String-) | Inititalizes new instance of the  PKCS1  class. |
### PKCS1(InputStream image) {#PKCS1-java.io.InputStream-}
```
public PKCS1(InputStream image)
```


Initializes new instance of the  PKCS1  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | This image will define signature appearance on the page. |

### PKCS1() {#PKCS1--}
```
public PKCS1()
```


Inititalizes new instance of the  PKCS1  class.

### PKCS1(String pfx, String password) {#PKCS1-java.lang.String-java.lang.String-}
```
public PKCS1(String pfx, String password)
```


Inititalizes new instance of the  PKCS1  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | java.lang.String | Pfx file which contains certificate for signing. |
| password | java.lang.String | Password for certificate. |

### PKCS1(InputStream pfx, String password) {#PKCS1-java.io.InputStream-java.lang.String-}
```
public PKCS1(InputStream pfx, String password)
```


Inititalizes new instance of the  PKCS1  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | java.io.InputStream | Stream with certificate data organized as pfx. |
| password | java.lang.String | Password to get access to the private key in the certificate. |

