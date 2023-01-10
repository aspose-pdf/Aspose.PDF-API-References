---
title: PKCS7
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents the PKCS#7 object that conform to the PKCS#7 specification in Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, Version 1.5.<br/>            The SHA1 digest of the document's byte range is encapsulated in the PKCS#7 SignedData field.
type: docs
weight: 190
url: /python-net/aspose.pdf.forms/pkcs7/
---

## PKCS7 class

Represents the PKCS#7 object that conform to the PKCS#7 specification in Internet RFC 2315, <br/>            PKCS #7: Cryptographic Message Syntax, Version 1.5.<br/>            The SHA1 digest of the document's byte range is encapsulated in the PKCS#7 SignedData field.

The PKCS7 type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PKCS7()|Inititalizes new instance of the [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/) class.|
|PKCS7(pfx, password)|Initializes a new instance of the PKCS7 class|
|PKCS7(pfx, password)|Initializes a new instance of the PKCS7 class|
## Properties
| Name | Description |
| :- | :- |
|custom_appearance|Gets/sets the custom appearance.|
|authority|The name of the person or authority signing the document.|
|date|The time of signing.|
|location|The CPU host name or physical location of the signing.|
|reason|The reason for the signing, such as (I agreeРІР‚В¦).|
|contact_info|Information provided by the signer to enable a recipient to contact the signer <br/>            to verify the signature, e.g. a phone number.|
|byte_range|An array of pairs of integers (starting byte offset, length in bytes) <br/>             that shall describe the exact byte range for the digest calculation.|
|timestamp_settings|Gets/sets timestamp settings.|
|ocsp_settings|Gets/sets ocsp settings.|
|use_ltv|Gets/sets ltv validation flag.|
|show_properties|Force to show/hide signature properties.<br/>            In case ShowProperties is true signature field has predefined format of appearance (strings to represent):<br/>            -------------------------------------------<br/>            Digitally signed by {certificate subject}<br/>            Date: {signature.Date}<br/>            Reason: {signature.Reason}<br/>            Location: {signature.Location}<br/>            -------------------------------------------<br/>            where {X} is placeholder for X value. Also signature can have image, in this case listed strings are placed over image.<br/>            ShowProperties is true by default.|
## Methods
| Name | Description |
| :- | :- |
|verify()|Verify the document regarding this signature and return true if document is valid <br/>            or otherwise false.|

### See Also

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

