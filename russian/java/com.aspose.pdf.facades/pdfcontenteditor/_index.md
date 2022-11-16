---
title: PdfContentEditor
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для редактирования содержимого файлов PDF.
type: docs
weight: 36
url: /ru/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfContentEditor extends SaveableFacade
```

Представляет класс для редактирования содержимого файла PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfContentEditor()](#PdfContentEditor--) | Конструктор объекта PdfContentEditor. |
| [PdfContentEditor(IDocument document)](#PdfContentEditor-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfContentEditor на основе документа. |
## Поля

| Поле | Описание |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT-CLOSE) | Тип события документа. |
| [DOCUMENT_OPEN](#DOCUMENT-OPEN) | Тип события документа. |
| [DOCUMENT_PRINTED](#DOCUMENT-PRINTED) | Тип события документа. |
| [DOCUMENT_SAVED](#DOCUMENT-SAVED) | Тип события документа. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT-WILL-PRINT) | Тип события документа. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT-WILL-SAVE) | Тип события документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [addDocumentAdditionalAction(String eventType, String code)](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | Добавляет дополнительное действие для события документа. |
| [addDocumentAttachment(InputStream fileAttachmentStream, String fileAttachmentName, String description)](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | Добавляет вложение документа без аннотации. |
| [addDocumentAttachment(String fileAttachmentPath, String description)](#addDocumentAttachment-java.lang.String-java.lang.String-) | Добавляет вложение документа без аннотации. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Связывает поток PDF для редактирования. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Связывает файл PDF для редактирования. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [changeViewerPreference(int viewerAttribution)](#changeViewerPreference-int-) | Изменяет настройки просмотра. |
| [close()](#close--) | Закрывает открытый документ. |
| [createApplicationLink(Rectangle rect, String application, int page)](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Создает ссылку для запуска приложения в документе PDF. |
| [createApplicationLink(Rectangle rect, String application, int page, Color clr)](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Создает ссылку для запуска приложения в документе PDF. |
| [createApplicationLink(Rectangle rect, String application, int page, Color clr, int[] actionName)](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---) | Создает ссылку для запуска приложения в документе PDF. |
| [createBookmarksAction(String title, Color color, boolean boldFlag, boolean italicFlag, String file, String actionType, String destination)](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Создает закладку с указанным действием. |
| [createCaret(int page, Rectangle annotRect, Rectangle caretRect, String symbol, String annotContents, Color color)](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Создает аннотацию вставки. |
| [createCustomActionLink(Rectangle rect, int originalPage, Color color, int[] actionName)](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-int---) | Создает ссылку на дополнительные действия в документе PDF. |
| [createFileAttachment(Rectangle rect, String contents, InputStream attachmentStream, String attachmentName, int page, String name)](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Создает аннотацию вложенного файла. |
| [createFileAttachment(Rectangle rect, String contents, String filePath, int page, String name)](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Создает аннотацию вложенного файла. |
| [createFreeText(Rectangle rect, String contents, int page)](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Создает произвольную текстовую аннотацию в документе PDF |
| [createJavaScriptLink(String code, Rectangle rect, int originalPage, Color color)](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Создает ссылку на JavaScript в документе PDF. |
| [createLine(Rectangle rect, String contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, String borderStyle, int[] dashArray, String[] LEArray)](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int---java.lang.String---) | Создает линейную аннотацию. |
| [createLocalLink(Rectangle rect, int desPage, int originalPage)](#createLocalLink-java.awt.Rectangle-int-int-) | Создает локальную ссылку в документе PDF. |
| [createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Создает локальную ссылку в документе PDF. |
| [createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, int[] actionName)](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-int---) | Создает локальную ссылку в документе PDF. |
| [createMarkup(Rectangle rect, String contents, int type, int page, Color clr)](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Создает аннотацию разметки в PDF-документе. |
| [createMovie(Rectangle rect, String filePath, int page)](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage)](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Создает ссылку на другую страницу документа PDF. |
| [createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr)](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Создает ссылку на другую страницу документа PDF. |
| [createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr, int[] actionName)](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-int---) | Создает ссылку на другую страницу документа PDF. |
| [createPolyLine(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Создает полилинейную аннотацию. |
| [createPolygon(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Создает полигональную аннотацию. |
| [createPopup(Rectangle rect, String contents, boolean open, int page)](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Создает всплывающую аннотацию в документе PDF. |
| [createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, InputStream appearanceStream)](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Создает аннотацию штампа. |
| [createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, String appearanceFile)](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Создает аннотацию штампа. |
| [createRubberStamp(int page, Rectangle annotRect, String icon, String annotContents, Color color)](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Создает аннотацию штампа. |
| [createSound(Rectangle rect, String filePath, String name, int page, String rate)](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle(Rectangle rect, String contents, Color clr, boolean square, int page, int borderWidth)](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Создает аннотацию квадрат-круг. |
| [createText(Rectangle rect, String title, String contents, boolean open, String icon, int page)](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Создает текстовую аннотацию в документе PDF |
| [createWebLink(Rectangle rect, String url, int originalPage)](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Создает веб-ссылку в документе PDF. |
| [createWebLink(Rectangle rect, String url, int originalPage, Color clr)](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Создает веб-ссылку в документе PDF. |
| [createWebLink(Rectangle rect, String url, int originalPage, Color clr, int[] actionName)](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---) | Создает веб-ссылку в документе PDF. |
| [deleteAttachments()](#deleteAttachments--) | Удаляет все вложения в документе PDF. |
| [deleteImage()](#deleteImage--) | Удаляет все изображения из документа PDF. |
| [deleteImage(int pageNumber, int[] index)](#deleteImage-int-int---) | Удаляет указанные изображения на указанной странице. |
| [deleteStamp(int pageNumber, int[] index)](#deleteStamp-int-int---) | Удаляет несколько штампов на указанной странице по индексам штампов. |
| [deleteStampById(int stampId)](#deleteStampById-int-) | Удалить штамп по ID со всех страниц документа. |
| [deleteStampById(int pageNumber, int stampId)](#deleteStampById-int-int-) | Удаляет штамп на указанной странице по идентификатору штампа. |
| [deleteStampByIds(int pageNumber, int[] stampIds)](#deleteStampByIds-int-int---) | Удаляет штампы на указанной странице по нескольким идентификаторам штампов. |
| [deleteStampByIds(int[] stampIds)](#deleteStampByIds-int---) | Удаляет штампы с указанными идентификаторами со всех страниц документа. |
| [dispose()](#dispose--) | Располагает фасад. |
| [drawCurve(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Создает аннотацию кривой. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractLink()](#extractLink--) | Извлекает коллекцию экземпляров Link, содержащихся в документе PDF. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getReplaceTextStrategy()](#getReplaceTextStrategy--) | Получить набор параметров для операции замены текста |
| [getStamps(int pageNumber)](#getStamps-int-) | Возвращает массив штампов на странице. |
| [getTextEditOptions()](#getTextEditOptions--) | Получает параметры редактирования текста. |
| [getTextReplaceOptions()](#getTextReplaceOptions--) | Получает параметры замены текста. |
| [getTextSearchOptions()](#getTextSearchOptions--) | Получает параметры поиска текста. |
| [getViewerPreference()](#getViewerPreference--) | Возвращает предпочтение просмотра. |
| [hashCode()](#hashCode--) |  |
| [hideStampById(int pageNumber, int stampId)](#hideStampById-int-int-) | Скрывает печать. |
| [moveStamp(int pageNumber, int stampIndex, double x, double y)](#moveStamp-int-int-double-double-) | Изменяет положение штампа на странице. |
| [moveStampById(int pageNumber, int stampId, double x, double y)](#moveStampById-int-int-double-double-) | Изменяет положение штампа на странице. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeDocumentOpenAction()](#removeDocumentOpenAction--) | Удаляет открытое действие из документа. |
| [replaceImage(int pageNumber, int index, String imageFile)](#replaceImage-int-int-java.lang.String-) | Заменяет указанное изображение на указанной странице документа PDF другим изображением. |
| [replaceText(String srcString, int thePage, String destString)](#replaceText-java.lang.String-int-java.lang.String-) | Заменяет текст в файле PDF на указанной странице. |
| [replaceText(String srcString, int thePage, String destString, TextState textState)](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | Заменяет текст в файле PDF на указанной странице. |
| [replaceText(String srcString, String destString)](#replaceText-java.lang.String-java.lang.String-) | Заменяет текст в файле PDF. |
| [replaceText(String srcString, String destString, TextState textState)](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | Заменяет текст в файле PDF, используя указанный объект TextState. |
| [replaceText(String srcString, String destString, int fontSize)](#replaceText-java.lang.String-java.lang.String-int-) | Заменяет текст в файле PDF и устанавливает размер шрифта. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет документ PDF в указанный поток. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет документ PDF в указанный файл. |
| [setReplaceTextStrategy(ReplaceTextStrategy value)](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Установить набор параметров для операции замены текста |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Задает параметры редактирования текста. |
| [setTextReplaceOptions(TextReplaceOptions value)](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Задает параметры замены текста. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Задает параметры поиска текста. |
| [showStampById(int pageNumber, int stampId)](#showStampById-int-int-) | Показывает штамп, который был скрыт HiddenStampById. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfContentEditor() {#PdfContentEditor--}
```
public PdfContentEditor()
```


Конструктор объекта PdfContentEditor.

### PdfContentEditor(IDocument document) {#PdfContentEditor-com.aspose.pdf.IDocument-}
```
public PdfContentEditor(IDocument document)
```


Инициализирует новый объект PdfContentEditor на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### DOCUMENT_CLOSE {#DOCUMENT-CLOSE}
```
public static final String DOCUMENT_CLOSE
```


Тип события документа. Закрывает документ.

### DOCUMENT_OPEN {#DOCUMENT-OPEN}
```
public static final String DOCUMENT_OPEN
```


Тип события документа. Открывает документ.

### DOCUMENT_PRINTED {#DOCUMENT-PRINTED}
```
public static final String DOCUMENT_PRINTED
```


Тип события документа. Выполнение действия после печати.

### DOCUMENT_SAVED {#DOCUMENT-SAVED}
```
public static final String DOCUMENT_SAVED
```


Тип события документа. Выполнить действие после сохранения.

### DOCUMENT_WILL_PRINT {#DOCUMENT-WILL-PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```


Тип события документа. Выполнить действие перед печатью.

### DOCUMENT_WILL_SAVE {#DOCUMENT-WILL-SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```


Тип события документа. Выполнить действие перед сохранением.

### addDocumentAdditionalAction(String eventType, String code) {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
```
public void addDocumentAdditionalAction(String eventType, String code)
```


Добавляет дополнительное действие для события документа.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | java.lang.String | Типы событий документа. |
| code | java.lang.String | Код JavaScript. |

### addDocumentAttachment(InputStream fileAttachmentStream, String fileAttachmentName, String description) {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
```
public void addDocumentAttachment(InputStream fileAttachmentStream, String fileAttachmentName, String description)
```


Добавляет вложение документа без аннотации.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 InputStream attStream = new FileInputStream("attachment_file.pdf")
     editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
     editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileAttachmentStream | java.io.InputStream | Поток файла будет прикреплен. |
| fileAttachmentName | java.lang.String | Имя вложения. |
| description | java.lang.String | Информация описания. |

### addDocumentAttachment(String fileAttachmentPath, String description) {#addDocumentAttachment-java.lang.String-java.lang.String-}
```
public void addDocumentAttachment(String fileAttachmentPath, String description)
```


Добавляет вложение документа без аннотации.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileAttachmentPath | java.lang.String | Путь к файлу будет прикреплен. |
| description | java.lang.String | Информация описания. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Связывает поток PDF для редактирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток PDF для редактирования. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |
| password | java.lang.String | Пароль документа PDF. |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Связывает файл PDF для редактирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | PDF-файл для редактирования. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл |
| password | java.lang.String | Пароль документа PDF. |

### changeViewerPreference(int viewerAttribution) {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```


Изменяет настройки просмотра.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.changeViewerPreference(ViewerPreference.HideMenubar);
 editor.changeViewerPreference(ViewerPreference.PageModeUseNone);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| viewerAttribution | int | Атрибуция представления, определенная в классе ViewerPreference. |

### close() {#close--}
```
public void close()
```


Закрывает открытый документ.

### createApplicationLink(Rectangle rect, String application, int page) {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
```
public void createApplicationLink(Rectangle rect, String application, int page)
```


Создает ссылку для запуска приложения в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createApplicationLink(new Rectangle(0, 0, 100, 100), "explorer", 1 });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| application | java.lang.String | Путь запускаемого приложения. |
| page | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный ссылкой. |

### createApplicationLink(Rectangle rect, String application, int page, Color clr) {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
```
public void createApplicationLink(Rectangle rect, String application, int page, Color clr)
```


Создает ссылку для запуска приложения в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createApplicationLink(new Rectangle(0, 0, 100, 100),
     "explorer", 1, Color.red });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| application | java.lang.String | Путь запускаемого приложения. |
| page | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный ссылкой. |
| clr | java.awt.Color | Цвет прямоугольника для активного клика. |

### createApplicationLink(Rectangle rect, String application, int page, Color clr, int[] actionName) {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---}
```
public void createApplicationLink(Rectangle rect, String application, int page, Color clr, int[] actionName)
```


Создает ссылку для запуска приложения в документе PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| application | java.lang.String | Путь запускаемого приложения. |
| page | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный ссылкой. |
| clr | java.awt.Color | Цвет прямоугольника для активного клика. |
| actionName | int[] | Массив действий (членов перечисления PredefinedAction), соответствующих выполнению пунктов меню в средстве просмотра Acrobat. |

### createBookmarksAction(String title, Color color, boolean boldFlag, boolean italicFlag, String file, String actionType, String destination) {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
```
public void createBookmarksAction(String title, Color color, boolean boldFlag, boolean italicFlag, String file, String actionType, String destination)
```


Создает закладку с указанным действием.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarksAction("bookmark title",
     Color.red, true, true, null, "GoTo", 1(page number));
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| title | java.lang.String | Название закладки. |
| color | java.awt.Color | Цвет заголовка закладки. |
| boldFlag | boolean | Флаг смелой атрибуции. |
| italicFlag | boolean | Флаг курсивной атрибуции. |
| file | java.lang.String | Требуется другой файл или приложение, если тип действия — «GoToR» или «Запуск». |
| actionType | java.lang.String | Тип действия. Значение может быть: "GoToR", "Launch", "GoTo", "URI". |
| destination | java.lang.String | Локальный пункт назначения или удаленный пункт назначения или URL-адрес. |

### createCaret(int page, Rectangle annotRect, Rectangle caretRect, String symbol, String annotContents, Color color) {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
```
public void createCaret(int page, Rectangle annotRect, Rectangle caretRect, String symbol, String annotContents, Color color)
```


Создает аннотацию вставки.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createCaret(1,
 	    new Rectangle(50, 50, 100, 100),
 	    new Rectangle(60, 60, 70, 70),
 	    "None", "Welcome to Aspose", Color.red);
  editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| annotRect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| caretRect | java.awt.Rectangle | Фактические границы основного курсора. |
| symbol | java.lang.String | Символ будет связан с кареткой. Значение может быть: "P" (абзац), "Нет". |
| annotContents | java.lang.String | Содержание аннотации. |
| color | java.awt.Color | Цвет аннотации. |

### createCustomActionLink(Rectangle rect, int originalPage, Color color, int[] actionName) {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-int---}
```
public void createCustomActionLink(Rectangle rect, int originalPage, Color color, int[] actionName)
```


Создает ссылку на дополнительные действия в документе PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный ссылкой. |
| color | java.awt.Color | Цвет прямоугольника для активного клика. |
| actionName | int[] | Массив действий (членов перечисления PredefinedAction), соответствующих выполнению пунктов меню в средстве просмотра Acrobat. |

### createFileAttachment(Rectangle rect, String contents, InputStream attachmentStream, String attachmentName, int page, String name) {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
```
public void createFileAttachment(Rectangle rect, String contents, InputStream attachmentStream, String attachmentName, int page, String name)
```


Создает аннотацию вложенного файла.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 java.io.InputStream attStream = new java.io.FileInputStream("attachment_file.pdf");

     editor.createFileAttachment(new Rectangle(0, 0, 100, 100),
         "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
     editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | java.lang.String | Содержание аннотации. |
| attachmentStream | java.io.InputStream | Поток вложенных файлов. |
| attachmentName | java.lang.String | Имя вложения. |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| name | java.lang.String | Имя значка будет использоваться при отображении аннотации. Это значение может быть: «График», «PushPin», «Скрепка», «Тег». |

### createFileAttachment(Rectangle rect, String contents, String filePath, int page, String name) {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
```
public void createFileAttachment(Rectangle rect, String contents, String filePath, int page, String name)
```


Создает аннотацию вложенного файла.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createFileAttachment(new Rectangle(0, 0, 100, 100),
     "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | java.lang.String | Содержание аннотации. |
| filePath | java.lang.String | Путь к файлу будет прикреплен. |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| name | java.lang.String | Имя значка будет использоваться при отображении аннотации. Это значение может быть: «График», «PushPin», «Скрепка», «Тег». |

### createFreeText(Rectangle rect, String contents, int page) {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
```
public void createFreeText(Rectangle rect, String contents, int page)
```


Создает произвольную текстовую аннотацию в документе PDF

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createFreeText(new Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | java.lang.String | Содержание аннотации. |
| page | int | Номер исходной страницы, на которой будет создана текстовая аннотация. |

### createJavaScriptLink(String code, Rectangle rect, int originalPage, Color color) {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
```
public void createJavaScriptLink(String code, Rectangle rect, int originalPage, Color color)
```


Создает ссылку на JavaScript в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createJavaScriptLink("app.alert('welcome to aspose!');",
     new Rectangle(0, 0, 100, 100), 1, Color.red });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| code | java.lang.String | Код JavaScript. |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный ссылкой. |
| color | java.awt.Color | Цвет прямоугольника для активного клика. |

### createLine(Rectangle rect, String contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, String borderStyle, int[] dashArray, String[] LEArray) {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int---java.lang.String---}
```
public void createLine(Rectangle rect, String contents, float x1, float y1, float x2, float y2, int page, int border, Color clr, String borderStyle, int[] dashArray, String[] LEArray)
```


Создает линейную аннотацию.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createLine(new Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
     1, 1, Color.red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | java.lang.String | Содержание аннотации. |
| x1 | float | Начальная горизонтальная координата линии. |
| y1 | float | Начальная вертикальная координата линии. |
| x2 | float | Конечная горизонтальная координата линии. |
| y2 | float | Конечная вертикальная координата линии. |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| border | int | Ширина границы в пунктах. Если это значение равно 0, граница не рисуется. Значение по умолчанию — 1. |
| clr | java.awt.Color | Цвет линии. |
| borderStyle | java.lang.String | Стиль границы, указывающий ширину и шаблон пунктира, которые будут использоваться при рисовании линии. Это значение может быть: «S» (сплошной), «D» (пунктирный), «B» (скошенный), «I» (врезной), «U» (подчеркнутый). |
| dashArray | int[] | Массив штрихов, определяющий образец штрихов и пробелов, который будет использоваться при рисовании пунктирной границы. Если он используется, то для свойства borderSyle должно быть установлено значение "D". |
| LEArray | java.lang.String[] | Массив из двух значений, соответственно определяющих начальный и конечный стиль линии рисования. Значения могут быть: «Квадрат», «Круг», «Ромб», «OpenArrow», «ClosedArrow», «None», «Top», «ROpenArrow», «RClosedArrow», «Slash». |

### createLocalLink(Rectangle rect, int desPage, int originalPage) {#createLocalLink-java.awt.Rectangle-int-int-}
```
public void createLocalLink(Rectangle rect, int desPage, int originalPage)
```


Создает локальную ссылку в документе PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| desPage | int | Страница назначения. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный локальной ссылкой. |

### createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr) {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
```
public void createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```


Создает локальную ссылку в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createLocalLink(new Rectangle(0, 0, 100, 100),
     2, 1, Color.red });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| desPage | int | Страница назначения. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный локальной ссылкой. |
| clr | java.awt.Color | Цвет прямоугольника для активного клика. |

### createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, int[] actionName) {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-int---}
```
public void createLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, int[] actionName)
```


Создает локальную ссылку в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createLocalLink(new Rectangle(0, 0, 100, 100),
     2, 1, Color.red,
     new int[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| desPage | int | Страница назначения. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный локальной ссылкой. |
| clr | java.awt.Color | Цвет прямоугольника для активного клика. |
| actionName | int[] | Массив действий (членов перечисления PredefinedAction), соответствующих выполнению пунктов меню в средстве просмотра Acrobat. |

### createMarkup(Rectangle rect, String contents, int type, int page, Color clr) {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
```
public void createMarkup(Rectangle rect, String contents, int type, int page, Color clr)
```


Создает аннотацию разметки в PDF-документе.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createMarkup(new Rectangle(0, 0, 100, 100),
     "Welcome to Aspose", 0, 1, Color.red);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник, определяющий расположение аннотации на странице. |
| contents | java.lang.String | Содержание аннотации. |
| type | int | Тип аннотации разметки. Может быть 0 (выделено), 1 (подчеркнуто), 2 (зачеркнуто), 3 (волнисто). |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| clr | java.awt.Color | Цвет разметки. |

### createMovie(Rectangle rect, String filePath, int page) {#createMovie-java.awt.Rectangle-java.lang.String-int-}
```
public void createMovie(Rectangle rect, String filePath, int page)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle |  |
| filePath | java.lang.String |  |
| page | int |  |

### createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage) {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
```
public void createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage)
```


Создает ссылку на другую страницу документа PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPdfDocumentLink(new Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| remotePdf | java.lang.String | Документ PDF, страница которого будет открыта. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный ссылкой. |
| destinationPage | int | Страница назначения. |

### createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr) {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
```
public void createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr)
```


Создает ссылку на другую страницу документа PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPdfDocumentLink(new Rectangle(0, 0, 100, 100),
     "another_example.pdf", 1, 1, Color.red });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| remotePdf | java.lang.String | Документ PDF, страница которого будет открыта. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный ссылкой. |
| destinationPage | int | Страница назначения. |
| clr | java.awt.Color | Цвет прямоугольника для активного клика. |

### createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr, int[] actionName) {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-int---}
```
public void createPdfDocumentLink(Rectangle rect, String remotePdf, int originalPage, int destinationPage, Color clr, int[] actionName)
```


Создает ссылку на другую страницу документа PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPdfDocumentLink(new Rectangle(0, 0, 100, 100),
     "another_example.pdf", 1, 1, Color.red,
     new int[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| remotePdf | java.lang.String | Документ PDF, страница которого будет открыта. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, связанный ссылкой. |
| destinationPage | int | Страница назначения. |
| clr | java.awt.Color | Цвет прямоугольника для активного клика. |
| actionName | int[] | Массив действий (членов перечисления PredefinedAction), соответствующих выполнению пунктов меню в средстве просмотра Acrobat. |

### createPolyLine(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents) {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
```
public void createPolyLine(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)
```


Создает полилинейную аннотацию.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 LineInfo lineInfo = new LineInfo();
 lineInfo.setVerticeCoordinate ( new float[] { 0, 0, 100, 100, 100, 50 });
 lineInfo.setVisibility ( true);
 editor.createPolyLine(lineInfo, 1 , new Rectangle(0, 0, 0, 0), "Welcome to Aspose");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| lineInfo | [LineInfo](../../com.aspose.pdf.facades/lineinfo) | Экземпляр класса LineInfo. |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| annotRect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| annotContents | java.lang.String | Содержание аннотации. |

### createPolygon(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents) {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
```
public void createPolygon(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)
```


Создает полигональную аннотацию.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 LineInfo lineInfo = new LineInfo();
 lineInfo.setVerticeCoordinate ( new float[] { 0, 0, 100, 100, 100, 50 });
 lineInfo.setVisibility ( true);
 editor.createPolygon(lineInfo, 1 , new Rectangle(0, 0, 0, 0), "Welcome to Aspose");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| lineInfo | [LineInfo](../../com.aspose.pdf.facades/lineinfo) | Экземпляр класса LineInfo. |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| annotRect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| annotContents | java.lang.String | Содержание аннотации. |

### createPopup(Rectangle rect, String contents, boolean open, int page) {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
```
public void createPopup(Rectangle rect, String contents, boolean open, int page)
```


Создает всплывающую аннотацию в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createPopup(new Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | java.lang.String | Содержание аннотации. |
| open | boolean | Флаг, указывающий, должна ли всплывающая аннотация изначально отображаться открытой. |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |

### createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, InputStream appearanceStream) {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
```
public void createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, InputStream appearanceStream)
```


Создает аннотацию штампа.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
  InputStream appStream = new FileInputStream("appearance_file.pdf");
 	    editor.createRubberStamp(1, Rectangle(0, 0, 100, 100),
 	        "Welcome to Aspose", Color.red, appStream);
      editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| annotRect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| annotContents | java.lang.String | Содержание аннотации. |
| color | java.awt.Color | Цвет аннотации. |
| appearanceStream | java.io.InputStream | Поток файла внешнего вида. |

### createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, String appearanceFile) {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
```
public void createRubberStamp(int page, Rectangle annotRect, String annotContents, Color color, String appearanceFile)
```


Создает аннотацию штампа.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createRubberStamp(1, Rectangle(0, 0, 100, 100),
 	    "Welcome to Aspose", Color.red, "appearance_file.pdf");
  editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| annotRect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| annotContents | java.lang.String | Содержание аннотации. |
| color | java.awt.Color | Цвет аннотации. |
| appearanceFile | java.lang.String | Путь к файлу внешнего вида. |

### createRubberStamp(int page, Rectangle annotRect, String icon, String annotContents, Color color) {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
```
public void createRubberStamp(int page, Rectangle annotRect, String icon, String annotContents, Color color)
```


Создает аннотацию штампа.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createRubberStamp(1, Rectangle(0, 0, 100, 100),
 	    "Welcome to Aspose", Color.red);
  editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| annotRect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| icon | java.lang.String | Строковое значение |
| annotContents | java.lang.String | Содержание аннотации. |
| color | java.awt.Color | Цвет аннотации. |

### createSound(Rectangle rect, String filePath, String name, int page, String rate) {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
```
public void createSound(Rectangle rect, String filePath, String name, int page, String rate)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle |  |
| filePath | java.lang.String |  |
| name | java.lang.String |  |
| page | int |  |
| rate | java.lang.String |  |

### createSquareCircle(Rectangle rect, String contents, Color clr, boolean square, int page, int borderWidth) {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
```
public void createSquareCircle(Rectangle rect, String contents, Color clr, boolean square, int page, int borderWidth)
```


Создает аннотацию квадрат-круг.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
  editor.bindPdf("example.pdf");
 	editor.createSquareCircle(new Rectangle(0, 0, 100, 100),
 	    "Welcome to Aspose", Color.red, false, 1, 5);
  editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| contents | java.lang.String | Содержание аннотации. |
| clr | java.awt.Color | Цвет квадрата или круга. |
| square | boolean | Правда (квадрат), ложь (круг). |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| borderWidth | int | Ширина границы квадрата или круга. |

### createText(Rectangle rect, String title, String contents, boolean open, String icon, int page) {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
```
public void createText(Rectangle rect, String title, String contents, boolean open, String icon, int page)
```


Создает текстовую аннотацию в документе PDF

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createText(new Rectangle(0, 0, 100, 100),
     "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| title | java.lang.String | Название аннотации. |
| contents | java.lang.String | Содержание аннотации. |
| open | boolean | Флаг, указывающий, должна ли аннотация изначально отображаться открытой. |
| icon | java.lang.String | Имя значка будет использоваться при отображении аннотации. Это значение может быть: «Комментарий», «Ключ», «Примечание», «Справка», «NewParagraph», «Абзац», «Вставка». |
| page | int | Номер исходной страницы, на которой будет создана текстовая аннотация. |

### createWebLink(Rectangle rect, String url, int originalPage) {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
```
public void createWebLink(Rectangle rect, String url, int originalPage)
```


Создает веб-ссылку в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createWebLink(new Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| url | java.lang.String | Адрес веб-ссылки. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, ограниченный веб-ссылкой. |

### createWebLink(Rectangle rect, String url, int originalPage, Color clr) {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
```
public void createWebLink(Rectangle rect, String url, int originalPage, Color clr)
```


Создает веб-ссылку в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createWebLink(new Rectangle(0, 0, 100, 100),
     "http://www.aspose.com", 1, Цвет.красный });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| url | java.lang.String | Адрес веб-ссылки. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, ограниченный веб-ссылкой. |
| clr | java.awt.Color | Цвет прямоугольника для активного клика. |

### createWebLink(Rectangle rect, String url, int originalPage, Color clr, int[] actionName) {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-int---}
```
public void createWebLink(Rectangle rect, String url, int originalPage, Color clr, int[] actionName)
```


Создает веб-ссылку в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.createWebLink(new Rectangle(0, 0, 100, 100),
     "http://www.aspose.com", 1, Цвет.красный,
     new int[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | java.awt.Rectangle | Прямоугольник для активного клика. |
| url | java.lang.String | Адрес веб-ссылки. |
| originalPage | int | Номер исходной страницы, на которой будет создан прямоугольник, ограниченный веб-ссылкой. |
| clr | java.awt.Color | Цвет прямоугольника для активного клика. |
| actionName | int[] | Массив действий (членов перечисления PredefinedAction), соответствующих выполнению пунктов меню в средстве просмотра Acrobat. |

### deleteAttachments() {#deleteAttachments--}
```
public void deleteAttachments()
```


Удаляет все вложения в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.deleteAttachments();
 editor.save("example_out.pdf");
```

### deleteImage() {#deleteImage--}
```
public void deleteImage()
```


Удаляет все изображения из документа PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.deleteImage();
 editor.save("example_out.pdf");
```

### deleteImage(int pageNumber, int[] index) {#deleteImage-int-int---}
```
public void deleteImage(int pageNumber, int[] index)
```


Удаляет указанные изображения на указанной странице.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.deleteImage(1, new int[] {1, 2});
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы, на которой необходимо удалить изображения. |
| index | int[] | Массив представляет индексы изображений. |

### deleteStamp(int pageNumber, int[] index) {#deleteStamp-int-int---}
```
public void deleteStamp(int pageNumber, int[] index)
```


Удаляет несколько штампов на указанной странице по индексам штампов.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStamp(1, new int[] { 2, 3, 5} );
 contentEditor.save("outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы, на которой штамп будет удален. |
| index | int[] | Штамповые индексы. |

### deleteStampById(int stampId) {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```


Удалить штамп по ID со всех страниц документа.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampById(100);
 contentEditor.save("outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stampId | int | Идентификатор штампа, который следует удалить. |

### deleteStampById(int pageNumber, int stampId) {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```


Удаляет штамп на указанной странице по идентификатору штампа.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampById(1, 100);
 contentEditor.save("outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы, на которой штамп будет удален. |
| stampId | int | Идентификатор штампа, который следует удалить. |

### deleteStampByIds(int pageNumber, int[] stampIds) {#deleteStampByIds-int-int---}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```


Удаляет штампы на указанной странице по нескольким идентификаторам штампов.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampByIds(1, new int[] { 100, 101 } );
 contentEditor.save("outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы, на которой штампы будут удалены. |
| stampIds | int[] | Массив идентификаторов штампов. |

### deleteStampByIds(int[] stampIds) {#deleteStampByIds-int---}
```
public void deleteStampByIds(int[] stampIds)
```


Удаляет штампы с указанными идентификаторами со всех страниц документа.

--------------------

```
PdfContentEditor contentEditor = new PdfContentEditor();
 contentEditor.bindPdf("file.pdf");
 contentEditor.deleteStampByIds(new int[] { 102, 103 } );
 contentEditor.save("outfile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stampIds | int[] | Массив идентификаторов штампов. |

### dispose() {#dispose--}
```
public void dispose()
```


Располагает фасад.

Этот метод устарел, вместо него используйте close().

### drawCurve(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents) {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
```
public void drawCurve(LineInfo lineInfo, int page, Rectangle annotRect, String annotContents)
```


Создает аннотацию кривой.

```
PdfContentEditor editor = new PdfContentEditor();
 newApiEditor.bindPdf("example.pdf");
 LineInfo lineInfo = new LineInfo();
 lineInfo.setVerticeCoordinate ( new float[] { 0, 0, 100, 100 });  //х1, у1, х2, у2, .. хп, уп
 lineInfo.setVisibility ( true);
 editor.drawCurve(lineInfo, 1, new Rectangle(0, 0, 0, 0), "Welcome to Aspose");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| lineInfo | [LineInfo](../../com.aspose.pdf.facades/lineinfo) | Экземпляр класса LineInfo. |
| page | int | Номер исходной страницы, на которой будет создана аннотация. |
| annotRect | java.awt.Rectangle | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| annotContents | java.lang.String | Содержание аннотации. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### extractLink() {#extractLink--}
```
public List<Annotation> extractLink()
```


Извлекает коллекцию экземпляров Link, содержащихся в документе PDF.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 List links = editor.extractLink();
 for (object obj : links)
 {
     Link link = (Link)obj;
     // работа с экземпляром Link
 }
```

**Возвращает:**
java.util.List<com.aspose.pdf.Annotation> — коллекция объектов Link
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getReplaceTextStrategy() {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```


Получить набор параметров для операции замены текста

**Возвращает:**
[ReplaceTextStrategy](../../com.aspose.pdf.facades/replacetextstrategy) - Элемент ReplaceTextStrategy
### getStamps(int pageNumber) {#getStamps-int-}
```
public StampInfo[] getStamps(int pageNumber)
```


Возвращает массив штампов на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы, на которой будет производиться поиск марок. |

**Возвращает:**
com.aspose.pdf.facades.StampInfo[] - Массив марок.
### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


Получает параметры редактирования текста.

**Возвращает:**
[TextEditOptions](../../com.aspose.pdf/texteditoptions) - Элемент TextEditOptions
### getTextReplaceOptions() {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```


Получает параметры замены текста.

**Возвращает:**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) - Элемент TextReplaceOptions
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Получает параметры поиска текста.

**Возвращает:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - Элемент TextSearchOptions
### getViewerPreference() {#getViewerPreference--}
```
public int getViewerPreference()
```


Возвращает предпочтение просмотра.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 int prefValue = editor.GetViewerPreference();
 if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
 { // ... }
```

**Возвращает:**
int — возвращает набор флагов ViewerPrefernece
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### hideStampById(int pageNumber, int stampId) {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```


Скрывает печать. После скрытия видимость штампа можно восстановить с помощью метода ShowStampById.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы. |
| stampId | int | Идентификатор штампа, который следует скрыть. |

### moveStamp(int pageNumber, int stampIndex, double x, double y) {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```


Изменяет положение штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы. |
| stampIndex | int | Указатель штампа на странице. |
| x | double | Новое горизонтальное положение штампа. |
| y | double | Новое вертикальное положение штампа. |

### moveStampById(int pageNumber, int stampId, double x, double y) {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```


Изменяет положение штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы. |
| stampId | int | Идентификатор штампа, который необходимо переместить. |
| x | double | Новое горизонтальное положение штампа на странице. |
| y | double | Новое вертикальное положение штампа на странице. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeDocumentOpenAction() {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```


Удаляет открытое действие из документа. Эта операция полезна при объединении нескольких документов, которые используют явное действие «Перейти» при запуске.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.removeDocumentOpenAction();
 editor.save("example_out.pdf");
```

### replaceImage(int pageNumber, int index, String imageFile) {#replaceImage-int-int-java.lang.String-}
```
public void replaceImage(int pageNumber, int index, String imageFile)
```


Заменяет указанное изображение на указанной странице документа PDF другим изображением.

--------------------

```
PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf("example.pdf");
 editor.replaceImage(1, 1, "image.jpg");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы, на которой заменяется изображение. |
| index | int | Индекс объекта изображения должен быть заменен. |
| imageFile | java.lang.String | Файл изображения будет использоваться для замены. |

### replaceText(String srcString, int thePage, String destString) {#replaceText-java.lang.String-int-java.lang.String-}
```
public boolean replaceText(String srcString, int thePage, String destString)
```


Заменяет текст в файле PDF на указанной странице.

--------------------

```
The example demonstrates how to replace text in PDF document on the specified page.


 // открыть документ
 Document doc = new Document(inFile);
 // создать объект PdfContentEditor для редактирования текста
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // изменить текст
 editor.replaceText("hello world", 1, "hi world");
 // сохранить документ
 doc.save(outFile);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | java.lang.String | Жало подлежит замене. |
| thePage | int | Номер страницы (0 для всех страниц) |
| destString | java.lang.String | Замена строки. |

**Возвращает:**
boolean - Возвращает true, если замена была произведена.
### replaceText(String srcString, int thePage, String destString, TextState textState) {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
```
public boolean replaceText(String srcString, int thePage, String destString, TextState textState)
```


Заменяет текст в файле PDF на указанной странице. Объект TextState (семейство шрифтов, цвет) может быть указан для замещаемого текста.

--------------------

```
The example demonstrates how to replace text on the first page of the PDF document and set ```
TextState
```
 свойства текста для нового текста.


 // открыть документ
 Документ документ = новый документ (в файле);
 com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New");
 font.isEmbedded (правда);
 // создаем объект PdfContentEditor для редактирования текста
 Редактор PdfContentEditor = новый PdfContentEditor();
 редактор.bindPdf(док);
 // создать объект textState
 com.aspose.pdf.TextState textState = новый com.aspose.pdf.TextState();
 textState.setFont (шрифт);
 textState.setFontSize (17);
 textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic);
 textState.setForegroundColor ( com.aspose.pdf.Color.getRed());
 // изменить текст указанным шрифтом
 editor.replaceText("привет мир", 1, "привет мир", textState);
 // сохранить документ
 doc.save (outFile);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcString | java.lang.String | The string to be replaced. |
| thePage | int | Page number (0 means "all pages"). |
| destString | java.lang.String | The replaced string. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Text state (Text Color, Font etc). |

**Returns:**
boolean - Returns true if replacement was made.
### replaceText(String srcString, String destString) {#replaceText-java.lang.String-java.lang.String-}
```
публичное логическое значение replaceText (String srcString, String destString)
```


Replaces text in the PDF file.

--------------------

```
В примере показано, как заменить текст в документе PDF.


 // открыть документ
 Документ документ = новый документ (в файле);
 // создаем объект PdfContentEditor для редактирования текста
 Редактор PdfContentEditor = новый PdfContentEditor();
 редактор.bindPdf(док);
 // изменить текст
 editor.replaceText ("привет, мир", "привет, мир");
 // сохранить документ
 doc.save (outFile);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcString | java.lang.String | The string to be replaced. |
| destString | java.lang.String | Replacing string. |

**Returns:**
boolean - Returns true if replacement was made.
### replaceText(String srcString, String destString, TextState textState) {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
```
public boolean replaceText (String srcString, String destString, TextState textState)
```


Replaces text in the PDF file using specified  TextState  object.

--------------------

```
В примере показано, как заменить текст и установить ```
текстстате
``` text properties for the new text.


 Document doc = new Document(inFile);
 // Создайте шрифт и отметьте его для встраивания
 com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New");
 font.isEmbedded ( true);
 // создать объект PdfContentEditor для редактирования текста
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // создать объект textState
 com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState();
 textState.setFont ( font);
 textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic);
 // изменить текст с указанным шрифтом
 editor.replaceText("hello world", "hi world", textState);
 // сохранить документ
 doc.save(outFile);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | java.lang.String | Строка для замены |
| destString | java.lang.String | Замена строки |
| textState | [TextState](../../com.aspose.pdf/textstate) | Состояние текста (цвет текста, шрифт и т. д.) |

**Возвращает:**
boolean - Возвращает true, если замена была произведена.
### replaceText(String srcString, String destString, int fontSize) {#replaceText-java.lang.String-java.lang.String-int-}
```
public boolean replaceText(String srcString, String destString, int fontSize)
```


Заменяет текст в файле PDF и устанавливает размер шрифта.

--------------------

```
The example demonstrates how to replace text and set font size for the new text.


 // открыть документ
 Document doc = new Document(inFile);
 // Создайте шрифт и отметьте его для встраивания
 com.aspose.pdf.Font font = FontRepository.FindFont("Courier New");
 font.isEmbedded ( true);
 // создать объект PdfContentEditor для редактирования текста
 PdfContentEditor editor = new PdfContentEditor();
 editor.bindPdf(doc);
 // изменить текст с указанным шрифтом
 editor.replaceText("hello world", "hi world", 14);
 // сохранить документ
 doc.save(outFile);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | java.lang.String | Строка для замены. |
| destString | java.lang.String | Замена строки. |
| fontSize | int | Размер шрифта. |

**Возвращает:**
boolean - Возвращает true, если замена была произведена.
### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Сохраняет документ PDF в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.OutputStream | Целевой поток. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Сохраняет документ PDF в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFile | java.lang.String | Файл назначения. |

### setReplaceTextStrategy(ReplaceTextStrategy value) {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
```
public void setReplaceTextStrategy(ReplaceTextStrategy value)
```


Установить набор параметров для операции замены текста

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ReplaceTextStrategy](../../com.aspose.pdf.facades/replacetextstrategy) | Элемент ReplaceTextStrategy |

### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions(TextEditOptions value)
```


Задает параметры редактирования текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Элемент setTextEditOptions |

### setTextReplaceOptions(TextReplaceOptions value) {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
```
public void setTextReplaceOptions(TextReplaceOptions value)
```


Задает параметры замены текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) | Элемент TextReplaceOptions |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Задает параметры поиска текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Элемент TextSearchOptions |

### showStampById(int pageNumber, int stampId) {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```


Показывает штамп, который был скрыт HiddenStampById.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы. |
| stampId | int | Идентификатор штампа, который должен быть показан. |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
