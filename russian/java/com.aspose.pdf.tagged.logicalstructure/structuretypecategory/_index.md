---
title: StructureTypeCategory
second_title: Aspose.PDF для справки по Java API
description: Представляет категории стандартных типов структур.
type: docs
weight: 17
url: /ru/java/com.aspose.pdf.tagged.logicalstructure/structuretypecategory/
---
**Наследование:**
java.lang.Object
```
public final class StructureTypeCategory
```

Представляет категории стандартных типов структур.
## Поля

| Поле | Описание |
| --- | --- |
| [BLSEs](#BLSEs) | Структурные элементы блочного уровня (BLSE) описывают общий макет контента на странице в направлении последовательности блоков. |
| [GroupingElements](#GroupingElements) | Группирующие элементы группируют другие элементы в последовательности или иерархии, но не содержат напрямую содержимого и не оказывают прямого влияния на макет. |
| [ILSEs](#ILSEs) | Структурные элементы встроенного уровня (ILSE) описывают расположение содержимого внутри BLSE в направлении встроенной последовательности. |
| [IllustrationElements](#IllustrationElements) | Элементы иллюстрации представляют собой компактные последовательности содержимого в порядке содержимого страницы, которые считаются едиными объектами по отношению к макету страницы. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает строку, которая представляет текущий объект. |
| [to_StructureTypeCategory(String name)](#to-StructureTypeCategory-java.lang.String-) |  Выполняет явное преобразование из строки в[StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BLSEs {#BLSEs}
```
public static final StructureTypeCategory BLSEs
```


Структурные элементы блочного уровня (BLSE) описывают общий макет контента на странице в направлении последовательности блоков.

### GroupingElements {#GroupingElements}
```
public static final StructureTypeCategory GroupingElements
```


Группирующие элементы группируют другие элементы в последовательности или иерархии, но не содержат напрямую содержимого и не оказывают прямого влияния на макет.

### ILSEs {#ILSEs}
```
public static final StructureTypeCategory ILSEs
```


Структурные элементы встроенного уровня (ILSE) описывают расположение содержимого внутри BLSE в направлении встроенной последовательности.

### IllustrationElements {#IllustrationElements}
```
public static final StructureTypeCategory IllustrationElements
```


Элементы иллюстрации представляют собой компактные последовательности содержимого в порядке содержимого страницы, которые считаются едиными объектами по отношению к макету страницы. Иллюстрацию можно рассматривать как BLSE или ILSE.

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




### toString() {#toString--}
```
public String toString()
```


Возвращает строку, которая представляет текущий объект.

**Возвращает:**
java.lang.String — строка, представляющая текущий объект.
### to_StructureTypeCategory(String name) {#to-StructureTypeCategory-java.lang.String-}
```
public static StructureTypeCategory to_StructureTypeCategory(String name)
```


 Выполняет явное преобразование из строки в[StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название. |

**Возвращает:**
[StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory) - Результат преобразования.
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
