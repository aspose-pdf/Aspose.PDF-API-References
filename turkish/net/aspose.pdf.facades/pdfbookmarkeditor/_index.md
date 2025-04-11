---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfBookmarkEditor sınıfı. PDF dosyalarının yer imleri ile çalışmak için bir sınıfı temsil eder; oluşturma, değiştirme, dışa aktarma, içe aktarma ve silme işlemlerini içerir.
type: docs
weight: 4420
url: /tr/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor Sınıfı

PDF dosyasının yer imleri ile çalışmak için bir sınıfı temsil eder; oluşturma, değiştirme, dışa aktarma, içe aktarma ve silme işlemlerini içerir.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | Yeni bir `PdfBookmarkEditor` nesnesi başlatır. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | *document* temelinde yeni bir `PdfBookmarkEditor` nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Yüzeyi başlatır. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Bir yüzeye bağlı Aspose.Pdf.Document nesnesini yok eder. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | Belirtilen sayfa için yer imi oluşturur. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | Belirtilen sayfalar için yer imleri oluşturur. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | Tüm sayfalar için yer imleri oluşturur. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | Belgedeki belirtilen yer imini oluşturur. Bu yöntem, iç içe yer imleri hiyerarşisi oluşturmak için kullanılabilir. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | Belirtilen renk ve stil (kalın, italik) ile tüm sayfalar için yer imleri oluşturur. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | PDF belgesinin tüm yer imlerini siler. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | PDF belgesinin yer imini siler. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | Yer imlerini XML akışına dışa aktarır. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | Yer imlerini XML dosyasına dışa aktarır. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | Belgedeki tüm seviyelerden yer imlerini çıkarır. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | Belirtilen yer imindeki başlık gibi bir başlığa sahip yer iminin çocuklarını çıkarır. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | Belgedeki tüm seviyelerden yer imlerini çıkarır. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | Belirtilen başlığa sahip yer imlerini çıkarır. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | XML dosyasından belgeye yer imleri içe aktarır. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | XML dosyasından belgeye yer imleri içe aktarır. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | Belirtilen yer imi başlığına göre yer imi başlığını değiştirir. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF belgesini belirtilen akışa kaydeder. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF belgesini belirtilen dosyaya kaydeder. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | Yer imlerini HTML dosyasına dışa aktarır. |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)