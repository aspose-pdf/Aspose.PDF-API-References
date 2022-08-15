---
title: PdfFileStamp
second_title: Aspose.PDF for .NET API Referansı
description: PDF dosyalarına damga filigran veya arka plan ekleme sınıfı.
type: docs
weight: 2580
url: /tr/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

PDF dosyalarına damga (filigran veya arka plan) ekleme sınıfı.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfFileStamp](pdffilestamp#constructor)() | PdfFileStamp. Oluşturucusu Girdi dosyası ve çıktı dosyası karşılık gelen özellikler aracılığıyla belirtilebilir. |
| [PdfFileStamp](pdffilestamp#constructor_1)(Document) | Yeniyi başlatır[`PdfFileStamp`](../pdffilestamp) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname) { get; set; } | İşlem sonucu ek olarak HttpResponse nesnelerinde depolandığında ekin adını alır veya ayarlar. |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition) { get; set; } | İşlem sonucu HttpResponse nesnesine depolandığında içeriğin nasıl depolanacağını alır veya ayarlar. Olası değer: satır içi / ek. Varsayılan: satır içi. |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto) { set; } | PDF dosya biçimini ayarlar. Sonuç dosyası, belirtilen dosya biçiminde kaydedilecektir. Bu özellik belirtilmezse, dosya dönüştürme yapılmadan varsayılan PDF formatında kaydedilecektir. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity) { get; set; } | Doğruysa güvenliği korur. (Bu özellik sonraki sürümlerde uygulanacaktır). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle) { get; set; } | Sayfa numaralandırma stilini alır veya ayarlar. Olası değerler: RakamlarArapça, RakamlarRomanBüyük Harf, RakamlarRomanKüçük Harf, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize) { get; set; } | Optimizasyon bayrağını alır veya ayarlar. Bu işaret ayarlanırsa, sonuçtaki dosyadaki eşit kaynak akışları tek bir PDF nesnesinde birleştirilir. Bu, sonuçta ortaya çıkan dosya boyutunu küçültmeye izin verir ancak daha yavaş yürütmeye ve daha büyük bellek gereksinimlerine neden olabilir. Varsayılan değer: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight) { get; } | Kaynak dosyasındaki ilk sayfanın yüksekliğini alır. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation) { get; set; } | Sayfa numarasının dönüşünü alır veya ayarlar. Döndürme derece cinsindendir. Varsayılan 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth) { get; } | Giriş dosyasındaki ilk sayfanın genişliğini alır. |
| [Response](../../aspose.pdf.facades/pdffilestamp/response) { get; set; } | İşlem sonucunun depolanacağı Response nesnesini alır veya ayarlar. |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions) { get; set; } | Sonuç HttpResponse. olarak depolandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid) { get; set; } | Bir sonraki eklenen damganın damga kimliği (sayfa üstbilgileri/önleyiciler/sayfa numaraları dahil). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber) { get; set; } | Girdi dosyasındaki ilk sayfanın başlangıç numarasını alır veya ayarlar. Sonraki sayfalar bu değerden başlayarak numaralandırılacaktır. Örneğin, Başlangıç Sayısı 100 olarak ayarlanmışsa, belge sayfalarında 100, 101, 102... numaraları olacaktır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter)(FormattedText, float) | Belgenin sayfalarına altbilgi ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_2)(Stream, float) | Sayfanın altbilgisi olarak resim ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_4)(string, float) | Belgenin sayfalarına alt bilgi olarak resim ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_1)(FormattedText, float, float, float) | Belgenin sayfalarına altbilgi ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_3)(Stream, float, float, float) | Sayfanın altbilgisi olarak resim ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_5)(string, float, float, float) | Sayfaların altbilgisi olarak resim ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader)(FormattedText, float) | Sayfaya başlık ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_2)(Stream, float) | Sayfalara üst bilgi olarak resim ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_4)(string, float) | Dosyanın sayfalarına başlık olarak resim ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_1)(FormattedText, float, float, float) | Dosyanın sayfalarına başlık ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_3)(Stream, float, float, float) | Sayfanın en üstüne resim ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_5)(string, float, float, float) | Sayfalara üst bilgi olarak resim ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber)(FormattedText) | Sayfaya sayfa numarası ekler. Sayfa numarası, sayfa numarası ile değiştirilecek # işareti içerebilir. Sayfa numarası, sayfanın altına yatay olarak ortalanır. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_4)(string) | Dosyaya sayfa numarası ekleyin. Sayfa numarası metni, sayfa numarası ile değiştirilecek olan # işareti içerebilir. Sayfa numarası, sayfanın alt kısmına yatay olarak ortalanır. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_1)(FormattedText, int) | Sayfalara sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_5)(string, int) | Sayfalara sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_3)(FormattedText, float, float) | Sayfada belirtilen konuma sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_7)(string, float, float) | Sayfada belirtilen konuma sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_2)(FormattedText, int, float, float, float, float) | Belgenin sayfalarına sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_6)(string, int, float, float, float, float) | Belgenin sayfalarına sayfa numarası ekler. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp)(Stamp) | Dosyaya damga ekler. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Cepheyi başlatır. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close)() | Açılan dosyaları kapatır ve değişiklikleri kaydeder. Uyarı. Giriş veya çıkış akışları belirtilirse, Close() yöntemiyle kapatılmazlar. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save)(Stream) | Belgeyi belirtilen akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save_1)(string) | Sonucu belirtilen dosyaya kaydeder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft) | Sol alt konum. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle) | Alt orta konum. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright) | Sağ alt konum. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft) | Sol konum. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright) | Sağ konum. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft) | Üst izin konumu. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle) | Üst orta konum. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright) | Sağ üst konum. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
