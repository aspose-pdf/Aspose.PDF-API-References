---
title: MCRElement
second_title: Aspose.PDF для справки по Java API
description: Представляет объект ссылки на отмеченное содержимое в логической структуре.
type: docs
weight: 15
url: /ru/java/com.aspose.pdf.tagged.logicalstructure.elements/mcrelement/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
```
public final class MCRElement extends Element
```

Представляет объект ссылки на отмеченное содержимое в логической структуре.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MCRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Найти элементы заданного типа |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Найти элементы заданного типа |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Добавить /Aspose.Pdf.LogicalStructure.Element к коллекции дочерних элементов. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildElements()](#getChildElements--) | Получает дочернюю коллекцию объектов Element. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | Получает текстовое содержимое для элемента ссылки с отмеченным содержимым. |
| [getElementEngine()](#getElementEngine--) | Получить родительский элемент. |
| [getImageHeight()](#getImageHeight--) | Только для внутреннего использования |
| [getImageResolution()](#getImageResolution--) | Только для внутреннего использования |
| [getImageSrc()](#getImageSrc--) | Получает источник изображения для элемента ссылки на отмеченное содержимое. |
| [getImageWidth()](#getImageWidth--) | Только для внутреннего использования |
| [getMCID()](#getMCID--) | Получает MCID объекта ссылки на отмеченное содержимое. |
| [getPage()](#getPage--) | Получить экземпляр страницы |
| [getParentElement()](#getParentElement--) | Получает родительскую коллекцию объектов Element. |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTrailer()](#getTrailer--) | Внутренний метод |
| [hashCode()](#hashCode--) |  |
| [isCreatedElement()](#isCreatedElement--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBdcOperator(BDC value)](#setBdcOperator-com.aspose.pdf.operators.BDC-) | Установить оператора BDC |
| [setContent(String value)](#setContent-java.lang.String-) | Получает текстовое содержимое для элемента ссылки с отмеченным содержимым. |
| [setHyperlink(Hyperlink hyperlink)](#setHyperlink-com.aspose.pdf.Hyperlink-) |  |
| [setImageHeight(Double[] value)](#setImageHeight-java.lang.Double---) | Только для внутреннего использования |
| [setImageResolution(Double[] value)](#setImageResolution-java.lang.Double---) | Только для внутреннего использования |
| [setImageSrc(String value)](#setImageSrc-java.lang.String-) | Получает источник изображения для элемента ссылки на отмеченное содержимое. |
| [setImageWidth(Double[] value)](#setImageWidth-java.lang.Double---) | Только для внутреннего использования |
| [setNewMCID(int value)](#setNewMCID-int-) | Получить значение MCID |
| [setPage(Page value)](#setPage-com.aspose.pdf.Page-) | Установить экземпляр страницы |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [toString()](#toString--) | Возвращает строку, которая представляет текущий объект. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MCRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#MCRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public MCRElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| taggedContext | [TaggedContext](../../com.aspose.pdf.tagged/taggedcontext) | Экземпляр TaggedContext |
| pdfEngineEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | Внутренний экземпляр |

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
### getContent() {#getContent--}
```
public final String getContent()
```


Получает текстовое содержимое для элемента ссылки с отмеченным содержимым.

 Для только что созданного объекта, реализующего[ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement). Является нулевым в других случаях.

**Возвращает:**
java.lang.String — Текстовое содержимое для элемента ссылки на отмеченное содержимое.
### getElementEngine() {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```


Получить родительский элемент.

**Возвращает:**
[ElementPdfEngine](../../com.aspose.pdf.tagged.logicalstructure/elementpdfengine) - Значение: родительский элемент.
### getImageHeight() {#getImageHeight--}
```
public final Double[] getImageHeight()
```


Только для внутреннего использования

**Возвращает:**
java.lang.Double[] - Только для внутреннего использования
### getImageResolution() {#getImageResolution--}
```
public final Double[] getImageResolution()
```


Только для внутреннего использования

**Возвращает:**
java.lang.Double[] - Только для внутреннего использования
### getImageSrc() {#getImageSrc--}
```
public final String getImageSrc()
```


Получает источник изображения для элемента ссылки на отмеченное содержимое.

 Для только что созданного[IllustrationElement](../../com.aspose.pdf.tagged.logicalstructure.elements/illustrationelement). Является нулевым в других случаях.

**Возвращает:**
java.lang.String — источник изображения для элемента ссылки на отмеченное содержимое.
### getImageWidth() {#getImageWidth--}
```
public final Double[] getImageWidth()
```


Только для внутреннего использования

**Возвращает:**
java.lang.Double[] - Только для внутреннего использования
### getMCID() {#getMCID--}
```
public final int getMCID()
```


Получает MCID объекта ссылки на отмеченное содержимое.

**Возвращает:**
int - MCID объекта ссылки на размеченное содержимое.
### getPage() {#getPage--}
```
public final Page getPage()
```


Получить экземпляр страницы

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Экземпляр страницы
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Получает родительскую коллекцию объектов Element.

**Возвращает:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Значение: родительская коллекция объектов Element.
### getTaggedContent() {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```




**Возвращает:**
[ITaggedContent](../../com.aspose.pdf.tagged/itaggedcontent)
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
### isCreatedElement() {#isCreatedElement--}
```
public final boolean isCreatedElement()
```




**Возвращает:**
логический
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBdcOperator(BDC value) {#setBdcOperator-com.aspose.pdf.operators.BDC-}
```
public final void setBdcOperator(BDC value)
```


Установить оператора BDC

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BDC](../../com.aspose.pdf.operators/bdc) | Оператор BDC |

### setContent(String value) {#setContent-java.lang.String-}
```
public final void setContent(String value)
```


Получает текстовое содержимое для элемента ссылки с отмеченным содержимым.

 Для только что созданного объекта, реализующего[ITextElement](../../com.aspose.pdf.tagged.logicalstructure.elements/itextelement). Является нулевым в других случаях.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Текстовое содержимое для элемента ссылки с отмеченным содержимым. |

### setHyperlink(Hyperlink hyperlink) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public final void setHyperlink(Hyperlink hyperlink)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| hyperlink | [Hyperlink](../../com.aspose.pdf/hyperlink) |  |

### setImageHeight(Double[] value) {#setImageHeight-java.lang.Double---}
```
public final void setImageHeight(Double[] value)
```


Только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Double[] | Только для внутреннего использования |

### setImageResolution(Double[] value) {#setImageResolution-java.lang.Double---}
```
public final void setImageResolution(Double[] value)
```


Только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Double[] | Только для внутреннего использования |

### setImageSrc(String value) {#setImageSrc-java.lang.String-}
```
public final void setImageSrc(String value)
```


Получает источник изображения для элемента ссылки на отмеченное содержимое.

 Для только что созданного[IllustrationElement](../../com.aspose.pdf.tagged.logicalstructure.elements/illustrationelement). Является нулевым в других случаях.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Источник изображения для элемента ссылки с помеченным содержимым. |

### setImageWidth(Double[] value) {#setImageWidth-java.lang.Double---}
```
public final void setImageWidth(Double[] value)
```


Только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Double[] | Только для внутреннего использования |

### setNewMCID(int value) {#setNewMCID-int-}
```
public final void setNewMCID(int value)
```


Получить значение MCID

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | значение MCID |

### setPage(Page value) {#setPage-com.aspose.pdf.Page-}
```
public final void setPage(Page value)
```


Установить экземпляр страницы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | Экземпляр страницы |

### setParentElement(Element parentElement) {#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void setParentElement(Element parentElement)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| parentElement | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

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
