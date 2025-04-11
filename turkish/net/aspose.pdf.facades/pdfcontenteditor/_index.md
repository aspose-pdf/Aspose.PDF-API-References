---
title: Class PdfContentEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfContentEditor sınıfı. PDF dosyalarının içeriğini düzenlemek için bir sınıfı temsil eder.
type: docs
weight: 4430
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor sınıfı

PDF dosyasının içeriğini düzenlemek için bir sınıfı temsil eder.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor/#constructor)() | PdfContentEditor nesnesinin yapıcısı. |
| [PdfContentEditor](pdfcontenteditor/#constructor_1)(Document) | *document* temelinde yeni bir `PdfContentEditor` nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy/) { get; set; } | Metin değiştirme işlemi için bir dizi parametre |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions/) { get; set; } | Metin düzenleme seçeneklerini alır veya ayarlar. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions/) { get; set; } | Metin değiştirme seçeneklerini alır veya ayarlar. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions/) { get; set; } | Metin arama seçeneklerini alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/)(string, string) | Belge olayı için ek eylem ekler. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment_1)(string, string) | Notasyon olmadan belge eki ekler. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment)(Stream, string, string) | Notasyon olmadan belge eki ekler. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_1)(Stream) | Düzenleme için bir PDF akışını bağlar. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_2)(string) | Düzenleme için bir PDF dosyasını bağlar. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/)(int) | Görünüm tercihlerini değiştirir. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close/)() | Açık belgeyi kapatır. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink)(Rectangle, string, int) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_1)(Rectangle, string, int, Color) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/)(string, Color, bool, bool, string, string, string) | Belirtilen eylemle bir yer imi oluşturur. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret/)(int, Rectangle, Rectangle, string, string, Color) | İmleç notasyonu oluşturur. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/)(Rectangle, int, Color, Enum[]) | PDF belgesinde özel eylemler için bir bağlantı oluşturur. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_2)(Rectangle, string, string, int, string) | Dosya eki notasyonu oluşturur. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment)(Rectangle, string, Stream, string, int, string) | Dosya eki notasyonu oluşturur. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_3)(Rectangle, string, string, int, string, double) | Dosya eki notasyonu oluşturur. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Dosya eki notasyonu oluşturur. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext/)(Rectangle, string, int) | PDF belgesinde serbest metin notasyonu oluşturur. |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/)(string, Rectangle, int, Color) | PDF belgesinde JavaScript için bir bağlantı oluşturur. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline/)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Çizgi notasyonu oluşturur. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink)(Rectangle, int, int) | PDF belgesinde yerel bir bağlantı oluşturur. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_1)(Rectangle, int, int, Color) | PDF belgesinde yerel bir bağlantı oluşturur. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | PDF belgesinde yerel bir bağlantı oluşturur. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup/)(Rectangle, string, int, int, Color) | PDF belgesinde işaretleme notasyonu oluşturur. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie/)(Rectangle, string, int) | Film Notasyonları oluşturur. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink)(Rectangle, string, int, int) | Başka bir PDF belgesi sayfasına bağlantı oluşturur. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Başka bir PDF belgesi sayfasına bağlantı oluşturur. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Başka bir PDF belgesi sayfasına bağlantı oluşturur. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon/)(LineInfo, int, Rectangle, string) | Çokgen notasyonu oluşturur. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline/)(LineInfo, int, Rectangle, string) | Poligon notasyonu oluşturur. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup/)(Rectangle, string, bool, int) | PDF belgesinde açılır notasyon oluşturur. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp)(int, Rectangle, string, Color, Stream) | Kauçuk damga notasyonu oluşturur. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_1)(int, Rectangle, string, Color, string) | Kauçuk damga notasyonu oluşturur. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_2)(int, Rectangle, string, string, Color) | Kauçuk damga notasyonu oluşturur. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound/)(Rectangle, string, string, int, string) | Ses Notasyonları oluşturur. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle/)(Rectangle, string, Color, bool, int, int) | Kare-daire notasyonu oluşturur. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext/)(Rectangle, string, string, bool, string, int) | PDF belgesinde metin notasyonu oluşturur. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink)(Rectangle, string, int) | PDF belgesinde bir web bağlantısı oluşturur. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_1)(Rectangle, string, int, Color) | PDF belgesinde bir web bağlantısı oluşturur. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_2)(Rectangle, string, int, Color, Enum[]) | PDF belgesinde bir web bağlantısı oluşturur. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments/)() | PDF belgesindeki tüm ekleri siler. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage)() | PDF belgesinden tüm resimleri siler. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage_1)(int, int[]) | Belirtilen sayfadaki belirtilen resimleri siler. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp/)(int, int[]) | Belirtilen sayfadaki birden fazla damgayı damga indekslerine göre siler. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid)(int) | Belgedeki tüm sayfalardan ID ile damgayı siler. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid_1)(int, int) | Belirtilen sayfadaki damgayı damga ID'sine göre siler. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids_1)(int[]) | Belgedeki tüm sayfalardan belirtilen ID'lere sahip damgaları siler. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids)(int, int[]) | Belirtilen sayfadaki birden fazla damga ID'sine göre damgaları siler. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve/)(LineInfo, int, Rectangle, string) | Eğri notasyonu oluşturur. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink/)() | PDF belgesinde bulunan Bağlantı örneklerinin koleksiyonunu çıkarır. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps/)(int) | Sayfadaki damgaların dizisini döndürür. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference/)() | Görünüm tercihlerini döndürür. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid/)(int, int) | Damgayı gizler. Gizledikten sonra, damga görünürlüğü ShowStampById yöntemi ile geri yüklenebilir. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp/)(int, int, double, double) | Sayfadaki damganın konumunu değiştirir. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid/)(int, int, double, double) | Sayfadaki damganın konumunu değiştirir. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/)() | Belgeden açılış eylemini kaldırır. Bu işlem, başlangıçta açıkça 'GoTo' eylemi kullanan birden fazla belgeyi birleştirirken faydalıdır. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage/)(int, int, string) | Belirtilen sayfadaki belirtilen resmi başka bir resimle değiştirir. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_2)(string, string) | PDF dosyasındaki metni değiştirir. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext)(string, int, string) | Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_4)(string, string, int) | PDF dosyasındaki metni değiştirir ve yazı tipi boyutunu ayarlar. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_3)(string, string, TextState) | Belirtilen [`TextState`](../../aspose.pdf.text/textstate/) nesnesini kullanarak PDF dosyasındaki metni değiştirir. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_1)(string, int, string, TextState) | Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. Değiştirilen metin için [`TextState`](../../aspose.pdf.text/textstate/) nesnesi (yazı tipi ailesi, renk) belirtilebilir. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid/)(int, int) | HiddenStampById ile gizlenen damgayı gösterir. |

## Alanlar

| İsim | Açıklama |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose/) | Bir belge olayı türü. Bir belgeyi kapatır. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen/) | Bir belge olayı türü. Bir belgeyi açar. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted/) | Bir belge olayı türü. Yazdırmadan sonra bir eylemi gerçekleştirir. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved/) | Bir belge olayı türü. Kaydettikten sonra bir eylemi gerçekleştirir. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint/) | Bir belge olayı türü. Yazdırmadan önce bir eylemi gerçekleştirir. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave/) | Bir belge olayı türü. Kaydetmeden önce bir eylemi gerçekleştirir. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)