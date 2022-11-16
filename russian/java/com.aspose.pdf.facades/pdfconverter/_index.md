---
title: PdfConverter
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для преобразования PDF-файлов каждой страницы в изображения с поддержкой BMP, JPEG, PNG и TIFF.
type: docs
weight: 37
url: /ru/java/com.aspose.pdf.facades/pdfconverter/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade)
```
public final class PdfConverter extends Facade
```

Представляет класс для преобразования каждой страницы PDF-файла в изображения, поддерживающие BMP, JPEG, PNG и TIFF. Поддерживаемый контент в pdf: картинки, форма, комментарий.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfConverter()](#PdfConverter--) | Инициализирует новый объект PdfConverter. |
| [PdfConverter(IDocument document)](#PdfConverter-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfConverter на основе документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | Связывает поток Pdf для конвертации. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | Связывает файл Pdf для преобразования. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Закройте экземпляр PdfConverter и освободите ресурсы. |
| [convertPageToPNGMemoryStream(Page page)](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Только для внутреннего использования |
| [dispose()](#dispose--) | Закройте экземпляр PdfConverter и освободите ресурсы. |
| [doConvert()](#doConvert--) | Выполните некоторые начальные действия по преобразованию документа PDF в изображения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateType()](#getCoordinateType--) | Получает тип координат страницы (поля мультимедиа/обрезки). |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getEndPage()](#getEndPage--) | Получает конечную позицию, которую вы хотите преобразовать. |
| [getFormPresentationMode()](#getFormPresentationMode--) | Получает режим представления формы. |
| [getNextImage(OutputStream outputStream)](#getNextImage-java.io.OutputStream-) | Сохраняет изображение в поток с форматом изображения по умолчанию - jpeg. |
| [getNextImage(OutputStream outputStream, ImageType format)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Сохраняет изображение в поток с заданным форматом изображения. |
| [getNextImage(OutputStream outputStream, ImageType format, double imageWidth, double imageHeight, int quality)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Сохраняет изображение в поток с заданным форматом, размером и качеством изображения. |
| [getNextImage(OutputStream outputStream, ImageType format, int quality)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Сохраняет изображение в поток с заданным форматом и качеством изображения. |
| [getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Сохраняет изображение в поток с заданным форматом, размером и качеством изображения. |
| [getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight, int quality)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Сохраняет изображение в поток с заданным форматом, размерами и качеством изображения. |
| [getNextImage(OutputStream outputStream, PageSize pageSize)](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Сохраняет изображение в поток с заданным размером страницы. |
| [getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format)](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Сохраняет изображение в поток с заданным размером страницы. |
| [getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format, int quality)](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Сохраняет изображение в поток с заданным размером страницы, форматом изображения и качеством. |
| [getNextImage(String outputFile)](#getNextImage-java.lang.String-) | Сохраняет изображение в файл с форматом изображения по умолчанию - jpeg. |
| [getNextImage(String outputFile, ImageType format)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Сохраняет изображение в файл с заданным форматом изображения. |
| [getNextImage(String outputFile, ImageType format, double imageWidth, double imageHeight, int quality)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | Сохраняет изображение в файл с заданным форматом, размером и качеством изображения. |
| [getNextImage(String outputFile, ImageType format, int quality)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Сохраняет изображение в файл с заданным форматом и качеством изображения. |
| [getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | Сохраняет изображение в файл с заданным форматом и размерами изображения. |
| [getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight, int quality)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | Сохраняет изображение в файл с заданным форматом, размерами и качеством изображения. |
| [getNextImage(String outputFile, PageSize pageSize)](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Сохраняет изображение в файл с заданным размером страницы и форматом изображения по умолчанию - jpeg. |
| [getNextImage(String outputFile, PageSize pageSize, ImageType format)](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Сохраняет изображение в файл с заданным размером страницы и форматом изображения. |
| [getNextImage(String outputFile, PageSize pageSize, ImageType format, int quality)](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Сохраняет изображение в файл с заданным размером страницы, форматом изображения и качеством. |
| [getPageCount()](#getPageCount--) | Получает количество страниц. |
| [getPassword()](#getPassword--) | Получает документ OwnerPassword. |
| [getRenderingOptions()](#getRenderingOptions--) | Получает параметры рендеринга. |
| [getResolution()](#getResolution--) | Получает разрешение во время преобразования. |
| [getStartPage()](#getStartPage--) | Получает начальную позицию, которую вы хотите преобразовать. |
| [getUserPassword()](#getUserPassword--) | Получает документ UserPassword. |
| [hasNextImage()](#hasNextImage--) | Указывает, есть ли в файле PDF больше изображений или нет. |
| [hashCode()](#hashCode--) |  |
| [isShowHiddenAreas()](#isShowHiddenAreas--) | Получает флаг, управляющий видимостью скрытых областей на странице. |
| [mergeImages(List<InputStream> inputImagesStreams, int outputImageFormat, int mergeMode, Integer horizontal, Integer vertical)](#mergeImages-java.util.List-java.io.InputStream--int-int-java.lang.Integer-java.lang.Integer-) | Объединяет список потоков изображений в один поток изображений. |
| [mergeImagesAsTiff(List<InputStream> inputImagesStreams)](#mergeImagesAsTiff-java.util.List-java.io.InputStream--) | Объединяет список потоков TIFF в один поток TIFF с несколькими кадрами. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveAsTIFF(OutputStream outputStream)](#saveAsTIFF-java.io.OutputStream-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF. |
| [saveAsTIFF(OutputStream outputStream, PageSize pageSize)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один поток TIFF. |
| [saveAsTIFF(OutputStream outputStream, PageSize pageSize, TiffSettings settings)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один поток TIFF. |
| [saveAsTIFF(OutputStream outputStream, TiffSettings settings)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF. |
| [saveAsTIFF(OutputStream outputStream, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF. |
| [saveAsTIFF(OutputStream outputStream, int compressionType)](#saveAsTIFF-java.io.OutputStream-int-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight)](#saveAsTIFF-java.io.OutputStream-int-int-) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF. |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings)](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF. |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF. |
| [saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, int compressionType)](#saveAsTIFF-java.io.OutputStream-int-int-int-) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF. |
| [saveAsTIFF(String outputFile)](#saveAsTIFF-java.lang.String-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(String outputFile, PageSize pageSize)](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(String outputFile, PageSize pageSize, TiffSettings settings)](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(String outputFile, TiffSettings settings)](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(String outputFile, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(String outputFile, int compressionType)](#saveAsTIFF-java.lang.String-int-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight)](#saveAsTIFF-java.lang.String-int-int-) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings)](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF. |
| [saveAsTIFF(String outputFile, int imageWidth, int imageHeight, int compressionType)](#saveAsTIFF-java.lang.String-int-int-int-) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF. |
| [saveAsTIFFClassF(OutputStream outputStream)](#saveAsTIFFClassF-java.io.OutputStream-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF ClassF. |
| [saveAsTIFFClassF(OutputStream outputStream, PageSize pageSize)](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF ClassF. |
| [saveAsTIFFClassF(OutputStream outputStream, int imageWidth, int imageHeight)](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF ClassF. |
| [saveAsTIFFClassF(String outputFile)](#saveAsTIFFClassF-java.lang.String-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF ClassF. |
| [saveAsTIFFClassF(String outputFile, PageSize pageSize)](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF ClassF. |
| [saveAsTIFFClassF(String outputFile, int imageWidth, int imageHeight)](#saveAsTIFFClassF-java.lang.String-int-int-) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF ClassF. |
| [setCoordinateType(int value)](#setCoordinateType-int-) | Устанавливает тип координат страницы (поля Media/Crop). |
| [setEndPage(int value)](#setEndPage-int-) | Устанавливает конечную позицию, которую вы хотите преобразовать. |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | Устанавливает режим представления формы. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Устанавливает документ OwnerPassword. |
| [setRangeOfPages(int startPage, int EndPage)](#setRangeOfPages-int-int-) | Устанавливает диапазон страниц, между которыми вы хотите конвертировать. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Устанавливает параметры рендеринга. |
| [setResolution(Resolution value)](#setResolution-com.aspose.pdf.devices.Resolution-) | Устанавливает разрешение во время конвертации. |
| [setShowHiddenAreas(boolean value)](#setShowHiddenAreas-boolean-) |  |
| [setStartPage(int value)](#setStartPage-int-) | Устанавливает начальную позицию, которую вы хотите преобразовать. |
| [setUserPassword(String value)](#setUserPassword-java.lang.String-) | Устанавливает документ UserPassword. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfConverter() {#PdfConverter--}
```
public PdfConverter()
```


Инициализирует новый объект PdfConverter.

### PdfConverter(IDocument document) {#PdfConverter-com.aspose.pdf.IDocument-}
```
public PdfConverter(IDocument document)
```


Инициализирует новый объект PdfConverter на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


Связывает поток Pdf для конвертации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток PDF. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |
| password | java.lang.String | Пароль документа PDF. |

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


Связывает файл Pdf для преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | PDF-файл. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл |
| password | java.lang.String | Пароль документа PDF. |

### close() {#close--}
```
public void close()
```


Закройте экземпляр PdfConverter и освободите ресурсы.

### convertPageToPNGMemoryStream(Page page) {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
```
public System.IO.MemoryStream convertPageToPNGMemoryStream(Page page)
```


Только для внутреннего использования

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Внутренний объект |

**Возвращает:**
com.aspose.ms.System.IO.MemoryStream — внутренний объект
### dispose() {#dispose--}
```
public void dispose()
```


Закройте экземпляр PdfConverter и освободите ресурсы.

Этот метод устарел, вместо него используйте close().

### doConvert() {#doConvert--}
```
public void doConvert()
```


Выполните некоторые начальные действия по преобразованию документа PDF в изображения.

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf("D:\\Test\\test.pdf");
  converter.doConvert();
  String prefix = "D:\\Test\\";
  String suffix = ".jpg";
  int imageCount = 1;
  while (converter.hasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix);
  	imageCount++;
  }
```

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
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


Получает тип координат страницы (поля мультимедиа/обрезки). Значение CropBox используется по умолчанию.

**Возвращает:**
int - элемент PageCoordinateType
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getEndPage() {#getEndPage--}
```
public int getEndPage()
```


Получает конечную позицию, которую вы хотите преобразовать.

**Возвращает:**
интервал - целочисленное значение
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Получает режим представления формы.

**Возвращает:**
int - режим представления формы.
### getNextImage(OutputStream outputStream) {#getNextImage-java.io.OutputStream-}
```
public void getNextImage(OutputStream outputStream)
```


Сохраняет изображение в поток с форматом изображения по умолчанию - jpeg.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения. |

### getNextImage(OutputStream outputStream, ImageType format) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public void getNextImage(OutputStream outputStream, ImageType format)
```


Сохраняет изображение в поток с заданным форматом изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |

### getNextImage(OutputStream outputStream, ImageType format, double imageWidth, double imageHeight, int quality) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
```
public void getNextImage(OutputStream outputStream, ImageType format, double imageWidth, double imageHeight, int quality)
```


Сохраняет изображение в поток с заданным форматом, размером и качеством изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| imageWidth | double | Ширина изображения, единица измерения — пиксель. |
| imageHeight | double | Высота изображения, единица измерения — пиксель. |
| quality | int | Качество файла Jpeg (0~100), 0 — самый низкий уровень, а 100 — самый высокий. |

### getNextImage(OutputStream outputStream, ImageType format, int quality) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
```
public void getNextImage(OutputStream outputStream, ImageType format, int quality)
```


Сохраняет изображение в поток с заданным форматом и качеством изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| quality | int | Качество файла Jpeg (0~100), 0 — самый низкий уровень, а 100 — самый высокий. |

### getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
```
public void getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight)
```


Сохраняет изображение в поток с заданным форматом, размером и качеством изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |

### getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight, int quality) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
```
public void getNextImage(OutputStream outputStream, ImageType format, int imageWidth, int imageHeight, int quality)
```


Сохраняет изображение в поток с заданным форматом, размерами и качеством изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |
| quality | int | Качество файла Jpeg (0~100), 0 — самый низкий уровень, а 100 — самый высокий. |

### getNextImage(OutputStream outputStream, PageSize pageSize) {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public void getNextImage(OutputStream outputStream, PageSize pageSize)
```


Сохраняет изображение в поток с заданным размером страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |

### getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format) {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
```
public void getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format)
```


Сохраняет изображение в поток с заданным размером страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |

### getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format, int quality) {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
```
public void getNextImage(OutputStream outputStream, PageSize pageSize, ImageType format, int quality)
```


Сохраняет изображение в поток с заданным размером страницы, форматом изображения и качеством.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| quality | int | Качество файла Jpeg (0~100), 0 — самый низкий уровень, а 100 — самый высокий. |

### getNextImage(String outputFile) {#getNextImage-java.lang.String-}
```
public void getNextImage(String outputFile)
```


Сохраняет изображение в файл с форматом изображения по умолчанию - jpeg.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения изображения. |

### getNextImage(String outputFile, ImageType format) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
```
public void getNextImage(String outputFile, ImageType format)
```


Сохраняет изображение в файл с заданным форматом изображения.

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.DoConvert();
  String prefix = @"D:\Test\";
  String suffix = ".png";
  int imageCount = 1;
  while (converter.HasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png);
  	imageCount++;
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |

### getNextImage(String outputFile, ImageType format, double imageWidth, double imageHeight, int quality) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
```
public void getNextImage(String outputFile, ImageType format, double imageWidth, double imageHeight, int quality)
```


Сохраняет изображение в файл с заданным форматом, размером и качеством изображения.

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.doConvert();
  String prefix = @"D:\Test\";
  String suffix = ".jpg";
  int imageCount = 1;
  float pixelX=800f;
  float pixelY=600f;
  while (converter.HasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
  	imageCount++;
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| imageWidth | double | Ширина изображения, единица измерения — пиксели. |
| imageHeight | double | Высота изображения, единица измерения — пиксели. |
| quality | int | Качество файла Jpeg (0~100), 0 — самый низкий уровень, а 100 — самый высокий. |

### getNextImage(String outputFile, ImageType format, int quality) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
```
public void getNextImage(String outputFile, ImageType format, int quality)
```


Сохраняет изображение в файл с заданным форматом и качеством изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| quality | int | Качество файла Jpeg (0~100), 0 — самый низкий уровень, а 100 — самый высокий. |

### getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
```
public void getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight)
```


Сохраняет изображение в файл с заданным форматом и размерами изображения.

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf("D:\\Test\\test.pdf");
  converter.DoConvert();
  String prefix = "D:\\Test\\";
  String suffix = ".jpg";
  int imageCount = 1;
  while (converter.hasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
  	imageCount++;
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |

### getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight, int quality) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
```
public void getNextImage(String outputFile, ImageType format, int imageWidth, int imageHeight, int quality)
```


Сохраняет изображение в файл с заданным форматом, размерами и качеством изображения.

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.doConvert();
  String prefix = @"D:\Test\";
  String suffix = ".jpg";
  int imageCount = 1;
  while (converter.HasNextImage())
  {
  	converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
  	imageCount++;
  }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |
| quality | int | Качество файла Jpeg (0~100), 0 — самый низкий уровень, а 100 — самый высокий. |

### getNextImage(String outputFile, PageSize pageSize) {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
```
public void getNextImage(String outputFile, PageSize pageSize)
```


Сохраняет изображение в файл с заданным размером страницы и форматом изображения по умолчанию - jpeg.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения изображения. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |

### getNextImage(String outputFile, PageSize pageSize, ImageType format) {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
```
public void getNextImage(String outputFile, PageSize pageSize, ImageType format)
```


Сохраняет изображение в файл с заданным размером страницы и форматом изображения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения изображения. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |

### getNextImage(String outputFile, PageSize pageSize, ImageType format, int quality) {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
```
public void getNextImage(String outputFile, PageSize pageSize, ImageType format, int quality)
```


Сохраняет изображение в файл с заданным размером страницы, форматом изображения и качеством.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Путь и имя файла для сохранения изображения. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Формат изображения. |
| quality | int | Качество файла Jpeg (0~100), 0 — самый низкий уровень, а 100 — самый высокий. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получает количество страниц.

**Возвращает:**
интервал - целочисленное значение
### getPassword() {#getPassword--}
```
public String getPassword()
```


Получает документ OwnerPassword.

**Возвращает:**
java.lang.String — строковое значение
### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


Получает параметры рендеринга.

**Возвращает:**
[RenderingOptions](../../com.aspose.pdf/renderingoptions) - варианты рендеринга.
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Получает разрешение во время преобразования. Чем выше разрешение, тем ниже скорость конвертации. Значение по умолчанию — 150.

**Возвращает:**
[Resolution](../../com.aspose.pdf.devices/resolution) - Элемент разрешения
### getStartPage() {#getStartPage--}
```
public int getStartPage()
```


Получает начальную позицию, которую вы хотите преобразовать. Минимальное значение равно 1.

**Возвращает:**
интервал - целочисленное значение
### getUserPassword() {#getUserPassword--}
```
public String getUserPassword()
```


Получает документ UserPassword.

**Возвращает:**
java.lang.String — строковое значение
### hasNextImage() {#hasNextImage--}
```
public boolean hasNextImage()
```


Указывает, есть ли в файле PDF больше изображений или нет.

**Возвращает:**
boolean - Может ли получить больше изображений или нет, true, если может, или false.
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


Получает флаг, управляющий видимостью скрытых областей на странице. Метод устарел.

**Возвращает:**
boolean - логическое значение
### mergeImages(List<InputStream> inputImagesStreams, int outputImageFormat, int mergeMode, Integer horizontal, Integer vertical) {#mergeImages-java.util.List-java.io.InputStream--int-int-java.lang.Integer-java.lang.Integer-}
```
public static InputStream mergeImages(List<InputStream> inputImagesStreams, int outputImageFormat, int mergeMode, Integer horizontal, Integer vertical)
```


Объединяет список потоков изображений в один поток изображений. Поддерживаются выходные форматы Png/jpg/tiff, в случае использования неподдерживаемого формата выходной поток закодирован как Jpeg по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputImagesStreams | java.util.List<java.io.InputStream> | Список потоков изображений для слияния. |
| outputImageFormat | int | Формат вывода изображения для объединенного потока. |
| mergeMode | int | Режим слияния. Используется для форматов Png/Jpg. |
| horizontal | java.lang.Integer | Горизонтальное соотношение для установки ширины холста для выходного потока изображения. Используется только для форматов Png/Jpg с ImageMergeMode.Center. |
| vertical | java.lang.Integer | Отношение по вертикали для установки высоты холста для выходного потока изображения. Используется только для форматов Png/Jpg с ImageMergeMode.Center. |

**Возвращает:**
java.io.InputStream — поток изображений, закодированный как выходной формат изображения.
### mergeImagesAsTiff(List<InputStream> inputImagesStreams) {#mergeImagesAsTiff-java.util.List-java.io.InputStream--}
```
public static InputStream mergeImagesAsTiff(List<InputStream> inputImagesStreams)
```


Объединяет список потоков TIFF в один поток TIFF с несколькими кадрами.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputImagesStreams | java.util.List<java.io.InputStream> | Список tiff-потоков. |

**Возвращает:**
java.io.InputStream — поток tiff из нескольких кадров.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveAsTIFF(OutputStream outputStream) {#saveAsTIFF-java.io.OutputStream-}
```
public void saveAsTIFF(OutputStream outputStream)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |

### saveAsTIFF(OutputStream outputStream, PageSize pageSize) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public void saveAsTIFF(OutputStream outputStream, PageSize pageSize)
```


Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один поток TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |

### saveAsTIFF(OutputStream outputStream, PageSize pageSize, TiffSettings settings) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(OutputStream outputStream, PageSize pageSize, TiffSettings settings)
```


Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один поток TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Объект настроек, определяющий параметры TIFF. |

### saveAsTIFF(OutputStream outputStream, TiffSettings settings) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(OutputStream outputStream, TiffSettings settings)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Объект настроек, определяющий параметры TIFF. |

### saveAsTIFF(OutputStream outputStream, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(OutputStream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Объект настроек, определяющий параметры TIFF. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### saveAsTIFF(OutputStream outputStream, int compressionType) {#saveAsTIFF-java.io.OutputStream-int-}
```
public void saveAsTIFF(OutputStream outputStream, int compressionType)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Выходной поток. |
| compressionType | int | Тип сжатия. |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight) {#saveAsTIFF-java.io.OutputStream-int-int-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight)
```


Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings) {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```


Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Объект настроек, определяющий параметры TIFF. |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)
```


Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Объект настроек, определяющий параметры TIFF. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, int compressionType) {#saveAsTIFF-java.io.OutputStream-int-int-int-}
```
public void saveAsTIFF(OutputStream outputStream, int imageWidth, int imageHeight, int compressionType)
```


Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |
| compressionType | int | Тип сжатия. |

### saveAsTIFF(String outputFile) {#saveAsTIFF-java.lang.String-}
```
public void saveAsTIFF(String outputFile)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.doConvert();
  converter.saveAsTIFF(@"D:\Test\test.tiff");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Файл для сохранения изображения TIFF. |

### saveAsTIFF(String outputFile, PageSize pageSize) {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
```
public void saveAsTIFF(String outputFile, PageSize pageSize)
```


Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один файл TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Имя файла для сохранения изображения TIFF |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |

### saveAsTIFF(String outputFile, PageSize pageSize, TiffSettings settings) {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(String outputFile, PageSize pageSize, TiffSettings settings)
```


Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один файл TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Имя файла для сохранения изображения TIFF |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Объект настроек, определяющий параметры TIFF. |

### saveAsTIFF(String outputFile, TiffSettings settings) {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(String outputFile, TiffSettings settings)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Имя файла для сохранения изображения TIFF |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки. |

### saveAsTIFF(String outputFile, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(String outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Имя файла для сохранения изображения TIFF |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Настройки. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### saveAsTIFF(String outputFile, int compressionType) {#saveAsTIFF-java.lang.String-int-}
```
public void saveAsTIFF(String outputFile, int compressionType)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF.

--------------------

```
PdfConverter converter = new PdfConverter();
 converter.bindPdf(@"D:\Test\test.pdf");
 converter.doConvert();
 converter.saveAsTIFF(@"D:\Test\test.tiff");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Выходной файл. |
| compressionType | int | Тип сжатия. |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight) {#saveAsTIFF-java.lang.String-int-int-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight)
```


Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Имя файла для сохранения изображения TIFF |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings) {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```


Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Имя файла для сохранения изображения TIFF |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Объект настроек, определяющий параметры TIFF. |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter) {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)
```


Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Имя файла для сохранения изображения TIFF |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Объект настроек, определяющий параметры TIFF. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | Внешний преобразователь |

### saveAsTIFF(String outputFile, int imageWidth, int imageHeight, int compressionType) {#saveAsTIFF-java.lang.String-int-int-int-}
```
public void saveAsTIFF(String outputFile, int imageWidth, int imageHeight, int compressionType)
```


Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Имя файла для сохранения изображения TIFF |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |
| compressionType | int | Тип сжатия. |

### saveAsTIFFClassF(OutputStream outputStream) {#saveAsTIFFClassF-java.io.OutputStream-}
```
public void saveAsTIFFClassF(OutputStream outputStream)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF ClassF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |

### saveAsTIFFClassF(OutputStream outputStream, PageSize pageSize) {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
```
public void saveAsTIFFClassF(OutputStream outputStream, PageSize pageSize)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF ClassF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |

### saveAsTIFFClassF(OutputStream outputStream, int imageWidth, int imageHeight) {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
```
public void saveAsTIFFClassF(OutputStream outputStream, int imageWidth, int imageHeight)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF ClassF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Поток для сохранения изображения TIFF. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |

### saveAsTIFFClassF(String outputFile) {#saveAsTIFFClassF-java.lang.String-}
```
public void saveAsTIFFClassF(String outputFile)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF ClassF.

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf("D:\\Test\\test.pdf");
  converter.doConvert();
  converter.saveAsTIFFClassF("D:\\Test\\test.tiff");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Поток для сохранения изображения TIFF. |

### saveAsTIFFClassF(String outputFile, PageSize pageSize) {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
```
public void saveAsTIFFClassF(String outputFile, PageSize pageSize)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF ClassF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Поток для сохранения изображения TIFF. |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Размер страницы изображения. |

### saveAsTIFFClassF(String outputFile, int imageWidth, int imageHeight) {#saveAsTIFFClassF-java.lang.String-int-int-}
```
public void saveAsTIFFClassF(String outputFile, int imageWidth, int imageHeight)
```


Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF ClassF.

--------------------

```
PdfConverter converter = new PdfConverter();
  converter.bindPdf(@"D:\Test\test.pdf");
  converter.doConvert();
  converter.saveAsTIFFClassF(@"D:\Test\test.tiff",204,196);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | java.lang.String | Поток для сохранения изображения TIFF. |
| imageWidth | int | Ширина изображения, единица измерения — пиксель. |
| imageHeight | int | Высота изображения, единица измерения — пиксель. |

### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


Устанавливает тип координат страницы (поля Media/Crop). Значение CropBox используется по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PageCoordinateType |

### setEndPage(int value) {#setEndPage-int-}
```
public void setEndPage(int value)
```


Устанавливает конечную позицию, которую вы хотите преобразовать.
используйте setEndPage(int) перед setStartPage(int)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


Устанавливает режим представления формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | режим представления формы. |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


Устанавливает документ OwnerPassword.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setRangeOfPages(int startPage, int EndPage) {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```


Устанавливает диапазон страниц, между которыми вы хотите конвертировать.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| startPage | int | целое значение |
| EndPage | int | целое значение |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


Устанавливает параметры рендеринга.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | варианты рендеринга. |

### setResolution(Resolution value) {#setResolution-com.aspose.pdf.devices.Resolution-}
```
public void setResolution(Resolution value)
```


Устанавливает разрешение во время конвертации. Чем выше разрешение, тем ниже скорость конвертации. Значение по умолчанию — 150.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Resolution](../../com.aspose.pdf.devices/resolution) | Элемент разрешения |

### setShowHiddenAreas(boolean value) {#setShowHiddenAreas-boolean-}
```
public void setShowHiddenAreas(boolean value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setStartPage(int value) {#setStartPage-int-}
```
public void setStartPage(int value)
```


Устанавливает начальную позицию, которую вы хотите преобразовать. Минимальное значение равно 1.
используйте setEndPage(int) перед setStartPage(int)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setUserPassword(String value) {#setUserPassword-java.lang.String-}
```
public void setUserPassword(String value)
```


Устанавливает документ UserPassword.

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
