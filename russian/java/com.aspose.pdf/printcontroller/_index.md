---
title: PrintController
second_title: Aspose.PDF для справки по Java API
description: Представляет контроллер печати.
type: docs
weight: 294
url: /ru/java/com.aspose.pdf/printcontroller/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.Drawing.Printing.PrintController

**Все реализованные интерфейсы:**
com.aspose.ms.System.IDisposable
```
public final class PrintController extends System.Drawing.Printing.PrintController implements System.IDisposable
```

Представляет контроллер печати.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PrintController()](#PrintController--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [dispose()](#dispose--) | распоряжаться экземпляром |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFileName()](#getFileName--) | Установить имя файла |
| [hashCode()](#hashCode--) |  |
| [isPreview()](#isPreview--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onEndPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)](#onEndPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-) | Только для внутреннего использования |
| [onEndPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)](#onEndPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-) | Только для внутреннего использования |
| [onStartPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)](#onStartPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-) | Только для внутреннего использования |
| [onStartPagePublic(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)](#onStartPagePublic-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-) | Только для внутреннего использования |
| [onStartPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)](#onStartPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-) | Только для внутреннего использования |
| [setFileName(String value)](#setFileName-java.lang.String-) | Установить имя файла |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintController() {#PrintController--}
```
public PrintController()
```


### dispose() {#dispose--}
```
public final void dispose()
```


распоряжаться экземпляром

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
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Установить имя файла

**Возвращает:**
java.lang.String — строковое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isPreview() {#isPreview--}
```
public boolean isPreview()
```




**Возвращает:**
логический
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onEndPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e) {#onEndPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-}
```
public void onEndPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)
```


Только для внутреннего использования

Срабатывает при печати в конце страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Внутренний экземпляр (документ для печати) |
| e | com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs | Внутренний экземпляр (аргументы события) |

### onEndPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e) {#onEndPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-}
```
public void onEndPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)
```


Только для внутреннего использования

Срабатывает при печати в конце страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Внутренний экземпляр (документ для печати) |
| e | com.aspose.ms.System.Drawing.Printing.PrintEventArgs | Внутренний экземпляр (аргументы события) |

### onStartPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e) {#onStartPage-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-}
```
public System.Drawing.Graphics onStartPage(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)
```


Только для внутреннего использования

Пожары при начале печати страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Внутренний экземпляр (документ для печати) |
| e | com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs | Внутренний экземпляр (аргументы события) |

**Возвращает:**
com.aspose.ms.System.Drawing.Graphics — внутренний экземпляр
### onStartPagePublic(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e) {#onStartPagePublic-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs-}
```
public Graphics2D onStartPagePublic(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintPageEventArgs e)
```


Только для внутреннего использования

Пожары при начале печати страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Внутренний экземпляр (документ для печати) |
| e | com.aspose.ms.System.Drawing.Printing.PrintPageEventArgs | Внутренний экземпляр (аргументы события) |

**Возвращает:**
java.awt.Graphics2D — экземпляр Graphics2D с напечатанной страницей.
### onStartPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e) {#onStartPrint-com.aspose.ms.System.Drawing.Printing.PrintDocument-com.aspose.ms.System.Drawing.Printing.PrintEventArgs-}
```
public void onStartPrint(System.Drawing.Printing.PrintDocument document, System.Drawing.Printing.PrintEventArgs e)
```


Только для внутреннего использования

Пожары при начале печати страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | com.aspose.ms.System.Drawing.Printing.PrintDocument | Внутренний экземпляр (документ для печати) |
| e | com.aspose.ms.System.Drawing.Printing.PrintEventArgs | Внутренний экземпляр (аргументы события) |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Установить имя файла

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

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
