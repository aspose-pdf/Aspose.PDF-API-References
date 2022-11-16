---
title: XmlLoadOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры для загрузки/импорта файла XML в документ PDF.
type: docs
weight: 415
url: /ru/java/com.aspose.pdf/xmlloadoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public class XmlLoadOptions extends LoadOptions
```

Представляет параметры для загрузки/импорта файла XML в документ PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmlLoadOptions()](#XmlLoadOptions--) | Создает объект XmlLoadOptions без данных xsl. |
| [XmlLoadOptions(String xslFile)](#XmlLoadOptions-java.lang.String-) | Создает объект XmlLoadOptions с данными xsl. |
| [XmlLoadOptions(InputStream xslStream)](#XmlLoadOptions-java.io.InputStream-) | Создает объект XmlLoadOptions с данными xsl. |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Закрыть экземпляр |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | Представляет формат файла, который описывает LoadOptions. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [getXslStream()](#getXslStream--) | Получает данные xsl для преобразования xml в документ pdf. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmlLoadOptions() {#XmlLoadOptions--}
```
public XmlLoadOptions()
```


Создает объект XmlLoadOptions без данных xsl.

### XmlLoadOptions(String xslFile) {#XmlLoadOptions-java.lang.String-}
```
public XmlLoadOptions(String xslFile)
```


Создает объект XmlLoadOptions с данными xsl.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xslFile | java.lang.String | Строковый файл Xsl для преобразования XML-документа в PDF-документ. |

### XmlLoadOptions(InputStream xslStream) {#XmlLoadOptions-java.io.InputStream-}
```
public XmlLoadOptions(InputStream xslStream)
```


Создает объект XmlLoadOptions с данными xsl.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xslStream | java.io.InputStream | Поток InputStream Xsl для преобразования XML-документа в PDF-документ. |

### close() {#close--}
```
public void close()
```


Закрыть экземпляр

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
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Обратный вызов для обработки любых сгенерированных предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Продолжить, либо Прервать. Продолжить — это действие по умолчанию, и операция загрузки продолжается, однако пользователь может также вернуть команду Abort, и в этом случае операция загрузки должна быть прекращена.

**Возвращает:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - Значение IWarningCallback
### getXslStream() {#getXslStream--}
```
public InputStream getXslStream()
```


Получает данные xsl для преобразования xml в документ pdf.

**Возвращает:**
java.io.InputStream — Входной поток
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
