---
title: Stamp
second_title: Aspose.PDF для справки по Java API
description: Абстрактный класс для различных видов штампов, являющихся потомками.
type: docs
weight: 335
url: /ru/java/com.aspose.pdf/stamp/
---
**Наследование:**
java.lang.Object
```
public abstract class Stamp
```

Абстрактный класс для различных видов штампов, являющихся потомками.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Stamp()](#Stamp--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | Получает нижнее поле штампа. |
| [getClass()](#getClass--) |  |
| [getHeight()](#getHeight--) | Получает желаемую высоту штампа на странице. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание штампа на странице. |
| [getLeftMargin()](#getLeftMargin--) | Получает левое поле штампа. |
| [getOpacity()](#getOpacity--) | Получает значение, указывающее непрозрачность штампа. |
| [getOutlineOpacity()](#getOutlineOpacity--) | Получает значение, указывающее непрозрачность контура штампа. |
| [getOutlineWidth()](#getOutlineWidth--) | Получает значение ширины контура штампа. |
| [getRightMargin()](#getRightMargin--) | Получает правое поле штампа. |
| [getRotate()](#getRotate--) | Получает поворот содержимого штампа в соответствии со значениями поворота. |
| [getRotateAngle()](#getRotateAngle--) | Получает угол поворота штампа в градусах. |
| [getStampId()](#getStampId--) | Получает идентификатор штампа. |
| [getTopMargin()](#getTopMargin--) | Получить верхнее поле штампа. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание штампа на странице. |
| [getWidth()](#getWidth--) | Получает желаемую ширину штампа на странице. |
| [getXIndent()](#getXIndent--) | Получить горизонтальную координату штампа, начиная слева. |
| [getYIndent()](#getYIndent--) | Получить вертикальную координату штампа, начиная снизу. |
| [getZoom()](#getZoom--) | Получает коэффициент масштабирования штампа. |
| [getZoomX()](#getZoomX--) | Получает горизонтальный коэффициент масштабирования штампа. |
| [getZoomY()](#getZoomY--) | Получает коэффициент масштабирования штампа по вертикали. |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | Получает логическое значение, указывающее, что содержимое помечается как фон. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Добавляет штамп на страницу. |
| [setBackground(boolean value)](#setBackground-boolean-) | Задает логическое значение, указывающее, что содержимое помечается как фон. |
| [setBottomMargin(double value)](#setBottomMargin-double-) | Устанавливает нижнее поле штампа. |
| [setHeight(double value)](#setHeight-double-) | Устанавливает желаемую высоту штампа на странице. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает Горизонтальное выравнивание штампа на странице. |
| [setLeftMargin(double value)](#setLeftMargin-double-) | Устанавливает левое поле штампа. |
| [setOpacity(double value)](#setOpacity-double-) | Задает значение, указывающее непрозрачность штампа. |
| [setOutlineOpacity(double value)](#setOutlineOpacity-double-) | Задает значение, указывающее непрозрачность контура штампа. |
| [setOutlineWidth(double value)](#setOutlineWidth-double-) | Устанавливает значение ширины контура штампа. |
| [setRightMargin(double value)](#setRightMargin-double-) | Устанавливает правое поле штампа. |
| [setRotate(int value)](#setRotate-int-) | Устанавливает поворот содержимого штампа в соответствии со значениями поворота. |
| [setRotateAngle(double value)](#setRotateAngle-double-) | Устанавливает угол поворота штампа в градусах. |
| [setStampId(int value)](#setStampId-int-) | Устанавливает идентификатор штампа. |
| [setTopMargin(double value)](#setTopMargin-double-) | Устанавливает верхнее поле штампа. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание штампа на странице. |
| [setWidth(double value)](#setWidth-double-) | Устанавливает желаемую ширину штампа на странице. |
| [setXIndent(double value)](#setXIndent-double-) | Установите горизонтальную координату штампа, начиная слева. |
| [setYIndent(double value)](#setYIndent-double-) | Установите вертикальную координату штампа, начиная снизу. |
| [setZoom(double value)](#setZoom-double-) | Получает коэффициент масштабирования штампа. |
| [setZoomX(double value)](#setZoomX-double-) | Устанавливает коэффициент масштабирования штампа по горизонтали. |
| [setZoomY(double value)](#setZoomY-double-) | Устанавливает коэффициент масштабирования штампа по вертикали. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Stamp() {#Stamp--}
```
public Stamp()
```


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
### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Получает нижнее поле штампа.

**Возвращает:**
двойное - двойное значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получает желаемую высоту штампа на странице.

**Возвращает:**
двойное - двойное значение
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает горизонтальное выравнивание штампа на странице.

**Возвращает:**
int - значение HorizontalAlignment
### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Получает левое поле штампа.

**Возвращает:**
двойное - двойное значение
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


Получает значение, указывающее непрозрачность штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0.

**Возвращает:**
двойное - двойное значение
### getOutlineOpacity() {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```


Получает значение, указывающее непрозрачность контура штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0.

**Возвращает:**
двойное - двойное значение
### getOutlineWidth() {#getOutlineWidth--}
```
public double getOutlineWidth()
```


Получает значение ширины контура штампа. По умолчанию значение равно 1,0.

**Возвращает:**
двойное - двойное значение
### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Получает правое поле штампа.

**Возвращает:**
двойное - двойное значение
### getRotate() {#getRotate--}
```
public int getRotate()
```


Получает поворот содержимого штампа в соответствии со значениями поворота. Примечание. Это свойство предназначено для заданных углов, кратных 90 градусам (0, 90, 180, 270 градусов). Для установки произвольного угла используйте свойство RotateAngle. Если угол, заданный ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None.

**Возвращает:**
int - Значение поворота
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Получает угол поворота штампа в градусах. Это свойство позволяет задать произвольный угол поворота.

**Возвращает:**
двойное - двойное значение
### getStampId() {#getStampId--}
```
public int getStampId()
```


Получает идентификатор штампа.

**Возвращает:**
int - Идентификатор штампа.
### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Получить верхнее поле штампа.

**Возвращает:**
двойное - двойное значение
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает вертикальное выравнивание штампа на странице.

**Возвращает:**
int — значение вертикального выравнивания
### getWidth() {#getWidth--}
```
public double getWidth()
```


Получает желаемую ширину штампа на странице.

**Возвращает:**
двойное - двойное значение
### getXIndent() {#getXIndent--}
```
public double getXIndent()
```


Получить горизонтальную координату штампа, начиная слева.

**Возвращает:**
двойное - двойное значение
### getYIndent() {#getYIndent--}
```
public double getYIndent()
```


Получить вертикальную координату штампа, начиная снизу.

**Возвращает:**
двойное - двойное значение
### getZoom() {#getZoom--}
```
public double getZoom()
```


Получает коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет свойства ZoomX и ZoomY. Если ZoomX и ZoomY разные, то свойство Zoom возвращает значение ZoomX.

**Возвращает:**
двойное - двойное значение
### getZoomX() {#getZoomX--}
```
public double getZoomX()
```


Получает горизонтальный коэффициент масштабирования штампа. Позволяет масштабировать штамп по горизонтали.

**Возвращает:**
двойное - двойное значение
### getZoomY() {#getZoomY--}
```
public double getZoomY()
```


Получает коэффициент масштабирования штампа по вертикали. Позволяет масштабировать штамп по вертикали.

**Возвращает:**
двойное - двойное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isBackground() {#isBackground--}
```
public boolean isBackground()
```


Получает логическое значение, указывающее, что содержимое помечается как фон. Если значение равно true, содержимое штампа размещается внизу. По умолчанию значение равно false, содержимое штампа откладывается вверху.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### put(Page page) {#put-com.aspose.pdf.Page-}
```
public abstract void put(Page page)
```


Добавляет штамп на страницу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Страница для добавления штампа. |

### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


Задает логическое значение, указывающее, что содержимое помечается как фон. Если значение равно true, содержимое штампа размещается внизу. По умолчанию значение равно false, содержимое штампа располагается вверху.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


Устанавливает нижнее поле штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Устанавливает желаемую высоту штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Устанавливает Горизонтальное выравнивание штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


Устанавливает левое поле штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


Задает значение, указывающее непрозрачность штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setOutlineOpacity(double value) {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```


Задает значение, указывающее непрозрачность контура штампа. Значение от 0,0 до 1,0. По умолчанию значение равно 1,0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setOutlineWidth(double value) {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```


Устанавливает значение ширины контура штампа. По умолчанию значение равно 1,0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


Устанавливает правое поле штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


Устанавливает поворот содержимого штампа в соответствии со значениями поворота. Примечание. Это свойство предназначено для заданных углов, кратных 90 градусам (0, 90, 180, 270 градусов). Для установки произвольного угла используйте свойство RotateAngle. Если угол, заданный ArbitraryAngle, не кратен 90, то свойство Rotate возвращает Rotation.None.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```


Устанавливает угол поворота штампа в градусах. Это свойство позволяет задать произвольный угол поворота.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | угол поворота |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```


Устанавливает идентификатор штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Новое значение идентификатора штампа. |

### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


Устанавливает верхнее поле штампа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение вертикального выравнивания |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Устанавливает желаемую ширину штампа на странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setXIndent(double value) {#setXIndent-double-}
```
public void setXIndent(double value)
```


Установите горизонтальную координату штампа, начиная слева.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setYIndent(double value) {#setYIndent-double-}
```
public void setYIndent(double value)
```


Установите вертикальную координату штампа, начиная снизу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setZoom(double value) {#setZoom-double-}
```
public void setZoom(double value)
```


Получает коэффициент масштабирования штампа. Позволяет масштабировать штамп. Обратите внимание, что пара свойств ZoomX и ZoomY позволяет установить коэффициент масштабирования для каждой оси отдельно. Установка этого свойства изменяет свойства ZoomX и ZoomY. Если ZoomX и ZoomY разные, то свойство Zoom возвращает значение ZoomX.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setZoomX(double value) {#setZoomX-double-}
```
public void setZoomX(double value)
```


Устанавливает коэффициент масштабирования штампа по горизонтали. Позволяет масштабировать штамп по горизонтали.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setZoomY(double value) {#setZoomY-double-}
```
public void setZoomY(double value)
```


Устанавливает коэффициент масштабирования штампа по вертикали. Позволяет масштабировать штамп по вертикали.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

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
