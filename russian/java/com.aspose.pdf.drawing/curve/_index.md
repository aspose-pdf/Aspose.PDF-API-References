---
title: Curve
second_title: Aspose.PDF для справки по Java API
description: Представляет кривую Безье.
type: docs
weight: 12
url: /ru/java/com.aspose.pdf.drawing/curve/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.drawing.Shape](../../com.aspose.pdf.drawing/shape)
```
public final class Curve extends Shape
```

Представляет кривую Безье.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Curve()](#Curve--) | Только для внутреннего использования |
| [Curve(float[] positionArray)](#Curve-float---) | Инициализирует новый экземпляр класса Curve. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getGraphInfo()](#getGraphInfo--) | Получает объект, который указывает информацию о графике, такую как цвет, ширина линии и т. д. |
| [getPositionArray()](#getPositionArray--) | Получает массив позиций с плавающей запятой. |
| [getText()](#getText--) | Получает или задает текст для формы |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGraphInfo(GraphInfo value)](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Устанавливает объект, который указывает информацию о графике, такую как цвет, ширина линии и т. д. |
| [setPositionArray(float[] value)](#setPositionArray-float---) | Устанавливает массив позиций с плавающей запятой. |
| [setText(TextFragment value)](#setText-com.aspose.pdf.TextFragment-) | Получает или задает текст для формы |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Curve() {#Curve--}
```
public Curve()
```


Только для внутреннего использования

### Curve(float[] positionArray) {#Curve-float---}
```
public Curve(float[] positionArray)
```


Инициализирует новый экземпляр класса Curve.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| positionArray | float[] | Массив положений контрольных точек кривой. Контрольных точек должно быть четыре, поэтому длина массива должна быть восемь. |

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
### getGraphInfo() {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```


Получает объект, который указывает информацию о графике, такую как цвет, ширина линии и т. д.

**Возвращает:**
[GraphInfo](../../com.aspose.pdf/graphinfo) - объект, указывающий информацию о графике.
### getPositionArray() {#getPositionArray--}
```
public float[] getPositionArray()
```


Получает массив позиций с плавающей запятой.

**Возвращает:**
плавать[] - плавать[] множество
### getText() {#getText--}
```
public TextFragment getText()
```


Получает или задает текст для формы

**Возвращает:**
[TextFragment](../../com.aspose.pdf/textfragment) Объект TextFragment
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




### setGraphInfo(GraphInfo value) {#setGraphInfo-com.aspose.pdf.GraphInfo-}
```
public void setGraphInfo(GraphInfo value)
```


Устанавливает объект, который указывает информацию о графике, такую как цвет, ширина линии и т. д.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GraphInfo](../../com.aspose.pdf/graphinfo) | что указывает информацию о графике. |

### setPositionArray(float[] value) {#setPositionArray-float---}
```
public void setPositionArray(float[] value)
```


Устанавливает массив позиций с плавающей запятой.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | плавать[] | float[] множество |

### setText(TextFragment value) {#setText-com.aspose.pdf.TextFragment-}
```
public void setText(TextFragment value)
```


Получает или задает текст для формы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | Объект TextFragment |

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
