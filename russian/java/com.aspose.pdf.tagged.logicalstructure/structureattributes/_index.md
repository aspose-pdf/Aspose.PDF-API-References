---
title: StructureAttributes
second_title: Aspose.PDF для справки по Java API
description: Представляет атрибуты элемента структуры для владельцев стандартных атрибутов.
type: docs
weight: 16
url: /ru/java/com.aspose.pdf.tagged.logicalstructure/structureattributes/
---
**Наследование:**
java.lang.Object
```
public class StructureAttributes
```

Представляет атрибуты элемента структуры для владельцев стандартных атрибутов.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttribute(AttributeKey key)](#getAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Получает StructureAttribute по AttributeKey. |
| [getClass()](#getClass--) |  |
| [getEngineAttributes()](#getEngineAttributes--) |  |
| [getOwner()](#getOwner--) | Получает владельца стандартного атрибута. |
| [hasAttribute(AttributeKey key)](#hasAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttribute(StructureAttribute attribute)](#setAttribute-com.aspose.pdf.tagged.logicalstructure.elements.StructureAttribute-) | Устанавливает StructureAttribute в StructureAttributes. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAttribute(AttributeKey key) {#getAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
```
public final StructureAttribute getAttribute(AttributeKey key)
```


Получает StructureAttribute по AttributeKey.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) | АтрибутКлюч. |

**Возвращает:**
[StructureAttribute](../../com.aspose.pdf.tagged.logicalstructure.elements/structureattribute) - экземпляр StructureAttribute
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getEngineAttributes() {#getEngineAttributes--}
```
public final IPdfDictionary getEngineAttributes()
```




**Возвращает:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary)
### getOwner() {#getOwner--}
```
public final AttributeOwnerStandard getOwner()
```


Получает владельца стандартного атрибута.

Значение: стандартный владелец атрибута.

**Возвращает:**
[AttributeOwnerStandard](../../com.aspose.pdf.tagged.logicalstructure/attributeownerstandard) - Экземпляр AttributeOwnerStandard
### hasAttribute(AttributeKey key) {#hasAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
```
public final boolean hasAttribute(AttributeKey key)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) |  |

**Возвращает:**
логический
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




### setAttribute(StructureAttribute attribute) {#setAttribute-com.aspose.pdf.tagged.logicalstructure.elements.StructureAttribute-}
```
public final void setAttribute(StructureAttribute attribute)
```


Устанавливает StructureAttribute в StructureAttributes.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| attribute | [StructureAttribute](../../com.aspose.pdf.tagged.logicalstructure.elements/structureattribute) | СтруктураАтрибут. |

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
