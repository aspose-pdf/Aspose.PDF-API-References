---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Signatur-Eigenschaft. Legt eine Option fest, die angibt, ob die Schätzung der Länge einer Signatur vermieden werden soll
type: docs
weight: 30
url: /de/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength-Eigenschaft

Legt eine Option fest, die angibt, ob die Schätzung der Länge einer Signatur vermieden werden soll.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Bemerkungen

Vermeidet die Schätzung der Signaturlänge vor einem zu signierenden Dokument. Wird verwendet für die Signatur über [`CustomSignHash`](../customsignhash/) und über [`ExternalSignature`](../../externalsignature/). Wenn [`CustomSignHash`](../customsignhash/) eine Signatur zurückgibt, die länger ist als [`DefaultSignatureLength`](../defaultsignaturelength/), wird eine [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) ausgelöst. Der Standardwert ist `false`.

### Siehe auch

* Klasse [Signature](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)