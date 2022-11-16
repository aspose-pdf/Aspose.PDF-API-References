---
title: Border
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий характеристики границы аннотации.
type: docs
weight: 36
url: /ru/java/com.aspose.pdf/border/
---
**Наследование:**
java.lang.Object
```
public final class Border
```

Класс, представляющий характеристики границы аннотации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Border(Annotation parent)](#Border-com.aspose.pdf.Annotation-) | Конструктор граничного объекта. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDash()](#getDash--) | Получает штриховой узор. |
| [getEffect()](#getEffect--) | Получает эффект границы. |
| [getEffectIntensity()](#getEffectIntensity--) | Получает интенсивность эффекта. |
| [getHCornerRadius()](#getHCornerRadius--) | Пока не поддерживается. |
| [getStyle()](#getStyle--) | Получает стиль границы. |
| [getVCornerRadius()](#getVCornerRadius--) | Получает вертикальный угловой радиус. |
| [getWidth()](#getWidth--) | Получает ширину границы. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDash(Dash value)](#setDash-com.aspose.pdf.Dash-) | Устанавливает шаблон штриховки. |
| [setEffect(int value)](#setEffect-int-) | Устанавливает эффект границы. |
| [setEffectIntensity(int value)](#setEffectIntensity-int-) | Устанавливает интенсивность эффекта. |
| [setHCornerRadius(double value)](#setHCornerRadius-double-) | Устанавливает горизонтальный угловой радиус. |
| [setStyle(int value)](#setStyle-int-) | Устанавливает стиль границы. |
| [setWidth(int value)](#setWidth-int-) | Устанавливает ширину границы. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Border(Annotation parent) {#Border-com.aspose.pdf.Annotation-}
```
public Border(Annotation parent)
```


Конструктор граничного объекта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| parent | [Annotation](../../com.aspose.pdf/annotation) | Родительская аннотация. |

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
### getDash() {#getDash--}
```
public Dash getDash()
```


Получает штриховой узор.

**Возвращает:**
[Dash](../../com.aspose.pdf/dash) - тире объект
### getEffect() {#getEffect--}
```
public int getEffect()
```


Получает эффект границы.

 Пограничный эффект 

**Возвращает:**
int - элемент BorderEffect
### getEffectIntensity() {#getEffectIntensity--}
```
public int getEffectIntensity()
```


 Получает интенсивность эффекта. Допустимый диапазон значений[0..2].

**Возвращает:**
интервал - целочисленное значение
### getHCornerRadius() {#getHCornerRadius--}
```
public final double getHCornerRadius()
```


Пока не поддерживается.

Получает горизонтальный угловой радиус.

**Возвращает:**
двойное - двойное значение
### getStyle() {#getStyle--}
```
public int getStyle()
```


Получает стиль границы.

 ГраницаСтиль 

**Возвращает:**
int - элемент BorderStyle
### getVCornerRadius() {#getVCornerRadius--}
```
public final double getVCornerRadius()
```


Получает вертикальный угловой радиус.

**Возвращает:**
двойной - вертикальный угловой радиус.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину границы.

**Возвращает:**
интервал - целочисленное значение
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




### setDash(Dash value) {#setDash-com.aspose.pdf.Dash-}
```
public void setDash(Dash value)
```


Устанавливает шаблон штриховки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Dash](../../com.aspose.pdf/dash) | Тире объект |

### setEffect(int value) {#setEffect-int-}
```
public void setEffect(int value)
```


Устанавливает эффект границы.

 Пограничный эффект 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент BorderEffect |

### setEffectIntensity(int value) {#setEffectIntensity-int-}
```
public void setEffectIntensity(int value)
```


 Устанавливает интенсивность эффекта. Допустимый диапазон значений[0..2].

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setHCornerRadius(double value) {#setHCornerRadius-double-}
```
public final void setHCornerRadius(double value)
```


Устанавливает горизонтальный угловой радиус.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


Устанавливает стиль границы.

 ГраницаСтиль 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент BorderStyle |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Устанавливает ширину границы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

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
