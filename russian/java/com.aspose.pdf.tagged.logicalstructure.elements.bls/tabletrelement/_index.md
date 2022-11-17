---
title: TableTRElement
second_title: Aspose.PDF для справки по Java API
description: Представляет элемент структуры TR в логической структуре таблицы.
type: docs
weight: 28
url: /ru/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablechildelement)
```
public final class TableTRElement extends TableChildElement
```

Представляет элемент структуры TR в логической структуре таблицы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | конструктор только для внутреннего использования |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Найти элементы заданного типа |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Найти элементы заданного типа |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Добавить /Aspose.Pdf.LogicalStructure.Element к коллекции дочерних элементов. |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Изменить родительский элемент для текущего элемента структуры |
| [clearId()](#clearId--) | Очистить ID для элемента структуры. |
| [createTD()](#createTD--) |  Создает[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) и добавил его в текущую таблицу. |
| [createTH()](#createTH--) |  Создает[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) и добавил его в текущую таблицу. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | Сгенерировать ID для элемента структуры. |
| [getActualText()](#getActualText--) | Получает или задает фактический текст для элемента структуры. |
| [getAlternativeText()](#getAlternativeText--) | Получает или задает альтернативный текст для элемента структуры. |
| [getAttributes()](#getAttributes--) | Получает объект StructureAttributeCollection. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает цвет фона строки. |
| [getBorder()](#getBorder--) | Получает или задает границу строки. |
| [getChildElements()](#getChildElements--) | Получает дочернюю коллекцию объектов Element. |
| [getClass()](#getClass--) |  |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | Получает объект /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard. |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Получает границу ячейки по умолчанию. |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Получает или задает поле по умолчанию для ячеек строки. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Получает или задает текстовое состояние по умолчанию для ячеек строки |
| [getElementEngine()](#getElementEngine--) | Получить родительский элемент. |
| [getExpansionText()](#getExpansionText--) | Получает или задает текст расширения для элемента структуры. |
| [getFixedRowHeight()](#getFixedRowHeight--) | Получает фиксированную высоту строки — строка может иметь фиксированную высоту. |
| [getID()](#getID--) | Получает идентификатор элемента структуры. |
| [getLanguage()](#getLanguage--) | Получает или задает язык для элемента структуры. |
| [getMinRowHeight()](#getMinRowHeight--) | Получает высоту строки. |
| [getParentElement()](#getParentElement--) | Получает родительскую коллекцию объектов Element. |
| [getS()](#getS--) |  |
| [getStructureType()](#getStructureType--) | Получает тип элемента структуры. |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | Получает или задает заголовок элемента структуры. |
| [getTrailer()](#getTrailer--) | Внутренний метод |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает или задает вертикальное выравнивание. |
| [hashCode()](#hashCode--) |  |
| [isInNewPage()](#isInNewPage--) | Получает фиксированную строку на новой странице — страница с этим свойством должна быть напечатана на следующей странице. По умолчанию false. |
| [isRowBroken()](#isRowBroken--) | Получает, что строка может быть разбита между двумя страницами. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | Получает или задает фактический текст для элемента структуры. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Получает или задает альтернативный текст для элемента структуры. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Получает или задает цвет фона строки. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Получает или задает границу строки. |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Получает границу ячейки по умолчанию. |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Получает или задает поле по умолчанию для ячеек строки. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Получает или задает текстовое состояние по умолчанию для ячеек строки |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | Получает или задает текст расширения для элемента структуры. |
| [setFixedRowHeight(double value)](#setFixedRowHeight-double-) | Получает фиксированную высоту строки — строка может иметь фиксированную высоту. |
| [setId(String id)](#setId-java.lang.String-) | Устанавливает ID для элемента структуры. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Получает фиксированную строку на новой странице — страница с этим свойством должна быть напечатана на следующей странице. По умолчанию false. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Получает или задает язык для элемента структуры. |
| [setMinRowHeight(double value)](#setMinRowHeight-double-) | Получает высоту строки. |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | установить родительский элемент |
| [setRowBroken(boolean value)](#setRowBroken-boolean-) | Получает, что строка может быть разбита между двумя страницами. |
| [setTag(String newTag)](#setTag-java.lang.String-) | Устанавливает пользовательский тег для элемента структуры. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Получает или задает заголовок элемента структуры. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Получает или задает вертикальное выравнивание. |
| [toString()](#toString--) | Возвращает строку, которая представляет текущий объект. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public TableTRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


конструктор только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) | Экземпляр TaggedContext |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | внутренний экземпляр |

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

### createTD() {#createTD--}
```
public final TableTDElement createTD()
```


 Создает[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) и добавил его в текущую таблицу.

**Возвращает:**
[TableTDElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletdelement) - Создан элемент структуры.
### createTH() {#createTH--}
```
public final TableTHElement createTH()
```


 Создает[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) и добавил его в текущую таблицу.

**Возвращает:**
[TableTHElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tablethelement) - Создан элемент структуры.
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


Получает или задает цвет фона строки.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной экземпляр
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Получает или задает границу строки.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - экземпляр BorderInfo
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
### getDefaultAttributeOwner() {#getDefaultAttributeOwner--}
```
public final AttributeOwnerStandard getDefaultAttributeOwner()
```


Получает объект /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard.

Значение: объект /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard.

**Возвращает:**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - Экземпляр AttributeOwnerStandard
### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```


Получает границу ячейки по умолчанию.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - экземпляр BorderInfo
### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```


Получает или задает поле по умолчанию для ячеек строки.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - Экземпляр MarginInfo
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Получает или задает текстовое состояние по умолчанию для ячеек строки

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
### getFixedRowHeight() {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```


Получает фиксированную высоту строки — строка может иметь фиксированную высоту.

**Возвращает:**
двойное - двойное значение
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
### getMinRowHeight() {#getMinRowHeight--}
```
public final double getMinRowHeight()
```


Получает высоту строки.

**Возвращает:**
двойное - двойное значение
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Получает родительскую коллекцию объектов Element.

**Возвращает:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Значение: родительская коллекция объектов Element.
### getS() {#getS--}
```
public final IPdfName getS()
```




**Возвращает:**
[IPdfName](../../com.aspose.pdf.engine.data/ipdfname)
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
### isInNewPage() {#isInNewPage--}
```
public final boolean isInNewPage()
```


Получает фиксированную строку на новой странице — страница с этим свойством должна быть напечатана на следующей странице. По умолчанию false.

**Возвращает:**
boolean - логическое значение
### isRowBroken() {#isRowBroken--}
```
public final boolean isRowBroken()
```


Получает, что строка может быть разбита между двумя страницами.

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


Получает или задает цвет фона строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Экземпляр цвета |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Получает или задает границу строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Экземпляр BorderInfo |

### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public final void setDefaultCellBorder(BorderInfo value)
```


Получает границу ячейки по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Экземпляр BorderInfo |

### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public final void setDefaultCellPadding(MarginInfo value)
```


Получает или задает поле по умолчанию для ячеек строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Экземпляр MarginInfo |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Получает или задает текстовое состояние по умолчанию для ячеек строки

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

### setFixedRowHeight(double value) {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```


Получает фиксированную высоту строки — строка может иметь фиксированную высоту.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setId(String id) {#setId-java.lang.String-}
```
public final void setId(String id)
```


Устанавливает ID для элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| id | java.lang.String | Значение ID для элемента структуры |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```


Получает фиксированную строку на новой странице — страница с этим свойством должна быть напечатана на следующей странице. По умолчанию false.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public final void setLanguage(String value)
```


Получает или задает язык для элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Значение: Язык элемента структуры. |

### setMinRowHeight(double value) {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```


Получает высоту строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


установить родительский элемент

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | ценность |

### setRowBroken(boolean value) {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```


Получает, что строка может быть разбита между двумя страницами.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setTag(String newTag) {#setTag-java.lang.String-}
```
public final void setTag(String newTag)
```


Устанавливает пользовательский тег для элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| newTag | java.lang.String | Название тэга |

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
