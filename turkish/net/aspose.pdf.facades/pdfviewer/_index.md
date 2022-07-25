---
title: PdfViewer
second_title: Aspose.PDF for .NET API Referansı
description: Bir pdfyi görüntülemek veya yazdırmak için bir sınıfı temsil eder.
type: docs
weight: 2640
url: /tr/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

Bir pdf'yi görüntülemek veya yazdırmak için bir sınıfı temsil eder.

```csharp
public sealed class PdfViewer : IFacade
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PdfViewer](pdfviewer#constructor)() | Yeniyi başlatır[`PdfViewer`](../pdfviewer) nesne. |
| [PdfViewer](pdfviewer#constructor_1)(Document) | Yeniyi başlatır[`PdfViewer`](../pdfviewer) nesne. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize) { get; set; } | Dosyanın optimize edilmiş boyutta yazdırılıp yazdırılmayacağını belirten bir bool değeri alır veya ayarlar.  Sayfa ölçekleme olmadan sayfa yanlış yazdırılıyorsa. Sayfa doğruysa yazdırılabilir alana sığacak şekilde ölçeklendirilerek yazdırılır. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate) { get; set; } | Dosyanın otomatik döndürme ile yazdırılıp yazdırılmayacağını belirten bir bool değeri alır veya ayarlar |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode) { get; set; } | Dönme yönünü belirten bir AutoRotateMode değeri alır veya ayarlar |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype) { get; set; } | Sayfa koordinat türünü alır veya ayarlar (Medya/Kırpma kutuları). CropBox değeri varsayılan olarak kullanılır. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode) { get; set; } | Form sunum modunu alır veya ayarlar. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment) { get; set; } | Yatay hizalamayı gösteren bir değer alır veya ayarlar |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount) { get; } | Geçerli Pdf dosyasının sayfa sayısını alır. |
| [Password](../../aspose.pdf.facades/pdfviewer/password) { get; set; } | Giriş belgesi parolasını alır veya ayarlar. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale) { get; set; } | Sayfanın gri tonlamalı olarak yazdırılıp yazdırılmadığını gösteren bir bool değeri alır veya ayarlar. Varsayılan olarak false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage) { get; set; } | PdfViewer'ın resim olarak yazdırması için bir mod ayarlar veya alır. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname) { get; set; } | Belge yazdırıldığında yazıcı kuyruğundaki belgenin adını alır veya ayarlar. Varsayılan değer dosya adıdır. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog) { get; set; } | Yazdırma sırasında sayfa numarası iletişim kutusunun oluşturulup oluşturulmayacağını belirten bir bool değeri alır veya ayarlar. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus) { get; } | Yazdırma işinin sonucunu alır. null'dan daha başarılı ise; aksi takdirde, istisna nesnesi. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions) { get; set; } | Oluşturma seçeneklerini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution) { get; set; } | Görüntüleme ve yazdırma sırasında çözünürlüğü alır veya ayarlar. Daha yüksek çözünürlük, daha yavaş hız. Varsayılan değer 150. 'dir |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor) { get; set; } | Ölçek faktörünü gösteren bir kayan nokta değeri alır veya ayarlar. Varsayılan değer 1.0. 'dir |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage) { get; set; } | Dosya modunda yazdırma sırasında pdf sayfasının ara png dosyasına dönüştürülmesinin kullanımını alır/ayarlar. Çıktı dosyasının boyutu önemli olduğunda kullanın. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment) { get; set; } | Dikey hizalamayı gösteren bir değer alır veya ayarlar |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf)(Document) | Cepheyi başlatır. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_1)(Stream) | Cepheyi başlatır. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_2)(string) | Cepheyi başlatır. |
| [Close](../../aspose.pdf.facades/pdfviewer/close)() | Cepheyi kapatır. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages)() | Geçerli pdf dosyasının sayfalarını alın. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage)(int) | Bir Pdf dosyasının bir sayfasının kodunu çözer. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose)() | Cephe kaynaklarını atar. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings)() | Varsayılan sayfa ayarlarını alır. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings)() | Varsayılan yazıcı ayarlarını alır. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument)() | Varsayılan yazıcıyı kullanarak Pdf belgesini yazdırır. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings_1)(PrinterSettings) | Pdf belgesini yazıcı ayarlarıyla yazdırır. Çıktı sayfa boyutu, belgenin ilk sayfa boyutuna sığacaktır. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings)(PageSettings, PrinterSettings) | Pdf belgesini ayarlarla yazdırır. Belge boyutu sayfa boyutuyla uyumlu değilse, pdf.kit onu sayfa boyutuna sığacak şekilde genişletir. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup)() | Pdf belgesini bir kurulum iletişim kutusuyla yazdırır. İletişim kutusunu kullanarak bir yazıcı seçin. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf)(Stream) | Büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den ise, daha iyi performans elde etmek için bu yöntem önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_3)(string) | Büyük bir Pdf dosyası açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den ise, daha iyi performans elde etmek için bu yöntem önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_2)(Stream, PrinterSettings) | Belirtilen yazıcı ayarlarıyla büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_5)(string, PrinterSettings) | Belirtilen yazıcı ayarlarıyla büyük bir Pdf dosyası açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Belirtilen sayfa ayarları ve yazıcı ayarları ile büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_4)(string, PageSettings, PrinterSettings) | Belirtilen sayfa ayarları ve yazıcı ayarları ile büyük bir Pdf dosyası açar ve yazdırır. Pdf dosyanız yüzlerce veya daha fazla sayfa içeriyorsa veya boyutu 3 MB'den büyükse, daha iyi performans elde etmek için bu yöntem önerilir. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save)(Stream) | Sonuç PDF belgesini akışa kaydeder. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save_1)(string) | Sonuç PDF belgesini dosyaya kaydeder. |

### Ayrıca bakınız

* interface [IFacade](../ifacade)
* ad alanı [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
