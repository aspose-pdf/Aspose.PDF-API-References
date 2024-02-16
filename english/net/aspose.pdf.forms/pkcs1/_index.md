---
title: Class PKCS1
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS1 class. Represents signature object regarding PKCS1 standard. RSA encryption algorithm and SHA1 digest method are used for signing
type: docs
weight: 3210
url: /net/aspose.pdf.forms/pkcs1/
---
## PKCS1 class

Represents signature object regarding PKCS#1 standard. RSA encryption algorithm and SHA-1 digest method are used for signing.

```csharp
public sealed class PKCS1 : Signature
```

## Constructors

| Name | Description |
| --- | --- |
| [PKCS1](pkcs1/#constructor)() | Inititalizes new instance of the `PKCS1` class. |
| [PKCS1](pkcs1/#constructor_1)(Stream) | Initializes new instance of the `PKCS1` class. |
| [PKCS1](pkcs1/#constructor_2)(Stream, string) | Inititalizes new instance of the `PKCS1` class. |
| [PKCS1](pkcs1/#constructor_3)(string, string) | Inititalizes new instance of the `PKCS1` class. |

## Properties

| Name | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | The name of the person or authority signing the document. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | An array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Gets/sets the custom appearance. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | The delegate for custom sign the document hash (Beta). |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | The time of signing. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | The CPU host name or physical location of the signing. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Gets/sets ocsp settings. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | The reason for the signing, such as (I agreeРІР‚В¦). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance (strings to represent): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image. ShowProperties is true by default. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Gets/sets timestamp settings. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Gets/sets ltv validation flag. |

## Methods

| Name | Description |
| --- | --- |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verify the document regarding this signature and return true if document is valid or otherwise false. |

### See Also

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


