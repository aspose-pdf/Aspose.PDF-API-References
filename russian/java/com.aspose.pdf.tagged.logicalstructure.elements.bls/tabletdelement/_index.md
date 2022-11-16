---
title: TableTDElement
second_title: Aspose.PDF для справки по Java API
description: Представляет элемент структуры ТД в логической структуре таблицы.
type: docs
weight: 24
url: /ru/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablechildelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement)
```
public final class TableTDElement extends TableCellElement
```

Представляет элемент структуры ТД в логической структуре таблицы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TableTDElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#TableTDElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Найти элементы заданного типа |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Найти элементы заданного типа |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Добавить /Aspose.Pdf.LogicalStructure.Element к коллекции дочерних элементов. |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Изменить родительский элемент для текущего элемента структуры |
| [clearId()](#clearId--) | Очистить ID для элемента структуры. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | Сгенерировать ID для элемента структуры. |
| [getActualText()](#getActualText--) | Получает или задает фактический текст для элемента структуры. |
| [getAlignment()](#getAlignment--) | Получает или задает выравнивание ячеек. |
| [getAlternativeText()](#getAlternativeText--) | Получает или задает альтернативный текст для элемента структуры. |
| [getAttributes()](#getAttributes--) | Получает объект StructureAttributeCollection. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает цвет фона ячейки. |
| [getBorder()](#getBorder--) | Получает или задает границу ячейки. |
| [getCell()](#getCell--) |  |
| [getChildElements()](#getChildElements--) | Получает дочернюю коллекцию объектов Element. |
| [getClass()](#getClass--) |  |
| [getColSpan()](#getColSpan--) | Получает или задает диапазон столбцов. |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | Получает объект /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Получает или задает состояние текста ячейки по умолчанию. |
| [getElementEngine()](#getElementEngine--) | Получить родительский элемент. |
| [getExpansionText()](#getExpansionText--) | Получает или задает текст расширения для элемента структуры. |
| [getID()](#getID--) | Получает идентификатор элемента структуры. |
| [getLanguage()](#getLanguage--) | Получает или задает язык для элемента структуры. |
| [getMargin()](#getMargin--) | Получает или задает заполнение. |
| [getParentElement()](#getParentElement--) | Получает родительскую коллекцию объектов Element. |
| [getRowSpan()](#getRowSpan--) | Получает или задает диапазон строк. |
| [getS()](#getS--) |  |
| [getStructureTextState()](#getStructureTextState--) | Получает объект /Aspose.Pdf.LogicalStructure.StructureTextState для текущего элемента. |
| [getStructureType()](#getStructureType--) | Получает тип элемента структуры. |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | Получает или задает заголовок элемента структуры. |
| [getTrailer()](#getTrailer--) | Внутренний метод |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает или задает вертикальное выравнивание. |
| [hashCode()](#hashCode--) |  |
| [isNoBorder()](#isNoBorder--) | Получает или задает ячейку с рамкой. |
| [isWordWrapped()](#isWordWrapped--) | Возвращает или задает перенос текстового слова ячейки. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | Получает или задает фактический текст для элемента структуры. |
| [setAlignment(int value)](#setAlignment-int-) | Получает или задает выравнивание ячеек. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Получает или задает альтернативный текст для элемента структуры. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Получает или задает цвет фона ячейки. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Получает или задает границу ячейки. |
| [setColSpan(int value)](#setColSpan-int-) | Получает или задает диапазон столбцов. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Получает или задает состояние текста ячейки по умолчанию. |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | Получает или задает текст расширения для элемента структуры. |
| [setId(String id)](#setId-java.lang.String-) | Устанавливает ID для элемента структуры. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Получает или задает язык для элемента структуры. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Получает или задает заполнение. |
| [setNoBorder(boolean value)](#setNoBorder-boolean-) | Получает или задает ячейку с рамкой. |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | установить родительский элемент |
| [setRowSpan(int value)](#setRowSpan-int-) | Получает или задает диапазон строк. |
| [setTag(String newTag)](#setTag-java.lang.String-) | Устанавливает пользовательский тег для элемента структуры. |
| [setText(String text)](#setText-java.lang.String-) | Добавляет текстовое содержимое к текущему текстовому элементу. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Получает или задает заголовок элемента структуры. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Получает или задает вертикальное выравнивание. |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | Возвращает или задает перенос текстового слова ячейки. |
| [toString()](#toString--) | Возвращает строку, которая представляет текущий объект. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TableTDElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#TableTDElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public TableTDElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) |  |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

### <T>findElements(Class<T> typeOfTboolean) {#-T-findElements-java.lang.Class-T--}
```
public List<T> <T>findElements(Class<T> typeOfTboolean)
```


Найти элементы заданного типа

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfTboolean | java.lang.Class<T> | экземпляр класса |

**Возвращает:**
java.util.List<T> - Список найденных элементов
### <T>findElements(Class<T> typeOfT, boolean recursiveSearch) {#-T-findElements-java.lang.Class-T--boolean-}
```
public List<T> <T>findElements(Class<T> typeOfT, boolean recursiveSearch)
```


Найти элементы заданного типа

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> | экземпляр класса |
| recursiveSearch | boolean | (Необязательно) Рекурсивный поиск (по умолчанию false, поиск только из прямых дочерних элементов) |

**Возвращает:**
java.util.List<T> - Список найденных элементов
### appendChild(Element element) {#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public final Element appendChild(Element element)
```


Добавить /Aspose.Pdf.LogicalStructure.Element к коллекции дочерних элементов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  Объект /Aspose.Pdf.LogicalStructure.Element для добавления. |

**Возвращает:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Добавлен /Aspose.Pdf.LogicalStructure.Element.
### changeParentElement(StructureElement newParentElement) {#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-}
```
public final void changeParentElement(StructureElement newParentElement)
```


Изменить родительский элемент для текущего элемента структуры

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| newParentElement | [StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement) | Новый элемент родительской структуры |

### clearId() {#clearId--}
```
public final void clearId()
```


Очистить ID для элемента структуры.

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
### generateId() {#generateId--}
```
public final void generateId()
```


Сгенерировать ID для элемента структуры.

### getActualText() {#getActualText--}
```
public final String getActualText()
```


Получает или задает фактический текст для элемента структуры.

**Возвращает:**
java.lang.String — Значение: Фактический текст элемента структуры.
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Получает или задает выравнивание ячеек.

**Возвращает:**
int - элемент HorizontalAlignment
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Получает или задает альтернативный текст для элемента структуры.

**Возвращает:**
java.lang.String — Значение: Альтернативный текст элемента структуры.
### getAttributes() {#getAttributes--}
```
public final StructureAttributeCollection getAttributes()
```


Получает объект StructureAttributeCollection.

**Возвращает:**
[StructureAttributeCollection](../../com.aspose.pdf.tagged.logicalstructure/structureattributecollection) - Объект StructureAttributeCollection.
### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Получает или задает цвет фона ячейки.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной экземпляр
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Получает или задает границу ячейки.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - экземпляр BorderInfo
### getCell() {#getCell--}
```
public final Cell getCell()
```




**Возвращает:**
[Cell](../../com.aspose.pdf/cell)
### getChildElements() {#getChildElements--}
```
public final ElementList getChildElements()
```


Получает дочернюю коллекцию объектов Element.

**Возвращает:**
[ElementList](../../com.aspose.pdf.tagged.logicalstructure/elementlist) - Значение: Дочерняя коллекция объектов Element.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```


Получает или задает диапазон столбцов.

**Возвращает:**
интервал - целочисленное значение
### getDefaultAttributeOwner() {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```


Получает объект /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard.

Значение: объект /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard.

**Возвращает:**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - Экземпляр AttributeOwnerStandard
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Получает или задает состояние текста ячейки по умолчанию.

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Экземпляр TextState
### getElementEngine() {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```


Получить родительский элемент.

**Возвращает:**
[ElementPdfEngine](../../com.aspose.pdf.tagged.logicalstructure/elementpdfengine) - Значение: родительский элемент.
### getExpansionText() {#getExpansionText--}
```
public final String getExpansionText()
```


Получает или задает текст расширения для элемента структуры.

**Возвращает:**
java.lang.String — Значение: текст расширения элемента структуры.
### getID() {#getID--}
```
public final String getID()
```


Получает идентификатор элемента структуры.

Значение: ID элемента структуры.

**Возвращает:**
java.lang.String — строковое значение
### getLanguage() {#getLanguage--}
```
public final String getLanguage()
```


Получает или задает язык для элемента структуры.

**Возвращает:**
java.lang.String - Значение: Язык элемента структуры.
### getMargin() {#getMargin--}
```
public final MarginInfo getMargin()
```


Получает или задает заполнение.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - Экземпляр MarginInfo
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Получает родительскую коллекцию объектов Element.

**Возвращает:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Значение: родительская коллекция объектов Element.
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```


Получает или задает диапазон строк.

**Возвращает:**
интервал - целочисленное значение
### getS() {#getS--}
```
public final IPdfName getS()
```




**Возвращает:**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname)
### getStructureTextState() {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```


Получает объект /Aspose.Pdf.LogicalStructure.StructureTextState для текущего элемента.

Значение: объект /Aspose.Pdf.LogicalStructure.StructureTextState для текущего элемента.

**Возвращает:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) - Экземпляр StructureTextState
### getStructureType() {#getStructureType--}
```
public final StructureTypeStandard getStructureType()
```


Получает тип элемента структуры.

**Возвращает:**
[StructureTypeStandard](../../com.aspose.pdf.tagged.logicalstructure/structuretypestandard) - Значение: объект StructureTypeStandard элемента структуры.
### getTaggedContent() {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```




**Возвращает:**
[ITaggedContent](../../com.aspose.pdf.tagged/itaggedcontent)
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Получает или задает заголовок элемента структуры.

**Возвращает:**
java.lang.String — Значение: Заголовок элемента структуры.
### getTrailer() {#getTrailer--}
```
public final ITrailerable getTrailer()
```


Внутренний метод

**Возвращает:**
[ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) - Внутренний элемент
### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Получает или задает вертикальное выравнивание.

**Возвращает:**
int - элемент вертикального выравнивания
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isNoBorder() {#isNoBorder--}
```
public final boolean isNoBorder()
```


Получает или задает ячейку с рамкой.

**Возвращает:**
boolean - логическое значение
### isWordWrapped() {#isWordWrapped--}
```
public final boolean isWordWrapped()
```


Возвращает или задает перенос текстового слова ячейки.

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




### setActualText(String value) {#setActualText-java.lang.String-}
```
public final void setActualText(String value)
```


Получает или задает фактический текст для элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение: Фактический текст элемента структуры. |

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Получает или задает выравнивание ячеек.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент HorizontalAlignment |

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Получает или задает альтернативный текст для элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение: Альтернативный текст элемента структуры. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Получает или задает цвет фона ячейки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Экземпляр цвета |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Получает или задает границу ячейки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Экземпляр BorderInfo |

### setColSpan(int value) {#setColSpan-int-}
```
public final void setColSpan(int value)
```


Получает или задает диапазон столбцов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Получает или задает состояние текста ячейки по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Экземпляр TextState |

### setExpansionText(String value) {#setExpansionText-java.lang.String-}
```
public final void setExpansionText(String value)
```


Получает или задает текст расширения для элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение: текст расширения элемента структуры. |

### setId(String id) {#setId-java.lang.String-}
```
public final void setId(String id)
```


Устанавливает ID для элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | java.lang.String | Значение ID для элемента структуры |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


Получает или задает язык для элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение: Язык элемента структуры. |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public final void setMargin(MarginInfo value)
```


Получает или задает заполнение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Экземпляр MarginInfo |

### setNoBorder(boolean value) {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```


Получает или задает ячейку с рамкой.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


установить родительский элемент

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | ценность |

### setRowSpan(int value) {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```


Получает или задает диапазон строк.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setTag(String newTag) {#setTag-java.lang.String-}
```
public final void setTag(String newTag)
```


Устанавливает пользовательский тег для элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| newTag | java.lang.String | Название тэга |

### setText(String text) {#setText-java.lang.String-}
```
public final void setText(String text)
```


Добавляет текстовое содержимое к текущему текстовому элементу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержимое |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Получает или задает заголовок элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение: Название элемента структуры. |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Получает или задает вертикальное выравнивание.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```


Возвращает или задает перенос текстового слова ячейки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, которая представляет текущий объект.

**Возвращает:**
java.lang.String — строка, представляющая текущий объект.
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
