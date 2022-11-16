---
title: PdfPageEditor
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для редактирования страницы файлов PDF, включая поворот страницы, масштабирование страницы, перемещение страницы и изменение размера страницы.
type: docs
weight: 49
url: /ru/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfPageEditor extends SaveableFacade
```

Представляет класс для редактирования страницы файла PDF, включая поворот страницы, масштабирование страницы, перемещение положения и изменение размера страницы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfPageEditor()](#PdfPageEditor--) | Конструктор класса PdfPageEditor. |
| [PdfPageEditor(Document document)](#PdfPageEditor-com.aspose.pdf.Document-) | Конструктор класса PdfPageEditor. |
## Поля

| Поле | Описание |
| --- | --- |
| [BLINDH](#BLINDH) | Вертикальные жалюзи |
| [BLINDV](#BLINDV) | Вертикальные жалюзи |
| [BTWIPE](#BTWIPE) | Нижняя-верхняя салфетка |
| [DGLITTER](#DGLITTER) | Диагональный блеск |
| [DISSOLVE](#DISSOLVE) | Старая страница растворяется |
| [INBOX](#INBOX) | Внутренняя коробка |
| [LRGLITTER](#LRGLITTER) | Левый-правый блеск |
| [LRWIPE](#LRWIPE) | Стирание влево-вправо |
| [OUTBOX](#OUTBOX) | Внешняя коробка |
| [RLWIPE](#RLWIPE) | Протрите вправо-влево |
| [SPLITHIN](#SPLITHIN) | В горизонтальном разделении |
| [SPLITHOUT](#SPLITHOUT) | Из горизонтального разделения |
| [SPLITVIN](#SPLITVIN) | В вертикальном разделении |
| [SPLITVOUT](#SPLITVOUT) | Выход по вертикали |
| [TBGLITTER](#TBGLITTER) | Блеск сверху и снизу |
| [TBWIPE](#TBWIPE) | Протирание сверху вниз |
## Методы

| Метод | Описание |
| --- | --- |
| [applyChanges()](#applyChanges--) | Примените изменения, сделанные на страницах документа. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Удаляет документ, связанный с фасадом. |
| [dispose()](#dispose--) | Располагает фасад. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Получает горизонтальное выравнивание исходного содержимого PDF на странице результатов, по умолчанию — AlignmentType.Left. |
| [getClass()](#getClass--) |  |
| [getDisplayDuration()](#getDisplayDuration--) | Получает продолжительность отображения для страниц. |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание исходного содержимого PDF на странице результатов, по умолчанию — AlignmentType.Left. |
| [getPageBoxSize(int page, String pageBoxName)](#getPageBoxSize-int-java.lang.String-) | Возвращает размер указанного блока в документе. |
| [getPageRotation(int page)](#getPageRotation-int-) | Возвращает поворот указанной страницы. |
| [getPageRotations()](#getPageRotations--) | Получает поворот страниц. Хеш-таблица содержит номер страницы и степень поворота, ключ представляет номер страницы, значение ключа представляет поворот в градусах. |
| [getPageSize()](#getPageSize--) | Получает размер страницы выходного файла. |
| [getPageSize(int page)](#getPageSize-int-) | Возвращает размер указанной страницы. |
| [getPages()](#getPages--) | Возвращает общее количество страниц. |
| [getProcessPages()](#getProcessPages--) | Получает номера страниц для редактирования. |
| [getRotation()](#getRotation--) | Получает поворот страниц, поворот должен быть 0, 90, 180 или 270. |
| [getTransitionDuration()](#getTransitionDuration--) | Получает продолжительность эффекта перехода. |
| [getTransitionType()](#getTransitionType--) | Получает стиль перехода, используемый при переходе на эту страницу с другой во время презентации. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание исходного содержимого PDF на странице результатов. Значение по умолчанию — VerticalAlignmentType.Bottom. |
| [getVerticalAlignmentType()](#getVerticalAlignmentType--) | Получает вертикальное выравнивание исходного содержимого PDF на странице результатов. Значение по умолчанию — VerticalAlignmentType.Bottom. |
| [getZoom()](#getZoom--) | Получить коэффициент масштабирования. |
| [hashCode()](#hashCode--) |  |
| [movePosition(float moveX, float moveY)](#movePosition-float-float-) | Перемещает начало координат из (0, 0) в назначенную точку. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Сохраняет измененный документ в поток. |
| [save(String outputFile)](#save-java.lang.String-) | Сохраняет измененный документ в файл. |
| [setAlignment(AlignmentType value)](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Задает горизонтальное выравнивание исходного содержимого PDF на странице результатов. По умолчанию используется значение AlignmentType.Left. |
| [setDisplayDuration(int value)](#setDisplayDuration-int-) | Устанавливает продолжительность отображения страниц. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Задает горизонтальное выравнивание исходного содержимого PDF на странице результатов. По умолчанию используется значение AlignmentType.Left. |
| [setPageRotations(Map<Integer,Integer> value)](#setPageRotations-java.util.Map-java.lang.Integer-java.lang.Integer--) | Устанавливает поворот страниц. Хеш-таблица содержит номер страницы и степень поворота, ключ представляет номер страницы, значение ключа представляет поворот в градусах. |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.pdf.PageSize-) | Устанавливает размер страницы выходного файла. |
| [setProcessPages(int[] value)](#setProcessPages-int---) | Устанавливает номера страниц для редактирования. |
| [setRotation(int value)](#setRotation-int-) | Устанавливает поворот страниц, поворот должен быть 0, 90, 180 или 270. |
| [setTransitionDuration(int value)](#setTransitionDuration-int-) | Устанавливает продолжительность эффекта перехода. |
| [setTransitionType(int value)](#setTransitionType-int-) | Задает стиль перехода, используемый при переходе на эту страницу с другой во время презентации. |
| [setVerticalAlignment(VerticalAlignmentType value)](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Задает вертикальное выравнивание исходного содержимого PDF на странице результатов. Значение по умолчанию — VerticalAlignmentType.Bottom. |
| [setVerticalAlignmentType(int value)](#setVerticalAlignmentType-int-) | Задает вертикальное выравнивание исходного содержимого PDF на странице результатов. Значение по умолчанию — VerticalAlignmentType.Bottom. |
| [setZoom(float value)](#setZoom-float-) | Устанавливает коэффициент масштабирования. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfPageEditor() {#PdfPageEditor--}
```
public PdfPageEditor()
```


Конструктор класса PdfPageEditor.

### PdfPageEditor(Document document) {#PdfPageEditor-com.aspose.pdf.Document-}
```
public PdfPageEditor(Document document)
```


Конструктор класса PdfPageEditor.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | Объект документа, который необходимо обработать. |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```


Вертикальные жалюзи

### BLINDV {#BLINDV}
```
public static final int BLINDV
```


Вертикальные жалюзи

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```


Нижняя-верхняя салфетка

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```


Диагональный блеск

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```


Старая страница растворяется

### INBOX {#INBOX}
```
public static final int INBOX
```


Внутренняя коробка

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```


Левый-правый блеск

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```


Стирание влево-вправо

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```


Внешняя коробка

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```


Протрите вправо-влево

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```


В горизонтальном разделении

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```


Из горизонтального разделения

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```


В вертикальном разделении

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```


Выход по вертикали

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```


Блеск сверху и снизу

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```


Протирание сверху вниз

### applyChanges() {#applyChanges--}
```
public void applyChanges()
```


Примените изменения, сделанные на страницах документа.

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


Удаляет документ, связанный с фасадом.

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
### getAlignment() {#getAlignment--}
```
public AlignmentType getAlignment()
```


Получает горизонтальное выравнивание исходного содержимого PDF на странице результатов, по умолчанию — AlignmentType.Left.
Вместо этого используйте getHorizontalAlignment

**Возвращает:**
[AlignmentType](../../com.aspose.pdf.facades/alignmenttype) - объект типа выравнивания
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDisplayDuration() {#getDisplayDuration--}
```
public int getDisplayDuration()
```


Получает продолжительность отображения для страниц.

**Возвращает:**
интервал - целочисленное значение
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает горизонтальное выравнивание исходного содержимого PDF на странице результатов, по умолчанию — AlignmentType.Left.

**Возвращает:**
int - элемент HorizontalAlignment
### getPageBoxSize(int page, String pageBoxName) {#getPageBoxSize-int-java.lang.String-}
```
public Rectangle getPageBoxSize(int page, String pageBoxName)
```


Возвращает размер указанного блока в документе.

--------------------

```
The following example demonstrates how to get media box of the 1st page:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 Rectangle rect = editor.getBoxSize(1, "media");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Индекс страницы. Страницы документа нумеруются с 1. |
| pageBoxName | java.lang.String | Имя типа ящика. Допустимые значения: «art», «bleed», «crop», «media», «trim». |

**Возвращает:**
[Rectangle](../../java.awt/rectangle) - Прямоугольник, содержащий запрошенное поле.
### getPageRotation(int page) {#getPageRotation-int-}
```
public int getPageRotation(int page)
```


Возвращает поворот указанной страницы.

--------------------

```
The following example demonstrates how to get page rotation:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 int rotation = editor.getPageSize(1);
 System.out.println("Rotation of 1st page : " + rotation + " degrees");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Индекс страницы. Страницы документа нумеруются с 1. |

**Возвращает:**
int - поворот страницы в градусах.
### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Integer> getPageRotations()
```


Получает поворот страниц. Хеш-таблица содержит номер страницы и степень поворота, ключ представляет номер страницы, значение ключа представляет поворот в градусах.

**Возвращает:**
java.util.Map<java.lang.Integer,java.lang.Integer> — объект карты
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Получает размер страницы выходного файла.

**Возвращает:**
[PageSize](../../com.aspose.pdf/pagesize) - объект PageSize
### getPageSize(int page) {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```


Возвращает размер указанной страницы.

--------------------

```
The following example demonstrates using of GetPageSize method:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 PageSize size = editor.getPageSize(1);
 System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight());
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Индекс страницы. Страницы документа нумеруются с 1. |

**Возвращает:**
[PageSize](../../com.aspose.pdf/pagesize) - Результат является экземпляром PageSize. Используйте свойства Width и Height возвращаемого объекта, чтобы получить ширину и высоту страницы.
### getPages() {#getPages--}
```
public int getPages()
```


Возвращает общее количество страниц.

--------------------

```
The following example demonstrates using of GetPages() method:


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 System.out.println("Document has: " + editor.GetPages());
```

**Возвращает:**
int - Количество страниц.
### getProcessPages() {#getProcessPages--}
```
public int[] getProcessPages()
```


Получает номера страниц для редактирования. По умолчанию каждая страница будет редактироваться.

**Возвращает:**
инт[] - массив целых значений
### getRotation() {#getRotation--}
```
public int getRotation()
```


Получает поворот страниц, поворот должен быть 0, 90, 180 или 270. Значение по умолчанию — 0.

**Возвращает:**
интервал - целочисленное значение
### getTransitionDuration() {#getTransitionDuration--}
```
public int getTransitionDuration()
```


Получает продолжительность эффекта перехода.

**Возвращает:**
интервал - целочисленное значение
### getTransitionType() {#getTransitionType--}
```
public int getTransitionType()
```


Получает стиль перехода, используемый при переходе на эту страницу с другой во время презентации.

**Возвращает:**
интервал - целочисленное значение
### getVerticalAlignment() {#getVerticalAlignment--}
```
public VerticalAlignmentType getVerticalAlignment()
```


Получает вертикальное выравнивание исходного содержимого PDF на странице результатов. Значение по умолчанию — VerticalAlignmentType.Bottom.
Вместо этого используйте getVerticalAlignmentType.

**Возвращает:**
[VerticalAlignmentType](../../com.aspose.pdf.facades/verticalalignmenttype) - объект VerticalAlignmentType
### getVerticalAlignmentType() {#getVerticalAlignmentType--}
```
public int getVerticalAlignmentType()
```


Получает вертикальное выравнивание исходного содержимого PDF на странице результатов. Значение по умолчанию — VerticalAlignmentType.Bottom.

**Возвращает:**
int — элемент VerticalAlignmentType
### getZoom() {#getZoom--}
```
public float getZoom()
```


Получить коэффициент масштабирования. Значение 1,0 соответствует 100%. Значение по умолчанию — 1,0.

**Возвращает:**
float - плавающее значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### movePosition(float moveX, float moveY) {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```


Перемещает начало координат из (0, 0) в назначенную точку. Происхождение находится слева внизу, а единица измерения - точка (1 дюйм = 72 точки).

--------------------

```
PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("input.pdf");
 editor.movePosition(-100, 60);
 editor.save("moved.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| moveX | float | X-координата. |
| moveY | float | Y-координата. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Сохраняет измененный документ в поток.

--------------------

```
The following sample demonstrates how to save changed PDF document into stream.


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 editor.setZoom ( 0.5f);
 editor.save("newdocument.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток, в котором будет сохранен измененный PDF-документ. |

### save(String outputFile) {#save-java.lang.String-}
```
public void save(String outputFile)
```


Сохраняет измененный документ в файл.

--------------------

```
The following sample demonstrates how to save changed PDF document


 PdfPageEditor editor = new PdfPageEditor();
 editor.bindPdf("sample.pdf");
 editor.setZoom ( 0.5f);
 editor.save("newdocument.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь к файлу, в котором будет сохранен документ. |

### setAlignment(AlignmentType value) {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
```
public void setAlignment(AlignmentType value)
```


Задает горизонтальное выравнивание исходного содержимого PDF на странице результатов. По умолчанию используется значение AlignmentType.Left.
Вместо этого используйте setHorizontalAlignment

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [AlignmentType](../../com.aspose.pdf.facades/alignmenttype) | Значение типа выравнивания |

### setDisplayDuration(int value) {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```


Устанавливает продолжительность отображения страниц.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Задает горизонтальное выравнивание исходного содержимого PDF на странице результатов. По умолчанию используется значение AlignmentType.Left.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPageRotations(Map<Integer,Integer> value) {#setPageRotations-java.util.Map-java.lang.Integer-java.lang.Integer--}
```
public void setPageRotations(Map<Integer,Integer> value)
```


Устанавливает поворот страниц. Хеш-таблица содержит номер страницы и степень поворота, ключ представляет номер страницы, значение ключа представляет поворот в градусах.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Map<java.lang.Integer,java.lang.Integer> |  Объект карты |

### setPageSize(PageSize value) {#setPageSize-com.aspose.pdf.PageSize-}
```
public void setPageSize(PageSize value)
```


Устанавливает размер страницы выходного файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.pdf/pagesize) | Объект PageSize |

### setProcessPages(int[] value) {#setProcessPages-int---}
```
public void setProcessPages(int[] value)
```


Устанавливает номера страниц для редактирования. По умолчанию каждая страница будет редактироваться.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | массив значений int |

### setRotation(int value) {#setRotation-int-}
```
public void setRotation(int value)
```


Устанавливает поворот страниц, поворот должен быть 0, 90, 180 или 270. Значение по умолчанию 0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setTransitionDuration(int value) {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```


Устанавливает продолжительность эффекта перехода.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setTransitionType(int value) {#setTransitionType-int-}
```
public void setTransitionType(int value)
```


Задает стиль перехода, используемый при переходе на эту страницу с другой во время презентации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setVerticalAlignment(VerticalAlignmentType value) {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
```
public void setVerticalAlignment(VerticalAlignmentType value)
```


Задает вертикальное выравнивание исходного содержимого PDF на странице результатов. Значение по умолчанию — VerticalAlignmentType.Bottom.
Вместо этого используйте setVerticalAlignmentType.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VerticalAlignmentType](../../com.aspose.pdf.facades/verticalalignmenttype) | Значение Вертикальалигнменттипе |

### setVerticalAlignmentType(int value) {#setVerticalAlignmentType-int-}
```
public void setVerticalAlignmentType(int value)
```


Задает вертикальное выравнивание исходного содержимого PDF на странице результатов. Значение по умолчанию — VerticalAlignmentType.Bottom.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

### setZoom(float value) {#setZoom-float-}
```
public void setZoom(float value)
```


Устанавливает коэффициент масштабирования. Значение 1,0 соответствует 100%. Значение по умолчанию — 1,0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение

--------------------

```
The following example demonstrates how to change zoom of the document pages.


                 PdfPageEditor editor = new PdfPageEditor();
                 editor.bindPdf("sample.pdf");
                 editor.setZoom ( 0.5f);
``` |

### toString() {#toString--}
```
публичная строка toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
публичный окончательный недействительный ожидание ()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
