---
title: Class PDF3DAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.PDF3DAnnotation sınıfı. PDF3DAnnotation Sınıfı. Bu sınıf miras alınamaz
type: docs
weight: 2150
url: /tr/net/aspose.pdf.annotations/pdf3dannotation/
---
## PDF3DAnnotation sınıfı

PDF3DAnnotation Sınıfı. Bu sınıf miras alınamaz.

```csharp
public sealed class PDF3DAnnotation : Annotation
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PDF3DAnnotation](pdf3dannotation/#constructor)(Sayfa, Dikdörtgen, PDF3DSanat) | `PDF3DAnnotation` sınıfının yeni bir örneğini başlatır. |
| [PDF3DAnnotation](pdf3dannotation/#constructor_1)(Sayfa, Dikdörtgen, PDF3DSanat, PDF3DEtkinleştirme) | `PDF3DAnnotation` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Eylemler](../../aspose.pdf.annotations/annotation/actions/) { get; } | Not eylemleri listesini alır. |
| sanal [AktifDurum](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut not görünüm durumunu alır veya ayarlar. |
| geçersiz [NotTürü](../../aspose.pdf.annotations/pdf3dannotation/annotationtype/) { get; } | Not türünü alır. |
| [Görünüm](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Notun görünüm sözlüğünü alır. |
| [Sınır](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Not sınır özelliklerini alır veya ayarlar. [`Sınır`](../annotation/border/) |
| [Özellikler](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Not özelliklerini alır. |
| [Renk](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Not rengini alır veya ayarlar. |
| [İçerik](../../aspose.pdf.annotations/pdf3dannotation/content/) { get; set; } | İçeriği alır veya ayarlar. |
| [İçerikler](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Not metnini alır veya ayarlar. |
| [Bayraklar](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Notun bayrakları. |
| [TamAd](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Notun tam nitelikli adını alır. |
| sanal [Yükseklik](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Notun yüksekliğini alır veya ayarlar. |
| sanal [Bağlantı](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça bağlantısını alır veya ayarlar (pdf oluşturucu için). |
| [SütundakiİlkParagraf](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [SatırİçiParagraf](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [YeniSayfada](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [SonrakiyleBirlikteTut](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [AydınlatmaŞeması](../../aspose.pdf.annotations/pdf3dannotation/lightingscheme/) { get; } | Aydınlatma şemasını alır. |
| [KenarBoşluğu](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| [Değiştirildi](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Notun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [İsim](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki not adını alır veya ayarlar. |
| sanal [Sayfaİndeksi](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Notu içeren sayfanın indeksini alır. |
| [Pdf3DSanat](../../aspose.pdf.annotations/pdf3dannotation/pdf3dartwork/) { get; } | 3D Sanatı alır. |
| sanal [Dikdörtgen](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Not dikdörtgenini alır veya ayarlar. |
| [RenderModu](../../aspose.pdf.annotations/pdf3dannotation/rendermode/) { get; } | Render modunu alır. |
| [Durumlar](../../aspose.pdf.annotations/annotation/states/) { get; } | Notun görünüm sözlüğünü alır. |
| [MetinYatayHizalama](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Not için metin hizalamasını alır veya ayarlar. |
| sanal [DikeyHizalama](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| [GörünümDizisi](../../aspose.pdf.annotations/pdf3dannotation/viewarray/) { get; } | Görünüm dizisini alır. |
| sanal [Genişlik](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Notun genişliğini alır veya ayarlar. |
| [ZIndeksi](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değeri alır veya ayarlar. Daha büyük ZIndeksi olan bir grafik, daha küçük ZIndeksi olan grafiğin üzerine yerleştirilecektir. ZIndeksi negatif olabilir. Negatif ZIndeksi olan grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| geçersiz [KabulEt](../../aspose.pdf.annotations/pdf3dannotation/accept/)(NotSeçici) | Not işleme için ziyaretçiyi kabul eder. |
| sanal [BoyutlandırmadanSonraDeğiştir](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matris) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| [ResimÖnizlemesiniTemizle](../../aspose.pdf.annotations/pdf3dannotation/clearimagepreview/)() | Resim önizlemesini temizler. |
| sanal [Klonla](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği klonlar. Sanal yöntem. Her zaman null döner. |
| sanal [Düzleştir](../../aspose.pdf.annotations/annotation/flatten/)() | Not içeriklerini doğrudan sayfaya yerleştirir, not nesnesi kaldırılacaktır. |
| [ResimÖnizlemesiniAl](../../aspose.pdf.annotations/pdf3dannotation/getimagepreview/)() | Resim önizlemesini alır. |
| [DikdörtgeniAl](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak notun dikdörtgenini döndürür. |
| [VarsayılanGörünümİndeksiniAyarla](../../aspose.pdf.annotations/pdf3dannotation/setdefaultviewindex/)(int) | Varsayılan görünümün indeksini ayarlar. |
| [ResimÖnizlemesiniAyarla](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview/#setimagepreview)(Akış) | Resim önizlemesini ayarlar. |
| [ResimÖnizlemesiniAyarla](../../aspose.pdf.annotations/pdf3dannotation/setimagepreview/#setimagepreview_1)(string) | Resim önizlemesini ayarlar. |

### Ayrıca Bakınız

* sınıf [Not](../annotation/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)