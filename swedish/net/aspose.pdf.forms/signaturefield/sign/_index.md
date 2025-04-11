---
title: SignatureField.Sign
second_title: Aspose.PDF for .NET API Reference
description: SignatureField-metod. Signerar dokumentet med hjälp av detta signaturfält
type: docs
weight: 50
url: /sv/net/aspose.pdf.forms/signaturefield/sign/
---
## Sign(Signature, Stream, string) {#sign_1}

Signerar dokumentet med hjälp av detta signaturfält.

```csharp
public void Sign(Signature signature, Stream pfx, string pass)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signature | Signature | Signaturobjekt, se [`PKCS1`](../../pkcs1/), [`PKCS7`](../../pkcs7/), [`PKCS7Detached`](../../pkcs7detached/). |
| pfx | Stream | Ström med certifikat. |
| pass | String | Lösenord för att få åtkomst till privat i *pfx*. |

### Se Även

* klass [Signature](../../signature/)
* klass [SignatureField](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Sign(Signature) {#sign}

Signera dokumentet med hjälp av detta signaturfält.

```csharp
public void Sign(Signature signature)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signature | Signature | Signaturobjekt, se [`PKCS1`](../../pkcs1/), [`PKCS7`](../../pkcs7/) och [`PKCS7Detached`](../../pkcs7detached/). |

### Se Även

* klass [Signature](../../signature/)
* klass [SignatureField](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)