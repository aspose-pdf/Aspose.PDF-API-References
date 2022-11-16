---
title: Group
second_title: Aspose.PDF для справки по Java API
description: Класс групповых атрибутов, определяющий атрибуты группы страниц pageu2019s для использования в модели прозрачного изображения.
type: docs
weight: 148
url: /ru/java/com.aspose.pdf/group/
---
**Наследование:**
java.lang.Object
```
public final class Group
```

Класс групповых атрибутов, определяющий атрибуты страницы\Группа страниц \u2019s для использования в модели прозрачного изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Group(Page page)](#Group-com.aspose.pdf.Page-) | Конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorSpace()](#getColorSpace--) | Получает ColorSpace |
| [hashCode()](#hashCode--) |  |
| [isKnockout()](#isKnockout--) | только для внутреннего использования |
| [isTransparency()](#isTransparency--) | только для внутреннего использования |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorSpace(int value)](#setColorSpace-int-) | Цветовое пространство группы. |
| [setKnockout(int value)](#setKnockout-int-) | Если этот флаг равен false, более поздние объекты в группе объединяются с более ранними объектами, с которыми они перекрываются; если правда, они составляются с группой\\u2019s исходный фон и перезаписать (\\u201отключить\=) любые ранее перекрывающиеся объекты. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Group(Page page) {#Group-com.aspose.pdf.Page-}
```
public Group(Page page)
```


Конструктор.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы PDF. |

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
### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Получает ColorSpace

**Возвращает:**
int - значение ColorSpace.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isKnockout() {#isKnockout--}
```
public int isKnockout()
```


только для внутреннего использования

Если этот флаг равен false, более поздние объекты в группе объединяются с более ранними объектами, с которыми они перекрываются; если правда, они составляются с группой\\u2019s исходный фон и перезаписать (\\u201отключить\=) любые ранее перекрывающиеся объекты.

**Возвращает:**
int — расширенный логический элемент
### isTransparency() {#isTransparency--}
```
public boolean isTransparency()
```


только для внутреннего использования

возвращает флаг прозрачности группы.

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




### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Цветовое пространство группы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение цветового пространства. |

### setKnockout(int value) {#setKnockout-int-}
```
public void setKnockout(int value)
```


Если этот флаг равен false, более поздние объекты в группе объединяются с более ранними объектами, с которыми они перекрываются; если правда, они составляются с группой\\u2019s исходный фон и перезаписать (\\u201отключить\=) любые ранее перекрывающиеся объекты.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ExtendedBoolean |

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
