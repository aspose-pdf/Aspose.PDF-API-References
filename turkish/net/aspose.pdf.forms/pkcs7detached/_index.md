---
title: Class PKCS7Detached
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.PKCS7Detached sınıfı. Internet RFC 2315 PKCS 7 Kriptografik Mesaj Söz Dizimi Versiyon 1.5'teki PKCS7 spesifikasyonuna uygun PKCS7 nesnesini temsil eder. Belgelerin byte aralığı üzerindeki orijinal imzalı mesaj özeti, normal PKCS7 SignedData alanı olarak dahil edilmiştir. PKCS7 SignedData alanında hiçbir veri kapsüllenmemelidir.
type: docs
weight: 5190
url: /tr/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached sınıfı

Internet RFC 2315'teki PKCS#7 spesifikasyonuna uygun PKCS#7 nesnesini temsil eder, PKCS #7: Kriptografik Mesaj Söz Dizimi, Versiyon 1.5. Belgelerin byte aralığı üzerindeki orijinal imzalı mesaj özeti, normal PKCS#7 SignedData alanı olarak dahil edilmiştir. PKCS#7 SignedData alanında hiçbir veri kapsüllenmemelidir.

```csharp
public sealed class PKCS7Detached : Signature
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | `PKCS7Detached` sınıfının yeni bir örneğini başlatır. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | `PKCS7Detached` sınıfının yeni bir örneğini başlatır. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | `PKCS7Detached` sınıfının yeni bir örneğini başlatır. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | `PKCS7Detached` sınıfının yeni bir örneğini başlatır. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | `PKCS7Detached` sınıfının yeni bir örneğini başlatır. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | `PKCS7Detached` sınıfının yeni bir örneğini başlatır. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | `PKCS7Detached` sınıfının yeni bir örneğini başlatır. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | `PKCS7Detached` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Belgeyi imzalayan kişi veya otoritenin adı. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | İmzanın uzunluğunu tahmin etmekten kaçınıp kaçınmayacağını belirten bir seçeneği alır ve ayarlar. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Özüt hesaplaması için tam byte aralığını tanımlayan tam sayı çiftleri (başlangıç byte ofseti, byte cinsinden uzunluk) dizisi. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | İmzalayan tarafından, alıcının imzayı doğrulamak için imzalayanla iletişim kurmasını sağlamak amacıyla sağlanan bilgi, örneğin bir telefon numarası. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Özel görünümü alır/ayarlar. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Belge hash'ini özel olarak imzalamak için delege. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | İmza zamanı. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | İmza verisinin byte cinsinden varsayılan uzunluğunu alır veya ayarlar. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | İmzanın yapıldığı CPU ana bilgisayar adı veya fiziksel konumu. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Ocsp ayarlarını alır/ayarlar. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | İmzanın nedeni, örneğin (Kabul ediyorum, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda imza alanı önceden tanımlanmış bir görünüm formatına sahiptir (temsil etmek için dizeler): ------------------------------------------- Dijital olarak imzalanmıştır {certificate subject} Tarih: {signature.Date} Neden: {signature.Reason} Konum: {signature.Location} ------------------------------------------- burada {X} X değeri için yer tutucudur. Ayrıca imza bir resme sahip olabilir, bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak true'dur. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Zaman damgası ayarlarını alır/ayarlar. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Ltv doğrulama bayrağını alır/ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | İmzada kullanılan imza algoritması hakkında bilgi alır. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |

### Ayrıca Bakınız

* sınıf [Signature](../signature/)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../)