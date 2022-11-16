---
title: IconFit
second_title: Aspose.PDF для справки по Java API
description: Описывает, как значок аннотаций виджета должен отображаться в прямоугольнике аннотаций.
type: docs
weight: 164
url: /ru/java/com.aspose.pdf/iconfit/
---
**Наследование:**
java.lang.Object
```
public final class IconFit
```

Описывает, как значок аннотации виджета должен отображаться внутри прямоугольника аннотации.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLeftoverBottom()](#getLeftoverBottom--) | Получает место для выделения в нижней части значка. |
| [getLeftoverLeft()](#getLeftoverLeft--) | Получает место для выделения слева от значка. |
| [getScalingMode()](#getScalingMode--) | Используемый тип масштабирования. |
| [getScalingReason()](#getScalingReason--) | Получает причину масштабирования. |
| [hashCode()](#hashCode--) |  |
| [isSpreadOnBorder()](#isSpreadOnBorder--) | Если значение равно true, указывает, что внешний вид кнопки должен быть масштабирован, чтобы полностью соответствовать границам аннотации без учета ширины линии границы. |
| [nameToScalingMode(String mode)](#nameToScalingMode-java.lang.String-) | Преобразует имя режима масштабирования в объект ScalingMode. |
| [nameToScalingReason(String reason)](#nameToScalingReason-java.lang.String-) | Преобразует имя причины масштабирования в объект ScalingReason. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scalingModeToName(int mode)](#scalingModeToName-int-) | Преобразует объект режима масштабирования в имя. |
| [scalingReasonToName(int reason)](#scalingReasonToName-int-) | Преобразует объект масштабирования в имя. |
| [setLeftoverBottom(double value)](#setLeftoverBottom-double-) | Устанавливает пространство для выделения в нижней части значка. |
| [setLeftoverLeft(double value)](#setLeftoverLeft-double-) | Устанавливает пространство для выделения слева от значка. |
| [setScalingMode(int value)](#setScalingMode-int-) | Используемый тип масштабирования. |
| [setScalingReason(int value)](#setScalingReason-int-) | Устанавливает причину масштабирования. |
| [setSpreadOnBorder(boolean value)](#setSpreadOnBorder-boolean-) | Если значение равно true, указывает, что внешний вид кнопки должен быть масштабирован, чтобы полностью соответствовать границам аннотации без учета ширины линии границы. |
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
### getLeftoverBottom() {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```


Получает место для выделения в нижней части значка.

**Возвращает:**
double - место для выделения внизу
### getLeftoverLeft() {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```


Получает место для выделения слева от значка.

**Возвращает:**
double - место для выделения слева от иконки.
### getScalingMode() {#getScalingMode--}
```
public int getScalingMode()
```


Используемый тип масштабирования.

**Возвращает:**
int - значение режима масштабирования
### getScalingReason() {#getScalingReason--}
```
public int getScalingReason()
```


Получает причину масштабирования.

**Возвращает:**
int — значение масштабируемой причины
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isSpreadOnBorder() {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```


Если значение равно true, указывает, что внешний вид кнопки должен быть масштабирован, чтобы полностью соответствовать границам аннотации без учета ширины линии границы.

**Возвращает:**
boolean - логическое значение
### nameToScalingMode(String mode) {#nameToScalingMode-java.lang.String-}
```
public static int nameToScalingMode(String mode)
```


Преобразует имя режима масштабирования в объект ScalingMode.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | java.lang.String | Название режима масштабирования. |

**Возвращает:**
int - объект режима масштабирования.
### nameToScalingReason(String reason) {#nameToScalingReason-java.lang.String-}
```
public static int nameToScalingReason(String reason)
```


Преобразует имя причины масштабирования в объект ScalingReason.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| reason | java.lang.String | Название причины масштабирования. |

**Возвращает:**
int - Масштабирование объекта причины.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### scalingModeToName(int mode) {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```


Преобразует объект режима масштабирования в имя.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | int | Объект режима масштабирования. |

**Возвращает:**
java.lang.String — имя режима масштабирования.
### scalingReasonToName(int reason) {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```


Преобразует объект масштабирования в имя.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| reason | int | Объект причины масштабирования, который необходимо преобразовать. |

**Возвращает:**
java.lang.String - Имя причины масштабирования.
### setLeftoverBottom(double value) {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```


Устанавливает пространство для выделения в нижней части значка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | место для выделения внизу |

### setLeftoverLeft(double value) {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```


Устанавливает пространство для выделения слева от значка.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | место, чтобы выделить слева от значка. |

### setScalingMode(int value) {#setScalingMode-int-}
```
public void setScalingMode(int value)
```


Используемый тип масштабирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение режима масштабирования |

### setScalingReason(int value) {#setScalingReason-int-}
```
public void setScalingReason(int value)
```


Устанавливает причину масштабирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение ScalingReason |

### setSpreadOnBorder(boolean value) {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```


Если значение равно true, указывает, что внешний вид кнопки должен быть масштабирован, чтобы полностью соответствовать границам аннотации без учета ширины линии границы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
