---
title: OutlineItemCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет запись схемы в иерархии структуры документа PDF.
type: docs
weight: 240
url: /ru/java/com.aspose.pdf/outlineitemcollection/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Outlines](../../com.aspose.pdf/outlines)
```
public final class OutlineItemCollection extends Outlines
```

Представляет запись схемы в иерархии структуры документа PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OutlineItemCollection(IPdfObject outline)](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Инициализирует новый экземпляр этого класса, используя объект записи структуры внутреннего механизма. |
| [OutlineItemCollection(OutlineCollection outlines)](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Инициализирует экземпляр элемента структуры, используя объект корневой иерархии. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(OutlineItemCollection outline)](#add-com.aspose.pdf.OutlineItemCollection-) | Добавляет элемент контура в коллекцию. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | Пока не поддерживается. |
| [copyTo(OutlineItemCollection[] array, int index)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | Копирует записи структуры в System.Array, начиная с определенного индекса System.Array. |
| [delete()](#delete--) | Удаляет этот элемент структуры из иерархии структуры документа. |
| [delete(String name)](#delete-java.lang.String-) | Удаляет запись структуры с указанным именем из иерархии структуры документа. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Получает действие для этого элемента схемы. |
| [getBold()](#getBold--) | Получает полужирный флаг для текста заголовка этого элемента структуры |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает цвет текста заголовка этого элемента схемы. |
| [getDestination()](#getDestination--) | Получает место назначения для этого элемента схемы. |
| [getEngineDict()](#getEngineDict--) | Только внутренний |
| [getEngineObj()](#getEngineObj--) | Только внутренний |
| [getFirst()](#getFirst--) | Получает элемент структуры, представляющий первый элемент верхнего уровня в иерархии структуры. |
| [getItalic()](#getItalic--) | Получает курсивный флаг для текста заголовка этого элемента структуры |
| [getLast()](#getLast--) | Получает элемент структуры, представляющий последний элемент верхнего уровня в иерархии структуры. |
| [getLevel()](#getLevel--) | Получает уровень иерархии элемента схемы. |
| [getNext()](#getNext--) | Получает элемент структуры, представляющий следующий элемент относительно этого элемента в иерархии структуры. |
| [getOpen()](#getOpen--) | Получить открытый статус (true/false) для элемента схемы. |
| [getParent()](#getParent--) | Получает родительский объект этого элемента структуры в иерархии структуры. |
| [getPrev()](#getPrev--) | Получает элемент структуры, представляющий предыдущий элемент относительно этого элемента в иерархии структуры. |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| [getTitle()](#getTitle--) | Получает заголовок для этого элемента схемы. |
| [getVisibleCount()](#getVisibleCount--) | Получает общее количество элементов структуры на всех уровнях иерархии структуры документа. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент схемы из коллекции, используя index. |
| [hasNext()](#hasNext--) | Проверьте, представляет ли элемент структуры следующий элемент относительно этого элемента в иерархии структуры. |
| [hashCode()](#hashCode--) |  |
| [insert(int index, OutlineItemCollection outline)](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Вставляет элемент схемы в коллекцию в указанном месте. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к этой коллекции синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [next()](#next--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | Пока не поддерживается. |
| [remove(int index)](#remove-int-) | Удалить элемент по индексу. |
| [setAction(PdfAction value)](#setAction-com.aspose.pdf.PdfAction-) | Задает действие для этого элемента схемы. |
| [setBold(boolean value)](#setBold-boolean-) | Устанавливает полужирный флаг для текста заголовка этого элемента структуры |
| [setColor(Color value)](#setColor-java.awt.Color-) | Задает цвет текста заголовка этого элемента структуры. |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Устанавливает место назначения для этого элемента структуры. |
| [setItalic(boolean value)](#setItalic-boolean-) | Устанавливает курсивный флаг для текста заголовка этого элемента структуры |
| [setOpen(boolean value)](#setOpen-boolean-) | Устанавливает открытый статус (true/false) для элемента схемы. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Устанавливает заголовок для этого элемента структуры. |
| [size()](#size--) | Количество предметов коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OutlineItemCollection(IPdfObject outline) {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
```
public OutlineItemCollection(IPdfObject outline)
```


Инициализирует новый экземпляр этого класса, используя объект записи структуры внутреннего механизма.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outline | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) | Внутренний объект движка контурной записи. |

### OutlineItemCollection(OutlineCollection outlines) {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
```
public OutlineItemCollection(OutlineCollection outlines)
```


Инициализирует экземпляр элемента структуры, используя объект корневой иерархии.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outlines | [OutlineCollection](../../com.aspose.pdf/outlinecollection) | Сборник аутлунов. |

### add(OutlineItemCollection outline) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public void add(OutlineItemCollection outline)
```


Добавляет элемент контура в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Добавляемый элемент схемы. |

### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из коллекции.

### contains(OutlineItemCollection item) {#contains-com.aspose.pdf.OutlineItemCollection-}
```
public boolean contains(OutlineItemCollection item)
```


Пока не поддерживается.

Всегда выдает NotImplementedException

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - логическое значение True - если элемент найден; в противном случае ложно.
### copyTo(OutlineItemCollection[] array, int index) {#copyTo-com.aspose.pdf.OutlineItemCollection---int-}
```
public void copyTo(OutlineItemCollection[] array, int index)
```


Копирует записи структуры в System.Array, начиная с определенного индекса System.Array.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [OutlineItemCollection\[\]](../../com.aspose.pdf/outlineitemcollection) | Одномерный System.Array, который является местом назначения. Должен иметь индексацию с отсчетом от нуля. |
| index | int | Отсчитываемый от нуля индекс в массиве, с которого начинается копирование. |

### delete() {#delete--}
```
public void delete()
```


Удаляет этот элемент структуры из иерархии структуры документа.

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Удаляет запись структуры с указанным именем из иерархии структуры документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название записи схемы будет удалено. |

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
### getAction() {#getAction--}
```
public PdfAction getAction()
```


Получает действие для этого элемента схемы.

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - Значение PdfAction
### getBold() {#getBold--}
```
public boolean getBold()
```


Получает полужирный флаг для текста заголовка этого элемента структуры

**Возвращает:**
boolean - логическое значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Получает цвет текста заголовка этого элемента схемы.

**Возвращает:**
[Color](../../java.awt/color) - Значение цвета
### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Получает место назначения для этого элемента схемы.

**Возвращает:**
[IAppointment](../../com.aspose.pdf/iappointment) - Значение IAppointment
### getEngineDict() {#getEngineDict--}
```
public IPdfDictionary getEngineDict()
```


Только внутренний

**Возвращает:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - Объект IPdfDictionary
### getEngineObj() {#getEngineObj--}
```
public IPdfObject getEngineObj()
```


Только внутренний

**Возвращает:**
[IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) - Объект IPdfObject
### getFirst() {#getFirst--}
```
public OutlineItemCollection getFirst()
```


Получает элемент структуры, представляющий первый элемент верхнего уровня в иерархии структуры.

**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - Значение OutlineItemCollection
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Получает курсивный флаг для текста заголовка этого элемента структуры

**Возвращает:**
boolean - логическое значение
### getLast() {#getLast--}
```
public OutlineItemCollection getLast()
```


Получает элемент структуры, представляющий последний элемент верхнего уровня в иерархии структуры.

**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - Значение OutlineItemCollection
### getLevel() {#getLevel--}
```
public int getLevel()
```


Получает уровень иерархии элемента схемы.

**Возвращает:**
интервал - целочисленное значение
### getNext() {#getNext--}
```
public OutlineItemCollection getNext()
```


Получает элемент структуры, представляющий следующий элемент относительно этого элемента в иерархии структуры.

**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - Значение OutlineItemCollection
### getOpen() {#getOpen--}
```
public boolean getOpen()
```


Получить открытый статус (true/false) для элемента схемы.

**Возвращает:**
boolean - логическое значение
### getParent() {#getParent--}
```
public Outlines getParent()
```


Получает родительский объект этого элемента структуры в иерархии структуры.

**Возвращает:**
[Outlines](../../com.aspose.pdf/outlines) - Стоимость объекта
### getPrev() {#getPrev--}
```
public OutlineItemCollection getPrev()
```


Получает элемент структуры, представляющий предыдущий элемент относительно этого элемента в иерархии структуры.

**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - Значение OutlineItemCollection
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который можно использовать для синхронизации доступа к этой коллекции.

**Возвращает:**
java.lang.Object — значение объекта
### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает заголовок для этого элемента схемы.

**Возвращает:**
java.lang.String — строковое значение
### getVisibleCount() {#getVisibleCount--}
```
public int getVisibleCount()
```


Получает общее количество элементов структуры на всех уровнях иерархии структуры документа.

**Возвращает:**
интервал - целочисленное значение
### get_Item(int index) {#get-Item-int-}
```
public OutlineItemCollection get_Item(int index)
```


Получает элемент схемы из коллекции, используя index.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель в коллекции. |

**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - Объект OutlineItemCollection.
### hasNext() {#hasNext--}
```
public final boolean hasNext()
```


Проверьте, представляет ли элемент структуры следующий элемент относительно этого элемента в иерархии структуры.

**Возвращает:**
boolean - логическое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### insert(int index, OutlineItemCollection outline) {#insert-int-com.aspose.pdf.OutlineItemCollection-}
```
public void insert(int index, OutlineItemCollection outline)
```


Вставляет элемент схемы в коллекцию в указанном месте.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс, указывающий место для вставки. |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Элемент структуры должен быть вставлен. |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Получает значение, указывающее, доступна ли коллекция только для чтения.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Получает значение, указывающее, является ли доступ к этой коллекции синхронизированным (потокобезопасным).

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public Iterator<OutlineItemCollection> iterator()
```


Возвращает перечислитель, который выполняет итерацию по коллекции.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.OutlineItemCollection> — объект System.Collections.IEnumerator, который можно использовать для перебора коллекции.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public final System.Collections.IEnumerator iterator_Rename_Namesake()
```




**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator
### next() {#next--}
```
public OutlineItemCollection next()
```




**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(OutlineItemCollection item) {#remove-com.aspose.pdf.OutlineItemCollection-}
```
public boolean remove(OutlineItemCollection item)
```


Пока не поддерживается.

Всегда выдает NotImplementedException

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Экземпляр OutlineItemCollection |

**Возвращает:**
boolean - логическое значение True - если элемент удален; в противном случае ложно.
### remove(int index) {#remove-int-}
```
public final void remove(int index)
```


Удалить элемент по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс удаляемого элемента. |

### setAction(PdfAction value) {#setAction-com.aspose.pdf.PdfAction-}
```
public void setAction(PdfAction value)
```


Задает действие для этого элемента схемы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | Значение PdfAction |

### setBold(boolean value) {#setBold-boolean-}
```
public void setBold(boolean value)
```


Устанавливает полужирный флаг для текста заголовка этого элемента структуры

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Задает цвет текста заголовка этого элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color | Цвет объекта |

### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Устанавливает место назначения для этого элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | Значение назначения |

### setItalic(boolean value) {#setItalic-boolean-}
```
public void setItalic(boolean value)
```


Устанавливает курсивный флаг для текста заголовка этого элемента структуры

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


Устанавливает открытый статус (true/false) для элемента схемы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Устанавливает заголовок для этого элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### size() {#size--}
```
public int size()
```


Количество предметов коллекции. Пожалуйста, не путайте с VisibleCount: VisibleCount получает количество видимых элементов контура на всех уровнях.

**Возвращает:**
инт
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
