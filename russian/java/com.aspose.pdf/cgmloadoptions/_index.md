---
title: CgmLoadOptions
second_title: Aspose.PDF для справки по Java API
description: Содержит опции для загрузки/импорта файла CGM в документ PDF.
type: docs
weight: 55
url: /ru/java/com.aspose.pdf/cgmloadoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class CgmLoadOptions extends LoadOptions
```

Содержит опции для загрузки/импорта файла CGM в документ PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CgmLoadOptions()](#CgmLoadOptions--) | Создает параметры загрузки по умолчанию для преобразования файла CGM в документ PDF. |
| [CgmLoadOptions(Dimension2D pageSize)](#CgmLoadOptions-java.awt.geom.Dimension2D-) | Создает параметры загрузки с определенным pageSize. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | Представляет формат файла, который описывает LoadOptions. |
| [getPageSize()](#getPageSize--) | Получает размер выходной страницы для импорта. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CgmLoadOptions() {#CgmLoadOptions--}
```
public CgmLoadOptions()
```


Создает параметры загрузки по умолчанию для преобразования файла CGM в документ PDF. Размер страницы PDF по умолчанию — A4 300 dpi 2480 X 3508.

### CgmLoadOptions(Dimension2D pageSize) {#CgmLoadOptions-java.awt.geom.Dimension2D-}
```
public CgmLoadOptions(Dimension2D pageSize)
```


Создает параметры загрузки с определенным pageSize.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | java.awt.geom.Dimension2D | Определяет ширину и высоту страницы PDF. |

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
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Представляет формат файла, который описывает LoadOptions.

**Возвращает:**
[LoadFormat](../../com.aspose.pdf/loadformat) - Элемент формата загрузки
### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


Получает размер выходной страницы для импорта.

**Возвращает:**
java.awt.geom.Dimension2D — объект Dimension2D
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть команду Abort, и в этом случае операция загрузки должна быть прекращена.

**Возвращает:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - Значение IWarningCallback
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




### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть команду Abort, и в этом случае операция загрузки должна быть прекращена.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | Значение IWarningCallback |

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
