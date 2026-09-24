---
title: "PKCS7.PKCS7"
linktitle: "PKCS7"
articleTitle: "PKCS7"
second_title: "Aspose.PDF for .NET"
description: "Initializes a new instance of the PKCS7 class."
type: docs
weight: 10
url: "/net/aspose.pdf.forms/pkcs7/pkcs7/"
product_version: "26.9.0"
---
## PKCS7() {#constructor}

Initializes new instance of the [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) class.

```csharp
public PKCS7()
```

### See Also

* class [PKCS7](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## PKCS7([TimestampSettings](../../../aspose.pdf/timestampsettings/)) {#constructor_1}

Inititalizes new instance of the [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) class.

The timestamp settings are used to create the timestamp signature without the need to provide a certificate.
 You can set the timestamp for a document as a separate signature.

```csharp
public PKCS7(TimestampSettings timestampSettings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| timestampSettings | TimestampSettings | The timestamp settings for the signature. |

### See Also

* class [PKCS7](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## PKCS7(string, string) {#constructor_2}

Initializes new instance of the [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) class.

```csharp
public PKCS7(string pfx, string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pfx | string | Pfx file which contains certificate for signing. |
| password | string | Password for certificate. |

### See Also

* class [PKCS7](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## PKCS7(Stream, string) {#constructor_3}

Initializes new instance of the [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) class.

```csharp
public PKCS7(Stream pfx, string password)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pfx | Stream | Stream with certificate data organized as pfx. |
| password | string | Password to get access to the private key in the certificate. |

### See Also

* class [PKCS7](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

