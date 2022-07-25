---
title: PdfPageEditor
second_title: Aspose.PDF for .NET API Referansı
description: Sayfa döndürme sayfayı yakınlaştırma konumu taşıma ve sayfa boyutunu değiştirme dahil olmak üzere PDF dosyasının sayfasını düzenlemek için bir sınıfı temsil eder.
type: docs
weight: 2600
url: /tr/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Sayfa döndürme, sayfayı yakınlaştırma, konumu taşıma ve sayfa boyutunu değiştirme dahil olmak üzere PDF dosyasının sayfasını düzenlemek için bir sınıfı temsil eder.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfPageEditor](pdfpageeditor#constructor)() | PdfPageEditor sınıfı için yapıcı. |
| [PdfPageEditor](pdfpageeditor#constructor_1)(Document) | PdfPageEditor sınıfı için yapıcı. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration) { get; set; } | Sayfalar için görüntüleme süresini alır veya ayarlar. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Üzerinde çalıştığı belge cephesini alır. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment) { get; set; } | Sonuç sayfasındaki orijinal PDF içeriğinin yatay hizalamasını alır veya ayarlar, varsayılan ayar AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations) { get; set; } | Bir karma tablo, sayfa numarasını ve döndürme derecesini içerir, anahtar sayfa numarasını temsil eder, anahtarın değeri derece cinsinden döndürmeyi temsil eder. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize) { get; set; } | Çıktı dosyasının sayfa boyutunu alır veya ayarlar. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages) { get; set; } | Düzenlenecek sayfa numaralarını alır veya ayarlar. Varsayılan olarak, her sayfa düzenlenir. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation) { get; set; } | Sayfaların dönüşünü alır veya ayarlar, dönüş 0, 90, 180 veya 270 olmalıdır. Varsayılan değer 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration) { get; set; } | Geçiş efektinin süresini alır veya ayarlar. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype) { get; set; } | Bir sunum sırasında bu sayfadan başka bir sayfaya geçerken kullanılacak geçiş stilini alır veya ayarlar. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype) { get; set; } | Sonuç sayfasındaki orijinal PDF içeriğinin dikey hizalamasını alır veya ayarlar, varsayılan VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom) { get; set; } | Yakınlaştırma katsayısını alır veya ayarlar. 1.0 değeri %100'e karşılık gelir. Varsayılan değer 1.0.  Aşağıdaki örnek, belge sayfalarının yakınlaştırmasının nasıl değiştirileceğini gösterir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges)() | Belge sayfalarına yapılan değişiklikleri uygulayın. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Cepheyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Cepheyi başlatır. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Aspose.Pdf.Document'ı bir cepheye bağlı olarak imha eder. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Cepheyi ortadan kaldırır. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize)(int, string) | Belgede belirtilen kutunun boyutunu döndürür. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation)(int) | Belirtilen sayfanın dönüşünü döndürür. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages)() | Toplam sayfa sayısını verir. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize)(int) | Belirtilen sayfanın sayfa boyutunu döndürür. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition)(float, float) | Orijini (0, 0) noktasından atanan noktaya taşır. Başlangıç noktası sol alt ve birim noktadır (1 inç = 72 nokta). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save)(Stream) | Değiştirilen belgeyi akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save_1)(string) | Değiştirilen belgeyi dosyaya kaydeder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh) | Dikey Jaluziler |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv) | Dikey Jaluziler |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe) | Alt-Üst Mendil |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter) | diyagonal parıltı |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve) | Eski sayfa çözülür |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox) | İç Kutu |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter) | Sol-Sağ Parıltı |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe) | Sol-Sağ Silme |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox) | Dış Kutu |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe) | Sağ-Sol Silme |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin) | Yatay Bölünmüş |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout) | Dışarıya Yatay Bölme |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin) | Dikey Bölmede |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout) | Dışarı Dikey Bölme |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter) | Üst-Alt Parıltı |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe) | Alt-Üst Silme |

### Ayrıca bakınız

* class [SaveableFacade](../saveablefacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
