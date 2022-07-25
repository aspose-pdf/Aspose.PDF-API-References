---
title: PdfConverter
second_title: Aspose.PDF для справочника API .NET
description: Представляет класс для преобразования каждой страницы pdf-файла в изображения с поддержкой форматов BMP JPEG PNG и TIFF. Поддерживаемый контент в pdf изображения формы комментарии.
type: docs
weight: 2450
url: /ru/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Представляет класс для преобразования каждой страницы pdf-файла в изображения с поддержкой форматов BMP, JPEG, PNG и TIFF. Поддерживаемый контент в pdf: изображения, формы, комментарии.

```csharp
public sealed class PdfConverter : Facade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfConverter](pdfconverter#constructor)() | Инициализирует новый[`PdfConverter`](../pdfconverter) объект. |
| [PdfConverter](pdfconverter#constructor_1)(Document) | Инициализирует новый[`PdfConverter`](../pdfconverter) объект на базе*document* . |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype) { get; set; } | Получает или задает тип координат страницы (поля мультимедиа/обрезки). Значение CropBox используется по умолчанию. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage) { get; set; } | Получает или задает конечную позицию, которую вы хотите преобразовать. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode) { get; set; } | Получает или задает режим представления формы. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount) { get; } | Получает количество страниц. |
| [Password](../../aspose.pdf.facades/pdfconverter/password) { get; set; } | Получает или задает документ OwnerPassword. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution) { get; set; } | Получает или устанавливает разрешение во время преобразования. Чем выше разрешение, тем медленнее скорость конвертации. Значение по умолчанию: 150. . |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage) { get; set; } | Получает или задает начальную позицию, которую вы хотите преобразовать. Минимальное значение 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword) { get; set; } | Получает или задает документ UserPassword. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_1)(Stream) | Привязывает поток PDF для конвертации. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_2)(string) | Привязывает файл PDF для конвертации. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close)() | Закройте экземпляр PdfConverter и освободите ресурсы. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert)() | Выполните некоторые начальные действия по преобразованию документа PDF в изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage)(Stream) | Сохраняет изображение в поток с форматом изображения по умолчанию - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_9)(string) | Сохраняет изображение в файл с форматом изображения по умолчанию - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_4)(Stream, ImageFormat) | Сохраняет изображение в поток с заданным форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_1)(Stream, PageSize) | Сохраняет изображение в поток с заданным размером страницы. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_13)(string, ImageFormat) | Сохраняет изображение в файл с заданным форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_10)(string, PageSize) | Сохраняет изображение в файл с заданным размером страницы и форматом изображения по умолчанию - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_6)(Stream, ImageFormat, int) | Сохраняет изображение в поток с заданным форматом и качеством изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_2)(Stream, PageSize, ImageFormat) | Сохраняет изображение в поток с заданным размером страницы. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_15)(string, ImageFormat, int) | Сохраняет изображение в файл с заданным форматом и качеством изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_11)(string, PageSize, ImageFormat) | Сохраняет изображение в файл с заданным размером страницы и форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_7)(Stream, ImageFormat, int, int) | Сохраняет изображение в поток с заданным форматом, размером и качеством изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Сохраняет изображение в поток с заданным размером страницы, форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_16)(string, ImageFormat, int, int) | Сохраняет изображение в файл с указанным форматом и размерами изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_12)(string, PageSize, ImageFormat, int) | Сохраняет изображение в файл с заданным размером страницы, форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_5)(Stream, ImageFormat, double, double, int) | Сохраняет изображение в поток с заданным форматом, размером и качеством изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_8)(Stream, ImageFormat, int, int, int) | Сохраняет изображение в поток с заданным форматом, размерами и качеством изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_14)(string, ImageFormat, double, double, int) | Сохраняет изображение в файл с заданным форматом изображения, размером и качеством изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_17)(string, ImageFormat, int, int, int) | Сохраняет изображение в файл с заданным форматом, размерами и качеством изображения. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage)() | Указывает, есть ли в файле PDF больше изображений или нет. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff)(Stream) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_10)(string) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_1)(Stream, CompressionType) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_4)(Stream, PageSize) | Преобразует каждую страницу pdf-документа в изображения с размером страницы и сохраняет изображения в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_2)(Stream, TiffSettings) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_11)(string, CompressionType) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_14)(string, PageSize) | Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_12)(string, TiffSettings) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_6)(Stream, int, int) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_5)(Stream, PageSize, TiffSettings) | Преобразует каждую страницу pdf-документа в изображения с размером страницы и сохраняет изображения в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_16)(string, int, int) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_15)(string, PageSize, TiffSettings) | Преобразует каждую страницу документа PDF в изображения с размером страницы и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_7)(Stream, int, int, CompressionType) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_8)(Stream, int, int, TiffSettings) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_17)(string, int, int, CompressionType) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_18)(string, int, int, TiffSettings) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Преобразует каждую страницу документа PDF в изображения с размерами и сохраняет изображения в один файл TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf)(Stream) | Преобразует каждую страницу pdf-документа в изображения и сохраняет изображения в один поток TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_3)(string) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_1)(Stream, PageSize) | Преобразует каждую страницу pdf-документа в изображения и сохраняет изображения в один поток TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_4)(string, PageSize) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_2)(Stream, int, int) | Преобразует каждую страницу pdf-документа в изображения и сохраняет изображения в один поток TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_5)(string, int, int) | Преобразует каждую страницу документа PDF в изображения и сохраняет изображения в один файл TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Объединяет список потоков изображений в один поток изображений. Поддерживаются выходные форматы Png/jpg/tiff, в случае использования неподдерживаемого формата выходной поток закодирован как Jpeg по умолчанию. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff)(List&lt;Stream&gt;) | Объединяет список потоков TIFF в один поток TIFF с несколькими кадрами. |

### Смотрите также

* class [Facade](../facade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
