---
title: BLSTextElement
second_title: Aspose.PDF для справки по Java API
description: Представляет базовый класс для элементов текстовой структуры блочного уровня в логической структуре.
type: docs
weight: 11
url: /ru/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/blstextelement/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element), [com.aspose.pdf.tagged.logicalstructure.elements.StructureElement](../../com.aspose.pdf.tagged.logicalstructure.elements/structureelement), [com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement](../../com.aspose.pdf.tagged.logicalstructure.elements.bls/blselement)

**Все реализованные интерфейсы:**
[com.aspose.pdf.tagged.logicalstructure.elements.ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement)
```
public abstract class BLSTextElement extends BLSElement implements ITextElement
```

Представляет базовый класс для элементов текстовой структуры блочного уровня в логической структуре.
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
| [getAlternativeText()](#getAlternativeText--) | Получает или задает альтернативный текст для элемента структуры. |
| [getAttributes()](#getAttributes--) | Получает объект StructureAttributeCollection. |
| [getChildElements()](#getChildElements--) | Получает дочернюю коллекцию объектов Element. |
| [getClass()](#getClass--) |  |
| [getDefaultAttributeOwner()](#getDefaultAttributeOwner--) | Получает объект /Aspose.Pdf.LogicalStructure.AttributeOwnerStandard. |
| [getElementEngine()](#getElementEngine--) | Получить родительский элемент. |
| [getExpansionText()](#getExpansionText--) | Получает или задает текст расширения для элемента структуры. |
| [getID()](#getID--) | Получает идентификатор элемента структуры. |
| [getLanguage()](#getLanguage--) | Получает или задает язык для элемента структуры. |
| [getParentElement()](#getParentElement--) | Получает родительскую коллекцию объектов Element. |
| [getS()](#getS--) |  |
| [getStructureTextState()](#getStructureTextState--) | Получает объект StructureTextState для текущего элемента. |
| [getStructureType()](#getStructureType--) | Получает тип элемента структуры. |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTextFragment()](#getTextFragment--) |  |
| [getTitle()](#getTitle--) | Получает или задает заголовок элемента структуры. |
| [getTrailer()](#getTrailer--) | Внутренний метод |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setActualText(String value)](#setActualText-java.lang.String-) | Получает или задает фактический текст для элемента структуры. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Получает или задает альтернативный текст для элемента структуры. |
| [setExpansionText(String value)](#setExpansionText-java.lang.String-) | Получает или задает текст расширения для элемента структуры. |
| [setId(String id)](#setId-java.lang.String-) | Устанавливает ID для элемента структуры. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | Получает или задает язык для элемента структуры. |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | установить родительский элемент |
| [setTag(String newTag)](#setTag-java.lang.String-) | Устанавливает пользовательский тег для элемента структуры. |
| [setText(String text)](#setText-java.lang.String-) | Добавляет текстовое содержимое к текущему текстовому элементу. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Получает или задает заголовок элемента структуры. |
| [toString()](#toString--) | Возвращает строку, которая представляет текущий объект. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
java.util.List<T> Список найденных элементов
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
java.util.List<T> Список найденных элементов
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
### getStructureTextState() {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```


Получает объект StructureTextState для текущего элемента.

Значение: объектstructureTextState для текущего элемента.

**Возвращает:**
[StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate)
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
### getTextFragment() {#getTextFragment--}
```
public final TextFragment getTextFragment()
```




**Возвращает:**
[TextFragment](../../com.aspose.pdf/textfragment)
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
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

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```


установить родительский элемент

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) | ценность |

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
