---
title: IPdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF для справки по Java API
description: Класс для указания параметров изменения размера страницы.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Наследование:**
java.lang.Object
```
public static class IPdfFileEditor.ContentsResizeParameters
```

Класс для указания параметров изменения размера страницы. Позволяет задать следующие параметры: Размер страницы результатов (ширина, высота) в единицах измерения по умолчанию или в процентах от размера исходных страниц; Левое, верхнее, нижнее и правое поля в пространственных единицах по умолчанию или в процентах от исходного размера страницы; Некоторые значения могут быть оставлены нулевыми для автоматического расчета. Эти значения будут рассчитаны из остального размера страницы после вычисления явно указанных значений. Например: если ширина страницы = 100, а новая ширина страницы указана в 60 единиц, то левое и правое поля вычисляются автоматически: (100 - 60) / 2 = 15. Этот класс используется в методе ResizeContents.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ContentsResizeParameters()](#ContentsResizeParameters--) | Создает параметры изменения размера, где для всех значений установлено значение «авто». |
| [ContentsResizeParameters(IPdfFileEditor.ContentsResizeValue leftMargin, IPdfFileEditor.ContentsResizeValue contentsWidth, IPdfFileEditor.ContentsResizeValue rightMargin, IPdfFileEditor.ContentsResizeValue topMargin, IPdfFileEditor.ContentsResizeValue contentsHeight, IPdfFileEditor.ContentsResizeValue bottomMargin)](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Создает параметры изменения размера с указанными значениями полей и размером содержимого. |
## Методы

| Метод | Описание |
| --- | --- |
| [contentSize(double width, double height)](#contentSize-double-double-) | Создает параметры изменения размера с указанным размером содержимого. |
| [contentSizePercent(double width, double height)](#contentSizePercent-double-double-) | Создает параметры изменения размера с указанным размером конусов в процентах от исходного размера страницы. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | Получает или задает нижнее поле результирующей страницы. |
| [getClass()](#getClass--) |  |
| [getContentsHeight()](#getContentsHeight--) | Получает или задает высоту содержимого исходной страницы на результирующей странице. |
| [getContentsWidth()](#getContentsWidth--) | Получает или задает ширину содержимого исходной страницы на результирующей странице. |
| [getLeftMargin()](#getLeftMargin--) | Получает или задает левое поле результирующей страницы. |
| [getRightMargin()](#getRightMargin--) | Получает или задает правое поле результирующей страницы. |
| [getTopMargin()](#getTopMargin--) | Получает или задает верхнее поле результирующей страницы. |
| [hashCode()](#hashCode--) |  |
| [margins(double left, double right, double top, double bottom)](#margins-double-double-double-double-) | Создает параметры изменения размера с указанным значением полей. |
| [marginsPercent(double left, double right, double top, double bottom)](#marginsPercent-double-double-double-double-) | Создает параметры изменения размера. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pageResize(double width, double height)](#pageResize-double-double-) | Создает параметры изменения размера страницы. |
| [pageResizePct(double widthPct, double heightPct)](#pageResizePct-double-double-) | Создает параметры изменения размера страницы. |
| [setBottomMargin(IPdfFileEditor.ContentsResizeValue value)](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задает нижнее поле результирующей страницы. |
| [setContentsHeight(IPdfFileEditor.ContentsResizeValue value)](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задает высоту содержимого исходной страницы на результирующей странице. |
| [setContentsWidth(IPdfFileEditor.ContentsResizeValue value)](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задает ширину содержимого исходной страницы на результирующей странице. |
| [setLeftMargin(IPdfFileEditor.ContentsResizeValue value)](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задает левое поле результирующей страницы. |
| [setRightMargin(IPdfFileEditor.ContentsResizeValue value)](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задает правое поле результирующей страницы. |
| [setTopMargin(IPdfFileEditor.ContentsResizeValue value)](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задает верхнее поле результирующей страницы. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentsResizeParameters() {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```


Создает параметры изменения размера, где для всех значений установлено значение «авто». При необходимости можно указать поля и размер содержимого позже.

### ContentsResizeParameters(IPdfFileEditor.ContentsResizeValue leftMargin, IPdfFileEditor.ContentsResizeValue contentsWidth, IPdfFileEditor.ContentsResizeValue rightMargin, IPdfFileEditor.ContentsResizeValue topMargin, IPdfFileEditor.ContentsResizeValue contentsHeight, IPdfFileEditor.ContentsResizeValue bottomMargin) {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public ContentsResizeParameters(IPdfFileEditor.ContentsResizeValue leftMargin, IPdfFileEditor.ContentsResizeValue contentsWidth, IPdfFileEditor.ContentsResizeValue rightMargin, IPdfFileEditor.ContentsResizeValue topMargin, IPdfFileEditor.ContentsResizeValue contentsHeight, IPdfFileEditor.ContentsResizeValue bottomMargin)
```


Создает параметры изменения размера с указанными значениями полей и размером содержимого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| leftMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Значение левого поля. |
| contentsWidth | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Ширина содержимого. |
| rightMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Правая маржа. |
| topMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Верхнее поле. |
| contentsHeight | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Высота содержимого. |
| bottomMargin | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Нижний край. |

### contentSize(double width, double height) {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```


Создает параметры изменения размера с указанным размером содержимого.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | double | Новая ширина содержимого. |
| height | double | Новая высота содержания. |

**Возвращает:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - Возвращает новые параметры изменения размера.
### contentSizePercent(double width, double height) {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```


Создает параметры изменения размера с указанным размером конусов в процентах от исходного размера страницы. Маржа рассчитывается автоматически.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | double | Ширина нового контента в процентах. |
| height | double | Высота нового содержимого в процентах. |

**Возвращает:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - Новые параметры изменения размера.
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
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```


Получает или задает нижнее поле результирующей страницы.

**Возвращает:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - Объект ContentsResizeValue
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getContentsHeight() {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```


Получает или задает высоту содержимого исходной страницы на результирующей странице.

**Возвращает:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - Объект ContentsResizeValue
### getContentsWidth() {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```


Получает или задает ширину содержимого исходной страницы на результирующей странице.

**Возвращает:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - Объект ContentsResizeValue
### getLeftMargin() {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```


Получает или задает левое поле результирующей страницы.

**Возвращает:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - Объект ContentsResizeValue
### getRightMargin() {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```


Получает или задает правое поле результирующей страницы.

**Возвращает:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - Объект ContentsResizeValue
### getTopMargin() {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```


Получает или задает верхнее поле результирующей страницы.

**Возвращает:**
[ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) - Объект ContentsResizeValue
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### margins(double left, double right, double top, double bottom) {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```


Создает параметры изменения размера с указанным значением полей. Размер содержимого рассчитывается автоматически.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | double | Левое поле. |
| right | double | Правая маржа. |
| top | double | Верхнее поле. |
| bottom | double | Нижний край. |

**Возвращает:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - Созданы параметры изменения размера.
### marginsPercent(double left, double right, double top, double bottom) {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```


Создает параметры изменения размера. Поля указываются в процентах от исходного размера страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| left | double | Левое поле (в процентах от ширины страницы). |
| right | double | Правое поле (в процентах от высоты страницы). |
| top | double | Верхнее поле (в процентах от высоты страницы). |
| bottom | double | Нижнее поле (в процентах от высоты страницы). |

**Возвращает:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - Возвращает новые параметры изменения размера.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### pageResize(double width, double height) {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```


Создает параметры изменения размера страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| width | double | Новая ширина страницы в единицах. |
| height | double | Новая высота страницы в единицах. |

**Возвращает:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - Новые параметры изменения размера.
### pageResizePct(double widthPct, double heightPct) {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```


Создает параметры изменения размера страницы. Новые размеры указаны в процентах.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| widthPct | double | Новая ширина страницы в процентах. |
| heightPct | double | Новая высота страницы в процентах. |

**Возвращает:**
[ContentsResizeParameters](../../com.aspose.pdf.facades/contentsresizeparameters) - Новые параметры изменения размера.
### setBottomMargin(IPdfFileEditor.ContentsResizeValue value) {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setBottomMargin(IPdfFileEditor.ContentsResizeValue value)
```


Получает или задает нижнее поле результирующей страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Объект ContentsResizeValue |

### setContentsHeight(IPdfFileEditor.ContentsResizeValue value) {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setContentsHeight(IPdfFileEditor.ContentsResizeValue value)
```


Получает или задает высоту содержимого исходной страницы на результирующей странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Объект ContentsResizeValue |

### setContentsWidth(IPdfFileEditor.ContentsResizeValue value) {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setContentsWidth(IPdfFileEditor.ContentsResizeValue value)
```


Получает или задает ширину содержимого исходной страницы на результирующей странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Объект ContentsResizeValue |

### setLeftMargin(IPdfFileEditor.ContentsResizeValue value) {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setLeftMargin(IPdfFileEditor.ContentsResizeValue value)
```


Получает или задает левое поле результирующей страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Объект ContentsResizeValue |

### setRightMargin(IPdfFileEditor.ContentsResizeValue value) {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setRightMargin(IPdfFileEditor.ContentsResizeValue value)
```


Получает или задает правое поле результирующей страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Объект ContentsResizeValue |

### setTopMargin(IPdfFileEditor.ContentsResizeValue value) {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
```
public void setTopMargin(IPdfFileEditor.ContentsResizeValue value)
```


Получает или задает верхнее поле результирующей страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ContentsResizeValue](../../com.aspose.pdf.facades/contentsresizevalue) | Объект ContentsResizeValue |

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
