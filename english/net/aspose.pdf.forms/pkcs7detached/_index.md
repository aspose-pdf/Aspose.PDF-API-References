---
title: Class PKCS7Detached
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS7Detached class. Represents the PKCS7 object that conform to the PKCS7 specification in Internet RFC 2315 PKCS 7 Cryptographic Message Syntax Version 1.5. The original signed message digest over the documents byte range is incorporated as the normal PKCS7 SignedData field. No data shall is encapsulated in the PKCS7 SignedData field
type: docs
weight: 5310
url: /net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached class

Represents the PKCS#7 object that conform to the PKCS#7 specification in Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. The original signed message digest over the document's byte range is incorporated as the normal PKCS#7 SignedData field. No data shall is encapsulated in the PKCS#7 SignedData field.

```csharp
public sealed class PKCS7Detached : Signature
```

## Constructors

| Name | Description |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | Inititalizes new instance of the `PKCS7Detached` class. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | Inititalizes new instance of the `PKCS7Detached` class. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | Initializes new instance of the `PKCS7Detached` class. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | Initializes new instance of the `PKCS7Detached` class. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | Inititalizes new instance of the `PKCS7Detached` class. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | Inititalizes new instance of the `PKCS7Detached` class. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | Inititalizes new instance of the `PKCS7Detached` class. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | Inititalizes new instance of the `PKCS7Detached` class. |

## Properties

| Name | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | The name of the person or authority signing the document. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Gets and sets an option means whether to avoid estimating the length of a signature. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | An array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Gets/sets the custom appearance. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | The delegate for custom sign the document hash. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | The time of signing. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Gets or sets the default length for the signature data in bytes. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | The CPU host name or physical location of the signing. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Gets/sets ocsp settings. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | The reason for the signing, such as (I agree, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Gets/sets timestamp settings. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Gets/sets ltv validation flag. |

## Methods

| Name | Description |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Retrieves information about the signature algorithm used in the signature. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verify the document regarding this signature and return true if document is valid or otherwise false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Verify the document regarding this signature and return true if document is valid or otherwise false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(X509Certificate2, ValidationOptions, out ValidationResult) | Verify the document regarding this signature and return true if document is valid or otherwise false. Verification is performed using the external public key certificate. |

### See Also

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


