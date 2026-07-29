---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF dosyasıyla işlemleri uygular: birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb."
type: docs
weight: 410
url: /tr/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

PDF dosyasıyla işlemleri uygular: birleştirme, bölme, sayfa çıkarma, kitapçık oluşturma vb.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | PdfFileEditor yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan uzay birimlerinde belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan uzay birimlerinde belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları sayfa boyutunun yüzde olarak belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları sayfa boyutunun yüzde olarak belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Belge sayfalarına sayfa sonları ekler. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Belge sayfalarına sayfa sonları ekler. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Belge sayfalarına sayfa sonları ekler. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Belge sayfalarına sayfa sonları ekler. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> Sayfaları ekler, portStreams içindeki belge dizisinden seçilen. Sonuç belgesi, firstInputFile ve tüm portStreams belgelerinin startPage ile endPage arasındaki sayfalarını içerir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Sayfaları ekler, portStream içindeki startPage ile endPage arasındaki aralıktan seçilen, portStream içinde firstInputStream'in sonunda. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> Sayfaları ekler, portFiles belgelerinden seçilen. Sonuç belgesi, firstInputFile ve tüm portFiles belgelerinin startPage ile endPage arasındaki sayfalarını içerir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> Sayfaları ekler, portFile içindeki startPage ile endPage arasındaki aralıktan seçilen, portFile içinde firstInputFile'in sonunda. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Belgeleri birleştirir. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> Dosyaları birleştirir </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> İki Pdf belgesini, sayfalar alternatif şekilde yeni bir Pdf belgesine birleştirir ve boş yerleri boş sayfalarla doldurur. ör.: document1 5 sayfaya sahiptir: p1, p2, p3, p4, p5. document2 3 sayfaya sahiptir: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sonuç belgesini şu sayfalarla üretir: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> İki dosyayı birleştirir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> Dosyaları tek bir dosyada birleştirir. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> İki dosyayı birleştirir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> İki Pdf belgesini, sayfalar alternatif şekilde yeni bir Pdf belgesine birleştirir ve boş yerleri boş sayfalarla doldurur. ör.: document1 5 sayfaya sahiptir: p1, p2, p3, p4, p5. document2 3 sayfaya sahiptir: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sonuç belgesini şu sayfalarla üretir: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Girdi dosyasından, sayı dizisiyle belirtilen sayfaları siler ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> Girdi dosyasından, sayı dizisiyle belirtilen sayfaları siler ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Sayı dizisiyle belirtilen sayfaları çıkarır ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Girdi dosyasından sayfaları çıkarır ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> Sayı dizisiyle belirtilen sayfaları çıkarır ve yeni bir PDF dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> Girdi dosyasından sayfaları çıkarır ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> True olarak ayarlanırsa, hata oluştuğunda istisnalar fırlatılır. Aksi takdirde istisnalar fırlatılmaz ve yöntemler başarısız olduğunda false döner. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | True olarak ayarlanırsa, akışlar işlem sonrası kapatılır. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | UseDiskBuffer true olarak ayarlandığında, birleştirme sırasında yeni artımlı güncelleme yapılmadan önce birleştirilen belge sayısı. |
| [getContentDisposition](#getContentDisposition--) | İşlemin sonucu HttpServletResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır. Olası değerler: inline / attachment. Varsayılan: inline. |
| [getConversionLog](#getConversionLog--) | Dönüştürme sürecinin günlüğünü alır. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | True ise, birleştirme gerçekleştirildiğinde dosyanın mantıksal yapısı kopyalanır. |
| [getCopyOutlines](#getCopyOutlines--) | True ise, anahatlar kopyalanır. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar. Olası değerler: StopWithError ve ConcatenateIgnoringCorrupted. |
| [getCorruptedItems](#getCorruptedItems--) | <p> Birleştirme gerçekleştirildiğinde karşılaşılan sorunların dizisi. Concatenate() fonksiyonuna geçirilen her bozuk belge için yeni bir CorruptedItem girdisi oluşturulur. Bu özellik yalnızca CorruptedFileAction ConcatenateIgnoringCorrupted olduğunda kullanılabilir. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Birleştirme sırasında çalışan ve iç birleştirme aşamalarının olaylarını dış müşteri koduna çeviren dahili ilerleme olayları işlemcisinin temsili. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | True ise, birleştirme sırasında artımlı güncellemeler yapılır. |
| [getKeepActions](#getKeepActions--) | True ise, eylemler kaynak belgelerden kopyalanır. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | True ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilir. Alan adlarına ekler eklenir, ek şablonu UniqueSuffix özelliğinde belirtilebilir. |
| [getLastException](#getLastException--) | Son meydana gelen istisnayı alır. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | True ise, yinelenen anahatlar birleştirilir. |
| [getOptimizeSize](#getOptimizeSize--) | Optimizasyon bayrağını alır veya ayarlar. |
| [getOwnerPassword](#getOwnerPassword--) | Kaynak girdi Pdf dosyası şifreli ise sahibinin şifresini alır. Bu özellik henüz uygulanmadı. |
| [getPreserveUserRights](#getPreserveUserRights--) | Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır. |
| [getRemoveSignatures](#getRemoveSignatures--) | Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz. |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpServletResponse olarak depolandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions. |
| [getUniqueSuffix](#getUniqueSuffix--) | Formlar birleştirildiğinde alan adını benzersiz kılmak için alan adına eklenen sonek formatını alın. Bu dize %NUM% alt dizesini içermelidir ve bu alt dize sayılarla değiştirilecektir. Örneğin UniqueSuffix = "ABC%NUM%" ise, "fieldName" alanı için adlar: fieldNameABC1, fieldNameABC2, fieldNameABC3 vb. olacaktır. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> Diğer bir dosyadan sayfaları PDF dosyasına bir konumda ekler. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini, yan yana yerleştirilen birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş şekilde içerir. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Bu seçenek kullanılırsa, hedef belge periyodik olarak diske kaydedilecek ve sonraki birleştirmeler artımlı güncellemeler olarak uygulanacaktır. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> InputStream'den outputStream'e kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> firstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> Giriş akışından kitapçık oluşturur ve sonucu çıkış akışına kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> firstInputStream'den outputStream'e kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> Giriş dosyasından çıkış dosyasına kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> firstInputFile'den outputFile'e özelleştirilmiş kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> inputFile dosyasından outputFile dosyasına bir kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> firstInputFile dosyasından outputFile dosyasına özelleştirilmiş bir kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> çoklu giriş PDF akışlarından outputStream'e N‑Up belge oluşturur. outputStream'in her sayfası, aynı sayfa numarasına sahip giriş akışlarındaki sayfalarla birleştirilmiş çoklu sayfalar içerir. isSidewise true ise çoklu sayfalar yatay olarak, false ise dikey olarak yığılır. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> iki giriş PDF akışından outputStream'e N‑Up belge oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> giriş akışından N‑Up belge oluşturur ve sonucu çıktı akışına kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> ilk giriş akışından çıktı akışına N‑Up belge oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> çoklu giriş PDF dosyalarından outputFile'a N‑Up belge oluşturur. outputFile'ın her sayfası, aynı sayfa numarasına sahip giriş dosyalarındaki sayfalarla birleştirilmiş çoklu sayfalar içerir. isSidewise true ise çoklu sayfalar yatay, false ise dikey olarak yığılır. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> firstInputFile dosyasından outputFile dosyasına N‑Up belge oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> giriş dosyasından outputFile dosyasına N‑Up belge oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> iki giriş PDF dosyasından outputFile dosyasına N‑Up belge oluşturur. outputFile'ın her sayfası iki sayfa içerir, bir sayfa ilk giriş dosyasından, diğeri ikinci giriş dosyasından. Bu iki sayfa yatay olarak yığılır. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarını yeniden boyutlandırır. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarını yeniden boyutlandırır. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfa içeriğini küçültür ve kenar boşlukları ekler. İçeriğin yeni boyutu varsayılan uzay birimlerinde belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarının içeriğini yeniden boyutlandırır. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. İçeriğin yeni boyutu varsayılan boşluk birimlerinde belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents(\"input.pdf\", \"output.pdf\", //belge içindeki tüm sayfaları yeniden boyutlandır null, //yeni içerik genişliği = 200 200, //yeni içerik yüksekliği = 300 300); // sayfanın kalan alanı boş olacaktır </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgedeki sayfaların içeriğini yeniden boyutlandırır. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzde olarak belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizePct(src, dest, //belge içindeki tüm sayfaları yeniden boyutlandır null, //yeni içerik genişliği = başlangıç boyutunun %60'ı 60, //yeni içerik yüksekliği = başlangıç boyutunun %60'ı 60); // Sayfanın kalan alanı boş olacaktır (sayfa kenar boşlukları). Sol ve sağ kenar boşluklarının boyutu (100% - 60%) / 2 = %20 // Üst ve alt kenar boşlukları için de aynı. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzde olarak belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct(\"input.pdf\", \"output.pdf\", //belge içindeki tüm sayfaları yeniden boyutlandır null, //yeni içerik genişliği = başlangıç boyutunun %60'ı 60, //yeni içerik yüksekliği = başlangıç boyutunun %60'ı 60); // Sayfanın kalan alanı boş olacaktır (sayfa kenar boşlukları). Sol ve sağ kenar boşluklarının boyutu (100% - 60%) / 2 = %20 // Üst ve alt kenar boşlukları için de aynı. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarını yeniden boyutlandırır. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Belgenin sayfalarını yeniden boyutlandırır. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> True olarak ayarlanırsa, hata oluştuğunda istisnalar fırlatılır. Aksi takdirde istisnalar fırlatılmaz ve yöntemler başarısız olduğunda false döner. </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını ayarlar. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> True olarak ayarlanırsa, akışlar işlem sonrası kapatılır. </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | UseDiskBuffer true olarak ayarlandığında, birleştirme sırasında yeni artımlı güncelleme yapılmadan önce birleştirilen belge sayısı. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpServletResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını ayarlar. Olası değerler: inline / attachment. Varsayılan: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF dosya formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse dosya, dönüşüm olmadan varsayılan PDF formatında kaydedilir. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | True ise, birleştirme gerçekleştirildiğinde dosyanın mantıksal yapısı kopyalanır. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | True ise, anahatlar kopyalanır. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar. Olası değerler: StopWithError ve ConcatenateIgnoringCorrupted. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Birleştirme sırasında çalışan ve iç birleştirme aşamalarının olaylarını dış müşteri koduna çeviren dahili ilerleme olayları işlemcisinin temsili. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | True ise, birleştirme sırasında artımlı güncellemeler yapılır. |
| [setKeepActions](#setKeepActions-boolean-) | True ise, eylemler kaynak belgelerden kopyalanır. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | True ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilir. Alan adlarına ekler eklenir, ek şablonu UniqueSuffix özelliğinde belirtilebilir. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Bu özellik true ise, aynı ada sahip birleştirilen belgelerin isteğe bağlı içerikleri sonuç belgesinde tek bir katmana birleştirilir. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | True ise, yinelenen anahatlar birleştirilir. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Optimizasyon bayrağını alır veya ayarlar. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Kaynak PDF dosyası şifreli ise sahibinin şifresini ayarlar. Bu özellik henüz uygulanmadı. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpServletResponse olarak kaydedildiğinde kaydetme seçeneklerini ayarlar. Varsayılan değer: PdfSaveOptions. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka plan görüntülerini, yan yana yerleştirilen birkaç aynı döşeme arka plan görüntüsünden oluşturulmuş şekilde içerir. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> Formlar birleştirildiğinde alan adına eklenen ve onu benzersiz kılan sonek formatını ayarlayın. Bu dize, sayılarla değiştirilecek %NUM% alt dizesini içermelidir. Örneğin UniqueSuffix = \"ABC%NUM%\" ise, \"fieldName\" alanı için adlar: fieldNameABC1, fieldNameABC2, fieldNameABC3 vb. olacaktır. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( \"_%NUM%\"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Bu seçenek kullanılırsa, hedef belge periyodik olarak diske kaydedilecek ve sonraki birleştirmeler artımlı güncellemeler olarak uygulanacaktır. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> Başlangıçtan belirtilen konuma kadar bölerek ön kısmı çıktı akışına kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Bu işlemden sonra akışlar KAPATILMAZ. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> Pdf dosyasını ilk sayfadan belirtilen konuma kadar bölerek ön kısmı yeni bir dosya olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst(\"input.pdf\", 5, \"out.pdf\"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> Belirtilen konumdan itibaren bölerek arka kısmı yeni bir dosya akışı olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> CloseConcatedStreams belirtilmediği sürece bu işlemden sonra akışlar KAPATILMAZ. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> Belirtilen konumdan itibaren bölerek arka kısmı yeni bir dosya olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd(\"input.pdf\", 5, \"out.pdf\"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | Pdf dosyasını tek sayfalık belgelere böler. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder. |
| [splitToPages](#splitToPages-java.lang.String-) | PDF dosyasını tek sayfalı belgelere böler. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder. |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

PdfFileEditor yapıcı.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan uzay birimlerinde belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları varsayılan uzay birimlerinde belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları sayfa boyutunun yüzde olarak belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileInputStream("output.pdf"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Sayfa içeriğini yeniden boyutlandırır ve belirtilen kenar boşluklarını ekler. Kenar boşlukları sayfa boyutunun yüzde olarak belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct("input.pdf", "output.pdf", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Belge sayfalarına sayfa sonları ekler.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Belge sayfalarına sayfa sonları ekler.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Belge sayfalarına sayfa sonları ekler.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Belge sayfalarına sayfa sonları ekler.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> Sayfaları ekler, portStreams içindeki belge dizisinden seçilen. Sonuç belgesi, firstInputFile ve tüm portStreams belgelerinin startPage ile endPage arasındaki sayfalarını içerir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Sayfaları ekler, portStream içindeki startPage ile endPage arasındaki aralıktan seçilen, portStream içinde firstInputStream'in sonunda. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> Sayfaları ekler, portFiles belgelerinden seçilen. Sonuç belgesi, firstInputFile ve tüm portFiles belgelerinin startPage ile endPage arasındaki sayfalarını içerir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> Sayfaları ekler, portFile içindeki startPage ile endPage arasındaki aralıktan seçilen, portFile içinde firstInputFile'in sonunda. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Belgeleri birleştirir.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> Dosyaları birleştirir </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> İki Pdf belgesini, sayfalar alternatif şekilde yeni bir Pdf belgesine birleştirir ve boş yerleri boş sayfalarla doldurur. ör.: document1 5 sayfaya sahiptir: p1, p2, p3, p4, p5. document2 3 sayfaya sahiptir: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sonuç belgesini şu sayfalarla üretir: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> İki dosyayı birleştirir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> Dosyaları tek bir dosyada birleştirir. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> İki dosyayı birleştirir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> İki Pdf belgesini, sayfalar alternatif şekilde yeni bir Pdf belgesine birleştirir ve boş yerleri boş sayfalarla doldurur. ör.: document1 5 sayfaya sahiptir: p1, p2, p3, p4, p5. document2 3 sayfaya sahiptir: p1', p2', p3'. İki Pdf belgesinin birleştirilmesi, sonuç belgesini şu sayfalarla üretir: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Girdi dosyasından, sayı dizisiyle belirtilen sayfaları siler ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> Girdi dosyasından, sayı dizisiyle belirtilen sayfaları siler ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Sayı dizisiyle belirtilen sayfaları çıkarır ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Girdi dosyasından sayfaları çıkarır ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> Sayı dizisiyle belirtilen sayfaları çıkarır ve yeni bir PDF dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> Girdi dosyasından sayfaları çıkarır ve yeni bir Pdf dosyası olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> True olarak ayarlanırsa, hata oluştuğunda istisnalar fırlatılır. Aksi takdirde istisnalar fırlatılmaz ve yöntemler başarısız olduğunda false döner. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
boolean değer @deprecated Bu özellik kullanımdan kaldırılmıştır ve istisna fırlatılmasına izin vermek için kullanılamaz.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır.

**Returns:**
String değeri

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

İşlemin sonucu HttpServletResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır. Olası değerler: inline / attachment. Varsayılan: inline.

**Returns:**
ContentDisposition öğesi @see ContentDisposition

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

Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar. Olası değerler: StopWithError ve ConcatenateIgnoringCorrupted.

**Returns:**
ConcatenateCorruptedFileAction ögesi @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> Birleştirme gerçekleştirildiğinde karşılaşılan sorunların dizisi. Concatenate() fonksiyonuna geçirilen her bozuk belge için yeni bir CorruptedItem girdisi oluşturulur. Bu özellik yalnızca CorruptedFileAction ConcatenateIgnoringCorrupted olduğunda kullanılabilir. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre>

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

True ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilir. Alan adlarına ekler eklenir, ek şablonu UniqueSuffix özelliğinde belirtilebilir.

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

Kaynak girdi Pdf dosyası şifreli ise sahibinin şifresini alır. Bu özellik henüz uygulanmadı.

**Returns:**
String değeri

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Doğru ise, ilk belgenin kullanıcı hakları birleştirilmiş belgeye uygulanır.

**Returns:**
boolean değer

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz.

**Returns:**
boolean değer

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Sonuç HttpServletResponse olarak depolandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions.

**Returns:**
SaveOptions nesnesi

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Formlar birleştirildiğinde alan adını benzersiz kılmak için alan adına eklenen sonek formatını alın. Bu dize %NUM% alt dizesini içermelidir ve bu alt dize sayılarla değiştirilecektir. Örneğin UniqueSuffix = "ABC%NUM%" ise, "fieldName" alanı için adlar: fieldNameABC1, fieldNameABC2, fieldNameABC3 vb. olacaktır.

**Returns:**
String değeri

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> Diğer bir dosyadan sayfaları giriş PDF dosyasına ekler. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> Diğer bir dosyadan sayfaları PDF dosyasına bir konumda ekler. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre>

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
<p> InputStream'den outputStream'e kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> firstInputStream'den outputStream'e özelleştirilmiş kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> Giriş akışından kitapçık oluşturur ve sonucu çıkış akışına kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> firstInputStream'den outputStream'e kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> Giriş dosyasından çıkış dosyasına kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> firstInputFile'den outputFile'e özelleştirilmiş kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> inputFile dosyasından outputFile dosyasına bir kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> firstInputFile dosyasından outputFile dosyasına özelleştirilmiş bir kitapçık oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> çoklu giriş PDF akışlarından outputStream'e N‑Up belge oluşturur. outputStream'in her sayfası, aynı sayfa numarasına sahip giriş akışlarındaki sayfalarla birleştirilmiş çoklu sayfalar içerir. isSidewise true ise çoklu sayfalar yatay olarak, false ise dikey olarak yığılır. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> iki giriş PDF akışından outputStream'e N‑Up belge oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> giriş akışından N‑Up belge oluşturur ve sonucu çıktı akışına kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> ilk giriş akışından çıktı akışına N‑Up belge oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> çoklu giriş PDF dosyalarından outputFile'a N‑Up belge oluşturur. outputFile'ın her sayfası, aynı sayfa numarasına sahip giriş dosyalarındaki sayfalarla birleştirilmiş çoklu sayfalar içerir. isSidewise true ise çoklu sayfalar yatay, false ise dikey olarak yığılır. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> firstInputFile dosyasından outputFile dosyasına N‑Up belge oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> giriş dosyasından outputFile dosyasına N‑Up belge oluşturur. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> iki giriş PDF dosyasından outputFile dosyasına N‑Up belge oluşturur. outputFile'ın her sayfası iki sayfa içerir, bir sayfa ilk giriş dosyasından, diğeri ikinci giriş dosyasından. Bu iki sayfa yatay olarak yığılır. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarını yeniden boyutlandırır.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarını yeniden boyutlandırır.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfa içeriğini küçültür ve kenar boşlukları ekler. İçeriğin yeni boyutu varsayılan uzay birimlerinde belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarının içeriğini yeniden boyutlandırır.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. İçeriğin yeni boyutu varsayılan boşluk birimlerinde belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents(\"input.pdf\", \"output.pdf\", //belge içindeki tüm sayfaları yeniden boyutlandır null, //yeni içerik genişliği = 200 200, //yeni içerik yüksekliği = 300 300); // sayfanın kalan alanı boş olacaktır </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgedeki sayfaların içeriğini yeniden boyutlandırır.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzde olarak belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizePct(src, dest, //belge içindeki tüm sayfaları yeniden boyutlandır null, //yeni içerik genişliği = başlangıç boyutunun %60'ı 60, //yeni içerik yüksekliği = başlangıç boyutunun %60'ı 60); // Sayfanın kalan alanı boş olacaktır (sayfa kenar boşlukları). Sol ve sağ kenar boşluklarının boyutu (100% - 60%) / 2 = %20 // Üst ve alt kenar boşlukları için de aynı. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> Belge sayfalarının içeriğini yeniden boyutlandırır. Sayfanın içeriğini küçültür ve kenar boşlukları ekler. Yeni içerik boyutu yüzde olarak belirtilir. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct(\"input.pdf\", \"output.pdf\", //belge içindeki tüm sayfaları yeniden boyutlandır null, //yeni içerik genişliği = başlangıç boyutunun %60'ı 60, //yeni içerik yüksekliği = başlangıç boyutunun %60'ı 60); // Sayfanın kalan alanı boş olacaktır (sayfa kenar boşlukları). Sol ve sağ kenar boşluklarının boyutu (100% - 60%) / 2 = %20 // Üst ve alt kenar boşlukları için de aynı. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarını yeniden boyutlandırır.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Belgenin sayfalarını yeniden boyutlandırır.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> True olarak ayarlanırsa, hata oluştuğunda istisnalar fırlatılır. Aksi takdirde istisnalar fırlatılmaz ve yöntemler başarısız olduğunda false döner. </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değeri <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated Bu özellik kullanımdan kaldırılmıştır ve istisna fırlatılmasına izin vermek için kullanılamaz. |

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpServletResponse nesnelerine ek olarak kaydedildiğinde ekin adını ayarlar.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> True olarak ayarlanırsa, akışlar işlem sonrası kapatılır. </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değeri <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

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
İşlemin sonucu HttpServletResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını ayarlar. Olası değerler: inline / attachment. Varsayılan: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF dosya formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse dosya, dönüşüm olmadan varsayılan PDF formatında kaydedilir.

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

Bu özellik, birleştirme işlemi bozuk bir dosyayla karşılaştığında davranışı tanımlar. Olası değerler: StopWithError ve ConcatenateIgnoringCorrupted.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değeri @see ConcatenateCorruptedFileAction |

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

True ise, formlar birleştirildiğinde alan adları benzersiz hâle getirilir. Alan adlarına ekler eklenir, ek şablonu UniqueSuffix özelliğinde belirtilebilir.

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
Kaynak PDF dosyası şifreli ise sahibinin şifresini ayarlar. Bu özellik henüz uygulanmadı.

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
public final void setRemoveSignatures(boolean value)
```

Doğru ise, tüm imzalar alanlardan kaldırılacak (alanlar kalacaktır); aksi takdirde geçersiz imzalar elde edebilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpServletResponse olarak kaydedildiğinde kaydetme seçeneklerini ayarlar. Varsayılan değer: PdfSaveOptions.

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
<p> Formlar birleştirildiğinde alan adına eklenen ve onu benzersiz kılan sonek formatını ayarlayın. Bu dize, sayılarla değiştirilecek %NUM% alt dizesini içermelidir. Örneğin UniqueSuffix = \"ABC%NUM%\" ise, \"fieldName\" alanı için adlar: fieldNameABC1, fieldNameABC2, fieldNameABC3 vb. olacaktır. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( \"_%NUM%\"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Bu seçenek kullanılırsa, hedef belge periyodik olarak diske kaydedilecek ve sonraki birleştirmeler artımlı güncellemeler olarak uygulanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> Başlangıçtan belirtilen konuma kadar bölerek ön kısmı çıktı akışına kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Bu işlemden sonra akışlar KAPATILMAZ.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> Pdf dosyasını ilk sayfadan belirtilen konuma kadar bölerek ön kısmı yeni bir dosya olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst(\"input.pdf\", 5, \"out.pdf\"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Pdf dosyasını birkaç belgeye böler. Belgeler tek sayfalı veya çok sayfalı olabilir.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> Belirtilen konumdan itibaren bölerek arka kısmı yeni bir dosya akışı olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream(\"file1.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> CloseConcatedStreams belirtilmediği sürece bu işlemden sonra akışlar KAPATILMAZ.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> Belirtilen konumdan itibaren bölerek arka kısmı yeni bir dosya olarak kaydeder. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd(\"input.pdf\", 5, \"out.pdf\"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
Pdf dosyasını tek sayfalık belgelere böler.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder.

### splitToPages {#splitToPages-java.lang.String-}
PDF dosyasını tek sayfalı belgelere böler.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Pdf dosyasını tek sayfalı belgelere bölerek belirtilen yola kaydeder.
