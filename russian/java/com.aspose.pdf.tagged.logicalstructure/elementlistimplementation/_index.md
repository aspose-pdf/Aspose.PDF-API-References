---
title: ElementListImplementation
second_title: Aspose.PDF для справки по Java API
description: 
type: docs
weight: 14
url: /ru/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.tagged.logicalstructure.ElementList](../../com.aspose.pdf.tagged.logicalstructure/elementlist)
```
public class ElementListImplementation extends ElementList
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ElementListImplementation(Element owner)](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCount()](#getCount--) |  |
| [item(int index)](#item-int-) |  |
| [iterator()](#iterator--) |  |
| [addElement(Element element, boolean updatePdfDictionary)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) |  |
| [removeElement(Element element)](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
### ElementListImplementation(Element owner) {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public ElementListImplementation(Element owner)
```


**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| owner | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

### getCount() {#getCount--}
```
public int getCount()
```


Получает количество элементов в ElementList.

**Возвращает:**
инт
### item(int index) {#item-int-}
```
public Element item(int index)
```


Извлекает элемент по заданному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<Element> iterator()
```


Получает перечислитель, который перебирает коллекцию элементов.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.tagged.logicalstructure.elements.Element>
### addElement(Element element, boolean updatePdfDictionary) {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
```
public void addElement(Element element, boolean updatePdfDictionary)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |
| updatePdfDictionary | boolean |  |

### removeElement(Element element) {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void removeElement(Element element)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |
