---
title: XslFoLoadOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры для загрузки/импорта файла XSL-FO в документ PDF.
type: docs
weight: 429
url: /ru/java/com.aspose.pdf/xslfoloadoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions), [com.aspose.pdf.XmlLoadOptions](../../com.aspose.pdf/xmlloadoptions)
```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Представляет параметры для загрузки/импорта файла XSL-FO в документ PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XslFoLoadOptions()](#XslFoLoadOptions--) | Создает объект XslFoLoadOptions без данных xsl. |
| [XslFoLoadOptions(String xslFile)](#XslFoLoadOptions-java.lang.String-) | Создает объект XslFoLoadOptions с данными xsl. |
| [XslFoLoadOptions(InputStream xslStream)](#XslFoLoadOptions-java.io.InputStream-) | Создает объект XslFoLoadOptions с данными xsl. |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Закрыть экземпляр |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBasePath()](#getBasePath--) | Базовый путь/URL, по которому выполняется поиск относительных путей к внешним ресурсам (если таковые имеются), на которые есть ссылки в загруженном файле SVG. |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | Представляет формат файла, который описывает LoadOptions. |
| [getParsingErrorsHandlingType()](#getParsingErrorsHandlingType--) | Исходный документ XSLFO может содержать ошибки форматирования. |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [getXslStream()](#getXslStream--) | Получает данные xsl для преобразования xml в документ pdf. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBasePath(String value)](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType(int parsingErrorsHandlingType)](#setParsingErrorsHandlingType-int-) | Исходный документ XSLFO может содержать ошибки форматирования. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XslFoLoadOptions() {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```


Создает объект XslFoLoadOptions без данных xsl.

### XslFoLoadOptions(String xslFile) {#XslFoLoadOptions-java.lang.String-}
```
public XslFoLoadOptions(String xslFile)
```


Создает объект XslFoLoadOptions с данными xsl.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xslFile | java.lang.String | Xsl для преобразования документа XSL-FO в документ PDF. |

### XslFoLoadOptions(InputStream xslStream) {#XslFoLoadOptions-java.io.InputStream-}
```
public XslFoLoadOptions(InputStream xslStream)
```


Создает объект XslFoLoadOptions с данными xsl.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xslStream | java.io.InputStream | Поток Xsl для преобразования документа XSL-FO в документ PDF. |

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
### getBasePath() {#getBasePath--}
```
public String getBasePath()
```


Базовый путь/URL, по которому выполняется поиск относительных путей к внешним ресурсам (если таковые имеются), на которые есть ссылки в загруженном файле SVG.

**Возвращает:**
java.lang.String — Строка
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
### getParsingErrorsHandlingType() {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```


Исходный документ XSLFO может содержать ошибки форматирования. Это перечисление перечисляет возможные стратегии обработки этих ошибок.

**Возвращает:**
int — элемент ParsingErrorsHandlingTypes
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




### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public void setBasePath(String value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setParsingErrorsHandlingType(int parsingErrorsHandlingType) {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```


Исходный документ XSLFO может содержать ошибки форматирования. Это перечисление перечисляет возможные стратегии обработки этих ошибок.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingErrorsHandlingType | int | Элемент ParsingErrorsHandlingTypes |

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
