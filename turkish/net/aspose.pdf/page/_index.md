---
title: Page
second_title: Aspose.PDF for .NET API Referansı
description: PDF belgesinin sayfasını temsil eden sınıf.
type: docs
weight: 5790
url: /tr/net/aspose.pdf/page/
---
## Page class

PDF belgesinin sayfasını temsil eden sınıf.

```csharp
public sealed class Page : IDisposable
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | Sayfa özellikleri koleksiyonunu alır. |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | Sayfa ek açıklamalarının koleksiyonunu alır. [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | Sayfanın resim kutusunu alır veya ayarlar. |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | Sayfadaki yapı koleksiyonunu alır. |
| [Background](../../aspose.pdf/page/background) { get; set; } | Sayfanın arka plan rengini alır veya ayarlar. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | Sayfa için arka plan resmini alır veya ayarlar (yalnızca jeneratör için). |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | Sayfanın taşma payı kutusunu alır veya ayarlar. |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | SetColor, resim ve form operatörlerinden alınan bilgilere göre sayfaların renk türünü ayarlar. |
| [Contents](../../aspose.pdf/page/contents) { get; } | Sayfanın içerik akışındaki operatörlerin koleksiyonunu alır. [`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | Sayfanın kırpma kutusunu alır veya ayarlar. |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | Ayarlanmış sayfa görüntüleme süresini alır. Bu, sunum sırasında sayfanın görüntüleneceği saniye cinsinden zamandır. Süre tanımlı değilse -1 döndürür. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | Bu sayfadaki Field nesnesinin listesini Sekme sırasında alır. |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | Sayfa alt bilgisini alır veya ayarlar. |
| [Group](../../aspose.pdf/page/group) { get; set; } | Saydam görüntüleme modelinde kullanım için sayfanın sayfa grubunun özniteliklerini belirten bir grup öznitelikleri sınıfını alır veya ayarlar. |
| [Header](../../aspose.pdf/page/header) { get; set; } | Sayfa başlığını alır veya ayarlar. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | Sayfanın son paragrafından sonraki paragrafların eklenmesini alır veya ayarlar |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | Katman koleksiyonunu alır veya ayarlar. |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | Sayfanın medya kutusunu alır veya ayarlar. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | Notlar için çizgi stilini alır veya ayarlar.(yalnızca oluşturucu için) |
| [Number](../../aspose.pdf/page/number) { get; } | Sayfanın numarasını alın. |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | Sayfa bilgisini alır veya ayarlar (yalnızca oluşturucu için, dosya okunurken doldurulmaz). |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | Paragrafları alır. |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | Sayfanın dikdörtgenini alır veya ayarlar. Belirtilirse sayfa kırpma kutusu döndürülür, aksi takdirde sayfa medya kutusu döndürülür. Lütfen bu özelliğin sayfa döndürmeyi dikkate almadığını unutmayın. Döndürmeyi dikkate alan sayfa dikdörtgeni almak için lütfen ActualRect. kullanın |
| [Resources](../../aspose.pdf/page/resources) { get; } | Sayfa kaynaklarını alır. Kaynaklar nesnesi, resim, form ve yazı tipi koleksiyonlarını içerir. [`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | Sayfanın dönüşünü alır veya ayarlar. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | Sayfa için dönüşüm matrisini alır. |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | Sayfanın sekme sırasını alır veya ayarlar. Olası değerler: Satır, Sütun. Varsayılan, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | İçindekiler bilgisini alır veya ayarlar. |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | Sayfanın kırpma kutusunu alır veya ayarlar. |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | UserUnit değerini alır veya ayarlar. 1 ⁄ 72 inç'in katları olarak varsayılan kullanıcı alanı birimlerinin boyutunu veren pozitif bir sayı. Varsayılan değer 1'dir. Sayfadaki bu girişi temizlemek için lütfen sıfır veya negatif değer ayarlayın. |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | Sayfanın filigranını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | Kabul eder[`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector) ek açıklamalarla çalışmak için işlevsellik sağlayan ziyaretçi nesnesi. |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | Kabul eder[`ImagePlacementAbsorber`](../imageplacementabsorber) görüntü yerleştirme nesneleri ile çalışmak için işlevsellik sağlayan ziyaretçi nesnesi. |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | Kabul eder[`TextAbsorber`](../../aspose.pdf.text/textabsorber) metin nesneleriyle çalışmak için işlevsellik sağlayan ziyaretçi nesnesi. |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | Kabul eder[`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber) metin nesneleriyle çalışmak için işlevsellik sağlayan ziyaretçi nesnesi. |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | Sayfaya resim ekler ve resmin oranını kaydeden belirtilen dikdörtgenin ortasına yerleştirir. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | Sayfaya resim ekler ve resmin oranını kaydeden belirtilen dikdörtgenin ortasına yerleştirir. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | Sayfaya aranabilir resim ekler ve resmin oranını kaydeden belirtilen dikdörtgenin ortasına yerleştirir. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | Sayfaya resim ekler ve resmin dikdörtgen konumuna göre yerleştirir. |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | Sayfaya damga koyun. Damga sayfa numarası, resim veya basit metin olabilir, örneğin bir logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | Geçerli sayfayı bitmap olarak dönüştürür ve ardından bayt dizisini döndürür. |
| [AsXml](../../aspose.pdf/page/asxml)() | Geçerli sayfayı utf8 kodlamasında xml olarak dönüştürür. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | bbox değerini hesaplar - görünür kenar boşlukları olmayan içerikleri içeren dikdörtgen. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | DSR, OMR, OCR görüntü akışı için sayfayı PNG'ye dönüştürün. |
| [Dispose](../../aspose.pdf/page/dispose)() | Belleği boşaltır |
| [Flatten](../../aspose.pdf/page/flatten)() | Sayfada bulunan tüm alanları kaldırır ve bunun yerine değerlerini yerleştirir. |
| [FreeMemory](../../aspose.pdf/page/freememory)() | Önbelleğe alınmış verileri temizler |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | Sayfa içeriğine sahip iç işlemlerle ilgili bildirimleri döndürür. (Artık yalnızca metin ekleme senaryolarındaki paragraf olaylarıyla ilgili bildirimler desteklenmektedir.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | Sayfanın dikdörtgenini döndürür. |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | Sayfanın boş olup olmadığına dair bayrağı alır. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | Sayfayı gri tonlamaya dönüştürür. |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | Sayfayı, verilen sayfa aygıtıyla işlemek için gönderir. |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | Sayfayı, verilen sayfa aygıtıyla işlemek için gönderir. |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | Sayfa için sayfa boyutunu ayarlar. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | Tamsayı değerini karşılık gelen döndürme numaralandırma üyesine çevirir. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | Döndürme numaralandırma üyesini tamsayı değerine çevirir. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | Üstbilgi ve altbilgiyi özelleştirme prosedürü. |

### Ayrıca bakınız

* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
