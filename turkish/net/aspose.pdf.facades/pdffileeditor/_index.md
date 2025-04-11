---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditor sınıfı. PDF dosyası birleştirme, ayırma, sayfa çıkarma, broşür yapma vb. işlemleri uygular.
type: docs
weight: 4460
url: /tr/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor sınıfı

PDF dosyası ile işlemleri uygular: birleştirme, ayırma, sayfa çıkarma, broşür yapma vb.

```csharp
public sealed class PdfFileEditor
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | true olarak ayarlandığında, işlemin ardından akışlar kapatılır. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | UseDiskBuffer true olarak ayarlandığında, birleştirme sırasında yeni artımlı güncelleme yapılmadan önce birleştirilen belge sayısı. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Dönüşüm sürecinin günlüğünü alır. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | PDF dosyası formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse, dosya varsayılan PDF formatında kaydedilecektir. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | true ise, birleştirme gerçekleştirildiğinde dosyanın mantıksal yapısı kopyalanır. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | true ise, taslaklar kopyalanır. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Bu özellik, birleştirme işlemi sırasında bozuk bir dosya ile karşılaşıldığında davranışı tanımlar. Olası değerler: StopWithError ve ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Birleştirme gerçekleştirildiğinde karşılaşılan sorunların dizisi. Concatenate() fonksiyonuna geçirilen her bozuk belge için yeni bir CorruptedItem girişi oluşturulur. Bu özellik yalnızca CorruptedFileAction ConcatenateIgnoringCorrupted olduğunda kullanılabilir. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | true ise, birleştirme sırasında artımlı güncellemeler yapılır. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | true ise, eylemler kaynak belgelerden kopyalanır. Varsayılan değer: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | true ise, formlar birleştirildiğinde alan adları benzersiz hale getirilir. Alan adlarına ekler eklenecek, ek şablonu UniqueSuffix özelliğinde belirtilebilir. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | En son meydana gelen istisnayı alır. Başarısızlık nedenini kontrol etmek için kullanılabilir. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | Bu özellik true ise, eşit isimli birleştirilmiş belgelerin içeriği bir katmanda birleştirilecektir. Aksi takdirde, eşit isimli katmanlar sonuç belgede farklı katmanlar olarak kaydedilecektir. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | true ise, yinelenen taslaklar birleştirilir. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Optimizasyon bayrağını alır veya ayarlar. Sonuç dosyasındaki eşit kaynak akışları bir PDF nesnesinde birleştirilir. Bu, sonuç dosyasının boyutunu azaltmaya olanak tanır ancak daha yavaş yürütme ve daha büyük bellek gereksinimlerine neden olabilir. Varsayılan değer: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Kaynak giriş PDF dosyası şifrelenmişse, sahibin şifresini ayarlar. Bu özellik henüz uygulanmamıştır. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | true ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır. Diğer belgelerin kullanıcı hakları göz ardı edilir. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | true ise, tüm imzalar alanlardan kaldırılacaktır (alanlar kalacaktır); aksi takdirde, geçersiz imzalar alabilirsiniz. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Formlar birleştirildiğinde alan adını benzersiz hale getirmek için eklenen ekin formatı. Bu dize, sayılarla değiştirilecek %NUM% alt dizesini içermelidir. Örneğin, UniqueSuffix = "ABC%NUM%" ise, "fieldName" alanı için isimler: fieldNameABC1, fieldNameABC2, fieldNameABC3 vb. olacaktır. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Bu seçenek kullanılıyorsa, hedef belge periyodik olarak diske kaydedilecek ve daha sonraki birleştirme artımlı güncellemeler olarak uygulanacaktır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan alan birimlerinde belirtilmiştir. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan alan birimlerinde belirtilmiştir. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları başlangıç sayfa boyutunun yüzdesi olarak belirtilmiştir. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları başlangıç sayfa boyutunun yüzdesi olarak belirtilmiştir. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Belge sayfalarına sayfa sonları ekler. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Belge sayfalarına sayfa sonları ekler. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Belge sayfalarına sayfa sonları ekler. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | portStream'den startPage ile endPage arasındaki aralıkta seçilen sayfaları, firstInputStream'in sonuna ekler. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | portStreams dizisindeki belgelerden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve tüm portStreams belgelerinin startPage ile endPage arasındaki sayfalarını içerir. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | portFile'den startPage ile endPage arasındaki aralıkta seçilen sayfaları, firstInputFile'in sonuna ekler. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | portFiles belgelerinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve tüm portFiles belgelerinin startPage ile endPage arasındaki sayfalarını içerir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Belgeleri birleştirir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Dosyaları birleştirir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Dosyaları tek bir dosya haline getirir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | İki dosyayı birleştirir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | İki dosyayı birleştirir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | İki PDF belgesini yeni bir PDF belgesine birleştirir ve sayfaları alternatif yollarla yerleştirir ve boş yerleri boş sayfalarla doldurur. Örneğin: document1 5 sayfaya sahiptir: p1, p2, p3, p4, p5. document2 3 sayfaya sahiptir: p1', p2', p3'. İki PDF belgesinin birleştirilmesi, sonuç belgesini şu sayfalarla üretecektir: p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | İki PDF belgesini yeni bir PDF belgesine birleştirir ve sayfaları alternatif yollarla yerleştirir ve boş yerleri boş sayfalarla doldurur. Örneğin: document1 5 sayfaya sahiptir: p1, p2, p3, p4, p5. document2 3 sayfaya sahiptir: p1', p2', p3'. İki PDF belgesinin birleştirilmesi, sonuç belgesini şu sayfalarla üretecektir: p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Giriş dosyasından numara dizisi ile belirtilen sayfaları siler, yeni bir PDF dosyası olarak kaydeder. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Giriş dosyasından numara dizisi ile belirtilen sayfaları siler, yeni bir PDF dosyası olarak kaydeder. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Numara dizisi ile belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Numara dizisi ile belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Giriş dosyasından sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Giriş dosyasından sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Başka bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Başka bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Başka bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Başka bir dosyadan sayfaları belirli bir konuma ekler. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | InputStream'den outputStream'e broşür yapar. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Giriş dosyasından çıkış dosyasına broşür yapar. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Giriş akışından broşür yapar ve sonucu çıkış akışına kaydeder. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Giriş dosyasından çıkış dosyasına broşür yapar. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | İlk InputStream'den outputStream'e özelleştirilmiş broşür yapar. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | İlk InputFile'dan outputFile'a özelleştirilmiş broşür yapar. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | İlk InputStream'den outputStream'e broşür yapar. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | İlk InputFile'dan outputFile'a özelleştirilmiş broşür yapar. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | İki giriş PDF akışından outputStream'e N-Up belgesi yapar. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Çoklu giriş PDF akışlarından outputStream'e N-Up belgesi yapar. Her outputStream sayfası, aynı sayfa numarasındaki giriş akışlarındaki sayfalarla birleştirilmiş çoklu sayfaları içerecektir. Çoklu sayfalar, isSidewise true ise yatay olarak, false ise dikey olarak birikmiş olacaktır. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | İki giriş PDF dosyasından outputFile'a N-Up belgesi yapar. Her outputFile sayfası, bir sayfa ilk giriş dosyasından ve diğeri ikinci giriş dosyasından olmak üzere iki sayfa içerecektir. İki sayfa yatay olarak birikmiş olacaktır. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Çoklu giriş PDF dosyalarından outputFile'a N-Up belgesi yapar. Her outputFile sayfası, aynı sayfa numarasındaki giriş dosyalarındaki sayfalarla birleştirilmiş çoklu sayfaları içerecektir. Çoklu sayfalar, isSidewise true ise yatay olarak, false ise dikey olarak birikmiş olacaktır. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Giriş akışından N-Up belgesi yapar ve sonucu çıkış akışına kaydeder. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | İlk InputFile'dan outputFile'a N-Up belgesi yapar. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | İlk giriş akışından çıkış akışına N-Up belgesi yapar. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Giriş dosyasından outputFile'a N-Up belgesi yapar. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Belgenin sayfalarını yeniden boyutlandırır. Küçültülen sayfanın etrafına boş kenar boşlukları eklenir. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Belgenin sayfalarını yeniden boyutlandırır. Küçültülen sayfanın etrafına boş kenar boşlukları eklenir. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Belgenin sayfalarının içeriğini yeniden boyutlandırır. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültüldüğünde, sayfanın etrafına boş kenar boşlukları eklenir. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. İçeriğin yeni boyutu varsayılan alan birimlerinde belirtilmiştir. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. İçeriğin yeni boyutu varsayılan alan birimlerinde belirtilmiştir. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzdelerle belirtilmiştir. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzdelerle belirtilmiştir. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Başlangıçtan belirtilen konuma kadar ayırır ve ön kısmı çıkış akışında kaydeder. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | PDF dosyasını ilk sayfadan belirtilen konuma kadar ayırır ve ön kısmı yeni bir dosya olarak kaydeder. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | PDF dosyasını birkaç belgeye ayırır. Belgeler tek sayfa veya çok sayfalı olabilir. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | PDF dosyasını birkaç belgeye ayırır. Belgeler tek sayfa veya çok sayfalı olabilir. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Belirtilen konumdan ayırır ve arka kısmı yeni bir dosya akışı olarak kaydeder. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Belirtilen konumdan ayırır ve arka kısmı yeni bir dosya olarak kaydeder. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | PDF dosyasını tek sayfa belgelerine ayırır. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | PDF dosyasını tek sayfa belgelerine ayırır. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | PDF dosyasını tek sayfa belgelerine ayırır ve belirtilen yola kaydeder. Yol, alan adı şablonuyla belirtilmiştir. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | PDF dosyasını tek sayfa belgelerine ayırır ve belirtilen yola kaydeder. Yol, alan adı şablonuyla belirtilmiştir. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | portStreams dizisindeki belgelerden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve tüm portStreams belgelerinin startPage ile endPage arasındaki sayfalarını içerir. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | portFiles belgelerinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve tüm portFiles belgelerinin startPage ile endPage arasındaki sayfalarını içerir. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Belgeleri birleştirir. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Dosyaları birleştirir. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Dosyaları tek bir dosya haline getirir. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | İki dosyayı birleştirir. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | İki PDF belgesini yeni bir PDF belgesine birleştirir ve sayfaları alternatif yollarla yerleştirir ve boş yerleri boş sayfalarla doldurur. Örneğin: document1 5 sayfaya sahiptir: p1, p2, p3, p4, p5. document2 3 sayfaya sahiptir: p1', p2', p3'. İki PDF belgesinin birleştirilmesi, sonuç belgesini şu sayfalarla üretecektir: p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | İki PDF belgesini yeni bir PDF belgesine birleştirir ve sayfaları alternatif yollarla yerleştirir ve boş yerleri boş sayfalarla doldurur. Örneğin: document1 5 sayfaya sahiptir: p1, p2, p3, p4, p5. document2 3 sayfaya sahiptir: p1', p2', p3'. İki PDF belgesinin birleştirilmesi, sonuç belgesini şu sayfalarla üretecektir: p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Giriş dosyasından numara dizisi ile belirtilen sayfaları siler, yeni bir PDF dosyası olarak kaydeder. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Giriş dosyasından numara dizisi ile belirtilen sayfaları siler, yeni bir PDF dosyası olarak kaydeder. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Numara dizisi ile belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Numara dizisi ile belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Giriş dosyasından sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Başka bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Başka bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | InputStream'den outputStream'e broşür yapar. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Giriş dosyasından çıkış dosyasına broşür yapar. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Giriş akışından broşür yapar ve sonucu çıkış akışına kaydeder. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Giriş dosyasından çıkış dosyasına broşür yapar. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | İlk InputStream'den outputStream'e özelleştirilmiş broşür yapar. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | İlk InputFile'dan outputFile'a özelleştirilmiş broşür yapar. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | İlk InputStream'den outputStream'e broşür yapar. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | İlk InputFile'dan outputFile'a özelleştirilmiş broşür yapar. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | İki giriş PDF akışından outputStream'e N-Up belgesi yapar. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Çoklu giriş PDF akışlarından outputStream'e N-Up belgesi yapar. Her outputStream sayfası, aynı sayfa numarasındaki giriş akışlarındaki sayfalarla birleştirilmiş çoklu sayfaları içerecektir. Çoklu sayfalar, isSidewise true ise yatay olarak, false ise dikey olarak birikmiş olacaktır. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | İki giriş PDF dosyasından outputFile'a N-Up belgesi yapar. Her outputFile sayfası, bir sayfa ilk giriş dosyasından ve diğeri ikinci giriş dosyasından olmak üzere iki sayfa içerecektir. İki sayfa yatay olarak birikmiş olacaktır. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Çoklu giriş PDF dosyalarından outputFile'a N-Up belgesi yapar. Her outputFile sayfası, aynı sayfa numarasındaki giriş dosyalarındaki sayfalarla birleştirilmiş çoklu sayfaları içerecektir. Çoklu sayfalar, isSidewise true ise yatay olarak, false ise dikey olarak birikmiş olacaktır. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Giriş akışından N-Up belgesi yapar ve sonucu çıkış akışına kaydeder. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | İlk InputFile'dan outputFile'a N-Up belgesi yapar. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | İlk giriş akışından çıkış akışına N-Up belgesi yapar. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Giriş dosyasından outputFile'a N-Up belgesi yapar. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Belgenin sayfalarının içeriğini yeniden boyutlandırır. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültüldüğünde, sayfanın etrafına boş kenar boşlukları eklenir. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. İçeriğin yeni boyutu varsayılan alan birimlerinde belirtilmiştir. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Başlangıçtan belirtilen konuma kadar ayırır ve ön kısmı çıkış akışında kaydeder. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | PDF dosyasını ilk sayfadan belirtilen konuma kadar ayırır ve ön kısmı yeni bir dosya olarak kaydeder. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Belirtilen konumdan ayırır ve arka kısmı yeni bir dosya akışı olarak kaydeder. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Belirtilen konumdan ayırır ve arka kısmı yeni bir dosya olarak kaydeder. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Birleştirme sürecinde bozuk dosya ile karşılaşıldığında gerçekleştirilen eylem. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Sayfa yeniden boyutlandırma parametrelerini belirtmek için sınıf. Aşağıdaki parametreleri ayarlamaya izin verir: Sonuç sayfasının boyutu (genişlik, yükseklik) varsayılan alan birimlerinde veya başlangıç sayfa boyutunun yüzdesi olarak; Sol, Üst, Alt ve Sağ kenar boşlukları varsayılan alan birimlerinde veya başlangıç sayfa boyutunun yüzdesi olarak; Bazı değerler otomatik hesaplama için null bırakılabilir. Bu değerler, açıkça belirtilen değerlerin hesaplanmasından sonra sayfa boyutunun geri kalanından hesaplanacaktır. Örneğin: sayfa genişliği = 100 ve yeni sayfa genişliği 60 birim olarak belirtilirse, sol ve sağ kenar boşlukları otomatik olarak hesaplanır: (100 - 60) / 2 = 15. Bu sınıf ResizeContents yönteminde kullanılır. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Varsayılan alan birimlerinde belirtilen kenar boşluğu veya içerik boyutunun değeri. Bu sınıf ContentsResizeParameters'da kullanılır. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Birleştirme sırasında bozuk dosyalar hakkında bilgi sağlayan sınıf. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Sayfa sonu konumunun verisi. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)