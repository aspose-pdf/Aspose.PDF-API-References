---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Stamp sınıfı. Damgayı temsil eden sınıf
type: docs
weight: 4720
url: /tr/net/aspose.pdf.facades/stamp/
---
## Damga Sınıfı

Damgayı temsil eden sınıf.

```csharp
public sealed class Stamp
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Stamp](stamp/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Sayfada şeffaflık ve karıştırma işlemleri gerçekleştirmek için kullanılan bir renk alanını tanımlayan BlendingColorSpace değerini alır veya ayarlar. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Arka plan durumunu alır veya ayarlar. Eğer doğruysa damga, damgalanmış sayfanın arka planı olarak yerleştirilecektir. Varsayılan olarak false olarak ayarlanmıştır. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Damganın opaklığını alır veya ayarlar. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Sayfa numarasını alır veya ayarlar. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Damgadan etkilenecek sayfa numaralarının bulunduğu diziyi alır veya ayarlar. Eğer Pages = null ise, belgenin tüm sayfaları etkilenir. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Resim damgasının kalitesini yüzde olarak alır veya ayarlar. Geçerli değerler 0..100% arasıdır. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Damganın derece cinsinden döndürülmesini alır veya ayarlar. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Damganın tanımlayıcısını alır veya ayarlar. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Damga olarak kullanılacak resmi ayarlar. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Resmi damga olarak ayarlar. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Metni damga olarak ayarlar. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Damga olarak kullanılacak PDF dosyasını ve sayfa numarasını ayarlar. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Damga olarak kullanılacak PDF dosyasını ve sayfa numarasını ayarlar. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Damga metninin metin durumunu ayarlar. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Resim damgasının boyutunu ayarlar. Resim belirtilen değerlere göre ölçeklendirilecektir. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Damganın yerleştirileceği sayfadaki konumu ayarlar. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)