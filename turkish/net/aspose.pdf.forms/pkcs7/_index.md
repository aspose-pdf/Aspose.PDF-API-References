---
title: Class PKCS7
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS7 sınıfı. Internet RFC 2315 PKCS 7 Kriptografik Mesaj Söz Dizimi Versiyon 1.5'teki PKCS7 spesifikasyonuna uygun PKCS7 nesnesini temsil eder. Belgelerin bayt aralığının SHA1 özeti PKCS7 SignedData alanında kapsüllenmiştir.
type: docs
weight: 5180
url: /tr/net/aspose.pdf.forms/pkcs7/
---
## PKCS7 sınıfı

Internet RFC 2315'teki PKCS#7 spesifikasyonuna uygun PKCS#7 nesnesini temsil eder, PKCS #7: Kriptografik Mesaj Söz Dizimi, Versiyon 1.5. Belgenin bayt aralığının `SHA1 özeti` PKCS#7 SignedData alanında kapsüllenmiştir.

```csharp
public sealed class PKCS7 : Signature
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PKCS7](pkcs7/#constructor)() | `PKCS7` sınıfının yeni bir örneğini başlatır. |
| [PKCS7](pkcs7/#constructor_1)(Stream, string) | `PKCS7` sınıfının yeni bir örneğini başlatır. |
| [PKCS7](pkcs7/#constructor_2)(string, string) | `PKCS7` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Belgeyi imzalayan kişi veya otoritenin adı. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Bir imzanın uzunluğunu tahmin etmekten kaçınıp kaçınmayacağını belirten bir seçeneği alır ve ayarlar. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Özüt hesaplaması için tam bayt aralığını tanımlayan tam sayı çiftleri (başlangıç bayt ofseti, bayt cinsinden uzunluk) dizisi. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | İmzalayan tarafından sağlanan, alıcının imzalayanla iletişim kurarak imzayı doğrulamasını sağlamak için gereken bilgi, örneğin bir telefon numarası. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Özel görünümü alır/ayarlar. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Belge özütünü imzalamak için özel bir delege. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | İmza tarihi. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | İmza verisi için bayt cinsinden varsayılan uzunluğu alır veya ayarlar. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | İmzanın yapıldığı CPU ana bilgisayar adı veya fiziksel konumu. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Ocsp ayarlarını alır/ayarlar. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | İmzanın nedeni, örneğin (Kabul ediyorum, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda imza alanı önceden tanımlanmış bir görünüm formatına sahiptir (temsil etmek için dizeler): ------------------------------------------- Dijital olarak imzalanmıştır {certificate subject} Tarih: {signature.Date} Neden: {signature.Reason} Konum: {signature.Location} ------------------------------------------- burada {X} X değeri için yer tutucudur. Ayrıca imza bir resme sahip olabilir, bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak true'dur. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Zaman damgası ayarlarını alır/ayarlar. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Ltv doğrulama bayrağını alır/ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | İmzada kullanılan imza algoritması hakkında bilgi alır. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |

### Ayrıca Bakınız

* sınıf [Signature](../signature/)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../)