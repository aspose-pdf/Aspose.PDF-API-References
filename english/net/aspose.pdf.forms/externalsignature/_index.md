---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ExternalSignature class. Creates a detached PKCS7Detached signature using a X509Certificate2. It supports usb smartcards tokens without exportable private keys
type: docs
weight: 3450
url: /net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class

Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

```csharp
public class ExternalSignature : Signature
```

## Constructors

| Name | Description |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [ExternalSignature](externalsignature/#constructor_1)(string, bool) | Creates a PKCS#7 (detached) signature using a X509Certificate2 as base64 string. |

## Properties

| Name | Description |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | The name of the person or authority signing the document. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | An array of pairs of integers (starting byte offset, length in bytes) that shall describe the exact byte range for the digest calculation. |
| [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) { get; } | The certificate with the private key. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Gets/sets the custom appearance. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | The delegate for custom sign the document hash (Beta). |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | The time of signing. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | The CPU host name or physical location of the signing. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Gets/sets ocsp settings. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | The reason for the signing, such as (I agree, Pip B.). |
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


