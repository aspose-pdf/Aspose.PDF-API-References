---
title: "Класс PdfConverter"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Facades.PdfConverter класс. Представляет класс для конвертации каждой страницы PDF‑файла в изображения, поддерживая BMP, JPEG, PNG и TIFF. Поддерживаемый контент в PDF‑изображениях из комментариев."
type: docs
weight: 4560
url: /ru/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Представляет класс для преобразования каждой Page pdf‑файла в изображения, сейчас поддерживает BMP, JPEG, PNG и TIFF. Поддерживаемое содержимое в pdf: изображения, формы, комментарии.

```csharp
public sealed class PdfConverter : Facade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | Инициализирует новый объект `PdfConverter`. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | Инициализирует новый объект `PdfConverter` на основе *document*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | Получает или задаёт конечную позицию, которую вы хотите конвертировать. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | Получает или задает режим отображения формы. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | Получает количество страниц. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | Получает или задаёт документ OwnerPassword. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | Получает или задаёт разрешение при конвертации. Чем выше разрешение, тем медленнее скорость конвертации. Значение по умолчанию — 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | Получает или задаёт начальную позицию, которую вы хотите конвертировать. Минимальное значение — 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | Получает или задаёт документ UserPassword. |

## Методы

| Имя | Описание |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf)(Document) | Привязывает PDF‑документ к экземпляру `PdfConverter` для дальнейшей обработки. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | Привязывает поток Pdf для конвертации. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | Привязывает PDF‑файл для конвертации. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | Закрывает экземпляр PdfConverter и освобождает ресурсы. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | Выполняет некоторые начальные работы по конвертации PDF‑документа в изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | Сохраняет изображение в поток с форматом изображения по умолчанию — jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | Сохраняет изображение в файл с форматом изображения по умолчанию — jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | Сохраняет изображение в поток с указанным форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | Сохраняет изображение в поток с указанным размером страницы. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | Сохраняет изображение в файл с указанным форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | Сохраняет изображение в файл с указанным размером страницы и форматом изображения по умолчанию — jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | Сохраняет изображение в поток с заданным форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | Сохраняет изображение в поток с указанным размером страницы. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | Сохраняет изображение в файл с заданным форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | Сохраняет изображение в файл с заданным размером страницы и форматом изображения. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | Сохраняет изображение в поток с указанным форматом изображения, размером и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Сохраняет изображение в поток с заданным размером страницы, форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | Сохраняет изображение в файл с заданным форматом изображения и размерами. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | Сохраняет изображение в файл с заданным размером страницы, форматом изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | Сохраняет изображение в поток с указанным форматом изображения, размером и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | Сохраняет изображение в поток с указанным форматом изображения, размерами и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | Сохраняет изображение в файл с указанным форматом изображения, размером изображения и качеством. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | Сохраняет изображение в файл с заданным форматом изображения, размерами и качеством. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | Указывает, содержит ли pdf‑файл дополнительные изображения или нет. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | Преобразует каждую страницу pdf‑документа в изображения с указанием размера страницы и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | Преобразует каждую страницу pdf‑документа в изображения с указанием размера страницы и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | Преобразует каждую страницу pdf‑документа в изображения с указанием размера страницы и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | Преобразует каждую страницу pdf‑документа в изображения с указанием размера страницы и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один файл TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один поток TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Преобразует каждую страницу pdf‑документа в изображения с размерами и сохраняет их в один файл TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один поток TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | Преобразует каждую страницу pdf‑документа в изображения и сохраняет их в один файл TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Объединяет список потоков изображений в один поток изображения. Поддерживаются форматы вывода Png/jpg/tiff; при использовании неподдерживаемого формата поток вывода по умолчанию кодируется как Jpeg. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | Объединяет список tiff‑потоков в один многокадровый tiff‑поток. |

### См. также

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


