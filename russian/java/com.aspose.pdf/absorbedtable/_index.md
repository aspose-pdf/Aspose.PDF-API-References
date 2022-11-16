---
title: AbsorbedTable
second_title: Aspose.PDF для справки по Java API
description: Представляет таблицу, которая существует на странице
type: docs
weight: 13
url: /ru/java/com.aspose.pdf/absorbedtable/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.pdf.ITableElement](../../com.aspose.pdf/itableelement)
```
public class AbsorbedTable implements ITableElement
```

Представляет таблицу, которая существует на странице
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageNum()](#getPageNum--) | Получает номер страницы, содержащей эту таблицу |
| [getRectangle()](#getRectangle--) | Получает прямоугольник, описывающий положение таблицы на странице |
| [getRowList()](#getRowList--) | Получает IList только для чтения, содержащий строки таблицы |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getPageNum() {#getPageNum--}
```
public int getPageNum()
```


Получает номер страницы, содержащей эту таблицу

**Возвращает:**
интервал - целочисленное значение
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает прямоугольник, описывающий положение таблицы на странице

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getRowList() {#getRowList--}
```
public List<AbsorbedRow> getRowList()
```


Получает IList только для чтения, содержащий строки таблицы

**Возвращает:**
java.util.List<com.aspose.pdf.AbsorbedRow> — объект IGenericList
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
