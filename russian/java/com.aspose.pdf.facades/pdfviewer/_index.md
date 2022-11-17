---
title: PdfViewer
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для просмотра или печати PDF-файла.
type: docs
weight: 53
url: /ru/java/com.aspose.pdf.facades/pdfviewer/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget

**Все реализованные интерфейсы:**
[com.aspose.pdf.facades.IFacade](../../com.aspose.pdf.facades/ifacade)
```
public final class PdfViewer extends IVentureLicenseTarget implements IFacade
```

Представляет класс для просмотра или печати PDF-файла.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfViewer()](#PdfViewer--) | Инициализирует новый объект PdfViewer. |
| [PdfViewer(IDocument document)](#PdfViewer-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfViewer. |
## Поля

| Поле | Описание |
| --- | --- |
| [EndPrint](#EndPrint) | Добавляет/удаляет подписку на событие печати последней страницы. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Добавляет/удаляет подписку на событие печати последней страницы. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Закрывает текущий файл PDF. |
| [closePdfFile()](#closePdfFile--) | Закрывает текущий файл PDF. |
| [decodeAllPages()](#decodeAllPages--) | Получить страницы текущего файла PDF. |
| [decodePage(int pageNumber)](#decodePage-int-) | Декодирует страницу одного файла Pdf. |
| [decodePageToImage(int pageNumber, ImageType imageFormat)](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Декодирует страницу в BufferedImage |
| [dispose()](#dispose--) | Распоряжается ресурсами фасада. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoResize()](#getAutoResize--) | Устанавливает логическое значение, указывающее, будет ли файл распечатываться с оптимизированным размером. |
| [getAutoRotate()](#getAutoRotate--) | Получает логическое значение, указывающее, следует ли печатать файл с автоматическим поворотом. |
| [getAutoRotateMode()](#getAutoRotateMode--) | Получает значение AutoRotateMode, указывающее направление вращения. |
| [getClass()](#getClass--) |  |
| [getCoordinateType()](#getCoordinateType--) | Получает тип координат страницы (поля мультимедиа/обрезки). |
| [getCopiesPrinted()](#getCopiesPrinted--) | Печатает копии |
| [getDefaultPageSettings()](#getDefaultPageSettings--) | Получает параметры страницы по умолчанию. |
| [getDefaultPrinterSettings()](#getDefaultPrinterSettings--) | Получает параметры принтера по умолчанию. |
| [getFormPresentationMode()](#getFormPresentationMode--) | Получает режим представления формы. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает значение, указывающее горизонтальное выравнивание |
| [getPageCount()](#getPageCount--) | Получает количество страниц текущего файла Pdf. |
| [getPassword()](#getPassword--) | Получает пароль входного документа. |
| [getPrintAsGrayscale()](#getPrintAsGrayscale--) | Получает или задает логическое значение, указывающее, печатается ли страница в оттенках серого. |
| [getPrintAsImage()](#getPrintAsImage--) | Получает режим для PdfViewer для печати в виде изображения. |
| [getPrintPageDialog()](#getPrintPageDialog--) | Получает логическое значение, указывающее, следует ли создавать диалоговое окно номера страницы при печати. |
| [getPrintStatus()](#getPrintStatus--) | Получает результат задания на печать. |
| [getPrinterJobName()](#getPrinterJobName--) | Получает имя документа в очереди печати при печати документа. |
| [getRenderingOptions()](#getRenderingOptions--) | Получает параметры рендеринга. |
| [getResolution()](#getResolution--) | Получает или задает разрешение во время просмотра и печати. |
| [getScaleFactor()](#getScaleFactor--) | Получает значение с плавающей запятой, указывающее коэффициент масштабирования. |
| [getUseIntermidiateImage()](#getUseIntermidiateImage--) | Получает использование преобразования страницы pdf в промежуточный файл png при печати в файловом режиме. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает значение, указывающее вертикальное выравнивание |
| [hashCode()](#hashCode--) |  |
| [isShowHiddenAreas()](#isShowHiddenAreas--) | Этот метод является устаревшим. Получает флаг, который управляет видимостью скрытых областей на странице. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [openPdfFile(InputStream inputStream)](#openPdfFile-java.io.InputStream-) | Открывает поток файлов PDF. |
| [openPdfFile(String filePath)](#openPdfFile-java.lang.String-) | Открывает файл Pdf, но фактически не декодирует страницы файла Pdf. |
| [printDocument()](#printDocument--) | Печать документа Pdf на принтере по умолчанию. |
| [printDocumentWithSettings(PdfPrinterSettings printerSettings)](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Печать документа Pdf с настройками принтера. |
| [printDocumentWithSettings(PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Распечатывает PDF-документ с настройками. |
| [printLargePdf(InputStream inputStream)](#printLargePdf-java.io.InputStream-) | Открывает и печатает большой поток PDF. |
| [printLargePdf(InputStream inputStream, PdfPrinterSettings printerSettings)](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | Открывает и печатает большой поток Pdf с указанными настройками принтера. |
| [printLargePdf(InputStream inputStream, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Открывает и печатает большой поток Pdf с указанными настройками страницы и настройками принтера. |
| [printLargePdf(String filePath)](#printLargePdf-java.lang.String-) | Открывает и печатает большой файл PDF. |
| [printLargePdf(String filePath, PdfPrinterSettings printerSettings)](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | Открывает и печатает большой файл Pdf с указанными настройками принтера. |
| [printLargePdf(String filePath, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Открывает и печатает большой файл Pdf с указанными параметрами страницы и параметрами принтера. |
| [save(InputStream destStream)](#save-java.io.InputStream-) | Сохраняет полученный PDF-документ в потоковом режиме. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет полученный PDF-документ в файл. |
| [setAutoResize(boolean value)](#setAutoResize-boolean-) | Устанавливает логическое значение, указывающее, будет ли файл распечатываться с оптимизированным размером. |
| [setAutoRotate(boolean value)](#setAutoRotate-boolean-) | Устанавливает логическое значение, указывающее, следует ли печатать файл с автоматическим поворотом. |
| [setAutoRotateMode(int value)](#setAutoRotateMode-int-) | Задает значение AutoRotateMode, указывающее направление вращения |
| [setCoordinateType(int value)](#setCoordinateType-int-) | Устанавливает тип координат страницы (поля Media/Crop). |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | Устанавливает режим представления формы. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает значение, указывающее горизонтальное выравнивание |
| [setPassword(String value)](#setPassword-java.lang.String-) | Устанавливает пароль входного документа. |
| [setPrintAsGrayscale(boolean value)](#setPrintAsGrayscale-boolean-) | Получает или задает логическое значение, указывающее, печатается ли страница в оттенках серого. |
| [setPrintAsImage(boolean value)](#setPrintAsImage-boolean-) | Устанавливает режим печати PdfViewer как изображения. |
| [setPrintPageDialog(boolean value)](#setPrintPageDialog-boolean-) | Задает логическое значение, указывающее, следует ли создавать диалоговое окно номера страницы при печати. |
| [setPrinterJobName(String value)](#setPrinterJobName-java.lang.String-) | Задает имя документа в очереди печати при печати документа. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Устанавливает параметры рендеринга. |
| [setResolution(int value)](#setResolution-int-) | Устанавливает разрешение во время просмотра и печати. |
| [setScaleFactor(float value)](#setScaleFactor-float-) | Задает значение с плавающей запятой, указывающее коэффициент масштабирования. |
| [setShowHiddenAreas(boolean value)](#setShowHiddenAreas-boolean-) |  |
| [setUseIntermidiateImage(boolean value)](#setUseIntermidiateImage-boolean-) | Устанавливает использование преобразования страницы pdf в промежуточный файл png при печати в файловом режиме. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает значение, указывающее вертикальное выравнивание |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfViewer() {#PdfViewer--}
```
public PdfViewer()
```


Инициализирует новый объект PdfViewer.

### PdfViewer(IDocument document) {#PdfViewer-com.aspose.pdf.IDocument-}
```
public PdfViewer(IDocument document)
```


Инициализирует новый объект PdfViewer.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Объект документа. |

### EndPrint {#EndPrint}
```
public final PdfEvent<System.Drawing.Printing.PrintEventHandler> EndPrint
```


Добавляет/удаляет подписку на событие печати последней страницы.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent<PdfQueryPageSettingsEventHandler> PdfQueryPageSettings
```


Добавляет/удаляет подписку на событие печати последней страницы.

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл. |

### close() {#close--}
```
public void close()
```


Закрывает текущий файл PDF.

### closePdfFile() {#closePdfFile--}
```
public void closePdfFile()
```


Закрывает текущий файл PDF.

### decodeAllPages() {#decodeAllPages--}
```
public BufferedImage[] decodeAllPages()
```


Получить страницы текущего файла PDF.

**Возвращает:**
java.awt.image.BufferedImage[] - вернуть массив изображений страниц Pdf.
### decodePage(int pageNumber) {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```


Декодирует страницу одного файла Pdf.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы одного файла Pdf, который должен быть между 1 и PageCount. |

**Возвращает:**
java.awt.image.BufferedImage — возвращает изображение страницы в формате PDF.
### decodePageToImage(int pageNumber, ImageType imageFormat) {#decodePageToImage-int-com.aspose.pdf.ImageType-}
```
public BufferedImage decodePageToImage(int pageNumber, ImageType imageFormat)
```


Декодирует страницу в BufferedImage

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | целое значение |
| imageFormat | [ImageType](../../com.aspose.pdf/imagetype) | Объект ImageType |

**Возвращает:**
java.awt.image.BufferedImage — значение BufferedImage
### dispose() {#dispose--}
```
public void dispose()
```


Распоряжается ресурсами фасада.

Этот метод устарел, вместо него используйте close().

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
### getAutoResize() {#getAutoResize--}
```
public boolean getAutoResize()
```


Устанавливает логическое значение, указывающее, будет ли файл распечатываться с оптимизированным размером.

**Возвращает:**
boolean - логическое значение: если false печатать страницу без масштабирования страницы. Если true, распечатайте страницу с масштабированием, чтобы соответствовать области печати.
### getAutoRotate() {#getAutoRotate--}
```
public boolean getAutoRotate()
```


Получает логическое значение, указывающее, следует ли печатать файл с автоматическим поворотом.

**Возвращает:**
boolean - логическое значение
### getAutoRotateMode() {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```


Получает значение AutoRotateMode, указывающее направление вращения.

**Возвращает:**
int — элемент AutoRotateMode
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


Получает тип координат страницы (поля мультимедиа/обрезки). Значение CropBox используется по умолчанию.

**Возвращает:**
int - элемент PageCoordinateType
### getCopiesPrinted() {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```


Печатает копии

**Возвращает:**
интервал - целочисленное значение
### getDefaultPageSettings() {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```


Получает параметры страницы по умолчанию.

**Возвращает:**
[PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) - Объект настроек страницы.
### getDefaultPrinterSettings() {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```


Получает параметры принтера по умолчанию.

**Возвращает:**
[PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) - Объект настроек страницы.
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Получает режим представления формы.

**Возвращает:**
int - элемент FormPresentationMode
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает значение, указывающее горизонтальное выравнивание

**Возвращает:**
int - элемент HorizontalAlignment
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получает количество страниц текущего файла Pdf.

**Возвращает:**
int - вернуть количество страниц.
### getPassword() {#getPassword--}
```
public String getPassword()
```


Получает пароль входного документа.

**Возвращает:**
java.lang.String — строковое значение
### getPrintAsGrayscale() {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```


Получает или задает логическое значение, указывающее, печатается ли страница в оттенках серого. По умолчанию ложно.

--------------------

Ложь по умолчанию — это ложь.

**Возвращает:**
boolean - логическое значение
### getPrintAsImage() {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```


Получает режим для PdfViewer для печати в виде изображения.

**Возвращает:**
boolean - логическое значение

--------------------

Если true, то всегда печатается как изображение (создается изображение, которое печатается). Если false, печатается непосредственно на устройство, если поддерживаются все функции. Если документ содержит неподдерживаемые функции, система может автоматически принять решение о печати в виде изображения. Значение по умолчанию — false.
### getPrintPageDialog() {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```


Получает логическое значение, указывающее, следует ли создавать диалоговое окно номера страницы при печати.

**Возвращает:**
boolean - логическое значение
### getPrintStatus() {#getPrintStatus--}
```
public Object getPrintStatus()
```


Получает результат задания на печать. Если успех, чем ноль; в противном случае объект исключения.

**Возвращает:**
java.lang.Object — объект исключения или ноль
### getPrinterJobName() {#getPrinterJobName--}
```
public String getPrinterJobName()
```


Получает имя документа в очереди печати при печати документа. Значение по умолчанию — имя файла.

**Возвращает:**
java.lang.String — строковое значение
### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


Получает параметры рендеринга.

**Возвращает:**
[RenderingOptions](../../com.aspose.pdf/renderingoptions) - Объект RenderingOptions
### getResolution() {#getResolution--}
```
public int getResolution()
```


Получает или задает разрешение во время просмотра и печати. Чем выше разрешение, тем ниже скорость. Значение по умолчанию — 150.

**Возвращает:**
интервал - целочисленное значение
### getScaleFactor() {#getScaleFactor--}
```
public float getScaleFactor()
```


Получает значение с плавающей запятой, указывающее коэффициент масштабирования. Значение по умолчанию — 1,0.

**Возвращает:**
float - значение с плавающей запятой.
### getUseIntermidiateImage() {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```


Получает использование преобразования страницы pdf в промежуточный файл png при печати в файловом режиме. Используйте его, когда важен размер выходного файла.

**Возвращает:**
boolean - логическое значение.
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает значение, указывающее вертикальное выравнивание

**Возвращает:**
int - элемент вертикального выравнивания
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isShowHiddenAreas() {#isShowHiddenAreas--}
```
public boolean isShowHiddenAreas()
```


Этот метод является устаревшим. Получает флаг, который управляет видимостью скрытых областей на странице.

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




### openPdfFile(InputStream inputStream) {#openPdfFile-java.io.InputStream-}
```
public void openPdfFile(InputStream inputStream)
```


Открывает поток файлов PDF. Но на самом деле не декодирует страницы файла Pdf.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile(new FileInputStream("d:\\test.pdf")));
 viewer.closePdfFile();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток PDF, который нужно открыть. |

### openPdfFile(String filePath) {#openPdfFile-java.lang.String-}
```
public void openPdfFile(String filePath)
```


Открывает файл Pdf, но фактически не декодирует страницы файла Pdf.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.closePdfFile();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу PDF. |

### printDocument() {#printDocument--}
```
public void printDocument()
```


Печать документа Pdf на принтере по умолчанию.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.setAutoResize ( true);         //распечатать файл с измененным размером
 viewer.setAutoRotate ( true);         //распечатать файл с отрегулированным поворотом
 viewer.setPrintPageDialog ( false);   //не создавать диалоговое окно номера страницы при печати
 viewer.printDocument(ps);
 viewer.closePdfFile();
```

### printDocumentWithSettings(PdfPrinterSettings printerSettings) {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printDocumentWithSettings(PdfPrinterSettings printerSettings)
```


Печать документа Pdf с настройками принтера. Размер выходной страницы будет соответствовать размеру первой страницы документа.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.setAutoResize ( true);         //распечатать файл с измененным размером
 viewer.setAutoRotate ( true);         //распечатать файл с отрегулированным поворотом
 viewer.setPrintPageDialog ( false);   //не создавать диалоговое окно номера страницы при печати
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName());
 viewer.printDocumentWithSettings(ps);
 viewer.closePdfFile();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | Настройка принтера для печати документа. |

### printDocumentWithSettings(PrintPageSettings pageSettings, PdfPrinterSettings printerSettings) {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printDocumentWithSettings(PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)
```


Распечатывает PDF-документ с настройками. Если размер документа не соответствует размеру страницы, pdf.kit расширит его до размера страницы.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.openPdfFile("d:\\test.pdf");
 viewer.setAutoResize ( true);         //распечатать файл с измененным размером
 viewer.setAutoRotate ( true);         //распечатать файл с отрегулированным поворотом
 viewer.setPrintPageDialog ( false);//не создавать диалоговое окно номера страницы при печати
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName());
 PageSettings pgs = new PageSettings();
 pgs.setPaperSize ( new PaperSize("A4", 827, 1169));
 pgs.setMargins ( new Margins(0, 0, 0, 0));
 viewer.printDocumentWithSettings(pgs, ps);
 viewer.closePdfFile();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | Параметры страницы печатаемого документа. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | Настройка принтера для печати документа.

--------------------

 Объект printerSettings используется для печати документа. Объект pageSettings.PrinterSettings игнорируется.|

### printLargePdf(InputStream inputStream) {#printLargePdf-java.io.InputStream-}
```
public void printLargePdf(InputStream inputStream)
```


Открывает и печатает большой поток PDF. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize ( true);        //распечатать файл с измененным размером
 viewer.setAutoRotate ( true);        //распечатать файл с отрегулированным поворотом
 viewer.printPageDialog=false;//не создавать диалоговое окно номера страницы при печати
 viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf")));
 viewer.closePdfFile();
```

--------------------

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать OpenPdfFile().

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток pdf, который нужно открыть и распечатать. |

### printLargePdf(InputStream inputStream, PdfPrinterSettings printerSettings) {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(InputStream inputStream, PdfPrinterSettings printerSettings)
```


Открывает и печатает большой поток Pdf с указанными настройками принтера. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize(true); // распечатать файл с измененным размером
 viewer.setAutoRotate(true); // распечатать файл с отрегулированным поворотом
 viewer.setPrintPageDialog(false); // не создавать диалоговое окно номера страницы, когда
 				  // печать
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName());
 viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps);
 viewer.closePdfFile();
```

--------------------

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать OpenPdfFile().

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток pdf, который нужно открыть и распечатать. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | Настройки принтера. |

### printLargePdf(InputStream inputStream, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings) {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(InputStream inputStream, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)
```


Открывает и печатает большой поток Pdf с указанными настройками страницы и настройками принтера. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize ( true);       //распечатать файл с измененным размером
 viewer.setAutoRotate ( true);       //распечатать файл с отрегулированным поворотом
 viewer.setPrintPageDialog ( false);//не создавать диалоговое окно номера страницы при печати
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName());
 PageSettings pgs = new PageSettings();
 pgs.setPaperSize ( new PaperSize("A4", 827, 1169));
 pgs.setMargins ( new Margins(0, 0, 0, 0));
 viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps);
 viewer.closePdfFile();
```

--------------------

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать OpenPdfFile().

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток PDF, который нужно открыть и распечатать. |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | Настройки страницы. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | Настройки принтера. |

### printLargePdf(String filePath) {#printLargePdf-java.lang.String-}
```
public void printLargePdf(String filePath)
```


Открывает и печатает большой файл PDF. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize(true); // распечатать файл с измененным размером
 viewer.setAutoRotate(true); // распечатать файл с отрегулированным поворотом
 viewer.setPrintPageDialog(false);// не создавать диалоговое окно номера страницы, когда
 									// печать
 viewer.setPrintLargePdf("d:\test.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу PDF.

--------------------

 Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать OpenPdfFile().|

### printLargePdf(String filePath, PdfPrinterSettings printerSettings) {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(String filePath, PdfPrinterSettings printerSettings)
```


Открывает и печатает большой файл Pdf с указанными настройками принтера. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize ( true);       //распечатать файл с измененным размером
 viewer.setAutoRotate ( true);       //распечатать файл с отрегулированным поворотом
 viewer.setPrintPageDialog ( false);//не создавать диалоговое окно номера страницы при печати
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName());
 viewer.printLargePdf("d:\\test.pdf",ps);
 viewer.closePdfFile();
```

--------------------

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать OpenPdfFile().

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу PDF. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | Настройки принтера. |

### printLargePdf(String filePath, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings) {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void printLargePdf(String filePath, PrintPageSettings pageSettings, PdfPrinterSettings printerSettings)
```


Открывает и печатает большой файл Pdf с указанными параметрами страницы и параметрами принтера. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности.

--------------------

```
PdfViewer viewer = new PdfViewer();
 viewer.setAutoResize(true); // распечатать файл с измененным размером
 viewer.setAutoRotate(true); // распечатать файл с отрегулированным поворотом
 viewer.setPrintPageDialog(false); // не создавать диалоговое окно номера страницы, когда
 				  // печать
 PrinterSettings ps = new PrinterSettings();
 PrintDocument prtdoc = new PrintDocument();
 ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName());
 PageSettings pgs = new PageSettings();
 pgs.setPaperSize(new PaperSize("A4", 827, 1169));
 pgs.setMargins(new Margins(0, 0, 0, 0));
 viewer.printLargePdf("d:\\test.pdf", pgs, ps);
 viewer.closePdfFile();
```

--------------------

Этот метод объединяет открытие и печать файла, и вам не нужно явно вызывать OpenPdfFile().

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу PDF. |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | Настройки страницы. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | Настройки принтера. |

### save(InputStream destStream) {#save-java.io.InputStream-}
```
public void save(InputStream destStream)
```


Сохраняет полученный PDF-документ в потоковом режиме.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.InputStream | Поток выходного PDF-документа. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Сохраняет полученный PDF-документ в файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFile | java.lang.String | Путь к выходному PDF-документу. |

### setAutoResize(boolean value) {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```


Устанавливает логическое значение, указывающее, будет ли файл распечатываться с оптимизированным размером.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение: если false, напечатать страницу без масштабирования страницы. Если true, распечатайте страницу с масштабированием, чтобы соответствовать области печати. |

### setAutoRotate(boolean value) {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```


Устанавливает логическое значение, указывающее, следует ли печатать файл с автоматическим поворотом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setAutoRotateMode(int value) {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```


Задает значение AutoRotateMode, указывающее направление вращения

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент AutoRotateMode |

### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


Устанавливает тип координат страницы (поля Media/Crop). Значение CropBox используется по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PageCoordinateType |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


Устанавливает режим представления формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент FormPresentationMode |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Устанавливает значение, указывающее горизонтальное выравнивание

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент HorizontalAlignment |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Устанавливает пароль входного документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setPrintAsGrayscale(boolean value) {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```


Получает или задает логическое значение, указывающее, печатается ли страница в оттенках серого. По умолчанию ложно.

--------------------

Ложь по умолчанию — это ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setPrintAsImage(boolean value) {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```


Устанавливает режим печати PdfViewer как изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение

--------------------

 Если true, то всегда печатается как изображение (создается изображение, которое печатается). Если false, печатается непосредственно на устройство, если поддерживаются все функции. Если документ содержит неподдерживаемые функции, система может автоматически принять решение о печати в виде изображения. Значение по умолчанию — false.|

### setPrintPageDialog(boolean value) {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```


Задает логическое значение, указывающее, следует ли создавать диалоговое окно номера страницы при печати.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setPrinterJobName(String value) {#setPrinterJobName-java.lang.String-}
```
public void setPrinterJobName(String value)
```


Задает имя документа в очереди печати при печати документа. Значение по умолчанию — имя файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


Устанавливает параметры рендеринга.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | Значение Рендерингоптионс |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


Устанавливает разрешение во время просмотра и печати. Чем выше разрешение, тем ниже скорость. Значение по умолчанию — 150.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setScaleFactor(float value) {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```


Задает значение с плавающей запятой, указывающее коэффициент масштабирования. Значение по умолчанию — 1,0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | значение с плавающей запятой. |

### setShowHiddenAreas(boolean value) {#setShowHiddenAreas-boolean-}
```
public void setShowHiddenAreas(boolean value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setUseIntermidiateImage(boolean value) {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```


Устанавливает использование преобразования страницы pdf в промежуточный файл png при печати в файловом режиме. Используйте его, когда важен размер выходного файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение. |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает значение, указывающее вертикальное выравнивание

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент вертикального выравнивания |

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
