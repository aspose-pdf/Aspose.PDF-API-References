---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfConverter. Представляет класс для конвертации каждой страницы pdf файла в изображения, поддерживающие BMP, JPEG, PNG и TIFF. Поддерживаемый контент в pdf изображения, формы, комментарии.
type: docs
weight: 4440
url: /ru/net/aspose.pdf.facades/pdfconverter/
---
## Класс PdfConverter

Представляет класс для конвертации каждой страницы pdf файла в изображения, поддерживающие BMP, JPEG, PNG и TIFF. Поддерживаемый контент в pdf: изображения, формы, комментарии.

```csharp
public sealed class PdfConverter : Facade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Инициализирует новый объект `PdfConverter`. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Инициализирует новый объект `PdfConverter` на основе *документа*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Получает или задает конечную позицию, которую вы хотите конвертировать. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Получает или задает режим представления формы. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Получает количество страниц. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Получает или задает OwnerPassword документа. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Получает или задает разрешение во время конвертации. Чем выше разрешение, тем медленнее скорость конвертации. Значение по умолчанию - 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Получает или задает начальную позицию, которую вы хотите конвертировать. Минимальное значение - 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Получает или задает UserPassword документа. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Привязывает поток Pdf для конвертации. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Привязывает файл Pdf для конвертации. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Закрывает экземпляр PdfConverter и освобождает ресурсы. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Уничтожает фасад. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Выполняет некоторые начальные работы для конвертации pdf документа в изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Сохраняет изображение в поток с форматом изображения по умолчанию - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Сохраняет изображение в файл с форматом изображения по умолчанию - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Сохраняет изображение в поток с заданным форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Сохраняет изображение в поток с заданным размером страницы. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Сохраняет изображение в файл с заданным форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Сохраняет изображение в файл с заданным размером страницы и форматом изображения по умолчанию - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Сохраняет изображение в поток с заданным форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Сохраняет изображение в поток с заданным размером страницы. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Сохраняет изображение в файл с заданным форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Сохраняет изображение в файл с заданным размером страницы и форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Сохраняет изображение в поток с заданным форматом изображения, размером и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Сохраняет изображение в поток с заданным размером страницы, форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Сохраняет изображение в файл с заданным форматом изображения и размерами. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Сохраняет изображение в файл с заданным размером страницы, форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Сохраняет изображение в поток с заданным форматом изображения, размером и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Сохраняет изображение в поток с заданным форматом изображения, размерами и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Сохраняет изображение в файл с заданным форматом изображения, размером изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Сохраняет изображение в файл с заданным форматом изображения, размерами и качеством. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Указывает, есть ли у pdf файла еще изображения или нет. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF поток. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Конвертирует каждую страницу pdf документа в изображения с размером страницы и сохраняет изображения в один TIFF поток. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF поток. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Конвертирует каждую страницу pdf документа в изображения с размером страницы и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Конвертирует каждую страницу pdf документа в изображения с размерами и сохраняет изображения в один TIFF поток. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Конвертирует каждую страницу pdf документа в изображения с размером страницы и сохраняет изображения в один TIFF поток. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF поток. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Конвертирует каждую страницу pdf документа в изображения с размерами и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Конвертирует каждую страницу pdf документа в изображения с размером страницы и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Конвертирует каждую страницу pdf документа в изображения с размерами и сохраняет изображения в один TIFF поток. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Конвертирует каждую страницу pdf документа в изображения с размерами и сохраняет изображения в один TIFF поток. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Конвертирует каждую страницу pdf документа в изображения с размерами и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Конвертирует каждую страницу pdf документа в изображения с размерами и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Конвертирует каждую страницу pdf документа в изображения с размерами и сохраняет изображения в один TIFF поток. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Конвертирует каждую страницу pdf документа в изображения с размерами и сохраняет изображения в один TIFF файл. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF ClassF поток. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF ClassF файл. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF ClassF поток. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF ClassF файл. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF ClassF поток. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Конвертирует каждую страницу pdf документа в изображения и сохраняет изображения в один TIFF ClassF файл. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Объединяет список потоков изображений в один поток изображения. Поддерживаются форматы вывода Png/jpg/tiff, в случае использования неподдерживаемого формата выходной поток кодируется как Jpeg по умолчанию. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Объединяет список потоков tiff в один многокадровый tiff поток. |

### См. также

* класс [Facade](../facade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)