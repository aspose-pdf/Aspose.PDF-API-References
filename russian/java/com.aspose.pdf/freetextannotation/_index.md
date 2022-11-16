---
title: FreeTextAnnotation
second_title: Aspose.PDF для справки по Java API
description: Представляет аннотацию произвольного текста, отображающую текст непосредственно на странице.
type: docs
weight: 142
url: /ru/java/com.aspose.pdf/freetextannotation/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Представляет аннотацию произвольного текста, отображающую текст непосредственно на странице. В отличие от обычной текстовой аннотации, аннотация произвольного текста не имеет открытого или закрытого состояния; вместо того, чтобы отображаться во всплывающем окне, текст всегда виден.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FreeTextAnnotation(IDocument document, DefaultAppearance appearance)](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Конструктор для использования с генератором. |
| [FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance)](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Создает новую аннотацию FreeText на указанной странице. |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Принимает объект посетителя для обработки аннотации. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Обновите параметры и внешний вид в соответствии с преобразованием матрицы. |
| [createAnnotation(IPdfObject annotEngineObj, Page page)](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Только для внутреннего использования |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Помещает содержимое аннотации непосредственно на страницу, объект аннотации будет удален. |
| [getActiveState()](#getActiveState--) | Получает текущее состояние внешнего вида аннотации. |
| [getAlignment()](#getAlignment--) | Выравнивание аннотации. |
| [getAnnotationType()](#getAnnotationType--) | Получает тип аннотации. |
| [getAppearance()](#getAppearance--) | Получает словарь внешнего вида аннотации. |
| [getBorder()](#getBorder--) | Получает характеристики границы аннотации. |
| [getCallout()](#getCallout--) | Массив точек, указывающих линию выноски. |
| [getCharacteristics()](#getCharacteristics--) | Получает характеристики аннотации. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает цвет аннотации. |
| [getContents()](#getContents--) | Получает текст аннотации. |
| [getCreationDate()](#getCreationDate--) | Получает дату и время создания аннотации. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Получает строку внешнего вида по умолчанию, которая будет использоваться при форматировании текста. |
| [getDefaultAppearanceObject()](#getDefaultAppearanceObject--) | Объект, представляющий внешний вид аннотации FreeText по умолчанию. |
| [getDefaultStyle()](#getDefaultStyle--) | Получает строку стиля по умолчанию. |
| [getEndingStyle()](#getEndingStyle--) | Получает стиль окончания строки для конечной точки строки. |
| [getEngineDict()](#getEngineDict--) | Только внутренний |
| [getEngineObj()](#getEngineObj--) | Только для внутреннего использования |
| [getFlags()](#getFlags--) | Получить флаги аннотации. |
| [getFullName()](#getFullName--) | Получает полное квалифицированное имя аннотации. |
| [getHeight()](#getHeight--) | Получает высоту аннотации. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание абзаца |
| [getHorizontalAlignment_Annotation_New()](#getHorizontalAlignment-Annotation-New--) | Получает или задает выравнивание текста для аннотации. |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getInReplyTo()](#getInReplyTo--) | Ссылка на аннотацию, на которую эта аннотация является «ответом». |
| [getIntent()](#getIntent--) | Получает назначение произвольной текстовой аннотации. |
| [getJustification()](#getJustification--) | Получает код, указывающий форму квадрирования (выравнивания), которая будет использоваться при отображении текста аннотации. |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getModified()](#getModified--) | Получает дату и время последнего изменения аннотации. |
| [getModifiedInternal()](#getModifiedInternal--) | Получает дату и время последнего изменения аннотации. |
| [getName()](#getName--) | Получает имя аннотации на странице. |
| [getNormalAppearance()](#getNormalAppearance--) | Принимает нормальный вид. |
| [getOpacity()](#getOpacity--) | Получает постоянное значение непрозрачности, используемое при рисовании аннотации. |
| [getPage()](#getPage--) | Получает объект страницы, с которым связана эта аннотация. |
| [getPageIndex()](#getPageIndex--) | Получает индекс страницы, содержащей аннотацию. |
| [getPageIndex(Annotation annotation)](#getPageIndex-com.aspose.pdf.Annotation-) | Получает индекс страницы, содержащей аннотацию. |
| [getPdfActions()](#getPdfActions--) | Получает список действий аннотации. |
| [getPopup()](#getPopup--) | Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией. |
| [getRect()](#getRect--) | Получает прямоугольник аннотации. |
| [getRectangle(boolean considerRotation)](#getRectangle-boolean-) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [getReplyType()](#getReplyType--) | Строка, указывающая связь («тип ответа») между этой аннотацией и аннотацией, указанной InReplyTo. |
| [getRichText()](#getRichText--) | Получает строку форматированного текста, которая будет отображаться во всплывающем окне при открытии аннотации. |
| [getRotate()](#getRotate--) | Угол поворота аннотации. |
| [getStartingStyle()](#getStartingStyle--) | Получает или задает стиль окончания линии для конечной точки линии. |
| [getStates()](#getStates--) | Получает словарь внешнего вида аннотации. |
| [getSubject()](#getSubject--) | Получает текст, представляющий описание объекта. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Получает выравнивание текста для аннотации. |
| [getTextRectangle()](#getTextRectangle--) | Прямоугольник, описывающий числовые различия между двумя прямоугольниками: запись Rect аннотации и прямоугольник, содержащийся в этом прямоугольнике. |
| [getTextStyle()](#getTextStyle--) | Получает или задает стиль текста во внешнем виде. при изменении стиля текста обновляется внешний вид текста. |
| [getTitle()](#getTitle--) | Получает текст, который должен отображаться в строке заголовка аннотации. |
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
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Устанавливает текущее состояние внешнего вида аннотации. |
| [setAlignment(int value)](#setAlignment-int-) | Выравнивание аннотации. |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | Задает характеристики границы аннотации. |
| [setCallout(Point[] value)](#setCallout-com.aspose.pdf.Point---) | Массив точек, указывающих линию выноски. |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | Устанавливает цвет аннотации. |
| [setContents(String value)](#setContents-java.lang.String-) | Устанавливает текст аннотации. |
| [setDefaultAppearance(String value)](#setDefaultAppearance-java.lang.String-) | Задает строку внешнего вида по умолчанию, которая будет использоваться при форматировании текста. |
| [setDefaultStyle(String value)](#setDefaultStyle-java.lang.String-) | Задает строку стиля по умолчанию. |
| [setEndingStyle(int value)](#setEndingStyle-int-) | Устанавливает стиль окончания линии для конечной точки линии. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setFlags(int value)](#setFlags-int-) | Установите флаги аннотации. |
| [setHeight(double value)](#setHeight-double-) | Устанавливает высоту аннотации. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание абзаца |
| [setHorizontalAlignment_Annotation_New(int value)](#setHorizontalAlignment-Annotation-New-int-) | Получает или задает выравнивание текста для аннотации. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку (для генератора pdf). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setInReplyTo(Annotation value)](#setInReplyTo-com.aspose.pdf.Annotation-) | Ссылка на аннотацию, на которую эта аннотация является «ответом». |
| [setIntent(int value)](#setIntent-int-) | Задает назначение произвольной текстовой аннотации. |
| [setJustification(int value)](#setJustification-int-) | Задает код, указывающий форму квадрирования (выравнивания), которая будет использоваться при отображении текста аннотации. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setModified(Date value)](#setModified-java.util.Date-) | Устанавливает дату и время последнего изменения аннотации. |
| [setModifiedInternal(System.DateTime value)](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Устанавливает дату и время последнего изменения аннотации. |
| [setName(String value)](#setName-java.lang.String-) | Задает имя аннотации на странице. |
| [setOpacity(double value)](#setOpacity-double-) | Задает постоянное значение непрозрачности, которое будет использоваться при рисовании аннотации. |
| [setPopup(PopupAnnotation value)](#setPopup-com.aspose.pdf.PopupAnnotation-) | Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Задает прямоугольник аннотации. |
| [setReplyType(int value)](#setReplyType-int-) | Строка, указывающая связь («тип ответа») между этой аннотацией и аннотацией, указанной InReplyTo. |
| [setRichText(String value)](#setRichText-java.lang.String-) | Задает форматированную текстовую строку, которая будет отображаться во всплывающем окне при открытии аннотации. |
| [setRotate(int value)](#setRotate-int-) | Угол поворота аннотации. |
| [setStartingStyle(int value)](#setStartingStyle-int-) | Получает или задает стиль окончания линии для конечной точки линии. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Задает текст, представляющий описание объекта. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Устанавливает выравнивание текста для аннотации. |
| [setTextRectangle(Rectangle value)](#setTextRectangle-com.aspose.pdf.Rectangle-) | Прямоугольник, описывающий числовые различия между двумя прямоугольниками: запись Rect аннотации и прямоугольник, содержащийся в этом прямоугольнике. |
| [setTextStyle(TextStyle value)](#setTextStyle-com.aspose.pdf.TextStyle-) | Задает стиль текста во внешнем виде. при изменении стиля текста обновляется внешний вид текста. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Задает текст, который должен отображаться в строке заголовка аннотации. |
| [setUpdateAppearanceOnConvert(boolean value)](#setUpdateAppearanceOnConvert-boolean-) | Если установлено значение true, внешний вид аннотации будет обновлен перед преобразованием документа PF в изображение. |
| [setUseFontSubset(boolean value)](#setUseFontSubset-boolean-) | Если для этого свойства установлено значение true, шрифты будут добавляться в документ как подмножества. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setWidth(double value)](#setWidth-double-) | Устанавливает ширину аннотации. |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [updateAppearance()](#updateAppearance--) | Обновляет внешний вид после изменения/перемещения текста. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FreeTextAnnotation(IDocument document, DefaultAppearance appearance) {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
```
public FreeTextAnnotation(IDocument document, DefaultAppearance appearance)
```


Конструктор для использования с генератором.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ, в котором будет создана аннотация. |
| appearance | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | Внешний вид по умолчанию |

### FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance) {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
```
public FreeTextAnnotation(Page page, Rectangle rect, DefaultAppearance appearance)
```


Создает новую аннотацию FreeText на указанной странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница документа, на которой должна быть создана аннотация. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник аннотации, определяющий расположение аннотации на странице. |
| appearance | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | Строка оформления по умолчанию, используемая при форматировании текста. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Принимает объект посетителя для обработки аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Объект посетителя. |

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
интервал - целочисленное значение
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
### getCallout() {#getCallout--}
```
public final Point[] getCallout()
```


Массив точек, указывающих линию выноски.

**Возвращает:**
com.aspose.pdf.Point[] - массив точек
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
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Получает дату и время создания аннотации.

**Возвращает:**
[Date](../../java.util/date) - Объект даты
### getDefaultAppearance() {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```


Получает строку внешнего вида по умолчанию, которая будет использоваться при форматировании текста.

**Возвращает:**
java.lang.String — строковое значение
### getDefaultAppearanceObject() {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```


Объект, представляющий внешний вид аннотации FreeText по умолчанию.

**Возвращает:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) - Объект DefaultAppearance
### getDefaultStyle() {#getDefaultStyle--}
```
public String getDefaultStyle()
```


Получает строку стиля по умолчанию.

**Возвращает:**
java.lang.String — строковое значение
### getEndingStyle() {#getEndingStyle--}
```
public int getEndingStyle()
```


Получает стиль окончания строки для конечной точки строки.

**Возвращает:**
int - значение LineEnding
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
### getInReplyTo() {#getInReplyTo--}
```
public Annotation getInReplyTo()
```


Ссылка на аннотацию, на которую эта аннотация является «ответом». Обе аннотации должны быть на одной странице документа.

**Возвращает:**
[Annotation](../../com.aspose.pdf/annotation) - Значение аннотации
### getIntent() {#getIntent--}
```
public int getIntent()
```


Получает назначение произвольной текстовой аннотации.

**Возвращает:**
интервал - целочисленное значение
### getJustification() {#getJustification--}
```
public int getJustification()
```


Получает код, указывающий форму квадрирования (выравнивания), которая будет использоваться при отображении текста аннотации.

**Возвращает:**
интервал - целочисленное значение
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
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Получает постоянное значение непрозрачности, используемое при рисовании аннотации.

**Возвращает:**
двойное - двойное значение
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
### getPopup() {#getPopup--}
```
public PopupAnnotation getPopup()
```


Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией.

**Возвращает:**
[PopupAnnotation](../../com.aspose.pdf/popupannotation) - Значение всплывающей аннотации
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
### getReplyType() {#getReplyType--}
```
public int getReplyType()
```


Строка, указывающая связь («тип ответа») между этой аннотацией и аннотацией, указанной InReplyTo.

**Возвращает:**
int — значение типа ответа
### getRichText() {#getRichText--}
```
public String getRichText()
```


Получает строку форматированного текста, которая будет отображаться во всплывающем окне при открытии аннотации.

**Возвращает:**
java.lang.String — строковое значение
### getRotate() {#getRotate--}
```
public int getRotate()
```


Угол поворота аннотации.

**Возвращает:**
int - Элемент вращения
### getStartingStyle() {#getStartingStyle--}
```
public final int getStartingStyle()
```


Получает или задает стиль окончания линии для конечной точки линии. OЭто свойство устарело, используйте EndingStyle.

**Возвращает:**
int - элемент LineEnding
### getStates() {#getStates--}
```
public AppearanceDictionary getStates()
```


Получает словарь внешнего вида аннотации.

**Возвращает:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - Объект AppearanceDictionary
### getSubject() {#getSubject--}
```
public String getSubject()
```


Получает текст, представляющий описание объекта.

**Возвращает:**
java.lang.String — строковое значение
### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public int getTextHorizontalAlignment()
```


Получает выравнивание текста для аннотации.

**Возвращает:**
int - выравнивание текста для аннотации.
### getTextRectangle() {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```


Прямоугольник, описывающий числовые различия между двумя прямоугольниками: запись Rect аннотации и прямоугольник, содержащийся в этом прямоугольнике. Во внутреннем прямоугольнике находится аннотация\Должен отображаться текст \ufffds.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Экземпляр прямоугольника
### getTextStyle() {#getTextStyle--}
```
public TextStyle getTextStyle()
```


Получает или задает стиль текста во внешнем виде. при изменении стиля текста обновляется внешний вид текста.

**Возвращает:**
[TextStyle](../../com.aspose.pdf/textstyle) - значение стиля текста
### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает текст, который должен отображаться в строке заголовка аннотации.

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

### setCallout(Point[] value) {#setCallout-com.aspose.pdf.Point---}
```
public final void setCallout(Point[] value)
```


Массив точек, указывающих линию выноски.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.pdf/point) | массив точек |

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

### setDefaultAppearance(String value) {#setDefaultAppearance-java.lang.String-}
```
public void setDefaultAppearance(String value)
```


Задает строку внешнего вида по умолчанию, которая будет использоваться при форматировании текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setDefaultStyle(String value) {#setDefaultStyle-java.lang.String-}
```
public void setDefaultStyle(String value)
```


Задает строку стиля по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setEndingStyle(int value) {#setEndingStyle-int-}
```
public void setEndingStyle(int value)
```


Устанавливает стиль окончания линии для конечной точки линии.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение LineEnding |

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

### setInReplyTo(Annotation value) {#setInReplyTo-com.aspose.pdf.Annotation-}
```
public void setInReplyTo(Annotation value)
```


Ссылка на аннотацию, на которую эта аннотация является «ответом». Обе аннотации должны быть на одной странице документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Annotation](../../com.aspose.pdf/annotation) | Значение аннотации |

### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Задает назначение произвольной текстовой аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setJustification(int value) {#setJustification-int-}
```
public void setJustification(int value)
```


Задает код, указывающий форму квадрирования (выравнивания), которая будет использоваться при отображении текста аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

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

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Задает постоянное значение непрозрачности, которое будет использоваться при рисовании аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setPopup(PopupAnnotation value) {#setPopup-com.aspose.pdf.PopupAnnotation-}
```
public void setPopup(PopupAnnotation value)
```


Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PopupAnnotation](../../com.aspose.pdf/popupannotation) | Значение PopupAnnotation |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


Задает прямоугольник аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Значение прямоугольника |

### setReplyType(int value) {#setReplyType-int-}
```
public void setReplyType(int value)
```


Строка, указывающая связь («тип ответа») между этой аннотацией и аннотацией, указанной InReplyTo.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение типа ответа |

### setRichText(String value) {#setRichText-java.lang.String-}
```
public void setRichText(String value)
```


Задает форматированную текстовую строку, которая будет отображаться во всплывающем окне при открытии аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


Угол поворота аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вращения |

### setStartingStyle(int value) {#setStartingStyle-int-}
```
public final void setStartingStyle(int value)
```


Получает или задает стиль окончания линии для конечной точки линии. OЭто свойство устарело, используйте EndingStyle.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент LineEnding |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Задает текст, представляющий описание объекта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public void setTextHorizontalAlignment(int value)
```


Устанавливает выравнивание текста для аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | выравнивание текста для аннотации. |

### setTextRectangle(Rectangle value) {#setTextRectangle-com.aspose.pdf.Rectangle-}
```
public final void setTextRectangle(Rectangle value)
```


Прямоугольник, описывающий числовые различия между двумя прямоугольниками: запись Rect аннотации и прямоугольник, содержащийся в этом прямоугольнике. Во внутреннем прямоугольнике находится аннотация\Должен отображаться текст \ufffds.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Экземпляр прямоугольника |

### setTextStyle(TextStyle value) {#setTextStyle-com.aspose.pdf.TextStyle-}
```
public void setTextStyle(TextStyle value)
```


Задает стиль текста во внешнем виде. при изменении стиля текста обновляется внешний вид текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextStyle](../../com.aspose.pdf/textstyle) | Объект TextStyle |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Задает текст, который должен отображаться в строке заголовка аннотации.

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
### updateAppearance() {#updateAppearance--}
```
public void updateAppearance()
```


Обновляет внешний вид после изменения/перемещения текста.

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
