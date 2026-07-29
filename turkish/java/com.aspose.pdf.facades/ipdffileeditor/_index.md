---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF dosyasıyla işlemleri uygular: birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb."
type: docs
weight: 290
url: /tr/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

PDF dosyasıyla işlemleri uygular: birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Sayfaları, portStreams içindeki belge dizisinden seçilen, ekler. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Sayfaları, startPage ile endPage arasındaki aralıkta portStream'ten seçilen, firstInputStream'in sonundaki portStream'e ekler. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Sayfaları, portFiles belgelerinden seçilen, ekler. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Sayfaları, startPage ile endPage arasındaki aralıkta portFile'dan seçilen, firstInputFile'ın sonundaki portFile'e ekler. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Belgeleri birleştirir. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Dosyaları birleştirir. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | İki Pdf belgesini sayfaları alternatif şekilde yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | İki dosyayı birleştirir. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Dosyaları tek bir dosyada birleştirir. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | İki dosyayı birleştirir. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | İki Pdf belgesini sayfaları alternatif şekilde yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Giriş dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Giriş dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Birleştirme İstisnalarına İzin Verilir |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | True olarak ayarlanırsa, akışlar işlem sonrası kapatılır. |
| [getContentDisposition](#getContentDisposition--) | İşlemin sonucu HttpServletResponse nesnesine depolandığında içeriğin nasıl saklanacağını alır. |
| [getConversionLog](#getConversionLog--) | Dönüştürme sürecinin günlüğünü alır. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | True ise, birleştirme sırasında artımlı güncellemeler yapılır. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Doğru ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilecektir. |
| [getLastException](#getLastException--) | Son oluşan istisna alınır. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | True ise, yinelenen anahatlar birleştirilir. |
| [getOwnerPassword](#getOwnerPassword--) | Kaynak giriş PDF dosyası şifreli ise, sahibinin parolası alınır. |
| [getPreserveUserRights](#getPreserveUserRights--) | Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır. |
| [getRemoveSignatures](#getRemoveSignatures--) | Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz. |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpServletResponse olarak depolandığında kaydetme seçeneklerini alır veya ayarlar. |
| [getUniqueSuffix](#getUniqueSuffix--) | Formlar birleştirildiğinde alan adına eklenen ve benzersiz hâle getiren sonek formatını al. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Diğer bir dosyadan sayfaları PDF dosyasına belirli bir konumda ekler. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | InputStream'den outputStream'e kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | firstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Giriş akışından kitapçık oluşturur ve sonucu çıkış akışına kaydeder. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | firstInputStream'den outputStream'e kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Giriş dosyasından çıkış dosyasına kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | firstInputFile'dan outputFile'a özelleştirilmiş kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | inputFile'dan outputFile'a kitapçık oluşturur. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | firstInputFile'dan outputFile'a özelleştirilmiş kitapçık oluşturur. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Çoklu giriş PDF akışlarından outputStream'e N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | İki giriş PDF akışından outputStream'e N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Giriş akışından N-Up belge oluşturur ve sonucu çıkış akışına kaydeder. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | İlk giriş akışından output stream'e N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Çoklu giriş PDF dosyalarından outputFile'a N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | firstInputFile'dan outputFile'a N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | giriş dosyasından outputFile'a N-Up belge oluşturur. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | İki giriş PDF dosyasından outputFile'a N-Up belge oluşturur. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Belge sayfalarının içeriklerini yeniden boyutlandırır. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Belge sayfalarının içeriklerini yeniden boyutlandırır. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Belge sayfalarının içeriklerini yeniden boyutlandırır. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Belge sayfalarının içeriklerini yeniden boyutlandırır. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Doğru olarak ayarlanırsa, hata oluştuğunda istisnalar fırlatılır. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını ayarlar. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | True olarak ayarlanırsa, akışlar işlem sonrası kapatılır. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpServletResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını ayarlar. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF dosya formatını ayarlar. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | True ise, birleştirme sırasında artımlı güncellemeler yapılır. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Doğru ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilecektir. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | True ise, yinelenen anahatlar birleştirilir. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Kaynak giriş Pdf dosyası şifreli ise, sahibinin şifresini ayarlar. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpServletResponse olarak kaydedildiğinde kaydetme seçeneklerini ayarlar. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Formlar birleştirildiğinde alan adına eklenerek benzersiz yapılmasını sağlayan sonek formatını ayarlar. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Başlangıçtan belirtilen konuma kadar bölerek,ön kısmı çıktı Akışına kaydeder. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Pdf dosyasını ilk sayfadan belirtilen konuma kadar bölerek, ön kısmı yeni bir dosya olarak kaydeder. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Belirtilen konumdan bölerek, arka kısmı yeni bir dosya Akışı olarak kaydeder. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Konumdan bölerek, arka kısmı yeni bir dosya olarak kaydeder. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Pdf dosyasını tek sayfalık belgelere böler. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder. |
| [splitToPages](#splitToPages-java.lang.String-) | PDF dosyasını tek sayfalı belgelere böler. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Sayfa içeriklerini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Sayfaları, portStreams içindeki belge dizisinden seçilen, ekler.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Sayfaları, startPage ile endPage arasındaki aralıkta portStream'ten seçilen, firstInputStream'in sonundaki portStream'e ekler.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Sayfaları, portFiles belgelerinden seçilen, ekler.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Sayfaları, startPage ile endPage arasındaki aralıkta portFile'dan seçilen, firstInputFile'ın sonundaki portFile'e ekler.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Belgeleri birleştirir.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Dosyaları birleştirir.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
İki Pdf belgesini sayfaları alternatif şekilde yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
İki dosyayı birleştirir.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Dosyaları tek bir dosyada birleştirir.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
İki dosyayı birleştirir.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
İki Pdf belgesini sayfaları alternatif şekilde yeni bir Pdf belgesinde birleştirir ve boş yerleri boş sayfalarla doldurur.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Giriş dosyasından sayı dizisiyle belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Giriş dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Giriş dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

Birleştirme İstisnalarına İzin Verilir

**Returns:**
boolean değer

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır.

**Returns:**
string value

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

True olarak ayarlanırsa, akışlar işlem sonrası kapatılır.

**Returns:**
boolean değer

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

İşlemin sonucu HttpServletResponse nesnesine depolandığında içeriğin nasıl saklanacağını alır.

**Returns:**
ContentDisposition öğesi

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

Dönüştürme sürecinin günlüğünü alır.

**Returns:**
string value

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar.

**Returns:**
ConcatenateCorruptedFileAction öğesi

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

True ise, birleştirme sırasında artımlı güncellemeler yapılır.

**Returns:**
boolean değer

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

Doğru ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilecektir.

**Returns:**
boolean değer

### getLastException {#getLastException--}
```
Exception getLastException()
```

Son oluşan istisna alınır.

**Returns:**
java.lang.Exception nesnesi

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir.

**Returns:**
boolean değer

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

True ise, yinelenen anahatlar birleştirilir.

**Returns:**
boolean değer

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

Kaynak giriş PDF dosyası şifreli ise, sahibinin parolası alınır.

**Returns:**
string value

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır.

**Returns:**
boolean değer

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz.

**Returns:**
boolean değer

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Sonuç HttpServletResponse olarak depolandığında kaydetme seçeneklerini alır veya ayarlar.

**Returns:**
SaveOptions nesnesi

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

Formlar birleştirildiğinde alan adına eklenen ve benzersiz hâle getiren sonek formatını al.

**Returns:**
string value

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Diğer bir dosyadan sayfaları PDF dosyasına belirli bir konumda ekler.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
InputStream'den outputStream'e kitapçık oluşturur.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
firstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Giriş akışından kitapçık oluşturur ve sonucu çıkış akışına kaydeder.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
firstInputStream'den outputStream'e kitapçık oluşturur.

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

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Giriş akışından N-Up belge oluşturur ve sonucu çıkış akışına kaydeder.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
İlk giriş akışından output stream'e N-Up belge oluşturur.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Çoklu giriş PDF dosyalarından outputFile'a N-Up belge oluşturur.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
firstInputFile'dan outputFile'a N-Up belge oluşturur.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
giriş dosyasından outputFile'a N-Up belge oluşturur.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
İki giriş PDF dosyasından outputFile'a N-Up belge oluşturur.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Belge sayfalarının içeriklerini yeniden boyutlandırır.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Belge sayfalarının içeriklerini yeniden boyutlandırır.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Belge sayfalarının içeriklerini yeniden boyutlandırır.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Belge sayfalarının içeriklerini yeniden boyutlandırır.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

Doğru olarak ayarlanırsa, hata oluştuğunda istisnalar fırlatılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını ayarlar.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

True olarak ayarlanırsa, akışlar işlem sonrası kapatılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
İşlemin sonucu HttpServletResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını ayarlar.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF dosya formatını ayarlar.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ConcatenateCorruptedFileAction öğesi |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

True ise, birleştirme sırasında artımlı güncellemeler yapılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

Doğru ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

True ise, yinelenen anahatlar birleştirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Kaynak giriş Pdf dosyası şifreli ise, sahibinin şifresini ayarlar.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpServletResponse olarak kaydedildiğinde kaydetme seçeneklerini ayarlar.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Formlar birleştirildiğinde alan adına eklenerek benzersiz yapılmasını sağlayan sonek formatını ayarlar.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Başlangıçtan belirtilen konuma kadar bölerek,ön kısmı çıktı Akışına kaydeder.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Pdf dosyasını ilk sayfadan belirtilen konuma kadar bölerek, ön kısmı yeni bir dosya olarak kaydeder.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Belirtilen konumdan bölerek, arka kısmı yeni bir dosya Akışı olarak kaydeder.

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
