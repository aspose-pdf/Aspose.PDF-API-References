---
title: TableElement
second_title: Aspose.PDF для справки по Java API
description: Представляет элемент структуры таблицы в логической структуре.
type: docs
weight: 21
url: /ru/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/blselement)
```
public final class TableElement extends BLSElement
```

Представляет элемент структуры таблицы в логической структуре.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | конструктор только для внутреннего использования |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Найти элементы заданного типа |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Найти элементы заданного типа |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Добавить /Aspose.Pdf.LogicalStructure.Element к коллекции дочерних элементов. |
| [changeParentElement(StructureElement newParentElement)](#changeParentElement-com.aspose.pdf.tagged.logicalstructure.elements.StructureElement-) | Изменить родительский элемент для текущего элемента структуры |
| [clearId()](#clearId--) | Очистить ID для элемента структуры. |
| [createTBody()](#createTBody--) |  Создает[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) и добавил его в текущую таблицу. |
| [createTFoot()](#createTFoot--) |  Создает[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) и добавил его в текущую таблицу. |
| [createTHead()](#createTHead--) |  Создает[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) и добавил его в текущую таблицу. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateId()](#generateId--) | Сгенерировать ID для элемента структуры. |
| [getActualText()](#getActualText--) | Получает или задает фактический текст для элемента структуры. |
| [getAlignment()](#getAlignment--) | Получает или задает выравнивание таблицы. |
| [getAlternativeText()](#getAlternativeText--) | Получает или задает альтернативный текст для элемента структуры. |
| [getAttributes()](#getAttributes--) | Получает объект StructureAttributeCollection. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает цвет фона таблицы. |
| [getBorder()](#getBorder--) | Получает или задает границу таблицы. |
| [getBroken()](#getBroken--) | Получает или устанавливает сломанную вертикаль таблицы; |
| [getChildElements()](#getChildElements--) | Получает дочернюю коллекцию объектов Element. |
| [getClass()](#getClass--) |  |
| [getColumnAdjustment()](#getColumnAdjustment--) | Получает или задает настройку столбца таблицы. |
| [getColumnWidths()](#getColumnWidths--) | Получает ширину столбцов таблицы. |
| [getCornerStyle()](#getCornerStyle--) | Получает или задает стили углов границы |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | Получает объект /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard. |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | Получает границу ячейки по умолчанию. |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | Получает или задает заполнение ячейки по умолчанию. |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | Получает или задает состояние текста ячейки по умолчанию. |
| [getDefaultColumnWidth()](#getDefaultColumnWidth--) | Получает или задает ширину столбца по умолчанию. |
| [getElementEngine()](#getElementEngine--) | Получить родительский элемент. |
| [getExpansionText()](#getExpansionText--) | Получает или задает текст расширения для элемента структуры. |
| [getID()](#getID--) | Получает идентификатор элемента структуры. |
| [getLanguage()](#getLanguage--) | Получает или задает язык для элемента структуры. |
| [getLeft()](#getLeft--) | Получает или задает левую координату стола. |
| [getParentElement()](#getParentElement--) | Получает родительскую коллекцию объектов Element. |
| [getRepeatingColumnsCount()](#getRepeatingColumnsCount--) | Получает или задает максимальное количество столбцов для таблицы. |
| [getRepeatingRowsCount()](#getRepeatingRowsCount--) | Получает количество первых строк, повторяющихся для нескольких страниц. |
| [getRepeatingRowsStyle()](#getRepeatingRowsStyle--) | Получает стиль для повторяющихся строк. |
| [getS()](#getS--) |  |
| [getStructureType()](#getStructureType--) | Получает тип элемента структуры. |
| [getTable()](#getTable--) |  |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTitle()](#getTitle--) | Получает или задает заголовок элемента структуры. |
| [getTop()](#getTop--) | Получает или задает координату столешницы. |
| [getTrailer()](#getTrailer--) | Внутренний метод |
| [hashCode()](#hashCode--) |  |
| [isBordersIncluded()](#isBordersIncluded--) | Получает или задает границу, включенную в ширину столбцов. |
| [isBroken()](#isBroken--) | Получает или устанавливает, что таблица не работает — будет усечена для следующей страницы. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | Получает или задает фактический текст для элемента структуры. |
| [setAlignment(int value)](#setAlignment-int-) | Получает или задает выравнивание таблицы. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Получает или задает альтернативный текст для элемента структуры. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Получает или задает цвет фона таблицы. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Получает или задает границу таблицы. |
| [setBordersIncluded(boolean value)](#setBordersIncluded-boolean-) | Получает или задает границу, включенную в ширину столбцов. |
| [setBroken(boolean value)](#setBroken-boolean-) | Получает или устанавливает, что таблица не работает — будет усечена для следующей страницы. |
| [setBroken(int value)](#setBroken-int-) | Получает или устанавливает сломанную вертикаль таблицы; |
| [setColumnAdjustment(int value)](#setColumnAdjustment-int-) | Получает или задает настройку столбца таблицы. |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | Получает ширину столбцов таблицы. |
| [setCornerStyle(int value)](#setCornerStyle-int-) | Получает или задает стили углов границы |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Получает границу ячейки по умолчанию. |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Получает или задает заполнение ячейки по умолчанию. |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Получает или задает состояние текста ячейки по умолчанию. |
| [setDefaultColumnWidth(String value)](#setDefaultColumnWidth-java.lang.String-) | Получает или задает ширину столбца по умолчанию. |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | Получает или задает текст расширения для элемента структуры. |
| [setId(String id)](#setId-java.lang.String-) | Устанавливает ID для элемента структуры. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Получает или задает язык для элемента структуры. |
| [setLeft(float value)](#setLeft-float-) | Получает или задает левую координату стола. |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | установить родительский элемент |
| [setRepeatingColumnsCount(int value)](#setRepeatingColumnsCount-int-) | Получает или задает максимальное количество столбцов для таблицы. |
| [setRepeatingRowsCount(int value)](#setRepeatingRowsCount-int-) | Получает количество первых строк, повторяющихся для нескольких страниц. |
| [setRepeatingRowsStyle(TextState value)](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Получает стиль для повторяющихся строк. |
| [setTag(String newTag)](#setTag-java.lang.String-) | Устанавливает пользовательский тег для элемента структуры. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Получает или задает заголовок элемента структуры. |
| [setTop(float value)](#setTop-float-) | Получает или задает координату столешницы. |
| [toString()](#toString--) | Возвращает строку, которая представляет текущий объект. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public TableElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
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

### createTBody() {#createTBody--}
```
public final TableTBodyElement createTBody()
```


 Создает[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) и добавил его в текущую таблицу.

**Возвращает:**
[TableTBodyElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletbodyelement) - Создан элемент структуры.
### createTFoot() {#createTFoot--}
```
public final TableTFootElement createTFoot()
```


 Создает[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) и добавил его в текущую таблицу.

**Возвращает:**
[TableTFootElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletfootelement) - Создан элемент структуры.
### createTHead() {#createTHead--}
```
public final TableTHeadElement createTHead()
```


 Создает[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) и добавил его в текущую таблицу.

**Возвращает:**
[TableTHeadElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletheadelement) - Создан элемент структуры.
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


Получает или задает выравнивание таблицы.

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


Получает или задает цвет фона таблицы.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной экземпляр
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


Получает или задает границу таблицы.

**Возвращает:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - экземпляр BorderInfo
### getBroken() {#getBroken--}
```
public final int getBroken()
```


Получает или устанавливает сломанную вертикаль таблицы;

**Возвращает:**
int - элемент TableBroken
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
### getColumnAdjustment() {#getColumnAdjustment--}
```
public final int getColumnAdjustment()
```


Получает или задает настройку столбца таблицы.

**Возвращает:**
int — элемент ColumnAdjustment
### getColumnWidths() {#getColumnWidths--}
```
public final String getColumnWidths()
```


Получает ширину столбцов таблицы.

**Возвращает:**
java.lang.String — строковое значение
### getCornerStyle() {#getCornerStyle--}
```
public final int getCornerStyle()
```


Получает или задает стили углов границы

**Возвращает:**
int - элемент BorderCornerStyle
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


Получает или задает заполнение ячейки по умолчанию.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - Экземпляр MarginInfo
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


Получает или задает состояние текста ячейки по умолчанию.

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Экземпляр TextState
### getDefaultColumnWidth() {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```


Получает или задает ширину столбца по умолчанию.

**Возвращает:**
java.lang.String — строковое значение
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
### getLeft() {#getLeft--}
```
public final float getLeft()
```


Получает или задает левую координату стола.

**Возвращает:**
float - плавающее значение
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Получает родительскую коллекцию объектов Element.

**Возвращает:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Значение: родительская коллекция объектов Element.
### getRepeatingColumnsCount() {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```


Получает или задает максимальное количество столбцов для таблицы.

**Возвращает:**
интервал - целочисленное значение
### getRepeatingRowsCount() {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```


Получает количество первых строк, повторяющихся для нескольких страниц.

**Возвращает:**
интервал - целочисленное значение
### getRepeatingRowsStyle() {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```


Получает стиль для повторяющихся строк.

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Экземпляр TextState
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
### getTable() {#getTable--}
```
public final Table getTable()
```




**Возвращает:**
[Table](../../com.aspose.pdf/table)
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
### getTop() {#getTop--}
```
public final float getTop()
```


Получает или задает координату столешницы.

**Возвращает:**
float - плавающее значение
### getTrailer() {#getTrailer--}
```
public final ITrailerable getTrailer()
```


Внутренний метод

**Возвращает:**
[ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) - Внутренний элемент
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isBordersIncluded() {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```


Получает или задает границу, включенную в ширину столбцов.

**Возвращает:**
boolean - логическое значение
### isBroken() {#isBroken--}
```
public final boolean isBroken()
```


Получает или устанавливает, что таблица не работает — будет усечена для следующей страницы.

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


Получает или задает выравнивание таблицы.

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


Получает или задает цвет фона таблицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Экземпляр цвета |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


Получает или задает границу таблицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | Экземпляр BorderInfo |

### setBordersIncluded(boolean value) {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```


Получает или задает границу, включенную в ширину столбцов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBroken(boolean value) {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```


Получает или устанавливает, что таблица не работает — будет усечена для следующей страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBroken(int value) {#setBroken-int-}
```
public final void setBroken(int value)
```


Получает или устанавливает сломанную вертикаль таблицы;

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент TableBroken |

### setColumnAdjustment(int value) {#setColumnAdjustment-int-}
```
public final void setColumnAdjustment(int value)
```


Получает или задает настройку столбца таблицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ColumnAdjustment |

### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public final void setColumnWidths(String value)
```


Получает ширину столбцов таблицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setCornerStyle(int value) {#setCornerStyle-int-}
```
public final void setCornerStyle(int value)
```


Получает или задает стили углов границы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент BorderCornerStyle |

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


Получает или задает заполнение ячейки по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Экземпляр MarginInfo |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


Получает или задает состояние текста ячейки по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Экземпляр TextState |

### setDefaultColumnWidth(String value) {#setDefaultColumnWidth-java.lang.String-}
```
public final void setDefaultColumnWidth(String value)
```


Получает или задает ширину столбца по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

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

### setLeft(float value) {#setLeft-float-}
```
public final void setLeft(float value)
```


Получает или задает левую координату стола.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


установить родительский элемент

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | ценность |

### setRepeatingColumnsCount(int value) {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```


Получает или задает максимальное количество столбцов для таблицы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setRepeatingRowsCount(int value) {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```


Получает количество первых строк, повторяющихся для нескольких страниц.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setRepeatingRowsStyle(TextState value) {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
```
public final void setRepeatingRowsStyle(TextState value)
```


Получает стиль для повторяющихся строк.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Экземпляр TextState |

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

### setTop(float value) {#setTop-float-}
```
public final void setTop(float value)
```


Получает или задает координату столешницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

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
