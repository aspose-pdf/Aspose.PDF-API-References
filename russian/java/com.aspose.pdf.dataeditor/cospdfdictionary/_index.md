---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Справочник API Aspose.PDF для Java"
description: "Класс для доступа к словарю объекта."
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

Класс для доступа к словарю объекта.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Создает словарь из ресурсов. @exception ArgumentNullException Ресурсы равны null. |

## Методы

| Метод | Описание |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Установить ICosPdfPrimitive в словарь. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Установите {@link ICosPdfPrimitive} в словарь. @exception ArgumentException Выбрасывает исключение, если ключ/значение нельзя изменить или удалить. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Добавить пару элементов. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Добавить элемент. |
| [clear](#clear--) | Удаляет все элементы из {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Определяет, содержит ли CosPdfDictionary конкретное значение. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Возвращает true, если содержит элемент |
| [containsKey](#containsKey-java.lang.String-) | Определяет, содержит ли {@link CosPdfDictionary} элемент с указанным ключом. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Копирует элементы CosPdfDictionary в массив, начиная с указанного индекса массива. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Копировать в массив |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Создает пустой словарь, который будет прикреплен к документу. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Создает пустой словарь, который будет прикреплен к странице. |
| [get_Item](#get_Item-java.lang.String-) | Получает или задаёт элемент с указанным ключом. |
| [getAllKeys](#getAllKeys--) | Полный набор ключей. Содержит редактируемые и не редактируемые ключи. |
| [getKeys](#getKeys--) | Коллекция редактируемых ключей. |
| [getValues](#getValues--) | Получает {@link ICollection}, содержащий значения в {@link CosPdfDictionary}. |
| [isReadOnly](#isReadOnly--) | Получает значение, указывающее, является ли {@link CosPdfDictionary} только для чтения. |
| [iterator](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Удаляет первое вхождение конкретного объекта из CosPdfDictionary. |
| [remove](#remove-java.lang.String-) | Удаляет элемент с указанным ключом из {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Удалить элемент |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Удалить элемент по ключу. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Получает или задает элемент с указанным ключом. @exception ArgumentNullException Ключ равен null. @exception KeyNotFoundException Свойство получено, но ключ не найден. @exception ArgumentException Выбрасывает исключение, если ключ нельзя изменить/установить. |
| [size](#size--) | Получает количество элементов, содержащихся в {@link CosPdfDictionary}. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Пытается привести этот экземпляр к {@link CosPdfDictionary}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Попробовать получить значение |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Создает словарь из ресурсов. @exception ArgumentNullException Ресурсы равны null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Установить ICosPdfPrimitive в словарь.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Установите {@link ICosPdfPrimitive} в словарь. @exception ArgumentException Выбрасывает исключение, если ключ/значение нельзя изменить или удалить.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Добавить пару элементов.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Добавить элемент.

### clear {#clear--}
```
public final void clear()
```

Удаляет все элементы из {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Определяет, содержит ли CosPdfDictionary конкретное значение.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Возвращает true, если содержит элемент

### containsKey {#containsKey-java.lang.String-}
Определяет, содержит ли {@link CosPdfDictionary} элемент с указанным ключом.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Копирует элементы CosPdfDictionary в массив, начиная с указанного индекса массива.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Копировать в массив

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Создает пустой словарь, который будет прикреплен к документу.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Создает пустой словарь, который будет прикреплен к странице.

### get_Item {#get_Item-java.lang.String-}
Получает или задаёт элемент с указанным ключом.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Полный набор ключей. Содержит редактируемые и не редактируемые ключи.

**Returns:**
Список строковых значений

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Коллекция редактируемых ключей.

**Returns:**
Список строковых значений

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Получает {@link ICollection}, содержащий значения в {@link CosPdfDictionary}.

**Returns:**
Список экземпляров ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Получает значение, указывающее, является ли {@link CosPdfDictionary} только для чтения.

**Returns:**
true, если {@link CosPdfDictionary} только для чтения; иначе false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Returns:**
Перечислитель, который можно использовать для перебора элементов коллекции.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Удаляет первое вхождение конкретного объекта из CosPdfDictionary.

### remove {#remove-java.lang.String-}
Удаляет элемент с указанным ключом из {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Удалить элемент

### removeItemByKey {#removeItemByKey-java.lang.String-}
Удалить элемент по ключу.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Получает или задает элемент с указанным ключом. @exception ArgumentNullException Ключ равен null. @exception KeyNotFoundException Свойство получено, но ключ не найден. @exception ArgumentException Выбрасывает исключение, если ключ нельзя изменить/установить.

### size {#size--}
```
public final int size()
```

Получает количество элементов, содержащихся в {@link CosPdfDictionary}.

**Returns:**
int значение

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Пытается привести этот экземпляр к {@link CosPdfDictionary}.

**Returns:**
null, если экземпляр не является {@link CosPdfDictionary}, иначе {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Попробовать получить значение
