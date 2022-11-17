---
title: Position
second_title: Aspose.PDF для справки по Java API
description: Представляет объект положения
type: docs
weight: 291
url: /ru/java/com.aspose.pdf/position/
---
**Наследование:**
java.lang.Object
```
public final class Position
```

Представляет объект положения
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Position(double xIndent, double yIndent)](#Position-double-double-) | Инициализирует новый экземпляр класса Position |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект текущему объекту Position. |
| [getClass()](#getClass--) |  |
| [getXIndent()](#getXIndent--) | Получает координату X объекта |
| [getYIndent()](#getYIndent--) | Получает координату Y объекта |
| [hashCode()](#hashCode--) | Возвращает значение хэш-кода для объекта. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setXIndent(double value)](#setXIndent-double-) | Устанавливает координату X объекта |
| [setYIndent(double value)](#setYIndent-double-) | Устанавливает координату Y объекта |
| [toString()](#toString--) | Получает строковое представление для текущего объекта Position. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Position(double xIndent, double yIndent) {#Position-double-double-}
```
public Position(double xIndent, double yIndent)
```


Инициализирует новый экземпляр класса Position

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xIndent | double | Значение координаты X. |
| yIndent | double | Значение координаты Y. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект текущему объекту Position.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект, который проверяется на равенство. |

**Возвращает:**
boolean — Истинно, если объекты равны.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getXIndent() {#getXIndent--}
```
public double getXIndent()
```


Получает координату X объекта

**Возвращает:**
двойное - двойное значение
### getYIndent() {#getYIndent--}
```
public double getYIndent()
```


Получает координату Y объекта

**Возвращает:**
двойное - двойное значение
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает значение хэш-кода для объекта. Этот метод поддерживается для хеш-таблиц, таких как предоставляемые java.util.HashMap.

Общий контракт hashCode:

 *  Всякий раз, когда он вызывается для одного и того же объекта более одного раза во время выполнения приложения Java, метод hashCode должен постоянно возвращать одно и то же целое число, при условии, что никакая информация, используемая в сравнениях на равенство для объекта, не изменяется. Это целое число не обязательно должно оставаться постоянным от одного выполнения приложения к другому выполнению того же приложения.
 *  Если два объекта равны в соответствии с методом equals(Object), то вызов метода hashCode для каждого из двух объектов должен давать одинаковый целочисленный результат.
 *   это*not*требуется, чтобы, если два объекта не равны в соответствии с java.lang.Object\#equals(java.lang.Object).equals(java.lang.Object), то вызов метода hashCode для каждого из двух объектов должен давать различные целочисленные результаты. Однако программист должен знать, что создание различных целочисленных результатов для неравных объектов может повысить производительность хеш-таблиц.

Насколько это целесообразно, метод hashCode, определенный классом Object, действительно возвращает разные целые числа для разных объектов. (Обычно это реализуется путем преобразования внутреннего адреса объекта в целое число, но этот метод реализации не требуется для языка программирования JavaTM.)

**Возвращает:**
int - значение хеш-кода для этого объекта.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setXIndent(double value) {#setXIndent-double-}
```
public void setXIndent(double value)
```


Устанавливает координату X объекта

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setYIndent(double value) {#setYIndent-double-}
```
public void setYIndent(double value)
```


Устанавливает координату Y объекта

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### toString() {#toString--}
```
public String toString()
```


Получает строковое представление для текущего объекта Position.

**Возвращает:**
java.lang.String — строковое представление объекта Position.
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
