---
title: PdfFileEditor
second_title: Aspose.PDF for .NET API Referansı
description: PDF dosyasıyla işlemleri uygular birleştirme bölme sayfaları ayıklama kitapçık oluşturma vb.
type: docs
weight: 2470
url: /tr/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

PDF dosyasıyla işlemleri uygular: birleştirme, bölme, sayfaları ayıklama, kitapçık oluşturma, vb.

```csharp
public sealed class PdfFileEditor
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfFileEditor](pdffileeditor)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffileeditor/attachmentname) { get; set; } | İşlem sonucu ek olarak HttpResponse nesnelerinde depolandığında ekin adını alır veya ayarlar. |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams) { get; set; } | True olarak ayarlanırsa, işlemden sonra akışlar kapatılır. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize) { get; set; } | UseDiskBuffer true olarak ayarlandığında birleştirme sırasında yeni artımlı güncelleme yapılmadan önce birleştirilen belge sayısı. |
| [ContentDisposition](../../aspose.pdf.facades/pdffileeditor/contentdisposition) { get; set; } | İşlem sonucu HttpResponse nesnesine depolandığında içeriğin nasıl depolanacağını alır veya ayarlar. Olası değer: satır içi / ek. Varsayılan: satır içi. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog) { get; } | Dönüştürme işleminin günlüğünü alır. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto) { set; } | PDF dosya biçimini ayarlar. Sonuç dosyası, belirtilen dosya biçiminde kaydedilecektir. Bu özellik belirtilmezse, dosya dönüştürme yapılmadan varsayılan PDF formatında kaydedilecektir. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure) { get; set; } | Doğru ise, birleştirme yapıldığında dosyanın mantıksal yapısı kopyalanır. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines) { get; set; } | Doğruysa, ana hatlar kopyalanacaktır. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction) { get; set; } | Bu özellik, birleştirme işlemi bozuk dosyayla karşılaştığında davranışı tanımlar. Olası değerler şunlardır: StopWithError ve ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems) { get; } | Birleştirme gerçekleştirilirken karşılaşılan sorunlar dizisi. Concatenate() işlevine geçirilen her bozuk belge için yeni CorruptedItem girişi oluşturulur. Bu özellik yalnızca CorruptedFileAction ConcatenateIgnoringCorrupted olduğunda kullanılabilir. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates) { get; set; } | True ise, birleştirme sırasında artımlı güncellemeler yapılır. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions) { get; set; } | Gerçek eylemler kaynak belgelerden kopyalanacaksa. Varsayılan değer: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique) { get; set; } | true ise formlar birleştirildiğinde alan adları benzersiz hale getirilecektir. Alan adlarına son ekler eklenecek, UniqueSuffix özelliğinde sonek şablonu belirtilebilir. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception) { get; } | En son oluşan istisnayı alır. Başarısızlığın nedenini kontrol etmek için kullanılabilir. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers) { get; set; } | Eşit adlara sahip birleştirilmiş belgelerin isteğe bağlı içerikleri, bu özellik doğruysa, sonuçtaki belgede tek bir katmanda birleştirilecektir. Aksi takdirde, eşit ada sahip katmanlar, ortaya çıkan belgede farklı katmanlar olarak kaydedilecektir. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines) { get; set; } | Doğruysa, yinelenen ana hatlar birleştirilir. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize) { get; set; } | Optimizasyon bayrağını alır veya ayarlar. Bu işaret ayarlanırsa, sonuçtaki dosyadaki eşit kaynak akışları tek bir PDF nesnesinde birleştirilir. Bu, sonuçta ortaya çıkan dosya boyutunu küçültmeye izin verir ancak daha yavaş yürütmeye ve daha büyük bellek gereksinimlerine neden olabilir. Varsayılan değer: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword) { get; set; } | Kaynak giriş Pdf dosyası şifrelenmişse sahibinin parolasını belirler. Bu özellik henüz uygulanmadı. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights) { get; set; } | Doğruysa, birleştirilmiş belgeye ilk belgenin kullanıcı hakları uygulanır. Diğer tüm belgelerin kullanıcı hakları yok sayılır. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures) { get; set; } | Doğruysa, alanlardaki tüm imzalar kaldırılacaktır (alanlar kalacaktır); aksi takdirde geçersiz imzalar alabilirsiniz. |
| [SaveOptions](../../aspose.pdf.facades/pdffileeditor/saveoptions) { get; set; } | Sonuç HttpResponse. olarak depolandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix) { get; set; } | Formlar birleştirildiğinde benzersiz olması için alan adına eklenen son ekin biçimi. Bu dize, sayılarla değiştirilecek %NUM% alt dize içermelidir. Örneğin, UniqueSuffix = "ABC%NUM%" ise, o zaman için alan "alanAdı" adları şöyle olacaktır: alanAdıABC1, alanAdıABC2, alanAdıABC3 vb. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer) { get; set; } | Bu seçenek kullanılırsa, hedef belge periyodik olarak diske kaydedilecek ve artımlı güncellemeler olarak daha fazla birleştirme uygulanacaktır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins)(Stream, Stream, int[], double, double, double, double) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan alan birimlerinde belirtilir. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins_1)(string, string, int[], double, double, double, double) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan alan birimlerinde belirtilir. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları, ilk sayfa boyutunun yüzdeleri olarak belirtilir. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct_1)(string, string, int[], double, double, double, double) | Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları, ilk sayfa boyutunun yüzdeleri olarak belirtilir. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak)(Document, Document, PageBreak[]) | Belge sayfalarına sayfa sonları ekler. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_1)(Stream, Stream, PageBreak[]) | Belge sayfalarına sayfa sonları ekler. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_2)(string, string, PageBreak[]) | Belge sayfalarına sayfa sonları ekler. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append)(Stream, Stream, int, int, Stream) | startPage ile endPage aralığında portStream'den seçilen sayfaları, firstInputStream'in sonunda portStream'e ekler. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_2)(Stream, Stream[], int, int, HttpResponse) | Belgeleri kaynak belgeye ekler ve sonucu yanıt nesnesine kaydeder. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_1)(Stream, Stream[], int, int, Stream) | portStreams içindeki belge dizisinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage - endPage aralığındaki tüm portStreams belge sayfalarını içerir. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_3)(string, string, int, int, string) | startPage ile endPage aralığındaki portFile'dan seçilen sayfaları, firstInputFile. 'nin sonundaki portFile'a ekler. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_5)(string, string[], int, int, HttpResponse) | Belgeleri kaynak belgeye ekler ve sonucu HttpResponse nesnesine kaydeder. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_4)(string, string[], int, int, string) | portFiles belgelerinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage - endPage aralığındaki tüm portFiles belge sayfalarını içerir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate)(Document[], Document) | Belgeleri birleştirir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_4)(Stream[], HttpResponse) | Dosyaları birleştirir ve sonucu HttpResponse nesnesinde saklar. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_3)(Stream[], Stream) | Dosyaları birleştirir |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_8)(string[], HttpResponse) | Dosyaları birleştirir ve reslt'yi HttpResposnse nesnesine kaydeder. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_7)(string[], string) | Dosyaları tek bir dosyada birleştirir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_1)(Stream, Stream, Stream) | İki dosyayı birleştirir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_5)(string, string, string) | İki dosyayı birleştirir. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_2)(Stream, Stream, Stream, Stream) | İki Pdf belgesini alternatif yollarla sayfaları olan yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası vardır: p1, p2, p3, p4, p5. belge2'nin 3 sayfası vardır: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfalarla sonuç belgesini üretecektir:p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_6)(string, string, string, string) | İki Pdf belgesini alternatif yollarla sayfaları olan yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası vardır: p1, p2, p3, p4, p5. belge2'nin 3 sayfası vardır: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfalarla sonuç belgesini üretecektir:p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_1)(Stream, int[], HttpResponse) | Belirtilen sayfaları belgeden siler ve sonucu HttpResponse nesnesine kaydeder. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete)(Stream, int[], Stream) | Girdi dosyasından sayı dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_3)(string, int[], HttpResponse) | Belgeden belirtilen sayfaları siler ve sonucu HttpResponse nesnesine kaydeder. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_2)(string, int[], string) | Girdi dosyasından sayı dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_2)(Stream, int[], HttpResponse) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine depolar. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_1)(Stream, int[], Stream) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_5)(string, int[], HttpResponse) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine depolar. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_4)(string, int[], string) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract)(Stream, int, int, Stream) | Girdi dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_3)(string, int, int, string) | Girdi dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_2)(Stream, int, Stream, int[], HttpResponse) | Belgeyi başka bir belgeye ekler ve sonucu yanıt nesnesine kaydeder. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_1)(Stream, int, Stream, int[], Stream) | Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_5)(string, int, string, int[], HttpResponse) | Dosyanın içeriğini kaynak dosyaya ekler ve sonucu HttpResponse nesnesine depolar. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_4)(string, int, string, int[], string) | Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert)(Stream, int, Stream, int, int, Stream) | Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_3)(string, int, string, int, int, string) | Başka bir dosyadan sayfaları bir konumda Pdf dosyasına ekler. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_2)(Stream, Stream) | InputStream'den outputStream. 'ye kitapçık yapar |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_8)(string, string) | Girdi dosyasından çıktı dosyasına kitapçık yapar. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_1)(Stream, PageSize, HttpResponse) | Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse. içinde saklar |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_3)(Stream, Stream, PageSize) | Giriş akışından kitapçık yapar ve sonucu çıkış akışına kaydeder. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_7)(string, PageSize, HttpResponse) | Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse nesnelerine kaydeder. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_9)(string, string, PageSize) | inputFile'dan outputFile. 'ye kitapçık yapar |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_5)(Stream, Stream, int[], int[]) | FirstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_11)(string, string, int[], int[]) | FirstInputFile'dan outputFile'a özelleştirilmiş kitapçık yapar. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet)(Stream, PageSize, int[], int[], HttpResponse) | PDF dosyasından kitapçık yapın ve onu HttpResponse. içine depolayın |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_4)(Stream, Stream, PageSize, int[], int[]) | FirstInputStream'den outputStream'e kitapçık oluşturur. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse nesnelerine kaydeder. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_10)(string, string, PageSize, int[], int[]) | FirstInputFile'dan outputFile'a özelleştirilmiş kitapçık yapar. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_4)(Stream, Stream, Stream) | İki giriş PDF akışından outputStream. 'ye N-Up belge oluşturur |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_5)(Stream[], Stream, bool) | Çoklu giriş PDF akışlarından outputStream'e N-Up belgesi oluşturur. outputStream'in her sayfası, aynı sayfa numarasının giriş akışlarındaki sayfalarıyla kombinasyon halinde olan birden çok sayfa içerecektir. Çoklu sayfalar, isSidewise doğruysa yatay olarak ve isSidewise yanlışsa dikey olarak yığılır. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_10)(string, string, string) | İki giriş PDF dosyasından outputFile'a N-Up belgesi yapar. outputFile'ın her sayfası iki sayfa içerecektir, bir sayfa ilk giriş dosyasından ve diğeri ikinci giriş dosyasındandır. İki sayfa yatay olarak yığılmıştır. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_11)(string[], string, bool) | Çoklu giriş PDF dosyalarından outputFile'a N-Up belgesi yapar. outputFile'ın her sayfası, aynı sayfa numarasının giriş dosyalarındaki sayfalarıyla kombinasyon halinde olan çoklu sayfaları içerecektir. Çoklu sayfalar, isSidewise doğruysa yatay olarak ve isSidewise yanlışsa dikey olarak yığılır. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_1)(Stream, int, int, HttpResponse) | N-yukarı belge oluşturur ve sonucu HttpResponse'da saklar. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_2)(Stream, Stream, int, int) | Giriş akışından N-Up belgesi oluşturur ve sonucu çıkış akışına kaydeder. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_7)(string, int, int, HttpResponse) | N-up belge oluşturur ve sonucu HttpResponse. içinde saklar |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_8)(string, string, int, int) | FirstInputFile'dan outputFile. 'ye N-Up belgesi yapar |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup)(Stream, int, int, PageSize, HttpResponse) | N-yukarı belge oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_3)(Stream, Stream, int, int, PageSize) | İlk giriş akışından çıkış akışına N-Up belge oluşturur. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_6)(string, int, int, PageSize, HttpResponse) | N-yukarı belge oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_9)(string, string, int, int, PageSize) | Girdi dosyasından çıktıFile. dosyasına N-Up belgesi yapar |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_6)(Document, ContentsResizeParameters) | Belgenin sayfalarını yeniden boyutlandırır. Küçülen sayfanın çevresine boş kenar boşlukları eklendi. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_7)(Document, int[], ContentsResizeParameters) | Belgenin sayfalarını yeniden boyutlandırır. Küçülen sayfanın çevresine boş kenar boşlukları eklendi. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. Sonuç, HttpResponse nesnesinde saklanır. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Belgenin sayfalarının içeriğini yeniden boyutlandırır. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. Sonuç, HttpResponse nesnesinde saklanır. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_4)(string, string, int[], ContentsResizeParameters) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_2)(Stream, Stream, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu varsayılan alan birimlerinde belirtilir. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_5)(string, string, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu varsayılan alan birimlerinde belirtilir. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct)(Stream, Stream, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfa içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzde olarak belirtilir. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct_1)(string, string, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfa içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzde olarak belirtilir. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_1)(Stream, int, HttpResponse) | Belgeyi başlangıçtan belirtilen konuma böler ve sonucu HttpResponse nesnesine depolar. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst)(Stream, int, Stream) | Başlangıçtan belirtilen konuma böler ve ön kısmı çıktı Akışına kaydeder. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_3)(string, int, HttpResponse) | Belgeyi ilk sayfadan konuma böler ve sonucu HttpResponse nesnelerine kaydeder. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_2)(string, int, string) | Pdf dosyasını ilk sayfadan belirtilen konuma böler ve ön kısmı yeni bir dosya olarak kaydeder. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks)(Stream, int[][]) | Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks_1)(string, int[][]) | Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_1)(Stream, int, HttpResponse) | Belirtilen konumdan ayrılır ve arka kısmı HttpResponse nesnesine kaydeder. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend)(Stream, int, Stream) | Belirtilen konumdan ayrılır ve arka kısmı yeni bir dosya olarak kaydeder Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_3)(string, int, HttpResponse) | Belirtilen konumdan ayrılır ve arka kısmı HttpResponse nesnesine kaydeder. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_2)(string, int, string) | Konumdan ayrılır ve arka kısmı yeni bir dosya olarak kaydeder. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages)(Stream) | Pdf dosyasını tek sayfalık belgelere böler. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_1)(string) | PDF dosyasını tek sayfalık belgelere böler. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_2)(Stream, string) | Pdf dosyasını tek sayfalık belgelere böler ve belirtilen yola kaydeder. Yol, temaplate. alan adına göre belirlenir |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_3)(string, string) | Pdf dosyasını tek sayfalık belgelere böler ve belirtilen yola kaydeder. Yol, temaplate. alan adına göre belirlenir |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_1)(Stream, Stream[], int, int, HttpResponse) | Belgeleri kaynak belgeye ekler ve sonucu yanıt nesnesine kaydeder. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend)(Stream, Stream[], int, int, Stream) | portStreams içindeki belge dizisinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage - endPage aralığındaki tüm portStreams belge sayfalarını içerir. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_3)(string, string[], int, int, HttpResponse) | Belgeleri kaynak belgeye ekler ve sonucu HttpResponse nesnesine kaydeder. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_2)(string, string[], int, int, string) | portFiles belgelerinden seçilen sayfaları ekler. Sonuç belgesi, firstInputFile ve startPage - endPage aralığındaki tüm portFiles belge sayfalarını içerir. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate)(Document[], Document) | Belgeleri birleştirir. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_3)(Stream[], HttpResponse) | Dosyaları birleştirir ve sonucu HttpResponse nesnesinde saklar. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_2)(Stream[], Stream) | Dosyaları birleştirir |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_7)(string[], HttpResponse) | Dosyaları birleştirir ve reslt'yi HttpResposnse nesnesine kaydeder. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_6)(string[], string) | Dosyaları tek bir dosyada birleştirir. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_4)(string, string, string) | İki dosyayı birleştirir. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_1)(Stream, Stream, Stream, Stream) | İki Pdf belgesini alternatif yollarla sayfaları olan yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası vardır: p1, p2, p3, p4, p5. belge2'nin 3 sayfası vardır: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfalarla sonuç belgesini üretecektir:p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_5)(string, string, string, string) | İki Pdf belgesini alternatif yollarla sayfaları olan yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. örneğin: belge1'in 5 sayfası vardır: p1, p2, p3, p4, p5. belge2'nin 3 sayfası vardır: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sayfalarla sonuç belgesini üretecektir:p1, p1', p2, p2', p3, p3', p4, boş sayfa, p5, boş sayfa . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_1)(Stream, int[], HttpResponse) | Belirtilen sayfaları belgeden siler ve sonucu HttpResponse nesnesine kaydeder. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete)(Stream, int[], Stream) | Girdi dosyasından sayı dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_3)(string, int[], HttpResponse) | Belgeden belirtilen sayfaları siler ve sonucu HttpResponse nesnesine kaydeder. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_2)(string, int[], string) | Girdi dosyasından sayı dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_1)(Stream, int[], HttpResponse) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine depolar. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract)(Stream, int[], Stream) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_4)(string, int[], HttpResponse) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine depolar. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_3)(string, int[], string) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_2)(string, int, int, string) | Girdi dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_1)(Stream, int, Stream, int[], HttpResponse) | Belgeyi başka bir belgeye ekler ve sonucu yanıt nesnesine kaydeder. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert)(Stream, int, Stream, int[], Stream) | Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_3)(string, int, string, int[], HttpResponse) | Dosyanın içeriğini kaynak dosyaya ekler ve sonucu HttpResponse nesnesine depolar. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_2)(string, int, string, int[], string) | Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_2)(Stream, Stream) | InputStream'den outputStream. 'ye kitapçık yapar |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_8)(string, string) | Girdi dosyasından çıktı dosyasına kitapçık yapar. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_1)(Stream, PageSize, HttpResponse) | Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse. içinde saklar |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_3)(Stream, Stream, PageSize) | Giriş akışından kitapçık yapar ve sonucu çıkış akışına kaydeder. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_7)(string, PageSize, HttpResponse) | Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse nesnelerine kaydeder. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_9)(string, string, PageSize) | inputFile'dan outputFile. 'ye kitapçık yapar |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_5)(Stream, Stream, int[], int[]) | FirstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_11)(string, string, int[], int[]) | FirstInputFile'dan outputFile'a özelleştirilmiş kitapçık yapar. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet)(Stream, PageSize, int[], int[], HttpResponse) | PDF dosyasından kitapçık yapın ve onu HttpResponse. içine depolayın |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_4)(Stream, Stream, PageSize, int[], int[]) | FirstInputStream'den outputStream'e kitapçık oluşturur. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Kaynak dosyadan kitapçık yapar ve sonucu HttpResponse nesnelerine kaydeder. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_10)(string, string, PageSize, int[], int[]) | FirstInputFile'dan outputFile'a özelleştirilmiş kitapçık yapar. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_4)(Stream, Stream, Stream) | İki giriş PDF akışından outputStream. 'ye N-Up belge oluşturur |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_5)(Stream[], Stream, bool) | Çoklu giriş PDF akışlarından outputStream'e N-Up belgesi oluşturur. outputStream'in her sayfası, aynı sayfa numarasının giriş akışlarındaki sayfalarıyla kombinasyon halinde olan birden çok sayfa içerecektir. Çoklu sayfalar, isSidewise doğruysa yatay olarak ve isSidewise yanlışsa dikey olarak yığılır. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_10)(string, string, string) | İki giriş PDF dosyasından outputFile'a N-Up belgesi yapar. outputFile'ın her sayfası iki sayfa içerecektir, bir sayfa ilk giriş dosyasından ve diğeri ikinci giriş dosyasındandır. İki sayfa yatay olarak yığılmıştır. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_11)(string[], string, bool) | Çoklu giriş PDF dosyalarından outputFile'a N-Up belgesi yapar. outputFile'ın her sayfası, aynı sayfa numarasının giriş dosyalarındaki sayfalarıyla kombinasyon halinde olan çoklu sayfaları içerecektir. Çoklu sayfalar, isSidewise doğruysa yatay olarak ve isSidewise yanlışsa dikey olarak yığılır. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_1)(Stream, int, int, HttpResponse) | N-yukarı belge oluşturur ve sonucu HttpResponse'da saklar. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_2)(Stream, Stream, int, int) | Giriş akışından N-Up belgesi oluşturur ve sonucu çıkış akışına kaydeder. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_7)(string, int, int, HttpResponse) | N-up belge oluşturur ve sonucu HttpResponse. içinde saklar |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_8)(string, string, int, int) | FirstInputFile'dan outputFile. 'ye N-Up belgesi yapar |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup)(Stream, int, int, PageSize, HttpResponse) | N-yukarı belge oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_3)(Stream, Stream, int, int, PageSize) | İlk giriş akışından çıkış akışına N-Up belge oluşturur. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_6)(string, int, int, PageSize, HttpResponse) | N-yukarı belge oluşturur ve sonucu HttpResponse nesnesine kaydeder. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_9)(string, string, int, int, PageSize) | Girdi dosyasından çıktıFile. dosyasına N-Up belgesi yapar |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. Sonuç, HttpResponse nesnesinde saklanır. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Belgenin sayfalarının içeriğini yeniden boyutlandırır. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. Sonuç, HttpResponse nesnesinde saklanır. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_4)(string, string, int[], ContentsResizeParameters) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. Sayfa küçültülürse, sayfanın etrafına boş kenar boşlukları eklenir. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_2)(Stream, Stream, int[], double, double) | Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu varsayılan alan birimlerinde belirtilir. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_1)(Stream, int, HttpResponse) | Belgeyi başlangıçtan belirtilen konuma böler ve sonucu HttpResponse nesnesine depolar. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst)(Stream, int, Stream) | Başlangıçtan belirtilen konuma böler ve ön kısmı çıktı Akışına kaydeder. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_3)(string, int, HttpResponse) | Belgeyi ilk sayfadan konuma böler ve sonucu HttpResponse nesnelerine kaydeder. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_2)(string, int, string) | Pdf dosyasını ilk sayfadan belirtilen konuma böler ve ön kısmı yeni bir dosya olarak kaydeder. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_1)(Stream, int, HttpResponse) | Belirtilen konumdan ayrılır ve arka kısmı HttpResponse nesnesine kaydeder. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend)(Stream, int, Stream) | Belirtilen konumdan ayrılır ve arka kısmı yeni bir dosya olarak kaydeder Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_3)(string, int, HttpResponse) | Belirtilen konumdan ayrılır ve arka kısmı HttpResponse nesnesine kaydeder. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_2)(string, int, string) | Konumdan ayrılır ve arka kısmı yeni bir dosya olarak kaydeder. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](pdffileeditor.concatenatecorruptedfileaction) | Birleştirme işleminde bozuk dosyayla karşılaşıldığında gerçekleştirilen eylem. |
| class [ContentsResizeParameters](pdffileeditor.contentsresizeparameters) | Sayfa yeniden boyutlandırma parametrelerini belirtmek için sınıf. Aşağıdaki parametreleri ayarlamaya izin verin: Varsayılan alan birimlerinde veya ilk sayfa boyutunun yüzdelerinde sonuç sayfasının boyutu (genişlik, yükseklik); Varsayılan boşluk birimlerinde veya ilk sayfa boyutunun yüzdelerinde Sol, Üst, Alt ve Sağ kenar boşlukları; Otomatik hesaplama için bazı değerler boş bırakılabilir. Bu değerler, açıkça belirtilen değerlerin hesaplanmasından sonra sayfa boyutunun geri kalanından olarak hesaplanacaktır. Örneğin: eğer sayfa genişliği = 100 ve yeni sayfa genişliği 60 birim olarak belirlenmişse, sol ve sağ kenar boşlukları otomatik olarak hesaplanır: (100 - 60) / 2 = 15. Bu sınıf ResizeContents yönteminde kullanılır. |
| class [ContentsResizeValue](pdffileeditor.contentsresizevalue) | Varsayılan alan birimlerinin yüzdeleri olarak belirtilen içerik boyutu veya kenar boşluğu değeri. Bu sınıf, ContentsResizeParameters içinde kullanılır. |
| class [CorruptedItem](pdffileeditor.corrupteditem) | Birleştirme sırasında bozulan dosyalar hakkında bilgi sağlayan sınıf. |
| class [PageBreak](pdffileeditor.pagebreak) | Sayfa sonu konumu verileri. |

### Ayrıca bakınız

* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
