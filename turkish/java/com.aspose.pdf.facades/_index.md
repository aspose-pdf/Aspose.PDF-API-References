---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu com.aspose.pdf.facades paketi, orijinal olarak Aspose.Pdf.Kit'ten gelen sınıflar sağlar."
type: docs
weight: 180
url: /tr/java/com.aspose.pdf.facades/
---
Bu com.aspose.pdf.facades paketi, orijinal olarak Aspose.Pdf.Kit'ten gelen sınıflar sağlar.

## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [IFacade](./ifacade/) | Ortak facade yöntemlerini tanımlayan genel bir facade arabirimi. |
| [IForm](./iform/) | Acro form nesnesini temsil eden sınıf. |
| [IFormEditor](./iformeditor/) | Formları düzenlemek için sınıf (alan ekleme/silme vb.) |
| [IPdfFileEditor](./ipdffileeditor/) | PDF dosyasıyla işlemleri uygular: birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb. |
| [IPdfFileStamp](./ipdffilestamp/) | PDF dosyalarına damga (filigran veya arka plan) eklemek için arabirim. |
| [ISaveableFacade](./isaveablefacade/) | Tüm kaydedilebilir facade'ler için ortak yöntemleri tanımlayan facade arabirimi. |
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [AlignmentType](./alignmenttype/) | Sınıf olası hizalama türlerini içerir. Bunun yerine HorizontalAlignment kullanın. |
| [AutoRotateMode](./autorotatemode/) | Belge yazdırıldığında dönüş yönü. |
| [BDCProperties](./bdcproperties/) | BDC operatör özellikleri. |
| [Bookmark](./bookmark/) | Yer işaretini temsil eder. |
| [Bookmarks](./bookmarks/) | {@code Bookmark} nesnelerinin bir koleksiyonunu temsil eder. |
| [CgmPdfProducer](./cgmpdfproducer/) | Computer Graphics Metafile (CGM) formatından PDF üretmek için bir sınıfı temsil eder. |
| [DataType](./datatype/) | Alan türü tanımlarını listeler. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Standart XMP özelliklerinin listesi. |
| [DocumentPrivilege](./documentprivilege/) | Pdf dosyasına erişim ayrıcalıklarını temsil eder. {@code PdfFileSecurity}'e bakınız. Bu sınıfı kullanmanın 4 yolu vardır: 1. Önceden tanımlı ayrıcalığı doğrudan kullanmak. 2. Önceden tanımlı bir ayrıcalığa dayanarak bazı belirli izinleri değiştirmek. 3. Önceden tanımlı bir ayrıcalığa dayanarak bazı belirli Adobe Professional izin kombinasyonlarını değiştirmek. 4. yol2 ve yol3'ü karıştırmak. //Way1: Önceden tanımlı ayrıcalığı doğrudan kullanma. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Önceden tanımlı bir ayrıcalığa dayanarak bazı belirli izinleri değiştirme. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Önceden tanımlı bir ayrıcalığa dayanarak bazı belirli Adobe Professional izin kombinasyonlarını değiştirme. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: yol2 ve yol3'ü karıştırma DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | Metnin kullandığı kodlama türlerini listeler. |
| [Facade](./facade/) | Temel dış yüz sınıfı. |
| [FontColor](./fontcolor/) | Metnin rengini temsil eden sınıf. |
| [Form](./form/) | Acro form nesnesini temsil eden sınıf. |
| [Form.ImportStatus](./form.importstatus/) | İçe aktarılan alanın durumu |
| [FormattedText](./formattedtext/) | Biçimlendirilmiş metni temsil eden sınıf. Metin ve onun rengi, boyutu, stili hakkında bilgi içerir. |
| [FormEditor](./formeditor/) | Formları düzenlemek için sınıf (alan ekleme/silme vb.) |
| [FormEditorWeb](./formeditorweb/) | Formları düzenlemek için sınıf (alan ekleme/silme vb.) |
| [FormFieldFacade](./formfieldfacade/) | Alan özelliklerini temsil eden sınıf. |
| [FormWeb](./formweb/) | Acro form arayüzünü temsil eder. |
| [InternalHelper](./internalhelper/) | Yardım sınıfı |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | Sayfa yeniden boyutlandırma parametrelerini belirlemek için sınıf. Aşağıdaki parametrelerin ayarlanmasına izin verir: Sonuç sayfasının boyutu (genişlik, yükseklik) varsayılan uzay birimlerinde veya başlangıç sayfasının boyutunun yüzdesi olarak; Sol, üst, alt ve sağ kenar boşlukları varsayılan uzay birimlerinde veya başlangıç sayfasının boyutunun yüzdesi olarak; Bazı değerler otomatik hesaplama için null bırakılabilir. Bu değerler, açıkça belirtilen değerlerin hesaplanmasından sonra sayfanın kalan boyutundan hesaplanır. Örneğin: sayfa genişliği = 100 ve yeni sayfa genişliği 60 birim olarak belirtilirse, sol ve sağ kenar boşlukları otomatik olarak hesaplanır: (100 - 60) / 2 = 15. Bu sınıf ResizeContents metodunda kullanılır. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | Kenar boşluğu veya içerik boyutunun, varsayılan uzay birimlerinin yüzdesi olarak belirtilen değeri. Bu sınıf ContentsResizeParameters içinde kullanılır. |
| [LineInfo](./lineinfo/) | Satır bilgisini temsil eder. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | PDF belge açıklamaları (yorumlar) ile çalışmak için bir sınıfı temsil eder. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | PDF dosyasının yer imleriyle (oluşturma, değiştirme, dışa aktarma, içe aktarma ve silme dahil) çalışmak için bir sınıfı temsil eder. |
| [PdfContentEditor](./pdfcontenteditor/) | PDF dosyasının içeriğini düzenlemek için bir sınıfı temsil eder. |
| [PdfConverter](./pdfconverter/) | PDF dosyasının her sayfasını görüntülere dönüştürmek için bir sınıfı temsil eder, şu anda BMP, JPEG, PNG ve TIFF desteklenir. PDF'lerde desteklenen içerik: resimler, form, yorum. |
| [PdfExtractor](./pdfextractor/) | PDF belgesinden görüntü ve metin çıkarmak için sınıf. |
| [PdfFileEditor](./pdffileeditor/) | PDF dosyasıyla işlemleri uygular: birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Birleştirme sürecinde bozuk dosya ile karşılaşıldığında gerçekleştirilen eylem. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | Birleştirmeden gelen ilerleme olaylarını işleyen ve genellikle çağıran tarafça sağlanan soyut bir metoda sahip sınıfı temsil eder. Böyle sağlanan müşterinin işleyicisi genellikle toplam birleştirme ilerlemesini konsolda veya ilerleme çubuğunda göstermek için kullanılabilir. Oluşan ilerleme olayı hakkında bilgi temsil eder. |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Birleştirme sırasında bozuk dosyalar hakkında bilgi sağlayan sınıf. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Sayfa kesme konumu verileri. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | Bu sınıf, dış uygulamada kullanılabilecek birleştirme ilerlemesi hakkında bilgi temsil eder. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | Bu enum, birleştirme sırasında oluşabilecek olası ilerleme olayı türlerini tanımlar |
| [PdfFileEditorWeb](./pdffileeditorweb/) | PdfFileEditorWeb sınıfını temsil eder ve PDF dosyasıyla birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb. işlemleri uygular. |
| [PdfFileInfo](./pdffileinfo/) | PDF belgesinin meta bilgilerine erişmek için bir sınıfı temsil eder. |
| [PdfFileMend](./pdffilemend/) | Mevcut PDF belgesinin sayfalarına metin ve resim eklemek için bir sınıfı temsil eder. |
| [PdfFileSanitization](./pdffilesanitization/) | Temizleme ve kurtarma API'sini temsil eder. Belgeleri başka bir şekilde oluşturamıyorsanız/aydınlayamıyorsanız kullanın. |
| [PdfFileSecurity](./pdffilesecurity/) | Bir PDF dosyasını sahibi veya kullanıcı şifresiyle şifreleme veya şifre çözme, güvenlik ayarlarını ve şifreyi değiştirmeyi temsil eder. |
| [PdfFileSignature](./pdffilesignature/) | Bir PDF dosyasını sertifika ile imzalamak için bir sınıfı temsil eder. |
| [PdfFileStamp](./pdffilestamp/) | PDF dosyalarına damga (filigran veya arka plan) eklemek için sınıf. |
| [PdfFileStampWeb](./pdffilestampweb/) | PDF dosyalarına damga (filigran veya arka plan) eklemek için sınıf. HttpServletResponse ile çalışmayı etkinleştirir. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Tüm JavaScript kodunu kaldırmak için sınıf. |
| [PdfPageEditor](./pdfpageeditor/) | PDF dosyasının sayfasını düzenlemek için bir sınıfı temsil eder; sayfayı döndürme, yakınlaştırma, konum taşıma ve sayfa boyutunu değiştirme gibi işlemleri içerir. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Mevcut baskı sayfası bilgilerini içeren bir nesneyi temsil eder. |
| [PdfProducer](./pdfproducer/) | <p> Diğer formatlardan PDF üretmek için bir sınıfı temsil eder. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | PrintDocument'in QueryPageSettings olayını işleyen yöntemi temsil eder. |
| [PdfViewer](./pdfviewer/) | PDF'i görüntülemek veya yazdırmak için bir sınıfı temsil eder. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | XMP meta verileriyle manipülasyon için sınıf. |
| [PositioningMode](./positioningmode/) | Konumlandırma modunu tanımlar. Olası değerler Legacy (geriye dönük uyumluluk) ve Current (güncellenmiş metin konumu hesaplama yöntemi) içerir |
| [PropertyFlag](./propertyflag/) | Olası alan bayraklarının enum'ı. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Bu sınıf, ReplaceText işlemi gerçekleştirildiğinde PdfContentEditor davranışını tanımlayan parametreleri içerir. |
| [SaveableFacade](./saveablefacade/) | <p> Tüm kaydedilebilir dış görünümler için temel sınıf. |
| [SignatureName](./signaturename/) | İmza adı için bir sınıfı temsil eder. Daha kesin bir imza adı temsil eder. Dize adları yerine kullanılır. Aynı dize adlarına sahip imzaları sunmanıza olanak tanır. |
| [Stamp](./stamp/) | Damga temsil eden sınıf. |
| [StampInfo](./stampinfo/) | Damga bilgilerini temsil eden sınıf. |
| [TextProperties](./textproperties/) | Metin boyutu, renk, stil vb. gibi metin özelliklerini temsil eder. |
| [VerticalAlignmentType](./verticalalignmenttype/) | Olası dikey hizalama değerlerini temsil eden sınıf. Bunun yerine VerticalAlignment kullanın |
| [ViewerPreference](./viewerpreference/) | Görüntüleyici tercihlerini (sayfa modu, tam ekran olmayan sayfa modu, sayfa düzeni) tanımlar. |
| [WordWrapMode](./wordwrapmode/) | Kelime kaydırma stratejilerini tanımlar |
## Enums

| Enum | Açıklama |
| --- | --- |
| [Algorithm](./algorithm/) | PDF belgesini şifrelemek için kullanılabilecek algoritmaları temsil eder. |
| [BlendingColorSpace](./blendingcolorspace/) | Karıştırma renk uzayını temsil eden sınıf. |
| [FieldType](./fieldtype/) | Olası alan türlerinin enumerasyonu. |
| [FontStyle](./fontstyle/) | 14 farklı yazı tipi türünü listeler. |
| [ImageMergeMode](./imagemergemode/) | Görüntü birleştirme modlarını temsil eder. |
| [KeySize](./keysize/) | PDF belgelerini şifrelemek için kullanılabilecek farklı anahtar boyutlarını tanımlar. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Yazı tipi gerekli karakteri içermediğinde yapılacak eylem |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Metin değiştirme işleminin uygulandığı kapsam, varsayılan olarak REPLACE_FIRST'tir. |
| [StampType](./stamptype/) | Damga türlerini tanımlar. |
| [SubmitFormFlag](./submitformflag/) | Olası gönder form bayraklarının enumerasyonu. |
