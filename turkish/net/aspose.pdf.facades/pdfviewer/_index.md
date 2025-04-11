---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfViewer sınıfı. Bir pdf'yi görüntülemek veya yazdırmak için bir sınıfı temsil eder
type: docs
weight: 4630
url: /tr/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer Sınıfı

Bir pdf'yi görüntülemek veya yazdırmak için bir sınıfı temsil eder.

```csharp
public sealed class PdfViewer : IFacade
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Yeni bir `PdfViewer` nesnesi başlatır. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Yeni bir `PdfViewer` nesnesi başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Dosyanın optimize edilmiş boyutla yazdırılıp yazdırılmayacağını belirten bir bool değeri alır veya ayarlar. Eğer false ise sayfa ölçeklendirmeden yazdırılır. Eğer true ise yazdırılacak alana sığacak şekilde ölçeklendirilerek yazdırılır. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Dosyanın otomatik döndürme ile yazdırılıp yazdırılmayacağını belirten bir bool değeri alır veya ayarlar. |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Dönüş yönünü belirten bir AutoRotateMode değeri alır veya ayarlar. |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Sayfa koordinat türünü alır veya ayarlar (Medya/Kırpma kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Form sunum modunu alır veya ayarlar. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Yatay hizalamayı belirten bir değeri alır veya ayarlar. |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Mevcut Pdf dosyasının sayfa sayısını alır. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Giriş belgesi şifresini alır veya ayarlar. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Sayfanın gri tonlamada yazdırılıp yazdırılmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan olarak false'dur. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | PdfViewer'ın görüntü olarak yazdırma modunu ayarlar veya alır. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Belge yazdırıldığında yazıcı kuyruğundaki belgenin adını alır veya ayarlar. Varsayılan değer dosya adıdır. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Yazdırma sırasında sayfa numarası diyaloğunun üretilip üretilmeyeceğini belirten bir bool değeri alır veya ayarlar. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Yazdırma işinin sonucunu alır. Başarılıysa null; aksi takdirde, istisna nesnesi. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | İşleme seçeneklerini alır veya ayarlar. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Görüntüleme ve yazdırma sırasında çözünürlüğü alır veya ayarlar. Daha yüksek çözünürlük, daha yavaş hız demektir. Varsayılan değer 150'dir. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Ölçek faktörünü belirten bir kayan nokta değerini alır veya ayarlar. Varsayılan değer 1.0'dır. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Yazdırma sırasında pdf sayfasının ara png dosyasına dönüştürülüp dönüştürülmeyeceğini alır veya ayarlar. Çıktı dosyasının boyutu önemli olduğunda kullanın. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Dikey hizalamayı belirten bir değeri alır veya ayarlar. |

## Metodlar

| İsim | Açıklama |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Fasadı başlatır. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Fasadı başlatır. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Fasadı başlatır. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Fasadı kapatır. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Mevcut pdf dosyasının sayfalarını alır. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Bir Pdf dosyasının bir sayfasını çözümler. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Fasad kaynaklarını serbest bırakır. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Varsayılan sayfa ayarlarını alır. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Varsayılan yazıcı ayarlarını alır. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Varsayılan yazıcıyı kullanarak Pdf belgesini yazdırır. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Yazıcı ayarları ile Pdf belgesini yazdırır. Çıktı sayfa boyutu, belgenin ilk sayfa boyutuna uyacak şekilde ayarlanacaktır. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Ayarlarla Pdf belgesini yazdırır. Belge boyutu sayfa boyutuna uymuyorsa, sayfa boyutuna uyacak şekilde uzatılacaktır. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Bir ayar diyaloğu ile Pdf belgesini yazdırır. Diyalogdan bir yazıcı seçin. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasını içeriyorsa veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasını içeriyorsa veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Belirtilen yazıcı ayarları ile büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasını içeriyorsa veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Belirtilen yazıcı ayarları ile büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasını içeriyorsa veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Belirtilen sayfa ayarları ve yazıcı ayarları ile büyük bir Pdf akışını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasını içeriyorsa veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Belirtilen sayfa ayarları ve yazıcı ayarları ile büyük bir Pdf dosyasını açar ve yazdırır. Pdf dosyanız yüzlerce sayfa veya daha fazlasını içeriyorsa veya boyutu 3 MB'dan fazlaysa, bu yöntem daha iyi performans almak için önerilir. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Sonuç PDF belgesini akışa kaydeder. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Sonuç PDF belgesini dosyaya kaydeder. |

## Olaylar

| İsim | Açıklama |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Yazdırma başlamadan önce meydana gelir ve varsayılan yerine özel yazdırma işleyicileri sağlamaya olanak tanır. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | PdfViewer'da bir sayfanın yazdırılması sona erdiğinde meydana gelir. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Son sayfa yazdırma olayına abonelik ekler/kaldırır. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Son sayfa yazdırma olayına abonelik ekler/kaldırır. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Bir sayfanın yazdırılmaya başlamasından önce meydana gelir. |

### Ayrıca Bakınız

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)