---
title: EpubLoadOptions
second_title: Aspose.PDF для справки по Java API
description: Содержит опции для загрузки/импорта файла EPUB в документ PDF.
type: docs
weight: 99
url: /ru/java/com.aspose.pdf/epubloadoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class EpubLoadOptions extends LoadOptions
```

Содержит опции для загрузки/импорта файла EPUB в документ PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EpubLoadOptions()](#EpubLoadOptions--) | Создает параметры загрузки по умолчанию для преобразования файла EPUB в документ PDF. |
| [EpubLoadOptions(Dimension2D pageSize)](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Создает параметры загрузки с указанным размером страницы. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | Представляет формат файла, который описывает LoadOptions. |
| [getMargin()](#getMargin--) | Получает ссылку на объект, который представляет информацию о полях. |
| [getMarginsAreaUsageMode()](#getMarginsAreaUsageMode--) | Представляет режим использования области полей - определяет обработку инструкций (если таковые имеются) CSS импортированного документа, связанных с использованием полей. |
| [getPageSize()](#getPageSize--) | Получает размер выходной страницы для импорта. |
| [getPageSizeAdjustmentMode()](#getPageSizeAdjustmentMode--) | ВНИМАНИЕ! |
| [getWarningHandler()](#getWarningHandler--) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Получает ссылку на объект, который представляет информацию о полях. |
| [setMarginsAreaUsageMode(int marginsAreaUsageMode)](#setMarginsAreaUsageMode-int-) | Представляет режим использования области полей - определяет обработку инструкций (если таковые имеются) CSS импортированного документа, связанных с использованием полей. |
| [setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)](#setPageSizeAdjustmentMode-int-) | ВНИМАНИЕ! |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Обратный вызов для обработки любых сгенерированных предупреждений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EpubLoadOptions() {#EpubLoadOptions--}
```
public EpubLoadOptions()
```


Создает параметры загрузки по умолчанию для преобразования файла EPUB в документ PDF. Размер страницы PDF по умолчанию — A4 300 dpi 2480 X 3508.

### EpubLoadOptions(Dimension2D pageSize) {#EpubLoadOptions-java.awt.geom.Dimension2D-}
```
public EpubLoadOptions(Dimension2D pageSize)
```


Создает параметры загрузки с указанным размером страницы.

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
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает ссылку на объект, который представляет информацию о полях.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - Объект MarginInfo
### getMarginsAreaUsageMode() {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```


Представляет режим использования области полей - определяет обработку инструкций (если таковые имеются) CSS импортированного документа, связанных с использованием полей.

**Возвращает:**
int — значение MarginsAreaUsageModes
### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


Получает размер выходной страницы для импорта.

**Возвращает:**
java.awt.geom.Dimension2D — объект Dimension2D
### getPageSizeAdjustmentMode() {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```


ВНИМАНИЕ! Эта функция реализована, но еще не размещена в общедоступном API, поскольку для примера документа обнаружена проблема с блокировщиком на уровне OSHARED. Представляет режим использования размера страницы во время преобразования. Форматы (например, HTML, EPUB и т. д.) обычно имеют плавающий дизайн, что позволяет вписаться в требуемый размер страницы. Но иногда контент имеет заданное положение по горизонтали или размер, что не позволяет поместить контент в нужный размер страницы. В таком случае мы можем определить, что следует делать в этом случае (например, когда размер содержимого не соответствует требуемому исходному размеру страницы результирующего PDF-документа).

**Возвращает:**
int - значение PageSizeAdjustmentModes
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




### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public final void setMargin(MarginInfo value)
```


Получает ссылку на объект, который представляет информацию о полях.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setMarginsAreaUsageMode(int marginsAreaUsageMode) {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```


Представляет режим использования области полей - определяет обработку инструкций (если таковые имеются) CSS импортированного документа, связанных с использованием полей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| marginsAreaUsageMode | int | Значение MarginsAreaUsageModes |

### setPageSizeAdjustmentMode(int pageSizeAdjustmentMode) {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```


ВНИМАНИЕ! Эта функция реализована, но еще не размещена в общедоступном API, поскольку для примера документа обнаружена проблема с блокировщиком на уровне OSHARED. Представляет режим использования размера страницы во время преобразования. Форматы (например, HTML, EPUB и т. д.) обычно имеют плавающий дизайн, что позволяет вписаться в требуемый размер страницы. Но иногда контент имеет заданное положение по горизонтали или размер, что не позволяет поместить контент в нужный размер страницы. В таком случае мы можем определить, что следует делать в этом случае (например, когда размер содержимого не соответствует требуемому исходному размеру страницы результирующего PDF-документа).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSizeAdjustmentMode | int | Значение PageSizeAdjustmentModes |

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
