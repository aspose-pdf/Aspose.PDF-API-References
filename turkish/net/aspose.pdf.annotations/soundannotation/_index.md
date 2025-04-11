---
title: Class SoundAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.SoundAnnotation sınıfı. Bilgisayarın mikrofonundan kaydedilen veya bir dosyadan içe aktarılan sesi içeren bir ses anotasyonunu temsil eder.
type: docs
weight: 2530
url: /tr/net/aspose.pdf.annotations/soundannotation/
---
## SesAnnotasyonu Sınıfı

Bilgisayarın mikrofonundan kaydedilen veya bir dosyadan içe aktarılan sesi içeren bir ses anotasyonunu temsil eder.

```csharp
public sealed class SoundAnnotation : MarkupAnnotation
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [SesAnnotasyonu](soundannotation/#constructor)(Sayfa, Dikdörtgen, string) | Belirtilen sayfada yeni bir Ses anotasyonu oluşturur. |
| [SesAnnotasyonu](soundannotation/#constructor_1)(Sayfa, Dikdörtgen, string, SesÖrnekVerisi) | Belirtilen sayfada yeni bir Ses anotasyonu oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Eylemler](../../aspose.pdf.annotations/annotation/actions/) { get; } | Anotasyon eylemlerinin listesini alır. |
| sanal [AktifDurum](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut anotasyon görünüm durumunu alır veya ayarlar. |
| geçersiz [AnotasyonTürü](../../aspose.pdf.annotations/soundannotation/annotationtype/) { get; } | Anotasyon türünü alır. |
| [Görünüm](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [Kenar](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Anotasyon kenar özelliklerini alır veya ayarlar. [`Kenar`](../annotation/border/) |
| [Özellikler](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Anotasyon özelliklerini alır. |
| [Renk](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Anotasyon rengini alır veya ayarlar. |
| [İçerikler](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Anotasyon metnini alır veya ayarlar. |
| [OluşturulmaTarihi](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Anotasyonun oluşturulduğu tarih ve saati alır. |
| [Bayraklar](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Anotasyonun bayrakları. |
| [TamAd](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Anotasyonun tam nitelikli adını alır. |
| sanal [Yükseklik](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Anotasyonun yüksekliğini alır veya ayarlar. |
| sanal [Bağlantı](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça bağlantısını alır veya ayarlar (pdf oluşturucu için). |
| [Simge](../../aspose.pdf.annotations/soundannotation/icon/) { get; set; } | Anotasyonu görüntülemek için kullanılacak bir simge alır veya ayarlar. |
| [YanıtOlarak](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Bu anotasyonun "yanıt olarak" olduğu anotasyona bir referans. Her iki anotasyon da belgenin aynı sayfasında olmalıdır. |
| [SütundaİlkParagrafMı](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [SatırİçiParagrafMı](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [YeniSayfadaMı](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [SonrakiyleBirlikteTutulacakMı](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [Kenarlık](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenarlığı alır veya ayarlar (pdf oluşturma için) |
| [Değiştirildi](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Anotasyonun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [İsim](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki anotasyon adını alır veya ayarlar. |
| [Opaklık](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Anotasyonu boyamak için kullanılacak sabit opaklık değerini alır veya ayarlar. |
| sanal [Sayfaİndeksi](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Anotasyonu içeren sayfanın indeksini alır. |
| [Açılır](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Bu anotasyonla ilişkili metni girmek veya düzenlemek için açılır anotasyon. |
| sanal [Dikdörtgen](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Anotasyon dikdörtgenini alır veya ayarlar. |
| [YanıtTürü](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Bu anotasyon ile InReplyTo tarafından belirtilen anotasyon arasındaki ilişkiyi ( "yanıt türü") belirten bir dize. |
| [ZenginMetin](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Anotasyon açıldığında açılır pencerede görüntülenecek zengin metin dizesini alır veya ayarlar. |
| [SesVerisi](../../aspose.pdf.annotations/soundannotation/sounddata/) { get; } | Anotasyon etkinleştirildiğinde çalınacak sesi tanımlayan bir ses nesnesini alır. |
| [Durumlar](../../aspose.pdf.annotations/annotation/states/) { get; } | Anotasyonun görünüm sözlüğünü alır. |
| [Konu](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Nesnenin tanımını temsil eden metni alır veya ayarlar. |
| [MetinYatayHizalama](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Anotasyon için metin hizalamasını alır veya ayarlar. |
| [Başlık](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Anotasyonun başlık çubuğunda görüntülenecek metni alır veya ayarlar. |
| sanal [DikeyHizalama](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar |
| sanal [Genişlik](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Anotasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasında yer alacaktır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| geçersiz [KabulEt](../../aspose.pdf.annotations/soundannotation/accept/)(AnotasyonSeçici) | Anotasyonu işlemek için ziyaretçi nesnesini kabul eder. |
| sanal [BoyutlandırmadanSonraDeğiştir](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matris) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| [DurumuTemizle](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Anotasyon için durumu ve durum modelini temizler. Örneğin, bir anotasyon için inceleme durumunu temizler. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| sanal [Klonla](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği klonlar. Sanal yöntem. Her zaman null döner. |
| sanal [Düzleştir](../../aspose.pdf.annotations/annotation/flatten/)() | Anotasyon içeriğini doğrudan sayfaya yerleştirir, anotasyon nesnesi kaldırılacaktır. |
| [DikdörtgenAl](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak anotasyonun dikdörtgenini döndürür. |
| [DurumuAl](../../aspose.pdf.annotations/markupannotation/getstate/)() | Anotasyonun durumunu alır. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| [DurumModeliniAl](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Anotasyonun durum modelini alır. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| [İşaretliDurumuAyarla](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Anotasyon için İşaretli ve İşaretsiz durumu ayarlar. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| [İncelemeDurumunuAyarla](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnotasyonDurumu) | Bir anotasyon için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, İnceleme Durum Modeline ait olmadıkları için göz ardı edilir. Durum, hedef anotasyonu oluşturan kullanıcı tarafından ayarlanır. Değer, hedef anotasyonun Başlık özelliğinden alınır. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |
| [İncelemeDurumunuAyarla](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnotasyonDurumu, string) | Bir anotasyon için inceleme durumunu ayarlar. İşaretli ve İşaretsiz durumlar, İnceleme Durum Modeline ait olmadıkları için göz ardı edilir. Not, durumun durum ve durum modeli anahtarlarına sahip diğer metin anotasyonlarında saklandığıdır. |

### Ayrıca Bakınız

* sınıf [MarkupAnnotation](../markupannotation/)
* ad alanı [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* derleme [Aspose.PDF](../../)