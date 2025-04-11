---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Page sınıfı. PDF belgesinin sayfasını temsil eden sınıf
type: docs
weight: 8050
url: /tr/net/aspose.pdf/page/
---
## Sayfa sınıfı

PDF belgesinin sayfasını temsil eden sınıf.

```csharp
public sealed class Page : IDisposable
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Sayfa özelliklerinin koleksiyonunu alır. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Sayfa notlarının koleksiyonunu alır. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Sayfanın sanat kutusunu alır veya ayarlar. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Sayfadaki nesnelerin koleksiyonunu alır. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Sayfanın arka plan rengini alır veya ayarlar. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Sayfa için arka plan resmini alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Sayfanın bleed kutusunu alır veya ayarlar. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Sayfaların renk türünü, SetColor, resimler ve formlardan alınan bilgilere göre ayarlar. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Sayfanın içerik akışındaki operatörlerin koleksiyonunu alır. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Sayfanın kırpma kutusunu alır veya ayarlar. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Sayfanın görüntülenme süresini alır veya ayarlar. Bu, sunum sırasında sayfanın görüntüleneceği süreyi saniye cinsinden belirtir. Süre tanımlanmamışsa -1 döner. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Bu sayfadaki Tab sırasındaki Field nesnelerinin listesini alır. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Sayfa altbilgisini alır veya ayarlar. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Sayfanın sayfa grubunun özelliklerini belirten bir grup özellikleri sınıfını alır veya ayarlar. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Sayfa üstbilgisini alır veya ayarlar. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Sayfanın son paragrafından sonra paragrafların eklenip eklenmeyeceğini alır veya ayarlar. |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Katmanlar koleksiyonunu alır veya ayarlar. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Sayfanın medya kutusunu alır veya ayarlar. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Notlar için çizgi stilini alır veya ayarlar. (yalnızca oluşturucu için, belge okunurken doldurulmaz) |
| [Number](../../aspose.pdf/page/number/) { get; } | Sayfanın numarasını alır. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Sayfa bilgisini alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Paragrafları alır. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Sayfanın dikdörtgenini alır veya ayarlar. Almak için: belirtilirse sayfa kırpma kutusu döner, aksi takdirde sayfa medya kutusu döner. Ayarlamak için: sayfa medya kutusu her zaman ayarlanır. Lütfen bu özelliğin sayfa döndürmesini dikkate almadığını unutmayın. Döndürmeyi dikkate alarak sayfa dikdörtgenini almak için lütfen ActualRect'i kullanın. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Sayfa kaynaklarını alır. Kaynak nesnesi, resimlerin, formların ve yazı tiplerinin koleksiyonlarını içerir. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Sayfanın döndürülmesini alır veya ayarlar. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Sayfa için dönüşüm matrisini alır. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Sayfanın sekme sırasını alır veya ayarlar. Olası değerler: Satır, Sütun. Varsayılan, Manuel |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | İçindekiler bilgilerini alır veya ayarlar. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Sayfanın trim kutusunu alır veya ayarlar. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | UserUnit değerini alır veya ayarlar. Pozitif bir sayı, varsayılan kullanıcı alanı birimlerinin boyutunu, 1 / 72 inç katları cinsinden verir. Varsayılan değer 1'dir. Bu girişi sayfada temizlemek için lütfen sıfır veya negatif bir değer ayarlayın. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Sayfanın filigranını alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Notlarla çalışmak için işlevsellik sağlayan [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) ziyaretçi nesnesini kabul eder. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Resim yerleştirme nesneleri ile çalışmak için işlevsellik sağlayan [`ImagePlacementAbsorber`](../imageplacementabsorber/) ziyaretçi nesnesini kabul eder. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Metin nesneleri ile çalışmak için işlevsellik sağlayan [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) ziyaretçi nesnesini kabul eder. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Metin nesneleri ile çalışmak için işlevsellik sağlayan [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) ziyaretçi nesnesini kabul eder. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Sayfaya grafik ekler. [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/) yöntemi ile tek tek öğe eklemekten daha hızlı çalışır. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Sayfaya resim ekler ve resmi belirtilen dikdörtgenin ortasına yerleştirir, resmin oranını korur. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Sayfaya resim ekler ve resmi belirtilen dikdörtgenin ortasına yerleştirir, resmin oranını korur. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Sayfaya aranabilir resim ekler ve resmi belirtilen dikdörtgenin ortasına yerleştirir, resmin oranını korur. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Sayfaya resim ekler ve resmi resim dikdörtgeninin konumuna göre yerleştirir. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Sayfaya damga koyar. Damga sayfa numarası, resim veya basit metin, örneğin bir logo olabilir. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Mevcut sayfayı bitmap olarak dönüştürür ve ardından byte dizisini döner. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Mevcut sayfayı utf8 kodlamasında xml olarak dönüştürür. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Görünür kenar boşlukları olmadan içerikleri içeren dikdörtgenin bbox değerini hesaplar. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Sayfayı DSR, OMR, OCR resim akışı için PNG'ye dönüştürür. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Sayfadan grafikleri siler. [`Remove`](../../aspose.pdf.vector/graphicelement/remove/) yöntemi ile tek tek öğe silmekten daha hızlı çalışır. |
| [Dispose](../../aspose.pdf/page/dispose/)() | Belleği serbest bırakır |
| [Flatten](../../aspose.pdf/page/flatten/)() | Sayfada bulunan tüm alanları kaldırır ve değerlerini yerine yerleştirir. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Önbelleğe alınmış verileri temizler |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Sayfa içeriği ile ilgili işlemler hakkında bildirimleri döner. (Şu anda yalnızca metin ekleme senaryolarında paragraf olayları hakkında bildirimler desteklenmektedir.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Sayfanın CropBox'una (veya CropBox null ise MediaBox'una) göre sayfanın dikdörtgenini döner. |
| [GetResources](../../aspose.pdf/page/getresources/)() | Sayfa ile ilişkili kaynakları alır. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Sayfada vektör grafikleri olup olmadığını tespit eder. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Sayfanın boş olup olmadığını belirten bayrağı alır. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Sayfayı gri tonlamaya dönüştürür. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Sayfadaki tüm katmanları belirtilen yeni katman adıyla tek bir katmanda birleştirir. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Sayfadaki tüm katmanları belirtilen yeni katman adıyla ve isteğe bağlı içerik grup kimliği ile tek bir katmanda birleştirir. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Sayfanın boyutunu değiştirir. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Sayfayı verilen sayfa cihazı ile işlenmek üzere gönderir. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Sayfayı verilen sayfa cihazı ile işlenmek üzere gönderir. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Sayfa için sayfa boyutunu ayarlar. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Sayfada mevcutsa vektör grafikleri kaydetmeye çalışır. Kaydetme formatı SVG'dir. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Tam sayı değerini karşılık gelen döndürme enumerasyon üyesine çevirir. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Dönüşüm enumerasyon üyesini tam sayı değerine çevirir. |

## Olaylar

| Ad | Açıklama |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Üstbilgiyi ve altbilgiyi özelleştirmek için olay. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Üstbilgiyi ve altbilgiyi özelleştirmek için prosedür. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)