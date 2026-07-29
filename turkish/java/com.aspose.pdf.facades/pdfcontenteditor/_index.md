---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF dosyasının içeriğini düzenlemek için bir sınıfı temsil eder."
type: docs
weight: 380
url: /tr/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

PDF dosyasının içeriğini düzenlemek için bir sınıfı temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | Bir belge olayı türü. Bir belgeyi kapatır. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | Bir belge olayı türü. Bir belgeyi açar. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | Bir belge olayı türü. Yazdırma işleminden sonra bir eylemi yürütür. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | Bir belge olayı türü. Kaydetme işleminden sonra bir eylemi yürütür. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | Bir belge olayı türü. Yazdırma işleminden önce bir eylemi yürütür. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | Bir belge olayı türü. Kaydetme işleminden önce bir eylemi yürütür. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | PdfContentEditor nesnesinin yapıcı yöntemi. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | PdfContentEditor nesnesinin yapıcı yöntemi. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> Belge olayı için ek bir eylem ekler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> Belgeye ek açıklama olmadan ek dosya ekler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> Belgeye ek açıklama olmadan ek dosya ekler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | Düzenleme için bir PDF akışı bağlar. |
| [bindPdf](#bindPdf-java.lang.String-) | Düzenleme için bir PDF dosyası bağlar. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> Görünüm tercihini değiştirir. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | Açılan belgeyi kapatır. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Belirtilen eyleme sahip bir yer imi oluşturur. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | İmleç açıklaması oluşturur. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | PDF belgesinde özel eylemlere bir bağlantı oluşturur. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Dosya ek açıklaması oluşturur. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Dosya ek açıklaması oluşturur. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | PDF belgesinde serbest metin açıklaması oluşturur |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | PDF belgesinde JavaScript'e bir bağlantı oluşturur. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | Çizgi açıklaması oluşturur. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | PDF belgesinde yerel bir bağlantı oluşturur. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | PDF belgesinde yerel bir bağlantı oluşturur. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | PDF belgesinde yerel bir bağlantı oluşturur. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | PDF belgesinde işaretleme açıklaması oluşturur. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Başka bir PDF belgesi sayfasına bir bağlantı oluşturur. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Başka bir PDF belgesi sayfasına bir bağlantı oluşturur. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Başka bir PDF belgesi sayfasına bir bağlantı oluşturur. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Poligon açıklaması oluşturur. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Çoklu çizgi açıklaması oluşturur. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | PDF belgesinde açılır pencere açıklaması oluşturur. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Kauçuk damga açıklaması oluşturur. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Kauçuk damga açıklaması oluşturur. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Kauçuk damga açıklaması oluşturur. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Kare-daire açıklaması oluşturur. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | PDF belgesinde metin açıklaması oluşturur |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | PDF belgesinde bir web bağlantısı oluşturur. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | PDF belgesinde bir web bağlantısı oluşturur. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | PDF belgesinde bir web bağlantısı oluşturur. |
| [deleteAttachments](#deleteAttachments--) | <p> PDF belgesindeki tüm ekleri siler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> PDF belgesindeki tüm görüntüleri siler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> Belirtilen sayfadaki belirtilen görüntüleri siler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> Belirtilen sayfada damga indekslerine göre birden fazla damgayı siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> Belgenin tüm sayfalarından kimliğe göre damgayı siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> Belirtilen sayfadaki damgayı kimliğe göre siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> Belgenin tüm sayfalarından belirtilen kimliklere sahip damgaları siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> Belirtilen sayfada birden fazla damga kimliğiyle damgaları siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Eğri açıklaması oluşturur. |
| [extractLink](#extractLink--) | <p> PDF belgesinde bulunan Link örneklerinin koleksiyonunu çıkarır. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | Metin değiştirme işlemi için bir dizi parametre al. |
| [getStamps](#getStamps-int-) | Sayfadaki damgaların dizisini döndürür. |
| [getTextEditOptions](#getTextEditOptions--) | Metin düzenleme seçeneklerini alır. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Metin değiştirme seçeneklerini alır. |
| [getTextSearchOptions](#getTextSearchOptions--) | Metin arama seçeneklerini alır. |
| [getViewerPreference](#getViewerPreference--) | <p> Görünüm tercihlerini döndürür. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | Damgayı gizler. Gizlendikten sonra damga görünürlüğü ShowStampById yöntemiyle geri getirilebilir. |
| [moveStamp](#moveStamp-int-int-double-double-) | Sayfadaki damganın konumunu değiştirir. |
| [moveStampById](#moveStampById-int-int-double-double-) | Sayfadaki damganın konumunu değiştirir. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> Belgeden açılış eylemini kaldırır. Bu işlem, başlangıçta açıkça 'GoTo' eylemi kullanan birden fazla belge birleştirildiğinde faydalıdır. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> PDF belgesinin belirtilen sayfasındaki belirtilen görüntüyü başka bir görüntüyle değiştirir. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. </p> <hr> <pre> Örnek, belirtilen sayfada PDF belgesindeki metnin nasıl değiştirileceğini gösterir. // belgeyi aç Document doc = new Document(inFile); // metni düzenlemek için PdfContentEditor nesnesi oluştur PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // metni değiştir editor.replaceText("hello world", 1, "hi world"); // belgeyi kaydet doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // belirtilen yazı tipiyle metni değiştir editor.replaceText("hello world", 1, "hi world", textState); // belgeyi kaydet doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> PDF dosyasındaki metni değiştirir. </p> <hr> <pre> Bu örnek, PDF belgesindeki metni nasıl değiştireceğinizi gösterir. Varsayılan olarak, bulunan ilk metni değiştirir. // belgeyi aç Document doc = new Document(inFile); // metni düzenlemek için PdfContentEditor nesnesi oluştur PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // metni değiştir editor.replaceText("hello world", "hi world"); // belgeyi kaydet doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> PDF dosyasındaki metni değiştirir ve yazı tipi boyutunu ayarlar. </p> <hr> <pre> Bu örnek, yeni metin için metni nasıl değiştireceğinizi ve yazı tipi boyutunu nasıl ayarlayacağınızı gösterir. // belgeyi aç Document doc = new Document(inFile); // yazı tipini oluştur ve gömülü olmasını işaretle com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // metni düzenlemek için PdfContentEditor nesnesi oluştur PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // belirtilen yazı tipiyle metni değiştir editor.replaceText("hello world", "hi world", 14); // belgeyi kaydet doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // belirtilen yazı tipiyle metni değiştir editor.replaceText("hello world", "hi world", textState); // belgeyi kaydet doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Metin değiştirme işlemi için bir dizi parametre ayarla |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Metin düzenleme seçeneklerini ayarlar. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Metin değiştirme seçeneklerini ayarlar. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Metin arama seçeneklerini ayarlar. |
| [showStampById](#showStampById-int-int-) | HiddenStampById tarafından gizlenen damgayı gösterir. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

Bir belge olayı türü. Bir belgeyi kapatır.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

Bir belge olayı türü. Bir belgeyi açar.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

Bir belge olayı türü. Yazdırma işleminden sonra bir eylemi yürütür.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

Bir belge olayı türü. Kaydetme işleminden sonra bir eylemi yürütür.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

Bir belge olayı türü. Yazdırma işleminden önce bir eylemi yürütür.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

Bir belge olayı türü. Kaydetme işleminden önce bir eylemi yürütür.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

PdfContentEditor nesnesinin yapıcı yöntemi.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
PdfContentEditor nesnesinin yapıcı yöntemi.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> Belge olayı için ek bir eylem ekler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> Belgeye ek açıklama olmadan ek dosya ekler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> Belgeye ek açıklama olmadan ek dosya ekler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
Düzenleme için bir PDF akışı bağlar.

### bindPdf {#bindPdf-java.lang.String-}
Düzenleme için bir PDF dosyası bağlar.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> Görünüm tercihini değiştirir. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| viewerAttribution |  | ViewerPreference sınıfında tanımlanan görünüm atıfı. |

### close {#close--}
```
public void close()
```

Açılan belgeyi kapatır.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
PDF belgesinde bir uygulamayı başlatmak için bir bağlantı oluşturur.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
Belirtilen eyleme sahip bir yer imi oluşturur.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
İmleç açıklaması oluşturur.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
PDF belgesinde özel eylemlere bir bağlantı oluşturur.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
Dosya ek açıklaması oluşturur.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
Dosya ek açıklaması oluşturur.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
PDF belgesinde serbest metin açıklaması oluşturur

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
PDF belgesinde JavaScript'e bir bağlantı oluşturur.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
Çizgi açıklaması oluşturur.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
PDF belgesinde yerel bir bağlantı oluşturur.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
PDF belgesinde yerel bir bağlantı oluşturur.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
PDF belgesinde yerel bir bağlantı oluşturur.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
PDF belgesinde işaretleme açıklaması oluşturur.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
Başka bir PDF belgesi sayfasına bir bağlantı oluşturur.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Başka bir PDF belgesi sayfasına bir bağlantı oluşturur.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Başka bir PDF belgesi sayfasına bir bağlantı oluşturur.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Poligon açıklaması oluşturur.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Çoklu çizgi açıklaması oluşturur.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
PDF belgesinde açılır pencere açıklaması oluşturur.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
Kauçuk damga açıklaması oluşturur.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
Kauçuk damga açıklaması oluşturur.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Kauçuk damga açıklaması oluşturur.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
Kare-daire açıklaması oluşturur.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
PDF belgesinde metin açıklaması oluşturur

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
PDF belgesinde bir web bağlantısı oluşturur.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
PDF belgesinde bir web bağlantısı oluşturur.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
PDF belgesinde bir web bağlantısı oluşturur.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> PDF belgesindeki tüm ekleri siler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> PDF belgesindeki tüm görüntüleri siler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> Belirtilen sayfadaki belirtilen görüntüleri siler. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Görsellerin silinmesi gereken sayfa numarası. |
| index |  | Görsellerin indekslerini temsil eden bir dizi. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> Belirtilen sayfada damga indekslerine göre birden fazla damgayı siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Damganın silineceği sayfa numarası. |
| index |  | Damga indeksleri. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> Belgenin tüm sayfalarından kimliğe göre damgayı siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stampId |  | Silinmesi gereken damganın tanımlayıcısı. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> Belirtilen sayfadaki damgayı kimliğe göre siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Damganın silineceği sayfa numarası. |
| stampId |  | Silinmesi gereken damganın tanımlayıcısı. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> Belgenin tüm sayfalarından belirtilen kimliklere sahip damgaları siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stampIds |  | Damga kimliklerinin dizisi. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> Belirtilen sayfada birden fazla damga kimliğiyle damgaları siler. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Damgaların silineceği sayfa numarası. |
| stampIds |  | Damga kimliklerinin dizisi. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Eğri açıklaması oluşturur.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> PDF belgesinde bulunan Link örneklerinin koleksiyonunu çıkarır. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre>

**Returns:**
Link nesnelerinin koleksiyonu

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

Metin değiştirme işlemi için bir dizi parametre al.

**Returns:**
ReplaceTextStrategy öğesi

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

Sayfadaki damgaların dizisini döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Damgaların aranacağı sayfa numarası. |

**Returns:**
Damgaların dizisi.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Metin düzenleme seçeneklerini alır.

**Returns:**
TextEditOptions öğesi

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Metin değiştirme seçeneklerini alır.

**Returns:**
TextReplaceOptions öğesi

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Metin arama seçeneklerini alır.

**Returns:**
TextSearchOptions öğesi

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> Görünüm tercihlerini döndürür. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
ViewerPrefernece bayraklarının kümesini döndürür

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

Damgayı gizler. Gizlendikten sonra damga görünürlüğü ShowStampById yöntemiyle geri getirilebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Sayfanın numarası. |
| stampId |  | Gizlenmesi gereken damganın tanımlayıcısı. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

Sayfadaki damganın konumunu değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Sayfa numarası. |
| stampIndex |  | Sayfadaki damganın indeksi. |
| x |  | Yeni damganın yatay konumu. |
| y |  | Yeni damganın dikey konumu. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

Sayfadaki damganın konumunu değiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Sayfa numarası. |
| stampId |  | Taşınması gereken damganın tanımlayıcısı. |
| x |  | Sayfada yeni damganın yatay konumu. |
| y |  | Sayfada yeni damganın dikey konumu. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> Belgeden açılış eylemini kaldırır. Bu işlem, başlangıçta açıkça 'GoTo' eylemi kullanan birden fazla belge birleştirildiğinde faydalıdır. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> PDF belgesinin belirtilen sayfasındaki belirtilen görüntüyü başka bir görüntüyle değiştirir. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> Belirtilen sayfadaki PDF dosyasındaki metni değiştirir. </p> <hr> <pre> Örnek, belirtilen sayfada PDF belgesindeki metnin nasıl değiştirileceğini gösterir. // belgeyi aç Document doc = new Document(inFile); // metni düzenlemek için PdfContentEditor nesnesi oluştur PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // metni değiştir editor.replaceText("hello world", 1, "hi world"); // belgeyi kaydet doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> Belirtilen sayfada PDF dosyasındaki metni değiştirir. {@code TextState} nesnesi (yazı tipi ailesi, renk) değiştirilecek metin için belirtilebilir. </p> <hr> <pre> Örnek, PDF belgesinin ilk sayfasındaki metni nasıl değiştireceğinizi ve yeni metin için {@code TextState} metin özelliklerini nasıl ayarlayacağınızı gösterir. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // change text with specified font editor.replaceText("hello world", 1, "hi world", textState); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> PDF dosyasındaki metni değiştirir. </p> <hr> <pre> Bu örnek, PDF belgesindeki metni nasıl değiştireceğinizi gösterir. Varsayılan olarak, bulunan ilk metni değiştirir. // belgeyi aç Document doc = new Document(inFile); // metni düzenlemek için PdfContentEditor nesnesi oluştur PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // metni değiştir editor.replaceText("hello world", "hi world"); // belgeyi kaydet doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> PDF dosyasındaki metni değiştirir ve yazı tipi boyutunu ayarlar. </p> <hr> <pre> Bu örnek, yeni metin için metni nasıl değiştireceğinizi ve yazı tipi boyutunu nasıl ayarlayacağınızı gösterir. // belgeyi aç Document doc = new Document(inFile); // yazı tipini oluştur ve gömülü olmasını işaretle com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // metni düzenlemek için PdfContentEditor nesnesi oluştur PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // belirtilen yazı tipiyle metni değiştir editor.replaceText("hello world", "hi world", 14); // belgeyi kaydet doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> Belirtilen {@code TextState} nesnesi kullanılarak PDF dosyasındaki metni değiştirir. </p> <hr> <pre> Örnek, metni nasıl değiştireceğinizi ve yeni metin için {@code TextState} metin özelliklerini nasıl ayarlayacağınızı gösterir. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // change text with specified font editor.replaceText("hello world", "hi world", textState); // save document doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
Metin değiştirme işlemi için bir dizi parametre ayarla

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Metin düzenleme seçeneklerini ayarlar.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Metin değiştirme seçeneklerini ayarlar.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Metin arama seçeneklerini ayarlar.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

HiddenStampById tarafından gizlenen damgayı gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber |  | Sayfanın numarası. |
| stampId |  | Gösterilmesi gereken damganın tanımlayıcısı. |
