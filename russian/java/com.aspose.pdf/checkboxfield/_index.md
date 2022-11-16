---
title: CheckboxField
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий поле флажка
type: docs
weight: 59
url: /ru/java/com.aspose.pdf/checkboxfield/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field)
```
public class CheckboxField extends Field
```

Класс, представляющий поле флажка
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CheckboxField(Page page, Rectangle rect)](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Конструктор класса CheckboxField. |
| [CheckboxField(IDocument doc, Rectangle rect)](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Конструктор класса CheckboxField. |
| [CheckboxField()](#CheckboxField--) | Создайте экземпляр CheckboxField. |
| [CheckboxField(IDocument doc)](#CheckboxField-com.aspose.pdf.IDocument-) | Конструктор для использования с генератором. |
## Поля

| Поле | Описание |
| --- | --- |
| [_FileSelect](#-FileSelect) | \_FileSelect |
| [_Пароль](#-Password) | \_Password |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Принимает посетителя. |
| [add(WidgetAnnotation item)](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Обновите параметры и внешний вид в соответствии с преобразованием матрицы. |
| [clear()](#clear--) |  |
| [contains(WidgetAnnotation item)](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo(Field[] array, int index)](#copyTo-com.aspose.pdf.Field---int-) | Копирует подполя этого поля в массив, начиная с указанного индекса. |
| [copyTo(WidgetAnnotation[] array, int arrayIndex)](#copyTo-com.aspose.pdf.WidgetAnnotation---int-) |  |
| [createAnnotation(IPdfObject annotEngineObj, Page page)](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Только для внутреннего использования |
| [deepClone()](#deepClone--) | Клонируйте флажок. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Удаляет это поле и размещает его значение прямо на странице. |
| [getActiveState()](#getActiveState--) | Получает текущее состояние внешнего вида аннотации. |
| [getAlignment()](#getAlignment--) | Выравнивание аннотации. |
| [getAllowedStates()](#getAllowedStates--) | Возвращает список разрешенных состояний. |
| [getAlternateName()](#getAlternateName--) | Получает альтернативное имя поля (альтернативное имя поля, которое должно использоваться вместо фактического имени поля везде, где поле должно быть идентифицировано в пользовательском интерфейсе). |
| [getAnnotationActions()](#getAnnotationActions--) | Получает действия аннотации. |
| [getAnnotationIndex()](#getAnnotationIndex--) | Получает индекс этой аннотации на странице. |
| [getAnnotationType()](#getAnnotationType--) | Получает тип аннотации. |
| [getAppearance()](#getAppearance--) | Получает словарь внешнего вида аннотации. |
| [getBorder()](#getBorder--) | Получает характеристики границы аннотации. |
| [getCharacteristics()](#getCharacteristics--) | Получает характеристики аннотации. |
| [getChecked()](#getChecked--) | Получает состояние флажка. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает цвет аннотации. |
| [getContents()](#getContents--) | Получает текст аннотации. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Получает внешний вид поля по умолчанию. |
| [getEngineDict()](#getEngineDict--) | Только внутренний |
| [getEngineObj()](#getEngineObj--) | Только для внутреннего использования |
| [getExportValue()](#getExportValue--) | Получает или задает экспортное значение поля CheckBox. |
| [getExportable()](#getExportable--) | Получает экспортируемый флаг поля. |
| [getFlags()](#getFlags--) | Получить флаги аннотации. |
| [getFullName()](#getFullName--) | Получает полное квалифицированное имя аннотации. |
| [getHeight()](#getHeight--) | Получает высоту аннотации. |
| [getHighlighting()](#getHighlighting--) | Режим выделения аннотаций. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание абзаца |
| [getHorizontalAlignment_Annotation_New()](#getHorizontalAlignment-Annotation-New--) | Получает или задает выравнивание текста для аннотации. |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getMappingName()](#getMappingName--) | Получает имя сопоставления поля, которое должно использоваться при экспорте данных поля интерактивной формы из документа. |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getMaxFontSize()](#getMaxFontSize--) | Максимальный размер шрифта, который можно использовать для содержимого поля. -1, чтобы не проверять размер. |
| [getMinFontSize()](#getMinFontSize--) | Минимальный размер шрифта, который можно использовать для содержимого поля. -1, чтобы не проверять размер. |
| [getModified()](#getModified--) | Получает дату и время последнего изменения аннотации. |
| [getModifiedInternal()](#getModifiedInternal--) | Получает дату и время последнего изменения аннотации. |
| [getName()](#getName--) | Получает имя аннотации на странице. |
| [getNormalAppearance()](#getNormalAppearance--) | Принимает нормальный вид. |
| [getNormalCaption()](#getNormalCaption--) | Получает обычный заголовок поля. |
| [getOnActivated()](#getOnActivated--) | Получить действие, которое должно быть выполнено при активации аннотации. |
| [getOnState()](#getOnState--) | Возвращает имя состояния, которое является состоянием флажка «Проверено». |
| [getPage()](#getPage--) | Получает объект страницы, с которым связана эта аннотация. |
| [getPageIndex()](#getPageIndex--) | Получает индекс страницы, содержащей это поле. |
| [getPageIndex(Annotation annotation)](#getPageIndex-com.aspose.pdf.Annotation-) | Получает индекс страницы, содержащей аннотацию. |
| [getParent()](#getParent--) | Получает родительскую аннотацию. |
| [getPartialName()](#getPartialName--) | Получает частичное имя поля. |
| [getPdfActions()](#getPdfActions--) | Получает список действий аннотации. |
| [getReadOnly()](#getReadOnly--) | Получает статус поля только для чтения. |
| [getRect()](#getRect--) | Получает прямоугольник поля. |
| [getRectangle(boolean considerRotation)](#getRectangle-boolean-) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [getRequired()](#getRequired--) | Получает обязательный статус поля. |
| [getStates()](#getStates--) | Получает словарь внешнего вида аннотации. |
| [getStyle()](#getStyle--) | Получает стиль флажка. |
| [getSyncRoot()](#getSyncRoot--) | Объект синхронизации. |
| [getTabOrder()](#getTabOrder--) | Получает или задает порядок табуляции поля. |
| [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | Получает выравнивание текста для аннотации. |
| [getValue()](#getValue--) | Получает значение поля флажка. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание абзаца |
| [getWidth()](#getWidth--) | Получает ширину аннотации. |
| [getZIndex()](#getZIndex--) | Получает значение int, указывающее Z-порядок графика. |
| [get_Item(int index)](#get-Item-int-) | Получает подполе, содержащееся в этом поле, по индексу. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Получает подполе, содержащееся в этом поле, по имени подполя. |
| [hashCode()](#hashCode--) |  |
| [initialize(IDocument doc)](#initialize-com.aspose.pdf.IDocument-) | Инициализация экземпляра |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [isFitIntoRectangle()](#isFitIntoRectangle--) | Если true, то размер шрифта будет уменьшен, чтобы текст соответствовал указанному прямоугольнику. |
| [isGroup()](#isGroup--) | Получает логическое значение, указывающее, является ли это поле нетерминальным полем, т.е. группой полей. |
| [isInLineParagraph()](#isInLineParagraph--) | Получает абзац встроенным. |
| [isInNewPage()](#isInNewPage--) | Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [isKeptWithNext()](#isKeptWithNext--) | Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. |
| [isReadOnly()](#isReadOnly--) |  |
| [isSharedField()](#isSharedField--) | Свойство для поддержки генератора. |
| [isSynchronized()](#isSynchronized--) | Возвращает true, если словарь синхронизирован. |
| [isUpdateAppearanceOnConvert()](#isUpdateAppearanceOnConvert--) | Если установлено значение true, внешний вид аннотации будет обновлен перед преобразованием документа PF в изображение. |
| [isUseFontSubset()](#isUseFontSubset--) | Если для этого свойства установлено значение true, шрифты будут добавляться в документ как подмножества. |
| [iterator()](#iterator--) | Возвращает перечислитель содержащихся полей. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recalculate()](#recalculate--) | Повторно вычисляет все вычисляемые поля в форме. |
| [remove(WidgetAnnotation item)](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setActiveState(String value)](#setActiveState-java.lang.String-) | Устанавливает текущее состояние внешнего вида аннотации. |
| [setAlignment(int value)](#setAlignment-int-) | Выравнивание аннотации. |
| [setAlternateName(String value)](#setAlternateName-java.lang.String-) | Устанавливает альтернативное имя поля (альтернативное имя поля, которое должно использоваться вместо фактического имени поля везде, где поле должно быть идентифицировано в пользовательском интерфейсе). |
| [setAnnotationIndex(int value)](#setAnnotationIndex-int-) | Устанавливает индекс этой аннотации на странице. |
| [setBorder(Border value)](#setBorder-com.aspose.pdf.Border-) | Задает характеристики границы аннотации. |
| [setChecked(boolean value)](#setChecked-boolean-) | Устанавливает состояние флажка. |
| [setColor(Color value)](#setColor-com.aspose.pdf.Color-) | Устанавливает цвет аннотации. |
| [setContents(String value)](#setContents-java.lang.String-) | Устанавливает текст аннотации. |
| [setDefaultAppearance(DefaultAppearance value)](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Задает внешний вид поля по умолчанию. |
| [setExportValue(String value)](#setExportValue-java.lang.String-) | Получает или задает экспортное значение поля CheckBox. |
| [setExportable(boolean value)](#setExportable-boolean-) | Устанавливает статус поля только для чтения. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setFitIntoRectangle(boolean value)](#setFitIntoRectangle-boolean-) | Если true, то размер шрифта будет уменьшен, чтобы текст соответствовал указанному прямоугольнику. |
| [setFlags(int value)](#setFlags-int-) | Установите флаги аннотации. |
| [setHeight(double value)](#setHeight-double-) | Устанавливает высоту аннотации. |
| [setHighlighting(int value)](#setHighlighting-int-) | Режим выделения аннотаций. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание абзаца |
| [setHorizontalAlignment_Annotation_New(int value)](#setHorizontalAlignment-Annotation-New-int-) | Получает или задает выравнивание текста для аннотации. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку (для генератора pdf). |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setMappingName(String value)](#setMappingName-java.lang.String-) | Задает имя сопоставления поля, которое будет использоваться при экспорте данных поля интерактивной формы из документа. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setMaxFontSize(double value)](#setMaxFontSize-double-) | Максимальный размер шрифта, который можно использовать для содержимого поля. -1, чтобы не проверять размер. |
| [setMinFontSize(double value)](#setMinFontSize-double-) | Минимальный размер шрифта, который можно использовать для содержимого поля. -1, чтобы не проверять размер. |
| [setModified(Date value)](#setModified-java.util.Date-) | Устанавливает дату и время последнего изменения аннотации. |
| [setModifiedInternal(System.DateTime value)](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Устанавливает дату и время последнего изменения аннотации. |
| [setName(String value)](#setName-java.lang.String-) | Задает имя аннотации на странице. |
| [setOnActivated(PdfAction value)](#setOnActivated-com.aspose.pdf.PdfAction-) | Установите действие, которое должно выполняться при активации аннотации. |
| [setPartialName(String value)](#setPartialName-java.lang.String-) | Задает частичное имя поля. |
| [setPosition(Point point)](#setPosition-com.aspose.pdf.Point-) | Установить положение поля. |
| [setReadOnly(boolean value)](#setReadOnly-boolean-) | Устанавливает статус поля только для чтения. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Устанавливает прямоугольник поля. |
| [setRequired(boolean value)](#setRequired-boolean-) | Устанавливает статус поля только для чтения. |
| [setSharedField(boolean value)](#setSharedField-boolean-) | Свойство для поддержки генератора. |
| [setStyle(int value)](#setStyle-int-) | Устанавливает стиль флажка. |
| [setTabOrder(int value)](#setTabOrder-int-) | Получает или задает порядок табуляции поля. |
| [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | Устанавливает выравнивание текста для аннотации. |
| [setUpdateAppearanceOnConvert(boolean value)](#setUpdateAppearanceOnConvert-boolean-) | Если установлено значение true, внешний вид аннотации будет обновлен перед преобразованием документа PF в изображение. |
| [setUseFontSubset(boolean value)](#setUseFontSubset-boolean-) | Если для этого свойства установлено значение true, шрифты будут добавляться в документ как подмножества. |
| [setValue(String value)](#setValue-java.lang.String-) | Устанавливает значение поля флажка. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание абзаца |
| [setWidth(double value)](#setWidth-double-) | Устанавливает ширину аннотации. |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [size()](#size--) | Получает количество подполей в этом поле. |
| [toString()](#toString--) |  |
| [updateAppearances()](#updateAppearances--) | Обновить значение внешнего вида. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CheckboxField(Page page, Rectangle rect) {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public CheckboxField(Page page, Rectangle rect)
```


Конструктор класса CheckboxField.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница, на которой будет установлен флажок. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Положение и размер флажка. |

### CheckboxField(IDocument doc, Rectangle rect) {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
```
public CheckboxField(IDocument doc, Rectangle rect)
```


Конструктор класса CheckboxField.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Документ, в котором будет создано новое поле. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольник, в котором будет создано новое поле. |

### CheckboxField() {#CheckboxField--}
```
public CheckboxField()
```


Создайте экземпляр CheckboxField.

### CheckboxField(IDocument doc) {#CheckboxField-com.aspose.pdf.IDocument-}
```
public CheckboxField(IDocument doc)
```


Конструктор для использования с генератором.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Документ, в котором будет создано поле. |

### _FileSelect {#-FileSelect}
```
public static final int _FileSelect
```


\_FileSelect

### _Password {#-Password}
```
public static final int _Password
```


\_Пароль

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Принимает посетителя.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Посетитель должен быть принят. |

### add(WidgetAnnotation item) {#add-com.aspose.pdf.WidgetAnnotation-}
```
public void add(WidgetAnnotation item)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Обновите параметры и внешний вид в соответствии с преобразованием матрицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Матрица, используемая для преобразования (изменения размера). |

### clear() {#clear--}
```
public void clear()
```




### contains(WidgetAnnotation item) {#contains-com.aspose.pdf.WidgetAnnotation-}
```
public boolean contains(WidgetAnnotation item)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

**Возвращает:**
логический
### copyTo(Field[] array, int index) {#copyTo-com.aspose.pdf.Field---int-}
```
public void copyTo(Field[] array, int index)
```


Копирует подполя этого поля в массив, начиная с указанного индекса.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [Field\[\]](../../com.aspose.pdf/field) | Массив, в который необходимо скопировать поле. |
| index | int | Начальный индекс, в который будут скопированы поля. |

### copyTo(WidgetAnnotation[] array, int arrayIndex) {#copyTo-com.aspose.pdf.WidgetAnnotation---int-}
```
public void copyTo(WidgetAnnotation[] array, int arrayIndex)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [WidgetAnnotation\[\]](../../com.aspose.pdf/widgetannotation) |  |
| arrayIndex | int |  |

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


Клонируйте флажок.

**Возвращает:**
java.lang.Object — клонированный объект
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


Удаляет это поле и размещает его значение прямо на странице.

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
### getAllowedStates() {#getAllowedStates--}
```
public List<String> getAllowedStates()
```


Возвращает список разрешенных состояний.

**Возвращает:**
java.util.List<java.lang.String> — список строковых значений
### getAlternateName() {#getAlternateName--}
```
public String getAlternateName()
```


Получает альтернативное имя поля (альтернативное имя поля, которое должно использоваться вместо фактического имени поля везде, где поле должно быть идентифицировано в пользовательском интерфейсе). Альтернативное имя используется в качестве подсказки к полю в Adobe Acrobat.

**Возвращает:**
java.lang.String — строковое значение
### getAnnotationActions() {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```


Получает действия аннотации.

**Возвращает:**
[AnnotationActionCollection](../../com.aspose.pdf/annotationactioncollection) - Объект AnnotationActionCollection
### getAnnotationIndex() {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```


Получает индекс этой аннотации на странице.

**Возвращает:**
интервал - целочисленное значение
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
### getChecked() {#getChecked--}
```
public boolean getChecked()
```


Получает состояние флажка.

**Возвращает:**
boolean - логическое значение
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
### getDefaultAppearance() {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```


Получает внешний вид поля по умолчанию.

**Возвращает:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) - Объект DefaultAppearance
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
### getExportValue() {#getExportValue--}
```
public final String getExportValue()
```


Получает или задает экспортное значение поля CheckBox.

**Возвращает:**
java.lang.String — строковое значение
### getExportable() {#getExportable--}
```
public boolean getExportable()
```


Получает экспортируемый флаг поля.

**Возвращает:**
boolean - логическое значение
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
### getHighlighting() {#getHighlighting--}
```
public int getHighlighting()
```


Режим выделения аннотаций.

**Возвращает:**
int — значение HighlightingMode
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
### getMappingName() {#getMappingName--}
```
public String getMappingName()
```


Получает имя сопоставления поля, которое должно использоваться при экспорте данных поля интерактивной формы из документа.

**Возвращает:**
java.lang.String — строковое значение
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает внешнее поле для абзаца (для создания pdf)

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getMaxFontSize() {#getMaxFontSize--}
```
public static synchronized double getMaxFontSize()
```


Максимальный размер шрифта, который можно использовать для содержимого поля. -1, чтобы не проверять размер.

**Возвращает:**
двойное - двойное значение
### getMinFontSize() {#getMinFontSize--}
```
public static double getMinFontSize()
```


Минимальный размер шрифта, который можно использовать для содержимого поля. -1, чтобы не проверять размер.

**Возвращает:**
двойное - двойное значение
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
### getNormalCaption() {#getNormalCaption--}
```
public String getNormalCaption()
```


Получает обычный заголовок поля.

**Возвращает:**
java.lang.String — строковое значение
### getOnActivated() {#getOnActivated--}
```
public PdfAction getOnActivated()
```


Получить действие, которое должно быть выполнено при активации аннотации.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - объект PdfAction
### getOnState() {#getOnState--}
```
public String getOnState()
```


Возвращает имя состояния, которое является состоянием флажка «Проверено». Это «Да», если присутствует, или любое другое значение, отличное от «Выкл.» и «Нет»;

**Возвращает:**
java.lang.String — строковое значение
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


Получает индекс страницы, содержащей это поле.

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
### getParent() {#getParent--}
```
public Field getParent()
```


Получает родительскую аннотацию.

**Возвращает:**
[Field](../../com.aspose.pdf/field) - Полевой объект
### getPartialName() {#getPartialName--}
```
public String getPartialName()
```


Получает частичное имя поля.

**Возвращает:**
java.lang.String — строковое значение
### getPdfActions() {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```


Получает список действий аннотации.

**Возвращает:**
[PdfActionCollection](../../com.aspose.pdf/pdfactioncollection) - Экземпляр PdfActionCollection
### getReadOnly() {#getReadOnly--}
```
public boolean getReadOnly()
```


Получает статус поля только для чтения.

**Возвращает:**
boolean - логическое значение
### getRect() {#getRect--}
```
public Rectangle getRect()
```


Получает прямоугольник поля.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - прямоугольник поля.
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
### getRequired() {#getRequired--}
```
public boolean getRequired()
```


Получает обязательный статус поля.

**Возвращает:**
boolean - логическое значение
### getStates() {#getStates--}
```
public AppearanceDictionary getStates()
```


Получает словарь внешнего вида аннотации.

**Возвращает:**
[AppearanceDictionary](../../com.aspose.pdf/appearancedictionary) - Объект AppearanceDictionary
### getStyle() {#getStyle--}
```
public int getStyle()
```


Получает стиль флажка.

**Возвращает:**
int - стиль флажка.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Объект синхронизации.

**Возвращает:**
java.lang.Object — значение объекта
### getTabOrder() {#getTabOrder--}
```
public int getTabOrder()
```


Получает или задает порядок табуляции поля.

**Возвращает:**
интервал - целочисленное значение
### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public int getTextHorizontalAlignment()
```


Получает выравнивание текста для аннотации.

**Возвращает:**
int - выравнивание текста для аннотации.
### getValue() {#getValue--}
```
public String getValue()
```


Получает значение поля флажка.

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
### get_Item(int index) {#get-Item-int-}
```
public WidgetAnnotation get_Item(int index)
```


Получает подполе, содержащееся в этом поле, по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс запрашиваемого подполя. |

**Возвращает:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - экземпляр поля.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public WidgetAnnotation get_Item(String name)
```


Получает подполе, содержащееся в этом поле, по имени подполя.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Содержит имя подполя. |

**Возвращает:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - экземпляр поля.
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
### isFitIntoRectangle() {#isFitIntoRectangle--}
```
public static synchronized boolean isFitIntoRectangle()
```


Если true, то размер шрифта будет уменьшен, чтобы текст соответствовал указанному прямоугольнику.

**Возвращает:**
boolean - логическое значение
### isGroup() {#isGroup--}
```
public boolean isGroup()
```


Получает логическое значение, указывающее, является ли это поле нетерминальным полем, т.е. группой полей.

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
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Возвращает:**
логический
### isSharedField() {#isSharedField--}
```
public boolean isSharedField()
```


Свойство для поддержки генератора. Используется, когда поле добавляется в верхний или нижний колонтитул. Если true, это поле будет создано один раз и его внешний вид будет виден на всех страницах документа. Если false, для каждой страницы документа будет создано отдельное поле.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Возвращает true, если словарь синхронизирован.

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
### iterator() {#iterator--}
```
public Iterator<WidgetAnnotation> iterator()
```


Возвращает перечислитель содержащихся полей.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.WidgetAnnotation> — объект перечислителя.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### recalculate() {#recalculate--}
```
public boolean recalculate()
```


Повторно вычисляет все вычисляемые поля в форме.

**Возвращает:**
boolean - true, если значение поля было изменено при пересчете.
### remove(WidgetAnnotation item) {#remove-com.aspose.pdf.WidgetAnnotation-}
```
public boolean remove(WidgetAnnotation item)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

**Возвращает:**
логический
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

### setAlternateName(String value) {#setAlternateName-java.lang.String-}
```
public void setAlternateName(String value)
```


Устанавливает альтернативное имя поля (альтернативное имя поля, которое должно использоваться вместо фактического имени поля везде, где поле должно быть идентифицировано в пользовательском интерфейсе). Альтернативное имя используется в качестве подсказки к полю в Adobe Acrobat.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setAnnotationIndex(int value) {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```


Устанавливает индекс этой аннотации на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setBorder(Border value) {#setBorder-com.aspose.pdf.Border-}
```
public void setBorder(Border value)
```


Задает характеристики границы аннотации. Граница 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Border](../../com.aspose.pdf/border) | Значение границы |

### setChecked(boolean value) {#setChecked-boolean-}
```
public void setChecked(boolean value)
```


Устанавливает состояние флажка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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

### setDefaultAppearance(DefaultAppearance value) {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
```
public void setDefaultAppearance(DefaultAppearance value)
```


Задает внешний вид поля по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | Объект DefaultAppearance |

### setExportValue(String value) {#setExportValue-java.lang.String-}
```
public final void setExportValue(String value)
```


Получает или задает экспортное значение поля CheckBox.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setExportable(boolean value) {#setExportable-boolean-}
```
public void setExportable(boolean value)
```


Устанавливает статус поля только для чтения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFitIntoRectangle(boolean value) {#setFitIntoRectangle-boolean-}
```
public static synchronized void setFitIntoRectangle(boolean value)
```


Если true, то размер шрифта будет уменьшен, чтобы текст соответствовал указанному прямоугольнику.

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

### setHighlighting(int value) {#setHighlighting-int-}
```
public void setHighlighting(int value)
```


Режим выделения аннотаций.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HighlightingMode |

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

### setMappingName(String value) {#setMappingName-java.lang.String-}
```
public void setMappingName(String value)
```


Задает имя сопоставления поля, которое будет использоваться при экспорте данных поля интерактивной формы из документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает внешнее поле для абзаца (для создания pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setMaxFontSize(double value) {#setMaxFontSize-double-}
```
public static synchronized void setMaxFontSize(double value)
```


Максимальный размер шрифта, который можно использовать для содержимого поля. -1, чтобы не проверять размер.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setMinFontSize(double value) {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```


Минимальный размер шрифта, который можно использовать для содержимого поля. -1, чтобы не проверять размер.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

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

### setOnActivated(PdfAction value) {#setOnActivated-com.aspose.pdf.PdfAction-}
```
public void setOnActivated(PdfAction value)
```


Установите действие, которое должно выполняться при активации аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Объект PdfAction |

### setPartialName(String value) {#setPartialName-java.lang.String-}
```
public void setPartialName(String value)
```


Задает частичное имя поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setPosition(Point point) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point point)
```


Установить положение поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.pdf/point) | Точка, где поле должно быть расположено. |

### setReadOnly(boolean value) {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```


Устанавливает статус поля только для чтения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


Устанавливает прямоугольник поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | прямоугольник поля. |

### setRequired(boolean value) {#setRequired-boolean-}
```
public void setRequired(boolean value)
```


Устанавливает статус поля только для чтения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSharedField(boolean value) {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```


Свойство для поддержки генератора. Используется, когда поле добавляется в верхний или нижний колонтитул. Если true, это поле будет создано один раз и его внешний вид будет виден на всех страницах документа. Если false, для каждой страницы документа будет создано отдельное поле.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Устанавливает стиль флажка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | BoxСтиль флажка. |

### setTabOrder(int value) {#setTabOrder-int-}
```
public void setTabOrder(int value)
```


Получает или задает порядок табуляции поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public void setTextHorizontalAlignment(int value)
```


Устанавливает выравнивание текста для аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | выравнивание текста для аннотации. |

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

### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Устанавливает значение поля флажка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

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

### size() {#size--}
```
public int size()
```


Получает количество подполей в этом поле. (Например, количество элементов в поле переключателя).

**Возвращает:**
интервал - целочисленное значение
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### updateAppearances() {#updateAppearances--}
```
public void updateAppearances()
```


Обновить значение внешнего вида.

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
