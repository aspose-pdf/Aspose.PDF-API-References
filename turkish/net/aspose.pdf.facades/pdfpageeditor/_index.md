---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfPageEditor sınıfı. PDF dosyalarının sayfalarını düzenlemek için bir sınıfı temsil eder; sayfa döndürme, sayfa yakınlaştırma, sayfa konumunu değiştirme ve sayfa boyutunu değiştirme işlemlerini içerir.
type: docs
weight: 4590
url: /tr/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor Sınıfı

PDF dosyasının sayfasını düzenlemek için bir sınıfı temsil eder; sayfa döndürme, sayfa yakınlaştırma, konum değiştirme ve sayfa boyutunu değiştirme işlemlerini içerir.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | PdfPageEditor sınıfı için yapıcı. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | PdfPageEditor sınıfı için yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Sayfalar için görüntüleme süresini alır veya ayarlar. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Üzerinde çalışılan belge yüzeyini alır. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Sonuç sayfasındaki orijinal PDF içeriğinin yatay hizalamasını alır veya ayarlar, varsayılan AlignmentType.Left'tır. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Sayfa numarası ve döndürme derecesini içeren bir hash tablosudur; anahtar sayfa numarasını, anahtarın değeri ise derece cinsinden döndürmeyi temsil eder. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Çıktı dosyasının sayfa boyutunu alır veya ayarlar. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Düzenlenecek sayfa numaralarını alır veya ayarlar. Varsayılan olarak, her sayfa düzenlenecektir. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Sayfaların döndürülmesini alır veya ayarlar; döndürme 0, 90, 180 veya 270 olmalıdır. Varsayılan değer 0'dır. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Geçiş efektinin süresini alır veya ayarlar. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Bir sunum sırasında başka bir sayfadan bu sayfaya geçerken kullanılacak geçiş stilini alır veya ayarlar. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Sonuç sayfasındaki orijinal PDF içeriğinin dikey hizalamasını alır veya ayarlar; varsayılan VerticalAlignmentType.Bottom'dır. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Yakınlaştırma katsayısını alır veya ayarlar. 1.0 değeri %100'e karşılık gelir. Varsayılan değer 1.0'dır. Aşağıdaki örnek, belge sayfalarının yakınlaştırmasını nasıl değiştireceğini gösterir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Belge sayfalarında yapılan değişiklikleri uygular. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Yüzeyi başlatır. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Yüzeyi başlatır. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Bir yüzeye bağlı Aspose.Pdf.Document'ı yok eder. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Yüzeyi yok eder. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Belgedeki belirtilen kutunun boyutunu döndürür. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Belirtilen sayfanın döndürmesini döndürür. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Toplam sayfa sayısını döndürür. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Belirtilen sayfanın sayfa boyutunu döndürür. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Orijini (0, 0) noktasından belirtilen noktaya taşır. Orijin sol-alt köşedir ve birim puandır (1 inç = 72 puan). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Değiştirilen belgeyi akışa kaydeder. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Değiştirilen belgeyi dosyaya kaydeder. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Dikey Panjurlar |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Dikey Panjurlar |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Alt-Üst Silme |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Diyagonal Parıltı |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | Eski sayfa çözülür |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | İçeri Kutusu |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Sol-Sağ Parıltı |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Sol-Sağ Silme |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Dışarı Kutusu |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Sağ-Sol Silme |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | İç Dikey Bölme |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Dış Dikey Bölme |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | İç Dikey Bölme |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Dış Dikey Bölme |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Üst-Aşağı Parıltı |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Üst-Aşağı Silme |

### Ayrıca Bakınız

* sınıf [SaveableFacade](../saveablefacade/)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../)