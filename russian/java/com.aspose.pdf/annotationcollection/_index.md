---
title: AnnotationCollection
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий коллекцию аннотаций.
type: docs
weight: 17
url: /ru/java/com.aspose.pdf/annotationcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class AnnotationCollection implements Iterable<Annotation>
```

Класс, представляющий коллекцию аннотаций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AnnotationCollection(Page page)](#AnnotationCollection-com.aspose.pdf.Page-) | Конструктор AnnotationCollection. |
## Методы

| Метод | Описание |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Принимает посетителя для обработки аннотации. |
| [add(Annotation annotation)](#add-com.aspose.pdf.Annotation-) | Добавляет аннотацию к коллекции. |
| [add(Annotation annotation, boolean considerRotation)](#add-com.aspose.pdf.Annotation-boolean-) | Добавляет аннотацию к коллекции. |
| [clear()](#clear--) | Удаляет все аннотации из коллекции. |
| [contains(Annotation annotation)](#contains-com.aspose.pdf.Annotation-) | Проверяет, принадлежит ли указанная аннотация коллекции. |
| [copyTo(Annotation[] array, int index)](#copyTo-com.aspose.pdf.Annotation---int-) | Копирует массив аннотаций в коллекцию. |
| [delete()](#delete--) | Удаляет все аннотации из коллекции. |
| [delete(Annotation annotation)](#delete-com.aspose.pdf.Annotation-) | Удаляет указанную аннотацию из коллекции. |
| [delete(int index)](#delete-int-) | Удаляет аннотацию из коллекции по индексу. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findByName(String name)](#findByName-java.lang.String-) | Возвращает аннотацию по ее имени. |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к com.aspose.pdf.AnnotationCollection. |
| [get_Item(int index)](#get-Item-int-) | Индекс элемента, который необходимо получить. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к com.aspose.pdf.AnnotationCollection синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает перечислитель коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Annotation annotation)](#remove-com.aspose.pdf.Annotation-) | Удаляет указанную аннотацию из коллекции. |
| [size()](#size--) | Получает количество аннотаций в коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnnotationCollection(Page page) {#AnnotationCollection-com.aspose.pdf.Page-}
```
public AnnotationCollection(Page page)
```


Конструктор AnnotationCollection. Создает коллекцию аннотаций для аннотаций на данной странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Родительская страница аннотаций. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Принимает посетителя для обработки аннотации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Объект выбора аннотаций. |

### add(Annotation annotation) {#add-com.aspose.pdf.Annotation-}
```
public void add(Annotation annotation)
```


Добавляет аннотацию к коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Аннотация, которая будет добавлена. |

### add(Annotation annotation, boolean considerRotation) {#add-com.aspose.pdf.Annotation-boolean-}
```
public void add(Annotation annotation, boolean considerRotation)
```


Добавляет аннотацию к коллекции. Если страница повернута, прямоугольник аннотации будет пересчитан соответствующим образом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Аннотация, которая будет добавлена. |
| considerRotation | boolean | Если true и страница повернута, то позиция аннотации будет пересчитываться в соответствии с поворотом страницы. |

### clear() {#clear--}
```
public void clear()
```


Удаляет все аннотации из коллекции.

### contains(Annotation annotation) {#contains-com.aspose.pdf.Annotation-}
```
public boolean contains(Annotation annotation)
```


Проверяет, принадлежит ли указанная аннотация коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Аннотация для поиска. |

**Возвращает:**
boolean - логическое значение True - если аннотация найдена; в противном случае ложно.
### copyTo(Annotation[] array, int index) {#copyTo-com.aspose.pdf.Annotation---int-}
```
public void copyTo(Annotation[] array, int index)
```


Копирует массив аннотаций в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [Annotation\[\]](../../com.aspose.pdf/annotation) | Массив для копирования в коллекцию. |
| index | int | Начальный индекс, куда будет скопирована коллекция. |

### delete() {#delete--}
```
public void delete()
```


Удаляет все аннотации из коллекции.

### delete(Annotation annotation) {#delete-com.aspose.pdf.Annotation-}
```
public void delete(Annotation annotation)
```


Удаляет указанную аннотацию из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Аннотация, которую следует удалить. |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Удаляет аннотацию из коллекции по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель аннотации, которую следует удалить. |

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
### findByName(String name) {#findByName-java.lang.String-}
```
public final Annotation findByName(String name)
```


Возвращает аннотацию по ее имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название аннотации |

**Возвращает:**
[Annotation](../../com.aspose.pdf/annotation) - Объект аннотации, если он найден; в противном случае ноль.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который можно использовать для синхронизации доступа к com.aspose.pdf.AnnotationCollection.

**Возвращает:**
java.lang.Object — Объект для синхронизации
### get_Item(int index) {#get-Item-int-}
```
public Annotation get_Item(int index)
```


Индекс элемента, который необходимо получить.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Значение индекса начиналось с единицы. |

**Возвращает:**
[Annotation](../../com.aspose.pdf/annotation) - Объект аннотации
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
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


Получает значение, указывающее, является ли доступ к com.aspose.pdf.AnnotationCollection синхронизированным (потокобезопасным).

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<Annotation> iterator()
```


Возвращает перечислитель коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.Annotation> — объект перечислителя
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(Annotation annotation) {#remove-com.aspose.pdf.Annotation-}
```
public boolean remove(Annotation annotation)
```


Удаляет указанную аннотацию из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | Аннотация, которую следует удалить. |

**Возвращает:**
boolean - логическое значение True - если аннотация найдена; в противном случае ложно.
### size() {#size--}
```
public int size()
```


Получает количество аннотаций в коллекции.

**Возвращает:**
интервал - целочисленное значение
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
