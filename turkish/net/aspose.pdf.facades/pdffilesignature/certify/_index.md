---
title: PdfFileSignature.Certify
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature metodu. Belgeyi MDP imzası ile onaylayın. İmza nedeni, iletişim ve konum gibi veriler, Signature nesnesinin sig özellikleri tarafından sağlanmalıdır.
type: docs
weight: 70
url: /tr/net/aspose.pdf.facades/pdffilesignature/certify/
---
## Certify(int, string, string, string, bool, Rectangle, DocMDPSignature) {#certify}

Belgeyi MDP imzası ile onaylayın. İmza nedeni, iletişim ve konum gibi veriler, Signature nesnesinin sig özellikleri tarafından sağlanmalıdır.

```csharp
public void Certify(int page, string SigReason, string SigContact, string SigLocation, 
    bool visible, Rectangle annotRect, DocMDPSignature docMdpSignature)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayfa | Int32 | İmzanın yapıldığı sayfa. |
| SigReason | String | İmzanın nedeni. |
| SigContact | String | İmzanın iletişimi. |
| SigLocation | String | İmzanın konumu. |
| visible | Boolean | İmzanın görünürlüğü. |
| annotRect | Rectangle | İmzanın dikdörtgeni. |
| docMdpSignature | DocMDPSignature | İmzanın belge MDP türü. |

### Ayrıca Bakınız

* sınıf [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* sınıf [PdfFileSignature](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## Certify(string, DocMDPSignature) {#certify_1}

Belgeyi, zaten mevcut olan imza alanında yer alan MDP imzası ile onaylayın. İmza alanı imzalamadan önce boş olmalıdır, yani alan imza sözlüğü içermemelidir. Bu nedenle pdf belgesi zaten bir imza alanına sahipse, imzayı damgalamak için yeri, ilgili sayfa ve dikdörtgen imza adı ile bulunan imza alanından alınır (bkz. sigName parametresi).

```csharp
public void Certify(string sigName, DocMDPSignature docMdpSignature)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sigName | String | İmza alanının adı. |
| docMdpSignature | DocMDPSignature | İmzanın türü, [`PKCS1`](../../../aspose.pdf.forms/pkcs1/), [`PKCS7`](../../../aspose.pdf.forms/pkcs7/) ve [`PKCS7Detached`](../../../aspose.pdf.forms/pkcs7detached/) olabilir. |

### Ayrıca Bakınız

* sınıf [DocMDPSignature](../../../aspose.pdf.forms/docmdpsignature/)
* sınıf [PdfFileSignature](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)