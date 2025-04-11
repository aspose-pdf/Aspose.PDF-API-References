---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.Signature sınıfı. PDF belgesindeki imza nesnesini temsil eden soyut bir sınıf. İmzalar, imza nesnelerinin değerleriyle alanlardır, sonuncusu belgenin geçerliliğini doğrulamak için kullanılan verileri içerir.
type: docs
weight: 5270
url: /tr/net/aspose.pdf.forms/signature/
---
## İmza sınıfı

PDF belgesindeki imza nesnesini temsil eden soyut bir sınıf. İmzalar, imza nesnelerinin değerleriyle alanlardır, sonuncusu belgenin geçerliliğini doğrulamak için kullanılan verileri içerir.

```csharp
public abstract class Signature
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Signature](signature/#constructor)() | `Signature` sınıfının yeni bir örneğini başlatır. |
| [Signature](signature/#constructor_1)(Stream, string) | `Signature` sınıfının yeni bir örneğini başlatır. |
| [Signature](signature/#constructor_2)(string, string) | `Signature` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Belgeyi imzalayan kişi veya otoritenin adı. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | İmzanın uzunluğunu tahmin etmekten kaçınıp kaçınmayacağını belirten bir seçeneği alır ve ayarlar. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Özdeş hesaplama için tam byte aralığını tanımlayan tam sayı çiftleri (başlangıç byte ofseti, byte cinsinden uzunluk) dizisi. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | İmzalayan tarafından sağlanan, alıcının imzayı doğrulamak için imzalayanla iletişim kurmasını sağlayan bilgi, örneğin bir telefon numarası. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Özel görünümü alır/ayarlar. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Belge hash'ini özel olarak imzalamak için delege. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | İmza zamanı. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | İmza verisi için byte cinsinden varsayılan uzunluğu alır veya ayarlar. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | İmzanın yapıldığı CPU ana bilgisayar adı veya fiziksel konumu. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | OCSP ayarlarını alır/ayarlar. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | İmza nedeni, örneğin (Kabul ediyorum, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | İmza özelliklerini gösterme/gizleme zorunluluğu. ShowProperties true olduğunda, imza alanı önceden tanımlanmış bir görünüm formatına sahiptir (temsil etmek için dizeler): ------------------------------------------- Dijital olarak imzalanmıştır {certificate subject} Tarih: {signature.Date} Sebep: {signature.Reason} Konum: {signature.Location} ------------------------------------------- burada {X} X değeri için yer tutucudur. Ayrıca imza bir resme sahip olabilir, bu durumda listelenen dizeler resmin üzerine yerleştirilir. ShowProperties varsayılan olarak true'dur. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Zaman damgası ayarlarını alır/ayarlar. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | LTV doğrulama bayrağını alır/ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | İmzada kullanılan imza algoritması hakkında bilgi alır. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | Bu imza ile belgeyi doğrular ve belge geçerliyse true, aksi takdirde false döner. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)