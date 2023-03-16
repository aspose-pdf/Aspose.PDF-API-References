---
title: PKCS7Detached
second_title: Aspose.PDF for Java API Reference
description: Represents the PKCS7 object that conform to the PKCS7 specification in Internet RFC 2315 PKCS 7 Cryptographic Message Syntax Version 1.5.
type: docs
weight: 254
url: /java/com.aspose.pdf/pkcs7detached/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Signature](../../com.aspose.pdf/signature)
```
public final class PKCS7Detached extends Signature
```

Represents the PKCS\#7 object that conform to the PKCS\#7 specification in Internet RFC 2315, PKCS \#7: Cryptographic Message Syntax, Version 1.5. The original signed message digest over the document's byte range is incorporated as the normal PKCS\#7 SignedData field. No data shall is encapsulated in the PKCS\#7 SignedData field.
## Constructors

| Constructor | Description |
| --- | --- |
| [PKCS7Detached(InputStream image)](#PKCS7Detached-java.io.InputStream-) | Initializes new instance of the  PKCS7Detached  class. |
| [PKCS7Detached()](#PKCS7Detached--) | Inititalizes new instance of the  PKCS7Detached  class. |
| [PKCS7Detached(String pfx, String password)](#PKCS7Detached-java.lang.String-java.lang.String-) | Inititalizes new instance of the  PKCS7Detached  class. |
| [PKCS7Detached(InputStream pfx, String password)](#PKCS7Detached-java.io.InputStream-java.lang.String-) | Inititalizes new instance of the  PKCS7Detached  class. |
### PKCS7Detached(InputStream image) {#PKCS7Detached-java.io.InputStream-}
```
public PKCS7Detached(InputStream image)
```


Initializes new instance of the  PKCS7Detached  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | This image will define signature appearance on the page. |

### PKCS7Detached() {#PKCS7Detached--}
```
public PKCS7Detached()
```


Inititalizes new instance of the  PKCS7Detached  class.

### PKCS7Detached(String pfx, String password) {#PKCS7Detached-java.lang.String-java.lang.String-}
```
public PKCS7Detached(String pfx, String password)
```


Inititalizes new instance of the  PKCS7Detached  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | java.lang.String | Pfx file which contains certificate for signing. |
| password | java.lang.String | Password to get access to the private key in the certificate. |

### PKCS7Detached(InputStream pfx, String password) {#PKCS7Detached-java.io.InputStream-java.lang.String-}
```
public PKCS7Detached(InputStream pfx, String password)
```


Inititalizes new instance of the  PKCS7Detached  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | java.io.InputStream | Stream with certificate data organized as pfx. |
| password | java.lang.String | Password to get access to the private key in the certificate. |

