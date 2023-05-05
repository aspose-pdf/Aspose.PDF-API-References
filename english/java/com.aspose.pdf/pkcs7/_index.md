---
title: PKCS7
second_title: Aspose.PDF for Java API Reference
description: Represents the PKCS7 object that conform to the PKCS7 specification in Internet RFC 2315 PKCS 7 Cryptographic Message Syntax Version 1.5.
type: docs
weight: 254
url: /java/com.aspose.pdf/pkcs7/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Signature](../../com.aspose.pdf/signature)
```
public final class PKCS7 extends Signature
```

Represents the PKCS\#7 object that conform to the PKCS\#7 specification in Internet RFC 2315, PKCS \#7: Cryptographic Message Syntax, Version 1.5. The SHA1 digest of the document's byte range is encapsulated in the PKCS\#7 SignedData field.
## Constructors

| Constructor | Description |
| --- | --- |
| [PKCS7()](#PKCS7--) | Inititalizes new instance of the  PKCS7  class. |
| [PKCS7(String pfx, String password)](#PKCS7-java.lang.String-java.lang.String-) | Inititalizes new instance of the  PKCS7  class. |
| [PKCS7(InputStream pfx, String password)](#PKCS7-java.io.InputStream-java.lang.String-) | Inititalizes new instance of the  PKCS7  class. |
### PKCS7() {#PKCS7--}
```
public PKCS7()
```


Inititalizes new instance of the  PKCS7  class.

### PKCS7(String pfx, String password) {#PKCS7-java.lang.String-java.lang.String-}
```
public PKCS7(String pfx, String password)
```


Inititalizes new instance of the  PKCS7  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | java.lang.String | Pfx file which contains certificate for signing. |
| password | java.lang.String | Password for certificate. |

### PKCS7(InputStream pfx, String password) {#PKCS7-java.io.InputStream-java.lang.String-}
```
public PKCS7(InputStream pfx, String password)
```


Inititalizes new instance of the  PKCS7  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | java.io.InputStream | Stream with certificate data organized as pfx. |
| password | java.lang.String | Password to get access to the private key in the certificate. |

