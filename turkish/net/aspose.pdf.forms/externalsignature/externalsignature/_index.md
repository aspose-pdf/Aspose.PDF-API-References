---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: ExternalSignature yapıcısı. X509Certificate2 kullanarak ayrılmış bir PKCS7 ayrılmış imza oluşturur. İhracat yapılabilir özel anahtarları olmayan usb akıllı kart token'larını destekler
type: docs
weight: 10
url: /tr/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

X509Certificate2 kullanarak ayrılmış bir PKCS#7 `(detached)` imza oluşturur. İhracat yapılabilir özel anahtarları olmayan usb akıllı kartları, token'ları destekler.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| certificate | X509Certificate2 | Özel anahtara sahip sertifika. |

## Açıklamalar

Özet algoritması, sertifika anahtar verilerine dayalı olarak otomatik olarak seçilecektir.

### Ayrıca Bakınız

* sınıf [ExternalSignature](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

X509Certificate2 kullanarak ayrılmış bir PKCS#7 `(detached)` imza oluşturur. İhracat yapılabilir özel anahtarları olmayan usb akıllı kartları, token'ları destekler.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| certificate | X509Certificate2 | Özel anahtara sahip sertifika. |
| digestHashAlgorithm | DigestHashAlgorithm | Bir belgeyi imzalamak için özet algoritması. |

### Ayrıca Bakınız

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* sınıf [ExternalSignature](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

X509Certificate2 kullanarak ayrılmış bir PKCS#7 imza oluşturur. İhracat yapılabilir özel anahtarları olmayan usb akıllı kartları, token'ları destekler.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| certificate | X509Certificate2 | Özel anahtara sahip sertifika. |
| detached | Boolean | İmzanın ayrılmış olması gerekiyorsa true, aksi takdirde false. |

## Açıklamalar

Ayrılmış false olarak ayarlandığında özet algoritması her zaman `SHA1` olacaktır. Aksi takdirde, özet algoritması sertifika anahtar verilerine dayalı olarak otomatik olarak seçilecektir (bkz. Auto).

### Ayrıca Bakınız

* sınıf [ExternalSignature](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

X509Certificate2'yi base64 dizesi olarak kullanarak bir PKCS#7 imzası oluşturur.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| base64 | String | X509Certificate2'yi base64 dizesi olarak. |
| detached | Boolean | İmzanın ayrılmış olması gerekiyorsa true, aksi takdirde false. |

## Açıklamalar

Ayrılmış false olarak ayarlandığında özet algoritması her zaman `SHA1` olacaktır. Aksi takdirde, özet algoritması sertifika anahtar verilerine dayalı olarak otomatik olarak seçilecektir (bkz. Auto).

### Ayrıca Bakınız

* sınıf [ExternalSignature](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

X509Certificate2'yi base64 dizesi olarak kullanarak ayrılmış bir PKCS#7 `(detached)` imza oluşturur.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| base64 | String | X509Certificate2'yi base64 dizesi olarak. |
| digestHashAlgorithm | DigestHashAlgorithm | Bir belgeyi imzalamak için özet algoritması. |

### Ayrıca Bakınız

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* sınıf [ExternalSignature](../)
* ad alanı [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../../)