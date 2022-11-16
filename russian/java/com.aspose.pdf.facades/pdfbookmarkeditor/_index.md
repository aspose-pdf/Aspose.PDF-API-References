---
title: PdfBookmarkEditor
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для работы с закладками файлов PDF, включая создание, изменение, экспорт, импорт и удаление.
type: docs
weight: 35
url: /ru/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfBookmarkEditor extends SaveableFacade
```

Представляет класс для работы с закладками файла PDF, включая создание, изменение, экспорт, импорт и удаление.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfBookmarkEditor()](#PdfBookmarkEditor--) | Инициализирует новый объект PdfBookmarkEditor. |
| [PdfBookmarkEditor(IDocument document)](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfBookmarkEditor на основе документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Закройте экземпляр PdfBookmarkEditor и освободите ресурсы. |
| [createBookmarkOfPage(String bookmarkName, int pageNumber)](#createBookmarkOfPage-java.lang.String-int-) | Создает закладку для указанной страницы. |
| [createBookmarkOfPage(String[] bookmarkName, int[] pageNumber)](#createBookmarkOfPage-java.lang.String---int---) | Создает закладки для указанных страниц. |
| [createBookmarks()](#createBookmarks--) | Создает закладки для всех страниц. |
| [createBookmarks(Bookmark bookmark)](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | Создает указанную закладку в документе. |
| [createBookmarks(Color color, boolean boldFlag, boolean italicFlag)](#createBookmarks-java.awt.Color-boolean-boolean-) | Создайте закладки для всех страниц с заданным цветом и стилем (жирный, курсив). |
| [deleteBookmarks()](#deleteBookmarks--) | Удаляет все закладки документа PDF. |
| [deleteBookmarks(String title)](#deleteBookmarks-java.lang.String-) | Удаляет закладку документа PDF. |
| [dispose()](#dispose--) | Располагает фасад. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportBookmarksToHtml(String inPdfFile, String outHtmlFile)](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | Экспортирует закладки в файл HTML. |
| [exportBookmarksToXML(OutputStream output)](#exportBookmarksToXML-java.io.OutputStream-) | Экспортирует закладки в поток XML. |
| [exportBookmarksToXML(String xmlFile)](#exportBookmarksToXML-java.lang.String-) | Экспортирует закладки в файл XML. |
| [extractBookmarks()](#extractBookmarks--) | Извлекает из документа закладки всех уровней. |
| [extractBookmarks(boolean upperLevel)](#extractBookmarks-boolean-) | Извлекает из документа закладки всех уровней. |
| [extractBookmarks(Bookmark bookmark)](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | Извлекает дочерние элементы закладки с заголовком, как в указанном bookamrk. |
| [extractBookmarks(String title)](#extractBookmarks-java.lang.String-) | Извлекает закладки с указанным заголовком. |
| [extractBookmarksToHTML(String pdfFile, String cssFile)](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | Экспортирует закладки в файл HTML. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [hashCode()](#hashCode--) |  |
| [importBookmarksWithXML(InputStream stream)](#importBookmarksWithXML-java.io.InputStream-) | Импортирует закладки в документ из файла XML. |
| [importBookmarksWithXML(String xmlFile)](#importBookmarksWithXML-java.lang.String-) | Импортирует закладки в документ из файла XML. |
| [modifyBookmarks(String sTitle, String dTitle)](#modifyBookmarks-java.lang.String-java.lang.String-) | Изменяет название закладки в соответствии с указанным названием закладки. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет документ PDF в указанный поток. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет документ PDF в указанный файл. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfBookmarkEditor() {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```


Инициализирует новый объект PdfBookmarkEditor.

### PdfBookmarkEditor(IDocument document) {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
```
public PdfBookmarkEditor(IDocument document)
```


Инициализирует новый объект PdfBookmarkEditor на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |

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

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл. |

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

### close() {#close--}
```
public void close()
```


Закройте экземпляр PdfBookmarkEditor и освободите ресурсы.

### createBookmarkOfPage(String bookmarkName, int pageNumber) {#createBookmarkOfPage-java.lang.String-int-}
```
public void createBookmarkOfPage(String bookmarkName, int pageNumber)
```


Создает закладку для указанной страницы.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarkOfPage("bookmark for page 1", 1);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| bookmarkName | java.lang.String | Указанное имя закладки. |
| pageNumber | int | Указанная целевая страница. |

### createBookmarkOfPage(String[] bookmarkName, int[] pageNumber) {#createBookmarkOfPage-java.lang.String---int---}
```
public void createBookmarkOfPage(String[] bookmarkName, int[] pageNumber)
```


Создает закладки для указанных страниц.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarkOfPage("bookmark for page 1", 1);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| bookmarkName | java.lang.String[] | Массив заголовков закладок. |
| pageNumber | int[] | Массив целевых страниц закладок. |

### createBookmarks() {#createBookmarks--}
```
public void createBookmarks()
```


Создает закладки для всех страниц.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarks();
 editor.save("example_out.pdf");
```

### createBookmarks(Bookmark bookmark) {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
```
public void createBookmarks(Bookmark bookmark)
```


Создает указанную закладку в документе. Метод может быть использован для формирования иерархии вложенных закладок.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
  editor.bindPdf("example.pdf");
  Bookmark bm1=new Bookmark();
  bm1.setPageNumber(1);
  bm1.setTitle("First child");
 	Bookmark bm2=new Bookmark();
 	bm2.setPageNumber(2);
  bm2.setTitle("Second child");
  Bookmark bm=new Bookmark();
  bm.setAction=(GoTo");
  bm.setPageNumber(1);
  bm.setTitle("Parent");
  Bookmarks bms=new Bookmarks();
  bms.add(bm1);
  bms.add(bm2);
  bm.setChildItem(bms);
  editor.setCreateBookmarks(bm);
  editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| bookmark | [Bookmark](../../com.aspose.pdf.facades/bookmark) | Закладка будет добавлена в документ. |

### createBookmarks(Color color, boolean boldFlag, boolean italicFlag) {#createBookmarks-java.awt.Color-boolean-boolean-}
```
public void createBookmarks(Color color, boolean boldFlag, boolean italicFlag)
```


Создайте закладки для всех страниц с заданным цветом и стилем (жирный, курсив).

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarks(System.Drawing.Color.Red, true, true);
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | java.awt.Color | Цвет заголовка. |
| boldFlag | boolean | Флаг смелой атрибуции. |
| italicFlag | boolean | Флаг курсивной атрибуции. |

### deleteBookmarks() {#deleteBookmarks--}
```
public void deleteBookmarks()
```


Удаляет все закладки документа PDF.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.deleteBookmarks();
 editor.save("example_out.pdf");
```

### deleteBookmarks(String title) {#deleteBookmarks-java.lang.String-}
```
public void deleteBookmarks(String title)
```


Удаляет закладку документа PDF.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.deleteBookmarks("existing bookmark title");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| title | java.lang.String | Название закладки удалено. |

### dispose() {#dispose--}
```
public void dispose()
```


Располагает фасад.

Этот метод устарел, вместо него используйте close().

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
### exportBookmarksToHtml(String inPdfFile, String outHtmlFile) {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
```
public static void exportBookmarksToHtml(String inPdfFile, String outHtmlFile)
```


Экспортирует закладки в файл HTML.

--------------------

```
PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inPdfFile | java.lang.String | Введите PDF-файл, закладки которого будут экспортированы. |
| outHtmlFile | java.lang.String | Выходной HTML-файл |

### exportBookmarksToXML(OutputStream output) {#exportBookmarksToXML-java.io.OutputStream-}
```
public void exportBookmarksToXML(OutputStream output)
```


Экспортирует закладки в поток XML.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| output | java.io.OutputStream | Выходной поток, в котором будут храниться данные. |

### exportBookmarksToXML(String xmlFile) {#exportBookmarksToXML-java.lang.String-}
```
public void exportBookmarksToXML(String xmlFile)
```


Экспортирует закладки в файл XML.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.exportBookmarksToXML("bookmarks.xml");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | java.lang.String | Выходной XML-файл. |

### extractBookmarks() {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```


Извлекает из документа закладки всех уровней.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 Bookmarks bms = editor.ExtractBookmarks();
 for(Bookmark bm : bms)
     System.out.println(bm.Title);
```

**Возвращает:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - Коллекция закладок всех закладок, существующих в документе.
### extractBookmarks(boolean upperLevel) {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```


Извлекает из документа закладки всех уровней.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| upperLevel | boolean | Если true, извлекаются только закладки верхнего уровня. В противном случае рекурсивно извлекает все закладки. |

**Возвращает:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - Список извлеченных закладок.
### extractBookmarks(Bookmark bookmark) {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
```
public Bookmarks extractBookmarks(Bookmark bookmark)
```


Извлекает дочерние элементы закладки с заголовком, как в указанном bookamrk.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 Bookmark bookmark = new Bookmark();
 bookmark.setTitle ( "Title");
 Bookmarks bms = editor.ExtractBookmarks(bookmark);
 for(Bookmark bm : ```
(Iterable)
```bms)
     System.out.println(bm.Title);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| bookmark | [Bookmark](../../com.aspose.pdf.facades/bookmark) | Указанный букамрк. |

**Возвращает:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - Коллекция закладок с дочерними закладками.
### extractBookmarks(String title) {#extractBookmarks-java.lang.String-}
```
public Bookmarks extractBookmarks(String title)
```


Извлекает закладки с указанным заголовком.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
  editor.bindPdf("example.pdf");
 	Bookmarks bms = editor.ExtractBookmarks("Title");
  for(Bookmark bm : ```
(Iterable)
```bms)
      System.out.println(bm.Title);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| title | java.lang.String | Извлеченное название элемента. |

**Возвращает:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - В коллекции объектов закладок есть элементы с одинаковым названием.
### extractBookmarksToHTML(String pdfFile, String cssFile) {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
```
public void extractBookmarksToHTML(String pdfFile, String cssFile)
```


Экспортирует закладки в файл HTML.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.extractBookmarksToHTML("example.pdf", null);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfFile | java.lang.String | Файл PDF, закладки которого будут экспортированы. |
| cssFile | java.lang.String | Файл CSS для отображения HTML-файла может быть нулевым. |

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### importBookmarksWithXML(InputStream stream) {#importBookmarksWithXML-java.io.InputStream-}
```
public void importBookmarksWithXML(InputStream stream)
```


Импортирует закладки в документ из файла XML.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток с данными закладок. |

### importBookmarksWithXML(String xmlFile) {#importBookmarksWithXML-java.lang.String-}
```
public void importBookmarksWithXML(String xmlFile)
```


Импортирует закладки в документ из файла XML.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.importBookmarksWithXML("bookmarks.xml");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xmlFile | java.lang.String | XML-файл, содержащий список закладок. |

### modifyBookmarks(String sTitle, String dTitle) {#modifyBookmarks-java.lang.String-java.lang.String-}
```
public void modifyBookmarks(String sTitle, String dTitle)
```


Изменяет название закладки в соответствии с указанным названием закладки.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.modifyBookmarks("existing bookmark title", "new bookmark title");
 editor.save("example_out.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| sTitle | java.lang.String | Заголовок исходной закладки. |
| dTitle | java.lang.String | Изменено название закладки. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
