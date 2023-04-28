---
title: Signature
second_title: Aspose.PDF for Java API Reference
description: An abstract class which represents signature object in the pdf document.
type: docs
weight: 324
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
| [Signature(InputStream pfx, String password)](#Signature-java.io.InputStream-java.lang.String-) | Inititalizes new instance of the  Signature  class. |
## Methods

| Method | Description |
| --- | --- |
| [getCustomAppearance()](#getCustomAppearance--) | Gets/sets the custom appearance. |
| [setCustomAppearance(SignatureCustomAppearance value)](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Gets/sets the custom appearance. |
| [getAuthority()](#getAuthority--) | The name of the person or authority signing the document. |
| [setAuthority(String value)](#setAuthority-java.lang.String-) | Sets the name of the person or authority signing the document. |
| [getDate()](#getDate--) | Gets the time of signing. |
| [setDate(Date value)](#setDate-java.util.Date-) | Set the time of signing. |
| [getLocation()](#getLocation--) | Gets the CPU host name or physical location of the signing. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Sets the CPU host name or physical location of the signing. |
| [getReason()](#getReason--) | Gets the reason for the signing, such as (I agreed!). |
| [setReason(String value)](#setReason-java.lang.String-) | Sets the reason for the signing, such as (I agreed!). |
| [getContactInfo()](#getContactInfo--) | Get information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Set information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [getByteRange()](#getByteRange--) | Get array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation. |
| [getTimestampSettings()](#getTimestampSettings--) | Gets timestamp settings. |
| [setTimestampSettings(TimestampSettings value)](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Sets timestamp settings. |
| [getOcspSettings()](#getOcspSettings--) | Gets/sets ocsp settings. |
| [setOcspSettings(OcspSettings value)](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Gets/sets ocsp settings. |
| [getUseLtv()](#getUseLtv--) | Gets/sets ltv validation flag. |
| [setUseLtv(boolean value)](#setUseLtv-boolean-) | Gets/sets ltv validation flag. |
| [getImageInternal()](#getImageInternal--) | Gets image stream. |
| [setImage(InputStream _signatureAppearanceStream)](#setImage-java.io.InputStream-) | Sets image stream. |
| [setImageInternal(System.IO.Stream value)](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [getSignatureReferences()](#getSignatureReferences--) | get Signature References |
| [verify()](#verify--) | Verify the document regarding this signature and return true if document is valid or otherwise false. |
| [isShowProperties()](#isShowProperties--) | Force to show/hide signature properties. |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) | Force to show/hide signature properties. |
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

### Signature(InputStream pfx, String password) {#Signature-java.io.InputStream-java.lang.String-}
```
public Signature(InputStream pfx, String password)
```


Inititalizes new instance of the  Signature  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pfx | java.io.InputStream | Stream with certificate data organized as pfx. |
| password | java.lang.String | Password to get access to the private key in the certificate. |

### getCustomAppearance() {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```


Gets/sets the custom appearance.

**Returns:**
[SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) - SignatureCustomAppearance instance
### setCustomAppearance(SignatureCustomAppearance value) {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
```
public final void setCustomAppearance(SignatureCustomAppearance value)
```


Gets/sets the custom appearance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SignatureCustomAppearance](../../com.aspose.pdf/signaturecustomappearance) | SignatureCustomAppearance instance |

### getAuthority() {#getAuthority--}
```
public final String getAuthority()
```


The name of the person or authority signing the document.

**Returns:**
java.lang.String - String value
### setAuthority(String value) {#setAuthority-java.lang.String-}
```
public void setAuthority(String value)
```


Sets the name of the person or authority signing the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getDate() {#getDate--}
```
public Date getDate()
```


Gets the time of signing.

**Returns:**
[Date](../../java.util/date) - Date value
### setDate(Date value) {#setDate-java.util.Date-}
```
public void setDate(Date value)
```


Set the time of signing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date object |

### getLocation() {#getLocation--}
```
public String getLocation()
```


Gets the CPU host name or physical location of the signing.

**Returns:**
java.lang.String - String value
### setLocation(String value) {#setLocation-java.lang.String-}
```
public void setLocation(String value)
```


Sets the CPU host name or physical location of the signing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getReason() {#getReason--}
```
public String getReason()
```


Gets the reason for the signing, such as (I agreed!).

**Returns:**
java.lang.String - String value
### setReason(String value) {#setReason-java.lang.String-}
```
public void setReason(String value)
```


Sets the reason for the signing, such as (I agreed!).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getContactInfo() {#getContactInfo--}
```
public String getContactInfo()
```


Get information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number.

**Returns:**
java.lang.String - String value
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public void setContactInfo(String value)
```


Set information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getByteRange() {#getByteRange--}
```
public int[] getByteRange()
```


Get array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation.

**Returns:**
int[] - array of int value
### getTimestampSettings() {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```


Gets timestamp settings.

**Returns:**
[TimestampSettings](../../com.aspose.pdf/timestampsettings) - TimestampSettings
### setTimestampSettings(TimestampSettings value) {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
```
public void setTimestampSettings(TimestampSettings value)
```


Sets timestamp settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimestampSettings](../../com.aspose.pdf/timestampsettings) | TimestampSettings |

### getOcspSettings() {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```


Gets/sets ocsp settings.

**Returns:**
[OcspSettings](../../com.aspose.pdf/ocspsettings) - OcspSettings instance
### setOcspSettings(OcspSettings value) {#setOcspSettings-com.aspose.pdf.OcspSettings-}
```
public void setOcspSettings(OcspSettings value)
```


Gets/sets ocsp settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [OcspSettings](../../com.aspose.pdf/ocspsettings) | OcspSettings instance |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Gets/sets ltv validation flag.

**Returns:**
boolean - boolean value
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Gets/sets ltv validation flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getImageInternal() {#getImageInternal--}
```
public System.IO.Stream getImageInternal()
```


Gets image stream.

For internal only usage

**Returns:**
com.aspose.ms.System.IO.Stream - Stream object
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

### getSignatureReferences() {#getSignatureReferences--}
```
public List<SignatureReference> getSignatureReferences()
```


get Signature References

**Returns:**
java.util.List<com.aspose.pdf.engine.security.impl.signatures.SignatureReference> -  java.util.List object 
### verify() {#verify--}
```
public boolean verify()
```


Verify the document regarding this signature and return true if document is valid or otherwise false.

**Returns:**
boolean - true if document is valid.
### isShowProperties() {#isShowProperties--}
```
public boolean isShowProperties()
```


Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by \{certificate subject\} Date: \{signature.Date\} Reason: \{signature.Reason\} Location: \{signature.Location\} ------------------------------------------- where \{X\} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default.

**Returns:**
boolean - boolean value
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```


Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by \{certificate subject\} Date: \{signature.Date\} Reason: \{signature.Reason\} Location: \{signature.Location\} ------------------------------------------- where \{X\} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### close() {#close--}
```
public void close()
```


Destructor which closes temporary streams (if necessary).

