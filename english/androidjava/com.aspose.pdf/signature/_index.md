---
title: Signature
second_title: Aspose.PDF for Java API Reference
description: An abstract class which represents signature object in the pdf document.
type: docs
weight: 263
url: /java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object
```
public abstract class Signature
```

An abstract class which represents signature object in the pdf document. Signatures are fields with values of signature objects, the last contain data which is used to verify the document validity.
## Constructors

| Constructor | Description |
| --- | --- |
| [Signature()](#Signature--) | Inititalizes new instance of the  Signature  class. |
| [Signature(String pfx, String password)](#Signature-java.lang.String-java.lang.String-) | Inititalizes new instance of the  Signature  class. |
| [Signature(System.IO.Stream pfx, String password)](#Signature-com.aspose.ms.System.IO.Stream-java.lang.String-) | Inititalizes new instance of the  Signature  class. |
## Methods

| Method | Description |
| --- | --- |
| [setImage(InputStream _image)](#setImage-java.io.InputStream-) |  |
| [getAuthority()](#getAuthority--) | The name of the person or authority signing the document. |
| [setAuthority(String value)](#setAuthority-java.lang.String-) |  |
| [getDate()](#getDate--) | The time of signing. |
| [setDate(System.DateTime value)](#setDate-com.aspose.ms.System.DateTime-) |  |
| [getLocation()](#getLocation--) | The CPU host name or physical location of the signing. |
| [setLocation(String value)](#setLocation-java.lang.String-) |  |
| [getReason()](#getReason--) | The reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
| [setReason(String value)](#setReason-java.lang.String-) |  |
| [getContactInfo()](#getContactInfo--) | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) |  |
| [getByteRange()](#getByteRange--) | An array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation. |
| [verify()](#verify--) | Verify the document regarding this signature and return true if document is valid or otherwise false. |
| [getShowProperties()](#getShowProperties--) | Force to show/hide signature properties. |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) |  |
| [close()](#close--) | Destructor which closes temporary streams (if necessary). |
### Signature() {#Signature--}
```
public Signature()
```


Inititalizes new instance of the  Signature  class.

### Signature(String pfx, String password) {#Signature-java.lang.String-java.lang.String-}
```
public Signature(String pfx, String password)
```


Inititalizes new instance of the  Signature  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | java.lang.String | Pfx file which contains certificate for signing. |
| password | java.lang.String | Password to get access to the private key in the certificate. |

### Signature(System.IO.Stream pfx, String password) {#Signature-com.aspose.ms.System.IO.Stream-java.lang.String-}
```
public Signature(System.IO.Stream pfx, String password)
```


Inititalizes new instance of the  Signature  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | com.aspose.ms.System.IO.Stream | Stream with certificate data organized as pfx. |
| password | java.lang.String | Password to get access to the private key in the certificate. |

### setImage(InputStream _image) {#setImage-java.io.InputStream-}
```
public void setImage(InputStream _image)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| _image | java.io.InputStream |  |

### getAuthority() {#getAuthority--}
```
public String getAuthority()
```


The name of the person or authority signing the document.

**Returns:**
java.lang.String
### setAuthority(String value) {#setAuthority-java.lang.String-}
```
public void setAuthority(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDate() {#getDate--}
```
public System.DateTime getDate()
```


The time of signing.

**Returns:**
com.aspose.ms.System.DateTime
### setDate(System.DateTime value) {#setDate-com.aspose.ms.System.DateTime-}
```
public void setDate(System.DateTime value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime |  |

### getLocation() {#getLocation--}
```
public String getLocation()
```


The CPU host name or physical location of the signing.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public void setLocation(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getReason() {#getReason--}
```
public String getReason()
```


The reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public void setReason(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContactInfo() {#getContactInfo--}
```
public String getContactInfo()
```


Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number.

**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public void setContactInfo(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getByteRange() {#getByteRange--}
```
public int[] getByteRange()
```


An array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation.

**Returns:**
int[]
### verify() {#verify--}
```
public boolean verify()
```


Verify the document regarding this signature and return true if document is valid or otherwise false.

**Returns:**
boolean
### getShowProperties() {#getShowProperties--}
```
public boolean getShowProperties()
```


Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by \{certificate subject\} Date: \{signature.Date\} Reason: \{signature.Reason\} Location: \{signature.Location\} ------------------------------------------- where \{X\} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default.

**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### close() {#close--}
```
public void close()
```


Destructor which closes temporary streams (if necessary).

