---
title: RichMediaAnnotation
second_title: Aspose.PDF для справки по Java API
description: Класс описывает RichMediaAnnotation, который позволяет вставлять видео/аудиоданные в документ PDF.
type: docs
weight: 312
url: /ru/java/com.aspose.pdf/richmediaannotation/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)
```
public class RichMediaAnnotation extends Annotation
```

Класс описывает RichMediaAnnotation, который позволяет вставлять видео/аудиоданные в документ PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RichMediaAnnotation(Page page, Rectangle rect)](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Инициализирует RichMediaAnnotation. |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Принимает посетителей для этой аннотации. |
| [addCustomData(String name, InputStream data)](#addCustomData-java.lang.String-java.io.InputStream-) | Добавьте пользовательские именованные данные (например, необходимые для flash-скрипта). |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Обновите параметры и внешний вид в соответствии с преобразованием матрицы. |
| [createAnnotation(IPdfObject annotEngineObj, Page page)](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Только для внутреннего использования |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален. |
| [getActivateOn()](#getActivateOn--) | Событие, которое активирует приложение. |
| [getActiveState()](#getActiveState--) | Получает текущее состояние внешнего вида аннотации. |
| [getAlignment()](#getAlignment--) | Выравнивание аннотации. |
| [getAnnotationType()](#getAnnotationType--) | Получает тип аннотации. |
| [getAppearance()](#getAppearance--) | Получает словарь внешнего вида аннотации. |
| [getBorder()](#getBorder--) | Получает характеристики границы аннотации. |
| [getCharacteristics()](#getCharacteristics--) | Получает характеристики аннотации. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает цвет аннотации. |
| [getContent()](#getContent--) | Данные о мультимедийном контенте. |
| [getContents()](#getContents--) | Получает текст аннотации. |
| [getCustomFlashVariables()](#getCustomFlashVariables--) | Устанавливает или получает flash-переменные, которые передаются игроку. |
| [getCustomPlayer()](#getCustomPlayer--) | Устанавливает или получает настраиваемый флэш-плеер для воспроизведения видео/аудиоданных. |
| [getEngineDict()](#getEngineDict--) | Только внутренний |
| [getEngineObj()](#getEngineObj--) | Только для внутреннего использования |
| [getFlags()](#getFlags--) | Получить флаги аннотации. |
| [getFullName()](#getFullName--) | Получает полное квалифицированное имя аннотации. |
| [getHeight()](#getHeight--) | Получает высоту аннотации. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание абзаца |
| [getHorizontalAlignment_Annotation_New()](#getHorizontalAlignment-Annotation-New--) | Получает или задает выравнивание текста для аннотации. |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getModified()](#getModified--) | Получает дату и время последнего изменения аннотации. |
| [getModifiedInternal()](#getModifiedInternal--) | Получает дату и время последнего изменения аннотации. |
| [getName()](#getName--) | Получает имя аннотации на странице. |
| [getNormalAppearance()](#getNormalAppearance--) | Принимает нормальный вид. |
| [getPage()](#getPage--) | Получает объект страницы, с которым связана эта аннотация. |
| [getPageIndex()](#getPageIndex--) | Получает индекс страницы, содержащей аннотацию. |
| [getPageIndex(Annotation annotation)](#getPageIndex-com.aspose.pdf.Annotation-) | Получает индекс страницы, содержащей аннотацию. |
| [getPdfActions()](#getPdfActions--) | Получает список действий аннотации. |
| [getRect()](#getRect--) | Получает прямоугольник аннотации. |
| [getRectangle(boolean considerRotation)](#getRectangle-boolean-) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [getStates()](#getStates--) | Получает словарь внешнего вида аннотации. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Получает выравнивание текста для аннотации. |
| [getType()](#getType--) | Получает или задает тип содержимого. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание абзаца |
| [getWidth()](#getWidth--) | Получает ширину аннотации. |
| [getZIndex()](#getZIndex--) | Получает значение int, указывающее Z-порядок графика. |
| [hashCode()](#hashCode--) |  |
| [initialize(IDocument doc)](#initialize-com.aspose.pdf.IDocument-) | Инициализация экземпляра |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [isInLineParagraph()](#isInLineParagraph--) | Получает абзац встроенным. |
| [isInNewPage()](#isInNewPage--) | Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [isKeptWithNext()](#isKeptWithNext--) | Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. |
| [isUpdateAppearanceOnConvert()](#isUpdateAppearanceOnConvert--) | Если установлено значение true, внешний вид аннотации будет обновлен перед преобразованием документа PF в изображение. |
| [isUseFontSubset()](#isUseFontSubset--) | Если для этого свойства установлено значение true, шрифты будут добавляться в документ как подмножества. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActivateOn(int value)](#setActivateOn-int-) | Событие, которое активирует приложение. |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Устанавливает текущее состояние внешнего вида аннотации. |
| [setAlignment(int value)](#setAlignment-int-) | Выравнивание аннотации. |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | Задает характеристики границы аннотации. |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | Устанавливает цвет аннотации. |
| [setContent(String fileName, InputStream audio)](#setContent-java.lang.String-java.io.InputStream-) | Установить поток контента. |
| [setContents(String value)](#setContents-java.lang.String-) | Устанавливает текст аннотации. |
| [setCustomFlashVariables(String value)](#setCustomFlashVariables-java.lang.String-) | Устанавливает или получает flash-переменные, которые передаются игроку. |
| [setCustomPlayer(InputStream value)](#setCustomPlayer-java.io.InputStream-) | Устанавливает или получает настраиваемый флэш-плеер для воспроизведения видео/аудиоданных. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setFlags(int value)](#setFlags-int-) | Установите флаги аннотации. |
| [setHeight(double value)](#setHeight-double-) | Устанавливает высоту аннотации. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание абзаца |
| [setHorizontalAlignment_Annotation_New(int value)](#setHorizontalAlignment-Annotation-New-int-) | Получает или задает выравнивание текста для аннотации. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку (для генератора pdf). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setModified(Date value)](#setModified-java.util.Date-) | Устанавливает дату и время последнего изменения аннотации. |
| [setModifiedInternal(System.DateTime value)](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Устанавливает дату и время последнего изменения аннотации. |
| [setName(String value)](#setName-java.lang.String-) | Задает имя аннотации на странице. |
| [setPoster(InputStream imageStream)](#setPoster-java.io.InputStream-) | Установите плакат аннотации. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Задает прямоугольник аннотации. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Устанавливает выравнивание текста для аннотации. |
| [setType(int value)](#setType-int-) | Получает или задает тип содержимого. |
| [setUpdateAppearanceOnConvert(boolean value)](#setUpdateAppearanceOnConvert-boolean-) | Если установлено значение true, внешний вид аннотации будет обновлен перед преобразованием документа PF в изображение. |
| [setUseFontSubset(boolean value)](#setUseFontSubset-boolean-) | Если для этого свойства установлено значение true, шрифты будут добавляться в документ как подмножества. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setWidth(double value)](#setWidth-double-) | Устанавливает ширину аннотации. |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [update()](#update--) | Обновляет данные с заданными параметрами. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RichMediaAnnotation(Page page, Rectangle rect) {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public RichMediaAnnotation(Page page, Rectangle rect)
```


Инициализирует RichMediaAnnotation.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница, на которой создается объект. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Координаты прямоугольника. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Принимает посетителей для этой аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Экземпляр посетителя. |

### addCustomData(String name, InputStream data) {#addCustomData-java.lang.String-java.io.InputStream-}
```
public void addCustomData(String name, InputStream data)
```


Добавьте пользовательские именованные данные (например, необходимые для flash-скрипта).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя данных. |
| data | java.io.InputStream | Данные. |

### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Обновите параметры и внешний вид в соответствии с преобразованием матрицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Матрица, используемая для преобразования (изменения размера). |

### createAnnotation(IPdfObject annotEngineObj, Page page) {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
```
public static Annotation createAnnotation(IPdfObject annotEngineObj, Page page)
```


Только для внутреннего использования

Инициализирует аннотацию из объекта PDF, который описывает аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotEngineObj | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | Объект PDF, описывающий аннотацию |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |

**Возвращает:**
[Annotation](../../com.aspose.pdf/annotation) - Создан объект аннотации соответствующего типа
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонирует этот экземпляр. Виртуальный метод. Всегда возвращайте ноль.

**Возвращает:**
java.lang.Object — ноль
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
### flatten() {#flatten--}
```
public void flatten()
```


Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален.

### getActivateOn() {#getActivateOn--}
```
public int getActivateOn()
```


Событие, которое активирует приложение.

**Возвращает:**
int — элемент ActivationEvent
### getActiveState() {#getActiveState--}
```
public String getActiveState()
```


Получает текущее состояние внешнего вида аннотации.

**Возвращает:**
java.lang.String — строковое значение
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Выравнивание аннотации. Это свойство устарело. Используйте getHorizontalAlignment\_Аннотация\_Новый вместо этого.

**Возвращает:**
int - элемент TextAlignment
### getAnnotationType() {#getAnnotationType--}
```
public int getAnnotationType()
```


Получает тип аннотации.

**Возвращает:**
int — элемент AnnotationType
### getAppearance() {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```


Получает словарь внешнего вида аннотации.

**Возвращает:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - Объект AppearanceDictionary
### getBorder() {#getBorder--}
```
public Border getBorder()
```


Получает характеристики границы аннотации. Граница 

**Возвращает:**
[Border](../../com.aspose.pdf/border) - Пограничный объект
### getCharacteristics() {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```


Получает характеристики аннотации.

**Возвращает:**
[Characteristics](../../com.aspose.pdf/characteristics) - Характеристики объекта
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Получает цвет аннотации.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цвет объекта
### getContent() {#getContent--}
```
public InputStream getContent()
```


Данные о мультимедийном контенте.

**Возвращает:**
java.io.InputStream — объект InputStream
### getContents() {#getContents--}
```
public String getContents()
```


Получает текст аннотации.

**Возвращает:**
java.lang.String — строковое значение
### getCustomFlashVariables() {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```


Устанавливает или получает flash-переменные, которые передаются игроку.

**Возвращает:**
java.lang.String — строковый объект
### getCustomPlayer() {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```


Устанавливает или получает настраиваемый флэш-плеер для воспроизведения видео/аудиоданных.

**Возвращает:**
java.io.InputStream — объект InputStream
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


Только внутренний

**Возвращает:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - Объект IPdfDictionary
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


Только для внутреннего использования

**Возвращает:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) - Внутреннее включение
### getFlags() {#getFlags--}
```
public int getFlags()
```


Получить флаги аннотации.

**Возвращает:**
int - Флаги аннотации
### getFullName() {#getFullName--}
```
public String getFullName()
```


Получает полное квалифицированное имя аннотации.

**Возвращает:**
java.lang.String — строковое значение
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получает высоту аннотации.

**Возвращает:**
double - высота аннотации
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает горизонтальное выравнивание абзаца

**Возвращает:**
int - значение HorizontalAlignment
### getHorizontalAlignment_Annotation_New() {#getHorizontalAlignment-Annotation-New--}
```
public final int getHorizontalAlignment_Annotation_New()
```


Получает или задает выравнивание текста для аннотации.

**Возвращает:**
int - выравнивание текста для аннотации.
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Получает гиперссылку фрагмента (для генератора pdf).

**Возвращает:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - гиперссылка на фрагмент (для генератора pdf).
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает внешнее поле для абзаца (для создания pdf)

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getModified() {#getModified--}
```
public Date getModified()
```


Получает дату и время последнего изменения аннотации.

**Возвращает:**
[Date](../../java.util/date) - дата и время последнего изменения аннотации.
### getModifiedInternal() {#getModifiedInternal--}
```
public System.DateTime getModifiedInternal()
```


Получает дату и время последнего изменения аннотации.

**Возвращает:**
com.aspose.ms.System.DateTime — объект DateTime
### getName() {#getName--}
```
public String getName()
```


Получает имя аннотации на странице.

**Возвращает:**
java.lang.String — строковое значение
### getNormalAppearance() {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```


Принимает нормальный вид.

**Возвращает:**
[XForm](../../com.aspose.pdf/xform) - XForm объект
### getPage() {#getPage--}
```
public Page getPage()
```


Получает объект страницы, с которым связана эта аннотация.

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Объект страницы
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Получает индекс страницы, содержащей аннотацию.

**Возвращает:**
интервал - целочисленное значение
### getPageIndex(Annotation annotation) {#getPageIndex-com.aspose.pdf.Annotation-}
```
public int getPageIndex(Annotation annotation)
```


Получает индекс страницы, содержащей аннотацию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Объект аннотации |

**Возвращает:**
интервал - целочисленное значение
### getPdfActions() {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```


Получает список действий аннотации.

**Возвращает:**
[PdfActionCollection](../../com.aspose.pdf/pdfactioncollection) - Экземпляр PdfActionCollection
### getRect() {#getRect--}
```
public Rectangle getRect()
```


Получает прямоугольник аннотации.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getRectangle(boolean considerRotation) {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```


Возвращает прямоугольник аннотации с учетом поворота страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| considerRotation | boolean | При значении true учитывается ротация страниц. |

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getStates() {#getStates--}
```
public AppearanceDictionary getStates()
```


Получает словарь внешнего вида аннотации.

**Возвращает:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - Объект AppearanceDictionary
### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public int getTextHorizontalAlignment()
```


Получает выравнивание текста для аннотации.

**Возвращает:**
int - выравнивание текста для аннотации.
### getType() {#getType--}
```
public int getType()
```


Получает или задает тип содержимого. Возможные значения: Аудио, Видео.

**Возвращает:**
int - значение ContentType
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает вертикальное выравнивание абзаца

**Возвращает:**
int - элемент вертикального выравнивания
### getWidth() {#getWidth--}
```
public double getWidth()
```


Получает ширину аннотации.

**Возвращает:**
double - двойное значение, ширина аннотации.
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Получает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### initialize(IDocument doc) {#initialize-com.aspose.pdf.IDocument-}
```
public void initialize(IDocument doc)
```


Инициализация экземпляра

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Объект IDocument |

### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Получает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isUpdateAppearanceOnConvert() {#isUpdateAppearanceOnConvert--}
```
public static synchronized boolean isUpdateAppearanceOnConvert()
```


Если установлено значение true, внешний вид аннотации будет обновлен перед преобразованием документа PF в изображение. Это позволяет корректно преобразовывать поля, но, вероятно, требует больше времени.

**Возвращает:**
boolean - логическое значение
### isUseFontSubset() {#isUseFontSubset--}
```
public static synchronized boolean isUseFontSubset()
```


Если для этого свойства установлено значение true, шрифты будут добавляться в документ как подмножества. Значение по умолчанию — истина.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setActivateOn(int value) {#setActivateOn-int-}
```
public void setActivateOn(int value)
```


Событие, которое активирует приложение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ActivationEvent |

### setActiveState(String value) {#setActiveState-java.lang.String-}
```
public void setActiveState(String value)
```


Устанавливает текущее состояние внешнего вида аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Выравнивание аннотации. Это свойство устарело. Используйте getHorizontalAlignment\_Аннотация\_Новый вместо этого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент TextAlignment |

### setBorder(Border value) {#setBorder-com.aspose.pdf.Border-}
```
public void setBorder(Border value)
```


Задает характеристики границы аннотации. Граница 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Border](../../com.aspose.pdf/border) | Значение границы |

### setColor(Color value) {#setColor-com.aspose.pdf.Color-}
```
public void setColor(Color value)
```


Устанавливает цвет аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Значение цвета |

### setContent(String fileName, InputStream audio) {#setContent-java.lang.String-java.io.InputStream-}
```
public void setContent(String fileName, InputStream audio)
```


Установить поток контента.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя потока. |
| audio | java.io.InputStream | Поток данных. |

### setContents(String value) {#setContents-java.lang.String-}
```
public void setContents(String value)
```


Устанавливает текст аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setCustomFlashVariables(String value) {#setCustomFlashVariables-java.lang.String-}
```
public void setCustomFlashVariables(String value)
```


Устанавливает или получает flash-переменные, которые передаются игроку.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setCustomPlayer(InputStream value) {#setCustomPlayer-java.io.InputStream-}
```
public void setCustomPlayer(InputStream value)
```


Устанавливает или получает настраиваемый флэш-плеер для воспроизведения видео/аудиоданных.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Объект InputStream |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Установите флаги аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | флаги аннотации |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Устанавливает высоту аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | высота аннотации |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Устанавливает горизонтальное выравнивание абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setHorizontalAlignment_Annotation_New(int value) {#setHorizontalAlignment-Annotation-New-int-}
```
public final void setHorizontalAlignment_Annotation_New(int value)
```


Получает или задает выравнивание текста для аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | выравнивание текста для аннотации. |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Устанавливает гиперссылку (для генератора pdf).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | гиперссылка (для генератора pdf). |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Устанавливает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает внешнее поле для абзаца (для создания pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setModified(Date value) {#setModified-java.util.Date-}
```
public void setModified(Date value)
```


Устанавливает дату и время последнего изменения аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Объект даты |

### setModifiedInternal(System.DateTime value) {#setModifiedInternal-com.aspose.ms.System.DateTime-}
```
public void setModifiedInternal(System.DateTime value)
```


Устанавливает дату и время последнего изменения аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | com.aspose.ms.System.DateTime | Объект DateTime |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Задает имя аннотации на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setPoster(InputStream imageStream) {#setPoster-java.io.InputStream-}
```
public void setPoster(InputStream imageStream)
```


Установите плакат аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Поток, содержащий изображение постера. |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


Задает прямоугольник аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Значение прямоугольника |

### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public void setTextHorizontalAlignment(int value)
```


Устанавливает выравнивание текста для аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | выравнивание текста для аннотации. |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Получает или задает тип содержимого. Возможные значения: Аудио, Видео.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ContentType |

### setUpdateAppearanceOnConvert(boolean value) {#setUpdateAppearanceOnConvert-boolean-}
```
public static synchronized void setUpdateAppearanceOnConvert(boolean value)
```


Если установлено значение true, внешний вид аннотации будет обновлен перед преобразованием документа PF в изображение. Это позволяет корректно преобразовывать поля, но, вероятно, требует больше времени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setUseFontSubset(boolean value) {#setUseFontSubset-boolean-}
```
public static synchronized void setUseFontSubset(boolean value)
```


Если для этого свойства установлено значение true, шрифты будут добавляться в документ как подмножества. Значение по умолчанию — истина.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Устанавливает ширину аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Ширина аннотации. |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### update() {#update--}
```
public void update()
```


Обновляет данные с заданными параметрами.

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
