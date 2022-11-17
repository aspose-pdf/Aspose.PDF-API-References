---
title: PsLoadOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет варианты загрузки/импорта .mht-файла в pdf-документ.
type: docs
weight: 297
url: /ru/java/com.aspose.pdf/psloadoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class PsLoadOptions extends LoadOptions
```

Представляет варианты загрузки/импорта .mht-файла в pdf-документ.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PsLoadOptions()](#PsLoadOptions--) | Создает параметры загрузки для преобразования PostScript в документ PDF с пустым базовым путем. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFontsFolders()](#getFontsFolders--) | Получает пути к папкам со шрифтами. |
| [getLoadFormat()](#getLoadFormat--) | Представляет формат файла, который описывает LoadOptions. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFontsFolders(String[] value)](#setFontsFolders-java.lang.String---) | Устанавливает пути к папкам со шрифтами. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsLoadOptions() {#PsLoadOptions--}
```
public PsLoadOptions()
```


Создает параметры загрузки для преобразования PostScript в документ PDF с пустым базовым путем.

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
### getFontsFolders() {#getFontsFolders--}
```
public String[] getFontsFolders()
```


Получает пути к папкам со шрифтами. Папки с дополнительными шрифтами для конвертации.

**Возвращает:**
java.lang.String[] - массив строковых значений
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Представляет формат файла, который описывает LoadOptions.

**Возвращает:**
[LoadFormat](../../com.aspose.pdf/loadformat) - Элемент формата загрузки
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




### setFontsFolders(String[] value) {#setFontsFolders-java.lang.String---}
```
public void setFontsFolders(String[] value)
```


Устанавливает пути к папкам со шрифтами. Папки с дополнительными шрифтами для конвертации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] | массив строковых значений |

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
