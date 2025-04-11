---
title: SignatureField.Sign
second_title: Aspose.PDF for .NET API Reference
description: SignatureField-Methode. Signiert das Dokument mit diesem Signaturfeld
type: docs
weight: 50
url: /de/net/aspose.pdf.forms/signaturefield/sign/
---
## Sign(Signature, Stream, string) {#sign_1}

Signiert das Dokument mit diesem Signaturfeld.

```csharp
public void Sign(Signature signature, Stream pfx, string pass)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signature | Signature | Signaturobjekt, siehe [`PKCS1`](../../pkcs1/), [`PKCS7`](../../pkcs7/), [`PKCS7Detached`](../../pkcs7detached/). |
| pfx | Stream | Stream mit Zertifikat. |
| pass | String | Passwort zum Zugriff auf das Private im *pfx*. |

### Siehe Auch

* Klasse [Signature](../../signature/)
* Klasse [SignatureField](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## Sign(Signature) {#sign}

Signieren Sie das Dokument mit diesem Signaturfeld.

```csharp
public void Sign(Signature signature)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signature | Signature | Signaturobjekt, siehe [`PKCS1`](../../pkcs1/), [`PKCS7`](../../pkcs7/) und [`PKCS7Detached`](../../pkcs7detached/). |

### Siehe Auch

* Klasse [Signature](../../signature/)
* Klasse [SignatureField](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)