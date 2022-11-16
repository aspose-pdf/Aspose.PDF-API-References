---
title: PdfPrinterSettings
second_title: Aspose.PDF для справки по Java API
description: Указывает информацию о способе печати документа, включая принтер, который его печатает.
type: docs
weight: 14
url: /ru/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Наследование:**
java.lang.Object
```
public class PdfPrinterSettings
```

Указывает информацию о способе печати документа, включая принтер, на котором он печатается.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfPrinterSettings()](#PdfPrinterSettings--) | Инициализирует новый экземпляр класса PrinterSettings. |
## Методы

| Метод | Описание |
| --- | --- |
| [canDuplex()](#canDuplex--) | Получает значение, указывающее, поддерживает ли принтер двустороннюю печать. |
| [createMeasurementGraphics()](#createMeasurementGraphics--) | Получить объект Graphics2D |
| [createMeasurementGraphics(boolean value)](#createMeasurementGraphics-boolean-) | Получить объект Graphics2D |
| [createMeasurementGraphics(PrintPageSettings value)](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Получить объект Graphics2D |
| [createMeasurementGraphics(PrintPageSettings pageSettings, boolean honorOriginAtMargins)](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Получить объект Graphics2D |
| [deepClone()](#deepClone--) | Получить клонированный объект |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCopies()](#getCopies--) | Получает количество копий документа для печати. |
| [getDefaultPageSettings()](#getDefaultPageSettings--) | Получает параметры страницы по умолчанию для этого принтера. |
| [getDuplex()](#getDuplex--) | Получает или задает параметр принтера для двусторонней печати. |
| [getFromPage()](#getFromPage--) | Получает или задает номер первой страницы для печати. |
| [getInstalledPrinters()](#getInstalledPrinters--) | Получает имена всех принтеров, установленных на компьютере. |
| [getLandscapeAngle()](#getLandscapeAngle--) | Получает угол в градусах, на который поворачивается книжная ориентация для получения альбомной ориентации. |
| [getMaximumCopies()](#getMaximumCopies--) | Получает максимальное количество копий, которое принтер позволяет пользователю распечатать за один раз. |
| [getMaximumPage()](#getMaximumPage--) | Получает или задает максимальное значение FromPage или ToPage, которое можно выбрать в PrintDialog. |
| [getMinimumPage()](#getMinimumPage--) | Получает или задает минимальное значение FromPage или ToPage, которое можно выбрать в PrintDialog. |
| [getPaperSizes()](#getPaperSizes--) | Получает размеры бумаги, поддерживаемые этим принтером. |
| [getPaperSources()](#getPaperSources--) | Получает лотки для подачи бумаги, доступные на принтере. |
| [getPrintFileName()](#getPrintFileName--) | Получает или задает имя файла при печати в файл. |
| [getPrintRange()](#getPrintRange--) | Получает или задает номера страниц, указанные пользователем для печати. |
| [getPrinterName()](#getPrinterName--) | Получает или задает имя используемого принтера. |
| [getPrinterResolutions()](#getPrinterResolutions--) | Получает все разрешения, поддерживаемые этим принтером. |
| [getPrinterSettings()](#getPrinterSettings--) | Возвращает объект PrinterSettings |
| [getSelectedPages()](#getSelectedPages--) | Получает количество выбранных страниц для печати. |
| [getToPage()](#getToPage--) | Получает или задает номер последней страницы для печати. |
| [hashCode()](#hashCode--) |  |
| [isCollate()](#isCollate--) | Получает или задает значение, указывающее, упорядочен ли напечатанный документ. |
| [isDefaultPrinter()](#isDefaultPrinter--) | Получает значение, указывающее, назначает ли свойство PrinterName принтер по умолчанию, за исключением случаев, когда пользователь явно задает PrinterName. |
| [isDirectPrintingSupported(ImageType format)](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Получает значение, указывающее, поддерживает ли принтер DirectPrinting. |
| [isDirectPrintingSupported(String filename)](#isDirectPrintingSupported-java.lang.String-) | Получает значение, указывающее, поддерживает ли принтер DirectPrinting. |
| [isPlotter()](#isPlotter--) | Получает значение, указывающее, является ли принтер плоттером. |
| [isPrintToFile()](#isPrintToFile--) | Получает значение, указывающее, отправляется ли вывод на печать в файл вместо порта. |
| [isSupportsColor()](#isSupportsColor--) | Получает значение, указывающее, поддерживает ли данный принтер цветную печать. |
| [isValid()](#isValid--) | Получает значение, указывающее, указывает ли свойство PrinterName действительный принтер. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCollate(boolean value)](#setCollate-boolean-) | Получает или задает значение, указывающее, упорядочен ли напечатанный документ. |
| [setCopies(short value)](#setCopies-short-) | Устанавливает количество копий документа для печати. |
| [setDuplex(int value)](#setDuplex-int-) | Получает или задает параметр принтера для двусторонней печати. |
| [setFromPage(int value)](#setFromPage-int-) | Получает или задает номер первой страницы для печати. |
| [setMaximumPage(int value)](#setMaximumPage-int-) | Получает или задает максимальное значение FromPage или ToPage, которое можно выбрать в PrintDialog. |
| [setMinimumPage(int value)](#setMinimumPage-int-) | Получает или задает минимальное значение FromPage или ToPage, которое можно выбрать в PrintDialog. |
| [setPrintFileName(String value)](#setPrintFileName-java.lang.String-) | Устанавливает имя файла для печати. |
| [setPrintRange(int value)](#setPrintRange-int-) | Устанавливает номера страниц, которые пользователь указал для печати. |
| [setPrintToFile(boolean value)](#setPrintToFile-boolean-) | Устанавливает значение, указывающее, отправляется ли вывод на печать в файл вместо порта. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Устанавливает имя используемого принтера. |
| [setSelectedPages(int[] pagesList)](#setSelectedPages-int---) | Устанавливает количество выбранных страниц для печати. |
| [setToPage(int value)](#setToPage-int-) | Устанавливает номер последней страницы для печати. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfPrinterSettings() {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```


Инициализирует новый экземпляр класса PrinterSettings.

### canDuplex() {#canDuplex--}
```
public boolean canDuplex()
```


Получает значение, указывающее, поддерживает ли принтер двустороннюю печать.

**Возвращает:**
boolean - логическое значение
### createMeasurementGraphics() {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```


Получить объект Graphics2D

**Возвращает:**
java.awt.Graphics2D — объект Graphics2D
### createMeasurementGraphics(boolean value) {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```


Получить объект Graphics2D

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

**Возвращает:**
java.awt.Graphics2D — объект Graphics2D
### createMeasurementGraphics(PrintPageSettings value) {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
```
public Graphics2D createMeasurementGraphics(PrintPageSettings value)
```


Получить объект Graphics2D

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | Значение PrintPageSettings |

**Возвращает:**
java.awt.Graphics2D — объект Graphics2D
### createMeasurementGraphics(PrintPageSettings pageSettings, boolean honorOriginAtMargins) {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
```
public Graphics2D createMeasurementGraphics(PrintPageSettings pageSettings, boolean honorOriginAtMargins)
```


Получить объект Graphics2D

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | Значение PrintPageSettings |
| honorOriginAtMargins | boolean | логическое значение |

**Возвращает:**
java.awt.Graphics2D — объект Graphics2D
### deepClone() {#deepClone--}
```
public PdfPrinterSettings deepClone()
```


Получить клонированный объект

**Возвращает:**
[PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) - Объект PdfPrinterSettings
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
### getCopies() {#getCopies--}
```
public short getCopies()
```


Получает количество копий документа для печати.

**Возвращает:**
короткий - количество копий
### getDefaultPageSettings() {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```


Получает параметры страницы по умолчанию для этого принтера.

**Возвращает:**
[PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) - настройки страницы по умолчанию
### getDuplex() {#getDuplex--}
```
public int getDuplex()
```


Получает или задает параметр принтера для двусторонней печати.

**Возвращает:**
интервал - целочисленное значение
### getFromPage() {#getFromPage--}
```
public int getFromPage()
```


Получает или задает номер первой страницы для печати.

**Возвращает:**
интервал - целочисленное значение
### getInstalledPrinters() {#getInstalledPrinters--}
```
public static ArrayList<String> getInstalledPrinters()
```


Получает имена всех принтеров, установленных на компьютере.

**Возвращает:**
java.util.ArrayList<java.lang.String> — объект ArrayList
### getLandscapeAngle() {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```


Получает угол в градусах, на который поворачивается книжная ориентация для получения альбомной ориентации.

**Возвращает:**
интервал - целочисленное значение
### getMaximumCopies() {#getMaximumCopies--}
```
public int getMaximumCopies()
```


Получает максимальное количество копий, которое принтер позволяет пользователю распечатать за один раз.

**Возвращает:**
интервал - целочисленное значение
### getMaximumPage() {#getMaximumPage--}
```
public int getMaximumPage()
```


Получает или задает максимальное значение FromPage или ToPage, которое можно выбрать в PrintDialog.

**Возвращает:**
интервал - целочисленное значение
### getMinimumPage() {#getMinimumPage--}
```
public int getMinimumPage()
```


Получает или задает минимальное значение FromPage или ToPage, которое можно выбрать в PrintDialog.

**Возвращает:**
интервал - целочисленное значение
### getPaperSizes() {#getPaperSizes--}
```
public ArrayList<PrintPaperSize> getPaperSizes()
```


Получает размеры бумаги, поддерживаемые этим принтером.

**Возвращает:**
java.util.ArrayList<com.aspose.pdf.printing.PrintPaperSize> — объект ArrayList
### getPaperSources() {#getPaperSources--}
```
public ArrayList<PrintPaperSource> getPaperSources()
```


Получает лотки для подачи бумаги, доступные на принтере.

**Возвращает:**
java.util.ArrayList<com.aspose.pdf.printing.PrintPaperSource> — объект ArrayList
### getPrintFileName() {#getPrintFileName--}
```
public String getPrintFileName()
```


Получает или задает имя файла при печати в файл.

**Возвращает:**
java.lang.String — строковый объект
### getPrintRange() {#getPrintRange--}
```
public int getPrintRange()
```


Получает или задает номера страниц, указанные пользователем для печати.

**Возвращает:**
интервал - целочисленное значение
### getPrinterName() {#getPrinterName--}
```
public String getPrinterName()
```


Получает или задает имя используемого принтера.

**Возвращает:**
java.lang.String — строковый объект
### getPrinterResolutions() {#getPrinterResolutions--}
```
public System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```


Получает все разрешения, поддерживаемые этим принтером.

**Возвращает:**
com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection — объект PrinterResolutionCollection
### getPrinterSettings() {#getPrinterSettings--}
```
public System.Drawing.Printing.PrinterSettings getPrinterSettings()
```


Возвращает объект PrinterSettings

**Возвращает:**
com.aspose.ms.System.Drawing.Printing.PrinterSettings — объект PrinterSettings
### getSelectedPages() {#getSelectedPages--}
```
public int[] getSelectedPages()
```


Получает количество выбранных страниц для печати.

**Возвращает:**
инт[] - массив страниц списка целых чисел
### getToPage() {#getToPage--}
```
public int getToPage()
```


Получает или задает номер последней страницы для печати.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isCollate() {#isCollate--}
```
public boolean isCollate()
```


Получает или задает значение, указывающее, упорядочен ли напечатанный документ.

**Возвращает:**
boolean - логическое значение
### isDefaultPrinter() {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```


Получает значение, указывающее, назначает ли свойство PrinterName принтер по умолчанию, за исключением случаев, когда пользователь явно задает PrinterName.

**Возвращает:**
boolean - логическое значение
### isDirectPrintingSupported(ImageType format) {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
```
public boolean isDirectPrintingSupported(ImageType format)
```


Получает значение, указывающее, поддерживает ли принтер DirectPrinting.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Объект ImageType |

**Возвращает:**
boolean - логическое значение
### isDirectPrintingSupported(String filename) {#isDirectPrintingSupported-java.lang.String-}
```
public boolean isDirectPrintingSupported(String filename)
```


Получает значение, указывающее, поддерживает ли принтер DirectPrinting.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | java.lang.String | Строковый объект |

**Возвращает:**
boolean - логическое значение
### isPlotter() {#isPlotter--}
```
public boolean isPlotter()
```


Получает значение, указывающее, является ли принтер плоттером.

**Возвращает:**
boolean - логическое значение
### isPrintToFile() {#isPrintToFile--}
```
public boolean isPrintToFile()
```


Получает значение, указывающее, отправляется ли вывод на печать в файл вместо порта.

**Возвращает:**
boolean - логическое значение
### isSupportsColor() {#isSupportsColor--}
```
public boolean isSupportsColor()
```


Получает значение, указывающее, поддерживает ли данный принтер цветную печать.

**Возвращает:**
boolean - логическое значение
### isValid() {#isValid--}
```
public boolean isValid()
```


Получает значение, указывающее, указывает ли свойство PrinterName действительный принтер.

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




### setCollate(boolean value) {#setCollate-boolean-}
```
public void setCollate(boolean value)
```


Получает или задает значение, указывающее, упорядочен ли напечатанный документ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setCopies(short value) {#setCopies-short-}
```
public void setCopies(short value)
```


Устанавливает количество копий документа для печати.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | Количество копий |

### setDuplex(int value) {#setDuplex-int-}
```
public void setDuplex(int value)
```


Получает или задает параметр принтера для двусторонней печати.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setFromPage(int value) {#setFromPage-int-}
```
public void setFromPage(int value)
```


Получает или задает номер первой страницы для печати.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setMaximumPage(int value) {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```


Получает или задает максимальное значение FromPage или ToPage, которое можно выбрать в PrintDialog.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setMinimumPage(int value) {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```


Получает или задает минимальное значение FromPage или ToPage, которое можно выбрать в PrintDialog.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setPrintFileName(String value) {#setPrintFileName-java.lang.String-}
```
public void setPrintFileName(String value)
```


Устанавливает имя файла для печати.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | строковое значение |

### setPrintRange(int value) {#setPrintRange-int-}
```
public void setPrintRange(int value)
```


Устанавливает номера страниц, которые пользователь указал для печати.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PdfPrintRange |

### setPrintToFile(boolean value) {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```


Устанавливает значение, указывающее, отправляется ли вывод на печать в файл вместо порта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public void setPrinterName(String value)
```


Устанавливает имя используемого принтера.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | строковое значение |

### setSelectedPages(int[] pagesList) {#setSelectedPages-int---}
```
public void setSelectedPages(int[] pagesList)
```


Устанавливает количество выбранных страниц для печати.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pagesList | int[] | массив целых чисел |

### setToPage(int value) {#setToPage-int-}
```
public void setToPage(int value)
```


Устанавливает номер последней страницы для печати.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PdfPrintRange |

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
