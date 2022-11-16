---
title: StructTreeRootElement
second_title: Aspose.PDF для справки по Java API
description: Представляет объект StructTreeRoot в логической структуре.
type: docs
weight: 14
url: /ru/java/com.aspose.pdf.tagged.logicalstructure/structtreerootelement/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.elements.Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
```
public final class StructTreeRootElement extends Element
```

Представляет объект StructTreeRoot в логической структуре.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StructTreeRootElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)](#StructTreeRootElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>findElements(Class<T> typeOfTboolean)](#-T-findElements-java.lang.Class-T--) | Найти элементы заданного типа |
| [<T>findElements(Class<T> typeOfT, boolean recursiveSearch)](#-T-findElements-java.lang.Class-T--boolean-) | Найти элементы заданного типа |
| [appendChild(Element element)](#appendChild-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Добавить /Aspose.Pdf.LogicalStructure.Element к коллекции дочерних элементов. |
| [createStructParents()](#createStructParents--) |  |
| [doPreSave()](#doPreSave--) |  |
| [doSave()](#doSave--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllElements()](#getAllElements--) |  |
| [getChildElements()](#getChildElements--) | Получает дочернюю коллекцию объектов Element. |
| [getClass()](#getClass--) |  |
| [getElementEngine()](#getElementEngine--) | Получить родительский элемент. |
| [getIDTree()](#getIDTree--) |  |
| [getParentElement()](#getParentElement--) | Получает родительскую коллекцию объектов Element. |
| [getRoleMap()](#getRoleMap--) |  |
| [getStructParentsArray(IPdfNumber structParents)](#getStructParentsArray-com.aspose.pdf.engine.data.IPdfNumber-) |  |
| [getTaggedContent()](#getTaggedContent--) |  |
| [getTrailer()](#getTrailer--) | Внутренний метод |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registrationObjectInParentTree(IPdfObject pdfObject)](#registrationObjectInParentTree-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [setParentElement(Element parentElement)](#setParentElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [toString()](#toString--) | Возвращает строку, которая представляет текущий объект. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructTreeRootElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity) {#StructTreeRootElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public StructTreeRootElement(TaggedContext taggedContext, IPdfPrimitive pdfEngineEntity)
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
### createStructParents() {#createStructParents--}
```
public final IPdfNumber createStructParents()
```




**Возвращает:**
[IPdfNumber](../../com.aspose.pdf.engine.data/ipdfnumber)
### doPreSave() {#doPreSave--}
```
public final void doPreSave()
```




### doSave() {#doSave--}
```
public final void doSave()
```




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
### getAllElements() {#getAllElements--}
```
public final System.Collections.Generic.List<Element> getAllElements()
```




**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.tagged.logicalstructure.elements.Element>
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
### getElementEngine() {#getElementEngine--}
```
public final ElementPdfEngine getElementEngine()
```


Получить родительский элемент.

**Возвращает:**
[ElementPdfEngine](../../com.aspose.pdf.tagged.logicalstructure/elementpdfengine) - Значение: родительский элемент.
### getIDTree() {#getIDTree--}
```
public final NamesTreeNode getIDTree()
```




**Возвращает:**
[NamesTreeNode](../../com.aspose.pdf.engine.commondata/namestreenode)
### getParentElement() {#getParentElement--}
```
public final Element getParentElement()
```


Получает родительскую коллекцию объектов Element.

**Возвращает:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Значение: родительская коллекция объектов Element.
### getRoleMap() {#getRoleMap--}
```
public final IPdfDictionary getRoleMap()
```




**Возвращает:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)
### getStructParentsArray(IPdfNumber structParents) {#getStructParentsArray-com.aspose.pdf.engine.data.IPdfNumber-}
```
public final IPdfArray getStructParentsArray(IPdfNumber structParents)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| structParents | [IPdfNumber](../../com.aspose.pdf.engine.data/ipdfnumber) |  |

**Возвращает:**
[IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray)
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registrationObjectInParentTree(IPdfObject pdfObject) {#registrationObjectInParentTree-com.aspose.pdf.engine.data.IPdfObject-}
```
public final int registrationObjectInParentTree(IPdfObject pdfObject)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfObject | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) |  |

**Возвращает:**
инт
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
