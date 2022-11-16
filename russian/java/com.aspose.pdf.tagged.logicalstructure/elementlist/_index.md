---
title: ElementList
second_title: Aspose.PDF для справки по Java API
description: Представляет упорядоченный набор элементов.
type: docs
weight: 13
url: /ru/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public abstract class ElementList implements System.Collections.Generic.IGenericEnumerable<Element>
```

Представляет упорядоченный набор элементов.
## Методы

| Метод | Описание |
| --- | --- |
| [addElement(Element element)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement(Element element, boolean updatePdfDictionary)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Получает количество элементов в ElementList. |
| [get_Item(int index)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) |  |
| [item(int index)](#item-int-) | Извлекает элемент по заданному индексу. |
| [iterator()](#iterator--) | Получает перечислитель, который перебирает коллекцию элементов. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeElement(Element element)](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addElement(Element element) {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void addElement(Element element)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

### addElement(Element element, boolean updatePdfDictionary) {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
```
public abstract void addElement(Element element, boolean updatePdfDictionary)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |
| updatePdfDictionary | boolean |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCount() {#getCount--}
```
public abstract int getCount()
```


Получает количество элементов в ElementList.

**Возвращает:**
интервал - целочисленное значение
### get_Item(int index) {#get-Item-int-}
```
public Element get_Item(int index)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### item(int index) {#item-int-}
```
public abstract Element item(int index)
```


Извлекает элемент по заданному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс в списке элементов. |

**Возвращает:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - Элемент /Aspose.Pdf.LogicalStructure.Element с указанным индексом в коллекции. Если индекс больше или равен количеству элементов в списке, возвращается значение null.
### iterator() {#iterator--}
```
public abstract System.Collections.Generic.IGenericEnumerator<Element> iterator()
```


Получает перечислитель, который перебирает коллекцию элементов.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.tagged.logicalstructure.elements.Element> — перечислитель, используемый для перебора коллекции элементов.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeElement(Element element) {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public abstract void removeElement(Element element)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

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
