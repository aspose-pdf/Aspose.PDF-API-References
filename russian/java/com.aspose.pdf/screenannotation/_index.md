---
title: ScreenAnnotation
second_title: Aspose.PDF для справки по Java API
description: Аннотация экрана, указывающая область страницы, на которой могут воспроизводиться медиаклипы.
type: docs
weight: 321
url: /ru/java/com.aspose.pdf/screenannotation/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)

**Все реализованные интерфейсы:**
[com.aspose.pdf.engine.ITitledAnnotation](../../com.aspose.pdf.engine/ititledannotation)
```
public final class ScreenAnnotation extends Annotation implements ITitledAnnotation
```

Аннотация экрана, указывающая область страницы, на которой могут воспроизводиться медиаклипы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ScreenAnnotation(Page page, Rectangle rect, String mediaFile)](#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Создает новую аннотацию экрана на указанной странице. |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Представлять метод принятия |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Обновите параметры и внешний вид в соответствии с преобразованием матрицы. |
| [createAnnotation(IPdfObject annotEngineObj, Page page)](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Только для внутреннего использования |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален. |
| [getAction()](#getAction--) | Получает действие, которое должно быть выполнено при активации аннотации. |
| [getActiveState()](#getActiveState--) | Получает текущее состояние внешнего вида аннотации. |
| [getAlignment()](#getAlignment--) | Выравнивание аннотации. |
| [getAnnotationType()](#getAnnotationType--) | Получает тип аннотации. |
| [getAppearance()](#getAppearance--) | Получает словарь внешнего вида аннотации. |
| [getBorder()](#getBorder--) | Получает характеристики границы аннотации. |
| [getCharacteristics()](#getCharacteristics--) | Получает характеристики аннотации. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает цвет аннотации. |
| [getContents()](#getContents--) | Получает текст аннотации. |
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
| [getTitle()](#getTitle--) | Получает заголовок аннотации экрана. |
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
| [setAction(PdfAction value)](#setAction-com.aspose.pdf.PdfAction-) | Задает действие, которое будет выполняться при активации аннотации. |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Устанавливает текущее состояние внешнего вида аннотации. |
| [setAlignment(int value)](#setAlignment-int-) | Выравнивание аннотации. |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | Задает характеристики границы аннотации. |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | Устанавливает цвет аннотации. |
| [setContents(String value)](#setContents-java.lang.String-) | Устанавливает текст аннотации. |
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
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Задает прямоугольник аннотации. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Устанавливает выравнивание текста для аннотации. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Устанавливает заголовок аннотации экрана. |
| [setUpdateAppearanceOnConvert(boolean value)](#setUpdateAppearanceOnConvert-boolean-) | Если установлено значение true, внешний вид аннотации будет обновлен перед преобразованием документа PF в изображение. |
| [setUseFontSubset(boolean value)](#setUseFontSubset-boolean-) | Если для этого свойства установлено значение true, шрифты будут добавляться в документ как подмножества. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setWidth(double value)](#setWidth-double-) | Устанавливает ширину аннотации. |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ScreenAnnotation(Page page, Rectangle rect, String mediaFile) {#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
```
public ScreenAnnotation(Page page, Rectangle rect, String mediaFile)
```


Создает новую аннотацию экрана на указанной странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница документа, на которой должна быть создана аннотация. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| mediaFile | java.lang.String | Путь к мультимедийному файлу. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Представлять метод принятия

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Объект AnnotationSelector |

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

### getAction() {#getAction--}
```
public PdfAction getAction()
```


Получает действие, которое должно быть выполнено при активации аннотации.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
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
### getContents() {#getContents--}
```
public String getContents()
```


Получает текст аннотации.

**Возвращает:**
java.lang.String — строковое значение
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
### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает заголовок аннотации экрана.

**Возвращает:**
java.lang.String — строковое значение
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




### setAction(PdfAction value) {#setAction-com.aspose.pdf.PdfAction-}
```
public void setAction(PdfAction value)
```


Задает действие, которое будет выполняться при активации аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

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

### setContents(String value) {#setContents-java.lang.String-}
```
public void setContents(String value)
```


Устанавливает текст аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

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

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Устанавливает заголовок аннотации экрана.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

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
