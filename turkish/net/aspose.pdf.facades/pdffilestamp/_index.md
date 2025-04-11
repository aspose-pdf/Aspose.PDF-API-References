---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileStamp sınıfı. PDF dosyalarına damgalar, filigran veya arka plan eklemek için sınıf
type: docs
weight: 4570
url: /tr/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp Sınıfı

PDF dosyalarına damgalar (filigran veya arka plan) eklemek için sınıf.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | PdfFileStamp'in yapıcısı. Giriş dosyası ve çıkış dosyası ilgili özellikler aracılığıyla belirtilebilir. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | *belge* temelinde yeni bir `PdfFileStamp` nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | PDF dosya formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse dosya varsayılan PDF formatında dönüştürülmeden kaydedilecektir. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Eğer true ise güvenliği korur. (Bu özellik sonraki sürümlerde uygulanacaktır). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Sayfa numaralandırma stilini alır veya ayarlar. Olası değerler: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Optimizasyon bayrağını alır veya ayarlar. Sonuç dosyasındaki eşit kaynak akışları bir PDF nesnesinde birleştirilir, bu bayrak ayarlandığında. Bu, sonuç dosyasının boyutunu azaltmaya olanak tanır ancak daha yavaş yürütme ve daha büyük bellek gereksinimlerine neden olabilir. Varsayılan değer: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Kaynak dosyadaki ilk sayfanın yüksekliğini alır. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Sayfa numarasının döndürülmesini alır veya ayarlar. Dönme dereceler cinsindendir. Varsayılan 0'dır. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Giriş dosyasındaki ilk sayfanın genişliğini alır. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | Eklenen sonraki damganın ID'si (sayfa başlıkları/alt başlıklar/sayfa numaraları dahil). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Giriş dosyasındaki ilk sayfa için başlangıç numarasını alır veya ayarlar. Sonraki sayfalar bu değerden başlayarak numaralandırılacaktır. Örneğin, StartingNumber 100 olarak ayarlanırsa, belge sayfaları 100, 101, 102... numaralarına sahip olacaktır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Belgenin sayfalarına alt bilgi ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Sayfanın alt bilgisi olarak bir resim ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Belgenin sayfalarına alt bilgi olarak bir resim ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Belgenin sayfalarına alt bilgi ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Sayfanın alt bilgisi olarak bir resim ekler. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Sayfaların alt bilgisi olarak bir resim ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Sayfaya üst bilgi ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Sayfaların üstünde bir resim ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Dosyanın sayfalarına üst bilgi olarak bir resim ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Dosyanın sayfalarına üst bilgi ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Sayfanın üst kısmına bir resim ekler. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Sayfalara üst bilgi olarak bir resim ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Sayfaya sayfa numarası ekler. Sayfa numarası # işareti içerebilir, bu işaret sayfa numarası ile değiştirilir. Sayfa numarası sayfanın altında yatay olarak ortalanmış olarak yer alır. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Dosyaya sayfa numarası ekler. Sayfa numarası metni # işareti içerebilir, bu işaret sayfanın numarası ile değiştirilir. Sayfa numarası sayfanın altında yatay olarak ortalanmış olarak yer alır. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Sayfalara sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Sayfalara sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Belirtilen konumda sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Belirtilen konumda sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Belgenin sayfalarına sayfa numarası ekler. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Belgenin sayfalarına sayfa numarası ekler. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Dosyaya damga ekler. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Yüzeyi başlatır. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Açık dosyaları kapatır ve değişiklikleri kaydeder. Uyarı. Giriş veya çıkış akışları belirtilmişse, Close() yöntemi ile kapatılmazlar. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Belgeyi belirtilen akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Sonucu belirtilen dosyaya kaydeder. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Alt sol konum. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Alt orta konum. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Alt sağ konum. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Sol konum. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Sağ konum. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Üst sol konum. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Üst orta konum. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Üst sağ konum. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)