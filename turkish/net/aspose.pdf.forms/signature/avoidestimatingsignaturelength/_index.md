---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: İmza özelliği. Bir imzanın uzunluğunu tahmin etmekten kaçınıp kaçınmama seçeneğini alır ve ayarlar
type: docs
weight: 30
url: /tr/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength özelliği

Bir imzanın uzunluğunu tahmin etmekten kaçınıp kaçınmama seçeneğini alır ve ayarlar.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Açıklamalar

Bir imzalı belge öncesinde imza uzunluğunu tahmin etmekten kaçınır. [`CustomSignHash`](../customsignhash/) ve [`ExternalSignature`](../../externalsignature/) aracılığıyla imzalamak için kullanılır. Eğer [`CustomSignHash`](../customsignhash/) [`DefaultSignatureLength`](../defaultsignaturelength/) değerinden daha uzun bir imza dönerse, [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) fırlatılacaktır. Varsayılan değer `false`'dur.

### Ayrıca Bakınız

* sınıf [Signature](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)