---
title: PKCS1
second_title: Aspose.PDF for Java API Reference
description: Represents signature object regarding PKCS1 standard.
type: docs
weight: 254
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
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Destructor which closes temporary streams (if necessary). |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuthority()](#getAuthority--) | The name of the person or authority signing the document. |
| [getByteRange()](#getByteRange--) | Get array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation. |
| [getClass()](#getClass--) |  |
| [getContactInfo()](#getContactInfo--) | Get information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [getCustomAppearance()](#getCustomAppearance--) | Gets/sets the custom appearance. |
| [getDate()](#getDate--) | Gets the time of signing. |
| [getImageInternal()](#getImageInternal--) | Gets image stream. |
| [getLocation()](#getLocation--) | Gets the CPU host name or physical location of the signing. |
| [getOcspSettings()](#getOcspSettings--) | Gets/sets ocsp settings. |
| [getReason()](#getReason--) | Gets the reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
| [getSignatureReferences()](#getSignatureReferences--) | get Signature References |
| [getTimestampSettings()](#getTimestampSettings--) | Gets timestamp settings. |
| [getUseLtv()](#getUseLtv--) | Gets/sets ltv validation flag. |
| [hashCode()](#hashCode--) |  |
| [isShowProperties()](#isShowProperties--) | Force to show/hide signature properties. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAuthority(String value)](#setAuthority-java.lang.String-) | Sets the name of the person or authority signing the document. |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Set information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [setCustomAppearance(SignatureCustomAppearance value)](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Gets/sets the custom appearance. |
| [setDate(Date value)](#setDate-java.util.Date-) | Set the time of signing. |
| [setImage(InputStream _signatureAppearanceStream)](#setImage-java.io.InputStream-) | Sets image stream. |
| [setImageInternal(System.IO.Stream value)](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation(String value)](#setLocation-java.lang.String-) | Sets the CPU host name or physical location of the signing. |
| [setOcspSettings(OcspSettings value)](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Gets/sets ocsp settings. |
| [setReason(String value)](#setReason-java.lang.String-) | Sets the reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) | Force to show/hide signature properties. |
| [setTimestampSettings(TimestampSettings value)](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Sets timestamp settings. |
| [setUseLtv(boolean value)](#setUseLtv-boolean-) | Gets/sets ltv validation flag. |
| [toString()](#toString--) |  |
| [verify()](#verify--) | Verify the document regarding this signature and return true if document is valid or otherwise false. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### close() {#close--}
```
public void close()
```


Destructor which closes temporary streams (if necessary).

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAuthority() {#getAuthority--}
```
public final String getAuthority()
```


The name of the person or authority signing the document.

**Returns:**
java.lang.String - String value
### getByteRange() {#getByteRange--}
```
public int[] getByteRange()
```


Get array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation.

**Returns:**
int[] - array of int value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContactInfo() {#getContactInfo--}
```
public String getContactInfo()
```


Get information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number.

**Returns:**
java.lang.String - String value
### getCustomAppearance() {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```


Gets/sets the custom appearance.

**Returns:**
[SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) - SignatureCustomAppearance instance
### getDate() {#getDate--}
```
public Date getDate()
```


Gets the time of signing.

**Returns:**
[Date](../../java.util/date) - Date value
### getImageInternal() {#getImageInternal--}
```
public System.IO.Stream getImageInternal()
```


Gets image stream.

For internal only usage

**Returns:**
com.aspose.ms.System.IO.Stream - Stream object
### getLocation() {#getLocation--}
```
public String getLocation()
```


Gets the CPU host name or physical location of the signing.

**Returns:**
java.lang.String - String value
### getOcspSettings() {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```


Gets/sets ocsp settings.

**Returns:**
[OcspSettings](../../com.aspose.pdf/ocspsettings) - OcspSettings instance
### getReason() {#getReason--}
```
public String getReason()
```


Gets the reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).

**Returns:**
java.lang.String - String value
### getSignatureReferences() {#getSignatureReferences--}
```
public List<SignatureReference> getSignatureReferences()
```


get Signature References

**Returns:**
java.util.List<com.aspose.pdf.engine.security.impl.signatures.SignatureReference> -  java.util.List object 
### getTimestampSettings() {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```


Gets timestamp settings.

**Returns:**
[TimestampSettings](../../com.aspose.pdf/timestampsettings) - TimestampSettings
### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Gets/sets ltv validation flag.

**Returns:**
boolean - boolean value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShowProperties() {#isShowProperties--}
```
public boolean isShowProperties()
```


Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by \{certificate subject\} Date: \{signature.Date\} Reason: \{signature.Reason\} Location: \{signature.Location\} ------------------------------------------- where \{X\} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAuthority(String value) {#setAuthority-java.lang.String-}
```
public void setAuthority(String value)
```


Sets the name of the person or authority signing the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public void setContactInfo(String value)
```


Set information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setCustomAppearance(SignatureCustomAppearance value) {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
```
public final void setCustomAppearance(SignatureCustomAppearance value)
```


Gets/sets the custom appearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) | SignatureCustomAppearance instance |

### setDate(Date value) {#setDate-java.util.Date-}
```
public void setDate(Date value)
```


Set the time of signing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### setImage(InputStream _signatureAppearanceStream) {#setImage-java.io.InputStream-}
```
public void setImage(InputStream _signatureAppearanceStream)
```


Sets image stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| _signatureAppearanceStream | java.io.InputStream | Steam object |

### setImageInternal(System.IO.Stream value) {#setImageInternal-com.aspose.ms.System.IO.Stream-}
```
public void setImageInternal(System.IO.Stream value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.IO.Stream |  |

### setLocation(String value) {#setLocation-java.lang.String-}
```
public void setLocation(String value)
```


Sets the CPU host name or physical location of the signing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setOcspSettings(OcspSettings value) {#setOcspSettings-com.aspose.pdf.OcspSettings-}
```
public void setOcspSettings(OcspSettings value)
```


Gets/sets ocsp settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OcspSettings](../../com.aspose.pdf/ocspsettings) | OcspSettings instance |

### setReason(String value) {#setReason-java.lang.String-}
```
public void setReason(String value)
```


Sets the reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```


Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by \{certificate subject\} Date: \{signature.Date\} Reason: \{signature.Reason\} Location: \{signature.Location\} ------------------------------------------- where \{X\} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setTimestampSettings(TimestampSettings value) {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
```
public void setTimestampSettings(TimestampSettings value)
```


Sets timestamp settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimestampSettings](../../com.aspose.pdf/timestampsettings) | TimestampSettings |

### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Gets/sets ltv validation flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### verify() {#verify--}
```
public boolean verify()
```


Verify the document regarding this signature and return true if document is valid or otherwise false.

**Returns:**
boolean - true if document is valid.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

