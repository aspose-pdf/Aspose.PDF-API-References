---
title: PrintPageSettings
second_title: Aspose.PDF для справки по Java API
description: Указывает параметры, которые применяются к одной печатной странице.
type: docs
weight: 15
url: /ru/java/com.aspose.pdf.printing/printpagesettings/
---
**Наследование:**
java.lang.Object
```
public class PrintPageSettings
```

Указывает параметры, которые применяются к одной печатной странице.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PrintPageSettings()](#PrintPageSettings--) | Инициализирует новый экземпляр класса PageSettings, используя принтер по умолчанию. |
| [PrintPageSettings(PdfPrinterSettings value)](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Инициализирует новый экземпляр класса PageSettings, используя указанный принтер. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Получает размер страницы с учетом ориентации страницы, заданной свойством Landscape. |
| [getClass()](#getClass--) |  |
| [getHardMarginX()](#getHardMarginX--) | Получает x-координату в сотых долях дюйма жесткого поля в левой части страницы. |
| [getHardMarginY()](#getHardMarginY--) | Получает координату Y в сотых долях дюйма жесткого поля в верхней части страницы. |
| [getMargins()](#getMargins--) | Получает поля для этой страницы. |
| [getPageSettings()](#getPageSettings--) | Получает настройки страницы |
| [getPaperSize()](#getPaperSize--) | Получает размер бумаги для страницы. |
| [getPaperSource()](#getPaperSource--) | Получает источник бумаги страницы; например, верхний лоток принтера. |
| [getPrintableArea()](#getPrintableArea--) | Получает границы области печати страницы для принтера. |
| [getPrinterResolution()](#getPrinterResolution--) | Получает разрешение принтера для страницы. |
| [getPrinterSettings()](#getPrinterSettings--) | Получает параметры принтера, связанные со страницей. |
| [hashCode()](#hashCode--) |  |
| [isColor()](#isColor--) | Получает или задает значение, указывающее, следует ли печатать страницу в цвете. |
| [isLandscape()](#isLandscape--) | Получает или задает значение, указывающее, печатается ли страница в альбомной или книжной ориентации. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(boolean value)](#setColor-boolean-) | Получает или задает значение, указывающее, следует ли печатать страницу в цвете. |
| [setLandscape(boolean value)](#setLandscape-boolean-) | Получает или задает значение, указывающее, печатается ли страница в альбомной или книжной ориентации. |
| [setMargins(PrinterMargins value)](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Устанавливает поля для этой страницы. |
| [setPaperSize(PrintPaperSize value)](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Устанавливает размер бумаги для страницы. |
| [setPaperSource(PrintPaperSource value)](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Устанавливает источник бумаги страницы; например, верхний лоток принтера. |
| [setPrinterResolution(PdfPrinterResolution value)](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Устанавливает разрешение принтера для страницы. |
| [setPrinterSettings(PdfPrinterSettings value)](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Задает параметры принтера, связанные со страницей. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintPageSettings() {#PrintPageSettings--}
```
public PrintPageSettings()
```


Инициализирует новый экземпляр класса PageSettings, используя принтер по умолчанию.

### PrintPageSettings(PdfPrinterSettings value) {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public PrintPageSettings(PdfPrinterSettings value)
```


Инициализирует новый экземпляр класса PageSettings, используя указанный принтер.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | Объект PdfPrinterSettings |

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
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает размер страницы с учетом ориентации страницы, заданной свойством Landscape.

**Возвращает:**
[Rectangle](../../java.awt/rectangle) - Прямоугольный объект
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getHardMarginX() {#getHardMarginX--}
```
public float getHardMarginX()
```


Получает x-координату в сотых долях дюйма жесткого поля в левой части страницы.

**Возвращает:**
float - плавающее значение
### getHardMarginY() {#getHardMarginY--}
```
public float getHardMarginY()
```


Получает координату Y в сотых долях дюйма жесткого поля в верхней части страницы.

**Возвращает:**
float - плавающее значение
### getMargins() {#getMargins--}
```
public PrinterMargins getMargins()
```


Получает поля для этой страницы.

**Возвращает:**
[PrinterMargins](../../com.aspose.pdf.printing/printermargins) - Объект PrinterMargins
### getPageSettings() {#getPageSettings--}
```
public System.Drawing.Printing.PageSettings getPageSettings()
```


Получает настройки страницы

**Возвращает:**
com.aspose.ms.System.Drawing.Printing.PageSettings — объект PageSettings
### getPaperSize() {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```


Получает размер бумаги для страницы.

**Возвращает:**
[PrintPaperSize](../../com.aspose.pdf.printing/printpapersize) - Объект PrintPaperSize
### getPaperSource() {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```


Получает источник бумаги страницы; например, верхний лоток принтера.

**Возвращает:**
[PrintPaperSource](../../com.aspose.pdf.printing/printpapersource) - Объект PrintPaperSource
### getPrintableArea() {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```


Получает границы области печати страницы для принтера.

**Возвращает:**
[Rectangle](../../java.awt/rectangle) - Прямоугольный объект
### getPrinterResolution() {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```


Получает разрешение принтера для страницы.

**Возвращает:**
[PdfPrinterResolution](../../com.aspose.pdf.printing/pdfprinterresolution) - Объект PdfPrinterResolution
### getPrinterSettings() {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```


Получает параметры принтера, связанные со страницей.

**Возвращает:**
[PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) - Объект PdfPrinterSettings
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isColor() {#isColor--}
```
public boolean isColor()
```


Получает или задает значение, указывающее, следует ли печатать страницу в цвете.

**Возвращает:**
boolean - логическое значение
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Получает или задает значение, указывающее, печатается ли страница в альбомной или книжной ориентации.

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




### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Получает или задает значение, указывающее, следует ли печатать страницу в цвете.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLandscape(boolean value) {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```


Получает или задает значение, указывающее, печатается ли страница в альбомной или книжной ориентации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMargins(PrinterMargins value) {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
```
public void setMargins(PrinterMargins value)
```


Устанавливает поля для этой страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | Объект PrinterMargins |

### setPaperSize(PrintPaperSize value) {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
```
public void setPaperSize(PrintPaperSize value)
```


Устанавливает размер бумаги для страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PrintPaperSize](../../com.aspose.pdf.printing/printpapersize) | Объект PrintPaperSize |

### setPaperSource(PrintPaperSource value) {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
```
public void setPaperSource(PrintPaperSource value)
```


Устанавливает источник бумаги страницы; например, верхний лоток принтера.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PrintPaperSource](../../com.aspose.pdf.printing/printpapersource) | Объект PrintPaperSource |

### setPrinterResolution(PdfPrinterResolution value) {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
```
public void setPrinterResolution(PdfPrinterResolution value)
```


Устанавливает разрешение принтера для страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfPrinterResolution](../../com.aspose.pdf.printing/pdfprinterresolution) | Объект PdfPrinterResolution |

### setPrinterSettings(PdfPrinterSettings value) {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void setPrinterSettings(PdfPrinterSettings value)
```


Задает параметры принтера, связанные со страницей.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | Объект PdfPrinterSettings |

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
