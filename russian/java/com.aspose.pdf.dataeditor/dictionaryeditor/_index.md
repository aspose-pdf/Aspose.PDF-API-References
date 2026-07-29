---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Справочник API Aspose.PDF для Java"
description: "Класс для доступа к дереву словарей документа (словарь документа, словарь страниц, словарь ресурсов)."
type: docs
weight: 70
url: /ru/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

Класс для доступа к дереву словарей документа (словарь документа, словарь страниц, словарь ресурсов).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException Ресурсы равны null. |

## Методы

| Метод | Описание |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Установить ICosPdfPrimitive в словарь. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Установить {@link ICosPdfPrimitive} в словарь. |
| [clear](#clear--) | Удаляет все элементы из {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Определяет, содержит ли DictionaryEditor определённое значение. |
| [containsKey](#containsKey-java.lang.String-) | Определяет, содержит ли {@link DictionaryEditor} элемент с указанным ключом. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Копирует элементы DictionaryEditor в Array, начиная с определённого индекса Array. |
| [get_Item](#get_Item-java.lang.String-) | Получает или задаёт элемент с указанным ключом. |
| [getAllKeys](#getAllKeys--) | Полный набор ключей. Содержит редактируемые и не редактируемые ключи. |
| [getKeys](#getKeys--) | Коллекция редактируемых ключей. |
| [getValues](#getValues--) | Получает {@link ICollection}, содержащий значения в {@link DictionaryEditor}. |
| [isReadOnly](#isReadOnly--) | Получает значение, указывающее, является ли {@link DictionaryEditor} только для чтения. |
| [iterator](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Удаляет первое вхождение конкретного объекта из DictionaryEditor. |
| [remove](#remove-java.lang.String-) | Удаляет элемент с указанным ключом из {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Получает или задаёт элемент с указанным ключом. |
| [size](#size--) | Получает количество элементов, содержащихся в {@link DictionaryEditor}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException Ресурсы равны null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Установить ICosPdfPrimitive в словарь.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Установить {@link ICosPdfPrimitive} в словарь.

### clear {#clear--}
```
public final void clear()
```

Удаляет все элементы из {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Определяет, содержит ли DictionaryEditor определённое значение.

### containsKey {#containsKey-java.lang.String-}
Определяет, содержит ли {@link DictionaryEditor} элемент с указанным ключом.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Копирует элементы DictionaryEditor в Array, начиная с определённого индекса Array.

### get_Item {#get_Item-java.lang.String-}
Получает или задаёт элемент с указанным ключом.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Полный набор ключей. Содержит редактируемые и не редактируемые ключи.

**Returns:**
Итерируемый объект экземпляра String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Коллекция редактируемых ключей.

**Returns:**
Итерируемый объект экземпляра String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Получает {@link ICollection}, содержащий значения в {@link DictionaryEditor}.

**Returns:**
Итерируемый объект экземпляра ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Получает значение, указывающее, является ли {@link DictionaryEditor} только для чтения.

**Returns:**
true, если {@link DictionaryEditor} только для чтения; иначе false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Возвращает перечислитель, который проходит по коллекции.

**Returns:**
Перечислитель, который можно использовать для перебора элементов коллекции.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Удаляет первое вхождение конкретного объекта из DictionaryEditor.

### remove {#remove-java.lang.String-}
Удаляет элемент с указанным ключом из {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Получает или задаёт элемент с указанным ключом.

### size {#size--}
```
public final int size()
```

Получает количество элементов, содержащихся в {@link DictionaryEditor}.

**Returns:**
int значение

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Для доступа к простым типам данных, таким как string, name, bool, number. Возвращает null для других типов.
