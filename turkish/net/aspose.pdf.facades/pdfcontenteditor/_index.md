---
title: PdfContentEditor
second_title: Aspose.PDF for .NET API Referansı
description: PDF dosyasının içeriğini düzenlemek için bir sınıfı temsil eder.
type: docs
weight: 2440
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

PDF dosyasının içeriğini düzenlemek için bir sınıfı temsil eder.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor#constructor)() | PdfContentEditor nesnesinin yapıcısı. |
| [PdfContentEditor](pdfcontenteditor#constructor_1)(Document) | Yeniyi başlatır[`PdfContentEditor`](../pdfcontenteditor) temelinde nesne*document* . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy) { get; set; } | Metin değiştirme işlemi için bir dizi parametre |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions) { get; set; } | Metin düzenleme seçeneklerini alır veya ayarlar. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions) { get; set; } | Metin değiştirme seçeneklerini alır veya ayarlar. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions) { get; set; } | Metin arama seçeneklerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction)(string, string) | Belge olayı için ek eylem ekler. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment_1)(string, string) | Ek açıklama olmadan belge eki ekler. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment)(Stream, string, string) | Ek açıklama olmadan belge eki ekler. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_1)(Stream) | Düzenleme için bir PDF akışını bağlar. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_2)(string) | Düzenleme için bir PDF dosyasını bağlar. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference)(int) | Görünüm tercihini değiştirir. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close)() | Açılan belgeyi kapatır. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink)(Rectangle, string, int) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_1)(Rectangle, string, int, Color) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction)(string, Color, bool, bool, string, string, string) | Belirtilen eylemle bir yer imi oluşturur. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret)(int, Rectangle, Rectangle, string, string, Color) | Düzeltme ek açıklaması oluşturur. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink)(Rectangle, int, Color, Enum[]) | PDF belgesinde özel eylemlere bağlantı oluşturur. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_2)(Rectangle, string, string, int, string) | Dosya eki açıklamasını oluşturur. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment)(Rectangle, string, Stream, string, int, string) | Dosya eki açıklamasını oluşturur. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_3)(Rectangle, string, string, int, string, double) | Dosya eki açıklamasını oluşturur. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Dosya eki açıklamasını oluşturur. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext)(Rectangle, string, int) | PDF belgesinde serbest metin açıklaması oluşturur |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink)(string, Rectangle, int, Color) | PDF belgesinde JavaScript'e bir bağlantı oluşturur. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Satır açıklaması oluşturur. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink)(Rectangle, int, int) | PDF belgesinde yerel bir bağlantı oluşturur. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_1)(Rectangle, int, int, Color) | PDF belgesinde yerel bir bağlantı oluşturur. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | PDF belgesinde yerel bir bağlantı oluşturur. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup)(Rectangle, string, int, int, Color) | PDF belgesinde işaretleme ek açıklaması oluşturur. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie)(Rectangle, string, int) | Film Açıklamaları Oluşturur. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink)(Rectangle, string, int, int) | Başka bir PDF belge sayfasına bağlantı oluşturur. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Başka bir PDF belge sayfasına bağlantı oluşturur. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Başka bir PDF belge sayfasına bağlantı oluşturur. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon)(LineInfo, int, Rectangle, string) | Çokgen ek açıklaması oluşturur. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline)(LineInfo, int, Rectangle, string) | Çoklu çizgi ek açıklaması oluşturur. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup)(Rectangle, string, bool, int) | PDF belgesinde açılır açıklama oluşturur. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp)(int, Rectangle, string, Color, Stream) | Bir lastik damga ek açıklaması oluşturur. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_1)(int, Rectangle, string, Color, string) | Bir lastik damga ek açıklaması oluşturur. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_2)(int, Rectangle, string, string, Color) | Bir lastik damga ek açıklaması oluşturur. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound)(Rectangle, string, string, int, string) | Ses Açıklamaları Oluşturur. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle)(Rectangle, string, Color, bool, int, int) | Kare daire ek açıklaması oluşturur. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext)(Rectangle, string, string, bool, string, int) | PDF belgesinde metin açıklaması oluşturur |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink)(Rectangle, string, int) | PDF belgesinde bir web bağlantısı oluşturur. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_1)(Rectangle, string, int, Color) | PDF belgesinde bir web bağlantısı oluşturur. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_2)(Rectangle, string, int, Color, Enum[]) | PDF belgesinde bir web bağlantısı oluşturur. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments)() | PDF belgesindeki tüm ekleri siler. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage)() | PDF belgesindeki tüm görüntüleri siler. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage_1)(int, int[]) | Belirtilen sayfada belirtilen resimleri siler. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp)(int, int[]) | Belirtilen sayfadaki birden çok damgayı damga dizinleriyle siler. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid)(int) | Belgenin tüm sayfalarından kimliğe göre damgayı silin. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid_1)(int, int) | Belirtilen sayfadaki damgayı damga kimliğine göre siler. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids_1)(int[]) | Belgenin tüm sayfalarından belirtilen kimliklere sahip damgaları siler. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids)(int, int[]) | Birden çok damga kimliğiyle belirtilen sayfadaki damgaları siler. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve)(LineInfo, int, Rectangle, string) | Eğri ek açıklaması oluşturur. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink)() | PDF belgesinde bulunan Link örnekleri koleksiyonunu çıkarır. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps)(int) | Sayfadaki damga dizisini döndürür. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference)() | Görünüm tercihini döndürür. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid)(int, int) | Damgayı gizler. Gizlendikten sonra, damga görünürlüğü ShowStampById yöntemiyle geri yüklenebilir. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp)(int, int, double, double) | Sayfadaki damganın konumunu değiştirir. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid)(int, int, double, double) | Sayfadaki damganın konumunu değiştirir. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction)() | Belgeden açık eylemi kaldırır. Bu işlem, başlangıçta açık 'Git' eylemi kullanan birden çok belgeyi birleştirirken kullanışlıdır. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage)(int, int, string) | PDF belgesinin belirtilen sayfasında belirtilen resmi başka bir resimle değiştirir. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_2)(string, string) | PDF dosyasındaki metni değiştirir. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext)(string, int, string) | Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_4)(string, string, int) | PDF dosyasındaki metni değiştirir ve yazı tipi boyutunu ayarlar. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_3)(string, string, TextState) | Belirtilen kullanarak PDF dosyasındaki metni değiştirir[`TextState`](../../aspose.pdf.text/textstate) nesne. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_1)(string, int, string, TextState) | Belirtilen sayfadaki PDF dosyasındaki metni değiştirir.[`TextState`](../../aspose.pdf.text/textstate) nesne (yazı tipi ailesi, renk) değiştirilecek metin olarak belirtilebilir. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid)(int, int) | HiddenStampById. tarafından gizlenen damgayı gösterir |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose) | Bir belge olay türü. Bir belgeyi kapatır. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen) | Bir belge olay türü. Bir belge açar. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted) | Bir belge olay türü. Yazdırdıktan sonra bir eylemi yürütün. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved) | Bir belge olay türü. Kaydettikten sonra bir eylemi yürütün. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint) | Bir belge olay türü. Yazdırmadan önce bir eylemi yürütün. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave) | Bir belge olay türü. Kaydetmeden önce bir eylemi yürütün. |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
