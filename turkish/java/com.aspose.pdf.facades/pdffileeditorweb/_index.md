---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Aspose.PDF for Java API Referansı"
description: "PdfFileEditorWeb sınıfını temsil eder ve PDF dosyasıyla birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb. işlemleri uygular."
type: docs
weight: 480
url: /tr/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

PdfFileEditorWeb sınıfını temsil eder ve PDF dosyasıyla birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb. işlemleri uygular.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | PdfFileEditorWeb yapıcısı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Belge sayfalarına sayfa sonları ekler. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Belge sayfalarına sayfa sonları ekler. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Belge sayfalarına sayfa sonları ekler. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Belge sayfalarına sayfa sonları ekler. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | Belgeleri kaynak belgeye ekler ve sonucu yanıt nesnesine kaydeder. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Sayfaları, portStreams içindeki belge dizisinden seçilen, ekler. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Sayfaları, startPage ile endPage arasındaki aralıkta portStream'ten seçilen, firstInputStream'in sonundaki portStream'e ekler. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | Belgeleri kaynak belgeye ekler ve sonucu HttpServletResponse nesnesine kaydeder. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Sayfaları, portFiles belgelerinden seçilen, ekler. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Sayfaları, startPage ile endPage arasındaki aralıkta portFile'dan seçilen, firstInputFile'ın sonundaki portFile'e ekler. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Belgeleri birleştirir. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | Dosyaları birleştirir ve sonucu HttpServletResponse nesnesine depolar. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Dosyaları birleştirir. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | İki Pdf belgesini sayfaları alternatif şekilde yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | İki dosyayı birleştirir. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | Dosyaları birleştirir ve sonucu HttpResposnse nesnesine kaydeder. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Dosyaları tek bir dosyada birleştirir. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | İki dosyayı birleştirir. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | İki Pdf belgesini sayfaları alternatif şekilde yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Belirtilen sayfaları belgeden siler ve sonucu HttpServletResponse nesnesine kaydeder. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Belirtilen sayfaları belgeden siler ve sonucu HttpServletResponse nesnesine depolar. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpServletResponse nesnesine depolar. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Giriş dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpServletResponse nesnesine depolar. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Giriş dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Kullanımdan kaldırıldı. Bu özellik kullanımdan kaldırılmıştır ve istisna fırlatılmasına izin vermek için kullanılamaz. |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | True olarak ayarlanırsa, akışlar işlem sonrası kapatılır. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | UseDiskBuffer true olarak ayarlandığında, birleştirme sırasında yeni artımlı güncelleme yapılmadan önce birleştirilen belge sayısı. |
| [getContentDisposition](#getContentDisposition--) | İşlemin sonucu HttpServletResponse nesnesine depolandığında içeriğin nasıl saklanacağını alır. |
| [getConversionLog](#getConversionLog--) | Dönüştürme sürecinin günlüğünü alır. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | True ise, birleştirme gerçekleştirildiğinde dosyanın mantıksal yapısı kopyalanır. |
| [getCopyOutlines](#getCopyOutlines--) | True ise, anahatlar kopyalanır. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar. |
| [getCorruptedItems](#getCorruptedItems--) | Birleştirme gerçekleştirildiğinde karşılaşılan sorunların dizisi. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Birleştirme sırasında çalışan ve iç birleştirme aşamalarının olaylarını dış müşteri koduna çeviren dahili ilerleme olayları işlemcisinin temsili. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | True ise, birleştirme sırasında artımlı güncellemeler yapılır. |
| [getKeepActions](#getKeepActions--) | True ise, eylemler kaynak belgelerden kopyalanır. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Doğru ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilecektir. |
| [getLastException](#getLastException--) | Son meydana gelen istisnayı alır. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | True ise, yinelenen anahatlar birleştirilir. |
| [getOptimizeSize](#getOptimizeSize--) | Optimizasyon bayrağını alır veya ayarlar. |
| [getOwnerPassword](#getOwnerPassword--) | Kaynak giriş PDF dosyası şifreli ise, sahibinin parolası alınır. |
| [getPreserveUserRights](#getPreserveUserRights--) | Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır. |
| [getRemoveSignatures](#getRemoveSignatures--) | Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz. |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpServletResponse olarak depolandığında kaydetme seçeneklerini alır veya ayarlar. |
| [getUniqueSuffix](#getUniqueSuffix--) | Formlar birleştirildiğinde alan adına eklenen ve benzersiz hâle getiren sonek formatını al. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Belgeyi başka bir belgeye ekler ve sonucu yanıt nesnesine kaydeder. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Dosyanın içeriğini kaynak dosyaya ekler ve sonucu HttpServletResponse nesnesine kaydeder. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Diğer bir dosyadan sayfaları PDF dosyasına belirli bir konumda ekler. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini, yan yana yerleştirilen birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş şekilde içerir. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Bu seçenek kullanılırsa, hedef belge periyodik olarak diske kaydedilecek ve sonraki birleştirmeler artımlı güncellemeler olarak uygulanacaktır. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | InputStream'den outputStream'e kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | firstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Giriş akışından kitapçık oluşturur ve sonucu çıkış akışına kaydeder. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | firstInputStream'den outputStream'e kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Kaynak dosyadan bir kitapçık oluşturur ve sonucu HttpServletResponse içine kaydeder. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | PDF dosyasından bir kitapçık oluşturur ve onu HttpServletResponse içine kaydeder. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Kaynak dosyadan bir kitapçık oluşturur ve sonucu HttpServletResponse nesnelerine kaydeder. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Kaynak dosyadan bir kitapçık oluşturur ve sonucu HttpServletResponse nesnelerine kaydeder. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Giriş dosyasından çıkış dosyasına kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | firstInputFile'dan outputFile'a özelleştirilmiş kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | inputFile'dan outputFile'a kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | firstInputFile'dan outputFile'a özelleştirilmiş kitapçık oluşturur. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Çoklu giriş PDF akışlarından outputStream'e N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | İki giriş PDF akışından outputStream'e N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | N-up belge oluşturur ve sonucu HttpServletResponse içine kaydeder. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | N-up belge oluşturur ve sonucu HttpServletResponse nesnesine kaydeder. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Giriş akışından N-Up belge oluşturur ve sonucu çıkış akışına kaydeder. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | İlk giriş akışından output stream'e N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Çoklu giriş PDF dosyalarından outputFile'a N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | N-up belge oluşturur ve sonucu HttpServletResponse içine kaydeder. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | N-up belge oluşturur ve sonucu HttpServletResponse nesnesine kaydeder. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | firstInputFile'dan outputFile'a N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | giriş dosyasından outputFile'a N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | İki giriş PDF dosyasından outputFile'a N-Up belge oluşturur. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarını yeniden boyutlandırır. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarını yeniden boyutlandırır. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Belge sayfalarının içeriklerini yeniden boyutlandırır. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarının içeriğini yeniden boyutlandırır. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Belge sayfalarının içeriklerini yeniden boyutlandırır. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Belge sayfalarının içeriklerini yeniden boyutlandırır. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Belge sayfalarının içeriklerini yeniden boyutlandırır. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarını yeniden boyutlandırır. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarını yeniden boyutlandırır. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Kullanımdan kaldırıldı. Bu özellik kullanımdan kaldırılmıştır ve istisna fırlatılmasına izin vermek için kullanılamaz. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını ayarlar. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | True olarak ayarlanırsa, akışlar işlem sonrası kapatılır. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | UseDiskBuffer true olarak ayarlandığında, birleştirme sırasında yeni artımlı güncelleme yapılmadan önce birleştirilen belge sayısı. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpServletResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını ayarlar. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF dosya formatını ayarlar. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | True ise, birleştirme gerçekleştirildiğinde dosyanın mantıksal yapısı kopyalanır. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | True ise, anahatlar kopyalanır. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Birleştirme sırasında çalışan ve iç birleştirme aşamalarının olaylarını dış müşteri koduna çeviren dahili ilerleme olayları işlemcisinin temsili. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | True ise, birleştirme sırasında artımlı güncellemeler yapılır. |
| [setKeepActions](#setKeepActions-boolean-) | True ise, eylemler kaynak belgelerden kopyalanır. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Doğru ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilecektir. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | True ise, yinelenen anahatlar birleştirilir. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Optimizasyon bayrağını alır veya ayarlar. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Kaynak giriş Pdf dosyası şifreli ise, sahibinin şifresini ayarlar. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpServletResponse olarak kaydedildiğinde kaydetme seçeneklerini ayarlar. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini, yan yana yerleştirilen birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş şekilde içerir. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Formlar birleştirildiğinde alan adına eklenerek benzersiz yapılmasını sağlayan sonek formatını ayarlar. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Bu seçenek kullanılırsa, hedef belge periyodik olarak diske kaydedilecek ve sonraki birleştirmeler artımlı güncellemeler olarak uygulanacaktır. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Belgeyi başlangıçtan belirtilen konuma kadar böler ve sonucu HttpServletResponse nesnesine kaydeder. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Başlangıçtan belirtilen konuma kadar bölerek,ön kısmı çıktı Akışına kaydeder. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Belgeyi ilk sayfadan konuma kadar böler ve sonucu HttpServletResponse nesnelerine kaydeder. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Pdf dosyasını ilk sayfadan belirtilen konuma kadar bölerek, ön kısmı yeni bir dosya olarak kaydeder. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Belgeyi belirtilen konumdan ayırır ve arka kısmı HttpServletResponse nesnesine kaydeder. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Belirtilen konumdan bölerek, arka kısmı yeni bir dosya Akışı olarak kaydeder. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Belgeyi belirtilen konumdan ayırır ve arka kısmı HttpServletResponse nesnesine kaydeder. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Konumdan bölerek, arka kısmı yeni bir dosya olarak kaydeder. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Pdf dosyasını tek sayfalık belgelere böler. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder. |
| [splitToPages](#splitToPages-java.lang.String-) | PDF dosyasını tek sayfalı belgelere böler. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

PdfFileEditorWeb yapıcısı.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Belge sayfalarına sayfa sonları ekler.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Belge sayfalarına sayfa sonları ekler.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Belge sayfalarına sayfa sonları ekler.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Belge sayfalarına sayfa sonları ekler.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
Belgeleri kaynak belgeye ekler ve sonucu yanıt nesnesine kaydeder.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Sayfaları, portStreams içindeki belge dizisinden seçilen, ekler.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Sayfaları, startPage ile endPage arasındaki aralıkta portStream'ten seçilen, firstInputStream'in sonundaki portStream'e ekler.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
Belgeleri kaynak belgeye ekler ve sonucu HttpServletResponse nesnesine kaydeder.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Sayfaları, portFiles belgelerinden seçilen, ekler.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Sayfaları, startPage ile endPage arasındaki aralıkta portFile'dan seçilen, firstInputFile'ın sonundaki portFile'e ekler.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Belgeleri birleştirir.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
Dosyaları birleştirir ve sonucu HttpServletResponse nesnesine depolar.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Dosyaları birleştirir.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
İki Pdf belgesini sayfaları alternatif şekilde yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
İki dosyayı birleştirir.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
Dosyaları birleştirir ve sonucu HttpResposnse nesnesine kaydeder.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Dosyaları tek bir dosyada birleştirir.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
İki dosyayı birleştirir.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
İki Pdf belgesini sayfaları alternatif şekilde yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Belirtilen sayfaları belgeden siler ve sonucu HttpServletResponse nesnesine kaydeder.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Belirtilen sayfaları belgeden siler ve sonucu HttpServletResponse nesnesine depolar.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpServletResponse nesnesine depolar.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Giriş dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpServletResponse nesnesine depolar.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Giriş dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

Kullanımdan kaldırıldı. Bu özellik kullanımdan kaldırılmıştır ve istisna fırlatılmasına izin vermek için kullanılamaz.

**Returns:**
Boolean değer

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır.

**Returns:**
string value

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

True olarak ayarlanırsa, akışlar işlem sonrası kapatılır.

**Returns:**
boolean değer

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

UseDiskBuffer true olarak ayarlandığında, birleştirme sırasında yeni artımlı güncelleme yapılmadan önce birleştirilen belge sayısı.

**Returns:**
int değer

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

İşlemin sonucu HttpServletResponse nesnesine depolandığında içeriğin nasıl saklanacağını alır.

**Returns:**
ContentDisposition öğesi

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Dönüştürme sürecinin günlüğünü alır.

**Returns:**
string value

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

True ise, birleştirme gerçekleştirildiğinde dosyanın mantıksal yapısı kopyalanır.

**Returns:**
boolean değer

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

True ise, anahatlar kopyalanır.

**Returns:**
boolean değer

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar.

**Returns:**
ConcatenateCorruptedFileAction öğesi

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

Birleştirme gerçekleştirildiğinde karşılaşılan sorunların dizisi.

**Returns:**
PdfFileEditor.CorruptedItem dizisi

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Birleştirme sırasında çalışan ve iç birleştirme aşamalarının olaylarını dış müşteri koduna çeviren dahili ilerleme olayları işlemcisinin temsili.

**Returns:**
ConcatenationProgressHandler örneği

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

True ise, birleştirme sırasında artımlı güncellemeler yapılır.

**Returns:**
boolean değer

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

True ise, eylemler kaynak belgelerden kopyalanır.

**Returns:**
boolean değer

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

Doğru ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilecektir.

**Returns:**
boolean değer

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Son meydana gelen istisnayı alır.

**Returns:**
java.lang.Exception nesnesi

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir.

**Returns:**
boolean değer

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

True ise, yinelenen anahatlar birleştirilir.

**Returns:**
boolean değer

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Optimizasyon bayrağını alır veya ayarlar.

**Returns:**
boolean değer

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Kaynak giriş PDF dosyası şifreli ise, sahibinin parolası alınır.

**Returns:**
Dize nesnesi

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır.

**Returns:**
boolean değer

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz.

**Returns:**
boolean değer

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Sonuç HttpServletResponse olarak depolandığında kaydetme seçeneklerini alır veya ayarlar.

**Returns:**
SaveOptions nesnesi

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Formlar birleştirildiğinde alan adına eklenen ve benzersiz hâle getiren sonek formatını al.

**Returns:**
Dize nesnesi

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Belgeyi başka bir belgeye ekler ve sonucu yanıt nesnesine kaydeder.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Dosyanın içeriğini kaynak dosyaya ekler ve sonucu HttpServletResponse nesnesine kaydeder.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Diğer bir dosyadan sayfaları PDF dosyasına belirli bir konumda ekler.

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini, yan yana yerleştirilen birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş şekilde içerir.

**Returns:**
boolean değer

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

Bu seçenek kullanılırsa, hedef belge periyodik olarak diske kaydedilecek ve sonraki birleştirmeler artımlı güncellemeler olarak uygulanacaktır.

**Returns:**
boolean değer

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
InputStream'den outputStream'e kitapçık oluşturur.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
firstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Giriş akışından kitapçık oluşturur ve sonucu çıkış akışına kaydeder.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
firstInputStream'den outputStream'e kitapçık oluşturur.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Kaynak dosyadan bir kitapçık oluşturur ve sonucu HttpServletResponse içine kaydeder.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
PDF dosyasından bir kitapçık oluşturur ve onu HttpServletResponse içine kaydeder.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Kaynak dosyadan bir kitapçık oluşturur ve sonucu HttpServletResponse nesnelerine kaydeder.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Kaynak dosyadan bir kitapçık oluşturur ve sonucu HttpServletResponse nesnelerine kaydeder.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
Giriş dosyasından çıkış dosyasına kitapçık oluşturur.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
firstInputFile'dan outputFile'a özelleştirilmiş kitapçık oluşturur.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
inputFile'dan outputFile'a kitapçık oluşturur.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
firstInputFile'dan outputFile'a özelleştirilmiş kitapçık oluşturur.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
Çoklu giriş PDF akışlarından outputStream'e N-Up belge oluşturur.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
İki giriş PDF akışından outputStream'e N-Up belge oluşturur.

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
N-up belge oluşturur ve sonucu HttpServletResponse içine kaydeder.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
N-up belge oluşturur ve sonucu HttpServletResponse nesnesine kaydeder.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Giriş akışından N-Up belge oluşturur ve sonucu çıkış akışına kaydeder.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
İlk giriş akışından output stream'e N-Up belge oluşturur.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Çoklu giriş PDF dosyalarından outputFile'a N-Up belge oluşturur.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
N-up belge oluşturur ve sonucu HttpServletResponse içine kaydeder.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
N-up belge oluşturur ve sonucu HttpServletResponse nesnesine kaydeder.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
firstInputFile'dan outputFile'a N-Up belge oluşturur.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
giriş dosyasından outputFile'a N-Up belge oluşturur.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
İki giriş PDF dosyasından outputFile'a N-Up belge oluşturur.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarını yeniden boyutlandırır.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarını yeniden boyutlandırır.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Belge sayfalarının içeriklerini yeniden boyutlandırır.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarının içeriğini yeniden boyutlandırır.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Belgedeki sayfaların içeriğini yeniden boyutlandırır.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Belgedeki sayfaların içeriğini yeniden boyutlandırır.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Belge sayfalarının içeriklerini yeniden boyutlandırır.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgedeki sayfaların içeriğini yeniden boyutlandırır.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Belge sayfalarının içeriklerini yeniden boyutlandırır.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Belge sayfalarının içeriklerini yeniden boyutlandırır.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarını yeniden boyutlandırır.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarını yeniden boyutlandırır.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

Kullanımdan kaldırıldı. Bu özellik kullanımdan kaldırılmıştır ve istisna fırlatılmasına izin vermek için kullanılamaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Boolean değer |

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını ayarlar.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

True olarak ayarlanırsa, akışlar işlem sonrası kapatılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

UseDiskBuffer true olarak ayarlandığında, birleştirme sırasında yeni artımlı güncelleme yapılmadan önce birleştirilen belge sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
İşlemin sonucu HttpServletResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını ayarlar.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF dosya formatını ayarlar.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

True ise, birleştirme gerçekleştirildiğinde dosyanın mantıksal yapısı kopyalanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

True ise, anahatlar kopyalanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ConcatenateCorruptedFileAction öğesi |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Birleştirme sırasında çalışan ve iç birleştirme aşamalarının olaylarını dış müşteri koduna çeviren dahili ilerleme olayları işlemcisinin temsili.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

True ise, birleştirme sırasında artımlı güncellemeler yapılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

True ise, eylemler kaynak belgelerden kopyalanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

Doğru ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

True ise, yinelenen anahatlar birleştirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Optimizasyon bayrağını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Kaynak giriş Pdf dosyası şifreli ise, sahibinin şifresini ayarlar.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpServletResponse olarak kaydedildiğinde kaydetme seçeneklerini ayarlar.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini, yan yana yerleştirilen birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş şekilde içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | boolean değer |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Formlar birleştirildiğinde alan adına eklenerek benzersiz yapılmasını sağlayan sonek formatını ayarlar.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Bu seçenek kullanılırsa, hedef belge periyodik olarak diske kaydedilecek ve sonraki birleştirmeler artımlı güncellemeler olarak uygulanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Belgeyi başlangıçtan belirtilen konuma kadar böler ve sonucu HttpServletResponse nesnesine kaydeder.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Başlangıçtan belirtilen konuma kadar bölerek,ön kısmı çıktı Akışına kaydeder.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Belgeyi ilk sayfadan konuma kadar böler ve sonucu HttpServletResponse nesnelerine kaydeder.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Pdf dosyasını ilk sayfadan belirtilen konuma kadar bölerek, ön kısmı yeni bir dosya olarak kaydeder.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Belgeyi belirtilen konumdan ayırır ve arka kısmı HttpServletResponse nesnesine kaydeder.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Belirtilen konumdan bölerek, arka kısmı yeni bir dosya Akışı olarak kaydeder.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Belgeyi belirtilen konumdan ayırır ve arka kısmı HttpServletResponse nesnesine kaydeder.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
Konumdan bölerek, arka kısmı yeni bir dosya olarak kaydeder.

### splitToPages {#splitToPages-java.io.InputStream-}
Pdf dosyasını tek sayfalık belgelere böler.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder.

### splitToPages {#splitToPages-java.lang.String-}
PDF dosyasını tek sayfalı belgelere böler.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder.
