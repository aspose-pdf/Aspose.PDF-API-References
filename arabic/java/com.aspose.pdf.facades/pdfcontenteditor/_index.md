---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لتعديل محتوى ملف PDF."
type: docs
weight: 380
url: /ar/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

يمثل فئة لتعديل محتوى ملف PDF.

## الحقول

| حقل | الوصف |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | نوع حدث المستند. يغلق المستند. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | نوع حدث المستند. يفتح المستند. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | نوع حدث المستند. ينفّذ إجراءً بعد الطباعة. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | نوع حدث المستند. ينفّذ إجراءً بعد الحفظ. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | نوع حدث المستند. ينفّذ إجراءً قبل الطباعة. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | نوع حدث المستند. ينفّذ إجراءً قبل الحفظ. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | المُنشئ لكائن PdfContentEditor. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | المُنشئ لكائن PdfContentEditor. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> يضيف إجراءً إضافيًا لحدث المستند. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> يضيف مرفق مستند بدون توضيح. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> يضيف مرفق مستند بدون توضيح. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | يربط تدفق PDF للتحرير. |
| [bindPdf](#bindPdf-java.lang.String-) | يربط ملف PDF للتحرير. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> يغيّر تفضيل العرض. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | يغلق المستند المفتوح. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | ينشئ رابطًا لتشغيل تطبيق في مستند PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | ينشئ رابطًا لتشغيل تطبيق في مستند PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | ينشئ رابطًا لتشغيل تطبيق في مستند PDF. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | ينشئ إشارة مرجعية بالإجراء المحدد. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | ينشئ توضيح caret. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | ينشئ رابطًا لإجراءات مخصصة في مستند PDF. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | ينشئ توضيح مرفق ملف. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | ينشئ توضيح مرفق ملف. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | ينشئ توضيح نص حر في مستند PDF |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | ينشئ رابطًا إلى JavaScript في مستند PDF. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | ينشئ توضيح خط. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | ينشئ رابطًا محليًا في مستند PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | ينشئ رابطًا محليًا في مستند PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | ينشئ رابطًا محليًا في مستند PDF. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | ينشئ توضيح تعليمات في مستند PDF. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | ينشئ رابطًا إلى صفحة مستند PDF آخر. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | ينشئ رابطًا إلى صفحة مستند PDF آخر. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | ينشئ رابطًا إلى صفحة مستند PDF آخر. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | ينشئ توضيح مضلع. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | ينشئ توضيح خط متعدد. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | ينشئ توضيح منبثق في مستند PDF. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | ينشئ توضيح ختم مطاطي. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | ينشئ توضيح ختم مطاطي. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | ينشئ توضيح ختم مطاطي. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | ينشئ توضيح مربع-دائرة. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | ينشئ توضيح نص في مستند PDF |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | ينشئ رابط ويب في مستند PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | ينشئ رابط ويب في مستند PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | ينشئ رابط ويب في مستند PDF. |
| [deleteAttachments](#deleteAttachments--) | <p> يحذف جميع المرفقات في مستند PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> يحذف جميع الصور من مستند PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> يحذف الصور المحددة في الصفحة المحددة. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> يحذف عدة طوابع في الصفحة المحددة حسب فهارس الطوابع. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> احذف طابعًا حسب المعرف من جميع صفحات المستند. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> يحذف طابعًا في الصفحة المحددة حسب معرف الطابع. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> يحذف طوابع بالمعرفات المحددة من جميع صفحات المستند. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> يحذف طوابع في الصفحة المحددة حسب عدة معرّفات للطوابع. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | ينشئ تعليقا منحنيًا. |
| [extractLink](#extractLink--) | <p> يستخرج مجموعة كائنات Link الموجودة في مستند PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | احصل على مجموعة من المعلمات لعملية استبدال النص |
| [getStamps](#getStamps-int-) | يعيد مصفوفة من الطوابع في الصفحة. |
| [getTextEditOptions](#getTextEditOptions--) | يحصل على خيارات تحرير النص. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | يحصل على خيارات استبدال النص. |
| [getTextSearchOptions](#getTextSearchOptions--) | يحصل على خيارات بحث النص. |
| [getViewerPreference](#getViewerPreference--) | <p> يعيد تفضيل العرض. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | يخفي الطابع. بعد الإخفاء، يمكن استعادة ظهور الطابع باستخدام طريقة ShowStampById. |
| [moveStamp](#moveStamp-int-int-double-double-) | يغيّر موضع الطابع في الصفحة. |
| [moveStampById](#moveStampById-int-int-double-double-) | يغيّر موضع الطابع في الصفحة. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> يزيل إجراء الفتح من المستند. هذه العملية مفيدة عند دمج مستندات متعددة تستخدم إجراء 'GoTo' صريح عند بدء التشغيل. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> يستبدل الصورة المحددة في الصفحة المحددة من مستند PDF بصورة أخرى. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> يستبدل النص في ملف PDF في الصفحة المحددة. </p> <hr> <pre> يوضح المثال كيفية استبدال النص في مستند PDF في الصفحة المحددة. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // تغيير النص باستخدام الخط المحدد editor.replaceText("hello world", 1, "hi world", textState); // حفظ المستند doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> يستبدل النص في ملف PDF. </p> <hr> <pre> المثال يوضح كيفية استبدال النص في مستند PDF. بشكل افتراضي، يستبدل أول نص يتم العثور عليه. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", "hi world"); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> يستبدل النص في ملف PDF ويحدد حجم الخط. </p> <hr> <pre> المثال يوضح كيفية استبدال النص وتحديد حجم الخط للنص الجديد. // open document Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text with specified font editor.replaceText("hello world", "hi world", 14); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // تغيير النص باستخدام الخط المحدد editor.replaceText("hello world", "hi world", textState); // حفظ المستند doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | تعيين مجموعة من المعلمات لعملية استبدال النص |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | يضبط خيارات تحرير النص. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | يضبط خيارات استبدال النص. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | يضبط خيارات البحث عن النص. |
| [showStampById](#showStampById-int-int-) | يعرض الطابع الذي تم إخفاؤه بواسطة HiddenStampById. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

نوع حدث المستند. يغلق المستند.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

نوع حدث المستند. يفتح المستند.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

نوع حدث المستند. ينفّذ إجراءً بعد الطباعة.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

نوع حدث المستند. ينفّذ إجراءً بعد الحفظ.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

نوع حدث المستند. ينفّذ إجراءً قبل الطباعة.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

نوع حدث المستند. ينفّذ إجراءً قبل الحفظ.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

المُنشئ لكائن PdfContentEditor.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
المُنشئ لكائن PdfContentEditor.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> يضيف إجراءً إضافيًا لحدث المستند. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> يضيف مرفق مستند بدون توضيح. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> يضيف مرفق مستند بدون توضيح. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
يربط تدفق PDF للتحرير.

### bindPdf {#bindPdf-java.lang.String-}
يربط ملف PDF للتحرير.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> يغيّر تفضيل العرض. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| viewerAttribution |  | سمة العرض المحددة في فئة ViewerPreference. |

### close {#close--}
```
public void close()
```

يغلق المستند المفتوح.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
ينشئ رابطًا لتشغيل تطبيق في مستند PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
ينشئ رابطًا لتشغيل تطبيق في مستند PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
ينشئ رابطًا لتشغيل تطبيق في مستند PDF.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
ينشئ إشارة مرجعية بالإجراء المحدد.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
ينشئ توضيح caret.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
ينشئ رابطًا لإجراءات مخصصة في مستند PDF.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
ينشئ توضيح مرفق ملف.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
ينشئ توضيح مرفق ملف.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
ينشئ توضيح نص حر في مستند PDF

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
ينشئ رابطًا إلى JavaScript في مستند PDF.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
ينشئ توضيح خط.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
ينشئ رابطًا محليًا في مستند PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
ينشئ رابطًا محليًا في مستند PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
ينشئ رابطًا محليًا في مستند PDF.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
ينشئ توضيح تعليمات في مستند PDF.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
ينشئ رابطًا إلى صفحة مستند PDF آخر.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
ينشئ رابطًا إلى صفحة مستند PDF آخر.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
ينشئ رابطًا إلى صفحة مستند PDF آخر.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
ينشئ توضيح مضلع.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
ينشئ توضيح خط متعدد.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
ينشئ توضيح منبثق في مستند PDF.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
ينشئ توضيح ختم مطاطي.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
ينشئ توضيح ختم مطاطي.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
ينشئ توضيح ختم مطاطي.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
ينشئ توضيح مربع-دائرة.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
ينشئ توضيح نص في مستند PDF

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
ينشئ رابط ويب في مستند PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
ينشئ رابط ويب في مستند PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
ينشئ رابط ويب في مستند PDF.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> يحذف جميع المرفقات في مستند PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> يحذف جميع الصور من مستند PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> يحذف الصور المحددة في الصفحة المحددة. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | عدد الصفحة التي يجب حذف الصور منها. |
| index |  | مصفوفة تمثل فهارس الصور. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> يحذف عدة طوابع في الصفحة المحددة حسب فهارس الطوابع. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة التي سيتم حذف الطابع منها. |
| index |  | فهارس الطوابع. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> احذف طابعًا حسب المعرف من جميع صفحات المستند. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stampId |  | معرف الطابع الذي يجب حذفه. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> يحذف طابعًا في الصفحة المحددة حسب معرف الطابع. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة التي سيتم حذف الطابع منها. |
| stampId |  | معرف الطابع الذي يجب حذفه. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> يحذف طوابع بالمعرفات المحددة من جميع صفحات المستند. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stampIds |  | مصفوفة معرفات الطوابع. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> يحذف طوابع في الصفحة المحددة حسب عدة معرّفات للطوابع. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة التي سيتم حذف الطوابع منها. |
| stampIds |  | مصفوفة معرفات الطوابع. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
ينشئ تعليقا منحنيًا.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> يستخرج مجموعة كائنات Link الموجودة في مستند PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre>

**Returns:**
مجموعة كائنات Link

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

احصل على مجموعة من المعلمات لعملية استبدال النص

**Returns:**
عنصر ReplaceTextStrategy

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

يعيد مصفوفة من الطوابع في الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة التي سيتم البحث عن الطوابع فيها. |

**Returns:**
مصفوفة الطوابع.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

يحصل على خيارات تحرير النص.

**Returns:**
عنصر TextEditOptions

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

يحصل على خيارات استبدال النص.

**Returns:**
عنصر TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

يحصل على خيارات بحث النص.

**Returns:**
عنصر TextSearchOptions

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> يعيد تفضيل العرض. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
يعيد مجموعة من أعلام ViewerPrefernece

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

يخفي الطابع. بعد الإخفاء، يمكن استعادة ظهور الطابع باستخدام طريقة ShowStampById.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة. |
| stampId |  | معرف الطابع الذي يجب إخفاؤه. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

يغيّر موضع الطابع في الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة. |
| stampIndex |  | فهرس الطابع في الصفحة. |
| x |  | الموضع الأفقي للطابع الجديد. |
| y |  | الموضع الرأسي للطابع الجديد. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

يغيّر موضع الطابع في الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة. |
| stampId |  | معرف الطابع الذي يجب تحريكه. |
| x |  | الموضع الأفقي للطابع الجديد في الصفحة. |
| y |  | الموضع الرأسي للطابع الجديد في الصفحة. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> يزيل إجراء الفتح من المستند. هذه العملية مفيدة عند دمج مستندات متعددة تستخدم إجراء 'GoTo' صريح عند بدء التشغيل. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> يستبدل الصورة المحددة في الصفحة المحددة من مستند PDF بصورة أخرى. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> يستبدل النص في ملف PDF في الصفحة المحددة. </p> <hr> <pre> يوضح المثال كيفية استبدال النص في مستند PDF في الصفحة المحددة. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> يستبدل النص في ملف PDF في الصفحة المحددة. يمكن تحديد كائن {@code TextState} (عائلة الخط، اللون) للنص المستبدل. </p> <hr> <pre> يوضح المثال كيفية استبدال النص في الصفحة الأولى من مستند PDF وتعيين خصائص النص {@code TextState} للنص الجديد. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // change text with specified font editor.replaceText("hello world", 1, "hi world", textState); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> يستبدل النص في ملف PDF. </p> <hr> <pre> المثال يوضح كيفية استبدال النص في مستند PDF. بشكل افتراضي، يستبدل أول نص يتم العثور عليه. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", "hi world"); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> يستبدل النص في ملف PDF ويحدد حجم الخط. </p> <hr> <pre> المثال يوضح كيفية استبدال النص وتحديد حجم الخط للنص الجديد. // open document Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text with specified font editor.replaceText("hello world", "hi world", 14); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> يستبدل النص في ملف PDF باستخدام كائن {@code TextState} المحدد. </p> <hr> <pre> يوضح المثال كيفية استبدال النص وتعيين خصائص النص {@code TextState} للنص الجديد. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // change text with specified font editor.replaceText("hello world", "hi world", textState); // save document doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
تعيين مجموعة من المعلمات لعملية استبدال النص

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
يضبط خيارات تحرير النص.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
يضبط خيارات استبدال النص.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
يضبط خيارات البحث عن النص.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

يعرض الطابع الذي تم إخفاؤه بواسطة HiddenStampById.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber |  | رقم الصفحة. |
| stampId |  | معرف الطابع الذي يجب إظهاره. |
