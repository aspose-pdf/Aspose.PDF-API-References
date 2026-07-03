---
title: Signature
linktitle: Signature
second_title: Aspose.PDF for Java API Reference
description: An abstract class which represents signature object in the pdf document. Signatures are fields with values of signature objects, the last contain data which is used to verify the.
type: docs
weight: 4490
url: /java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

An abstract class which represents signature object in the pdf document. Signatures are fields with values of signature objects, the last contain data which is used to verify the document validity.

## Constructors

| Constructor | Description |
| --- | --- |
| [Signature](#Signature--) | Initializes new instance of the {@code Signature} class. |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | Initializes new instance of the {@code Signature} class. |
| [Signature](#Signature-java.lang.String-java.lang.String-) | Initializes new instance of the {@code Signature} class. |

## Methods

| Method | Description |
| --- | --- |
| [close](#close--) | Destructor which closes temporary streams (if necessary). |
| [getAuthority](#getAuthority--) | The name of the person or authority signing the document. |
| [getByteRange](#getByteRange--) | Get array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation. |
| [getContactInfo](#getContactInfo--) | Get information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [getCustomAppearance](#getCustomAppearance--) | Gets/sets the custom appearance. |
| [getCustomSign](#getCustomSign--) | The delegate for custom hash and sign the document (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [getCustomSignHash](#getCustomSignHash--) | The delegate for custom sign the document hash (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [getDate](#getDate--) | Gets the time of signing. |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | Gets or sets the default length for the signature data in bytes. This is an estimation of the length of the signature in bytes. Used for signing via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) if the {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) parameter is set. The default value is 3000. |
| [getImageInternal](#getImageInternal--) | Gets image stream. For internal only usage |
| [getLocation](#getLocation--) | Gets the CPU host name or physical location of the signing. |
| [getOcspSettings](#getOcspSettings--) | Gets/sets ocsp settings. |
| [getReason](#getReason--) | Gets the reason for the signing, such as (I agreed!, Pip B.). |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | Retrieves information about the signature algorithm used in the signature. |
| [getSignatureReferences](#getSignatureReferences--) | get Signature References |
| [getTimestampSettings](#getTimestampSettings--) | Gets timestamp settings. |
| [getUseLtv](#getUseLtv--) | Gets/sets ltv validation flag. |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | Gets and sets an option means whether to avoid estimating the length of a signature. Avoids to estimate signature length before a signing document. Used for signing via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) an via {@code ExternalSignature}. If {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) returns a signature longer than {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), then {@code SignatureLengthMismatchException} will be thrown. The default value is {@code false}. |
| [isShowProperties](#isShowProperties--) | Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default. |
| [setAuthority](#setAuthority-java.lang.String-) | Sets the name of the person or authority signing the document. |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | Gets and sets an option means whether to avoid estimating the length of a signature. Avoids to estimate signature length before a signing document. Used for signing via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) an via {@code ExternalSignature}. If {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) returns a signature longer than {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), then {@code SignatureLengthMismatchException} will be thrown. The default value is {@code false}. |
| [setContactInfo](#setContactInfo-java.lang.String-) | Set information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | Gets/sets the custom appearance. |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | The delegate for custom hash and sign the document (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | The delegate for custom sign the document hash (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [setDate](#setDate-java.util.Date-) | Set the time of signing. |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | Gets or sets the default length for the signature data in bytes. This is an estimation of the length of the signature in bytes. Used for signing via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) if the {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) parameter is set. The default value is 3000. |
| [setImage](#setImage-java.io.InputStream-) | Sets image stream. |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | Sets the CPU host name or physical location of the signing. |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | Gets/sets ocsp settings. |
| [setReason](#setReason-java.lang.String-) | Sets the reason for the signing, such as (I agreed!, Pip B.). |
| [setShowProperties](#setShowProperties-boolean-) | Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default. |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | Sets timestamp settings. |
| [setUseLtv](#setUseLtv-boolean-) | Gets/sets ltv validation flag. |
| [verify](#verify--) | Verify the document regarding this signature and return true if document is valid or otherwise false. |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verify the document regarding this signature and return true if document is valid or otherwise false. |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verify the document regarding this signature and return true if document is valid or otherwise false. |

### Signature {#Signature--}
```
public Signature()
```

Initializes new instance of the {@code Signature} class.

### Signature {#Signature-java.io.InputStream-java.lang.String-}
Initializes new instance of the {@code Signature} class.

### Signature {#Signature-java.lang.String-java.lang.String-}
Initializes new instance of the {@code Signature} class.

### close {#close--}
```
public void close()
```

Destructor which closes temporary streams (if necessary).

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

The name of the person or authority signing the document.

**Returns:**
String value

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

Get array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation.

**Returns:**
array of int value

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

Get information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number.

**Returns:**
String value

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

Gets/sets the custom appearance.

**Returns:**
SignatureCustomAppearance instance

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

The delegate for custom hash and sign the document (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

**Returns:**
SignHash instance

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

The delegate for custom sign the document hash (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

**Returns:**
SignHash instance

### getDate {#getDate--}
```
public Date getDate()
```

Gets the time of signing.

**Returns:**
Date value

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

Gets or sets the default length for the signature data in bytes. This is an estimation of the length of the signature in bytes. Used for signing via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) if the {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) parameter is set. The default value is 3000.

**Returns:**
int value

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

Gets image stream. For internal only usage

**Returns:**
Stream object

### getLocation {#getLocation--}
```
public String getLocation()
```

Gets the CPU host name or physical location of the signing.

**Returns:**
String value

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

Gets/sets ocsp settings.

**Returns:**
OcspSettings instance

### getReason {#getReason--}
```
public String getReason()
```

Gets the reason for the signing, such as (I agreed!, Pip B.).

**Returns:**
String value

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

Retrieves information about the signature algorithm used in the signature.

**Returns:**
An instance of { SignatureAlgorithmInfo} that contains details about the signature algorithm.

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

get Signature References

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

Gets timestamp settings.

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

Gets/sets ltv validation flag.

**Returns:**
boolean value

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

Gets and sets an option means whether to avoid estimating the length of a signature. Avoids to estimate signature length before a signing document. Used for signing via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) an via {@code ExternalSignature}. If {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) returns a signature longer than {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), then {@code SignatureLengthMismatchException} will be thrown. The default value is {@code false}.

**Returns:**
boolean value

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default.

**Returns:**
boolean value

### setAuthority {#setAuthority-java.lang.String-}
Sets the name of the person or authority signing the document.

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

Gets and sets an option means whether to avoid estimating the length of a signature. Avoids to estimate signature length before a signing document. Used for signing via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) an via {@code ExternalSignature}. If {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) returns a signature longer than {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}), then {@code SignatureLengthMismatchException} will be thrown. The default value is {@code false}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setContactInfo {#setContactInfo-java.lang.String-}
Set information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number.

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
Gets/sets the custom appearance.

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
The delegate for custom hash and sign the document (Beta). {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
The delegate for custom sign the document hash (Beta). {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

### setDate {#setDate-java.util.Date-}
Set the time of signing.

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

Gets or sets the default length for the signature data in bytes. This is an estimation of the length of the signature in bytes. Used for signing via {@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) if the {@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) parameter is set. The default value is 3000.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setImage {#setImage-java.io.InputStream-}
Sets image stream.

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
Sets the CPU host name or physical location of the signing.

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
Gets/sets ocsp settings.

### setReason {#setReason-java.lang.String-}
Sets the reason for the signing, such as (I agreed!, Pip B.).

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
Sets timestamp settings.

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

Gets/sets ltv validation flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### verify {#verify--}
```
public boolean verify()
```

Verify the document regarding this signature and return true if document is valid or otherwise false.

**Returns:**
true if document is valid.

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verify the document regarding this signature and return true if document is valid or otherwise false.

**Returns:**
true if document is valid.

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verify the document regarding this signature and return true if document is valid or otherwise false.

**Returns:**
true if document is valid.
