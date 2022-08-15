---
title: PdfViewer
second_title: Aspose.PDF для справочника API .NET
description: Представляет класс для просмотра или печати PDF-файла.
type: docs
weight: 2640
url: /ru/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

Представляет класс для просмотра или печати PDF-файла.

```csharp
public sealed class PdfViewer : IFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfViewer](pdfviewer#constructor)() | Инициализирует новый[`PdfViewer`](../pdfviewer) объект. |
| [PdfViewer](pdfviewer#constructor_1)(Document) | Инициализирует новый[`PdfViewer`](../pdfviewer) объект. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize) { get; set; } | Получает или задает логическое значение, указывающее, будет ли файл распечатан с оптимизированным размером.  Если false, напечатать страницу без масштабирования страницы. Если true, напечатать страницу с масштабированием, чтобы оно соответствовало области печати. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate) { get; set; } | Получает или задает логическое значение, указывающее, следует ли печатать файл с автоматическим поворотом |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode) { get; set; } | Получает или задает значение AutoRotateMode, указывающее направление вращения |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype) { get; set; } | Получает или задает тип координат страницы (поля мультимедиа/обрезки). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode) { get; set; } | Получает или задает режим представления формы. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment) { get; set; } | Получает или задает значение, указывающее горизонтальное выравнивание |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount) { get; } | Получает количество страниц текущего файла Pdf. |
| [Password](../../aspose.pdf.facades/pdfviewer/password) { get; set; } | Получает или устанавливает пароль входного документа. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale) { get; set; } | Получает или задает логическое значение, указывающее, печатается ли страница в оттенках серого. По умолчанию false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage) { get; set; } | Устанавливает или получает режим печати PdfViewer как изображения. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname) { get; set; } | Получает или задает имя документа в очереди печати при печати документа. Значение по умолчанию — имя файла. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog) { get; set; } | Получает или задает логическое значение, указывающее, следует ли создавать диалоговое окно номера страницы при печати. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus) { get; } | Получает результат задания на печать. Если успех, чем ноль; в противном случае объект исключения. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution) { get; set; } | Получает или задает разрешение при просмотре и печати. Чем выше разрешение, тем ниже скорость. Значение по умолчанию: 150. . |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor) { get; set; } | Получает или задает значение с плавающей запятой, указывающее коэффициент масштабирования. Значение по умолчанию: 1.0. . |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage) { get; set; } | Получает/задает использование преобразования страницы pdf в промежуточный файл png при печати в файловом режиме. Используйте его, когда важен размер выходного файла. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment) { get; set; } | Получает или задает значение, указывающее вертикальное выравнивание |

## Методы

| Имя | Описание |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf)(Document) | Инициализирует фасад. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_1)(Stream) | Инициализирует фасад. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_2)(string) | Инициализирует фасад. |
| [Close](../../aspose.pdf.facades/pdfviewer/close)() | Закрывает фасад. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages)() | Получить страницы текущего pdf-файла. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage)(int) | Декодирует страницу одного файла Pdf. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose)() | Удаляет ресурсы фасада. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings)() | Получает настройки страницы по умолчанию. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings)() | Получает настройки принтера по умолчанию. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument)() | Печать документа Pdf на принтере по умолчанию. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings_1)(PrinterSettings) | Печать документа Pdf с настройками принтера. Размер выходной страницы будет соответствовать размеру первой страницы документа. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings)(PageSettings, PrinterSettings) | Печать документа Pdf с настройками. Если размер документа не соответствует размеру страницы, pdf.kit расширит его до размера страницы. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup)() | Печать документа Pdf с диалоговым окном настройки. Выберите принтер в диалоговом окне. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf)(Stream) | Открывает и печатает большой поток PDF. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_3)(string) | Открывает и печатает большой файл PDF. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_2)(Stream, PrinterSettings) | Открывает и печатает большой поток Pdf с указанными настройками принтера. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_5)(string, PrinterSettings) | Открывает и печатает большой файл PDF с указанными настройками принтера. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Открывает и печатает большой поток PDF с указанными настройками страницы и настройками принтера. Если ваш файл Pdf содержит сотни страниц и более или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности . |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_4)(string, PageSettings, PrinterSettings) | Открывает и печатает большой файл Pdf с заданными настройками страницы и настройками принтера. Если ваш файл Pdf содержит сотни страниц или более или его размер превышает 3 МБ, рекомендуется использовать этот метод, чтобы повысить производительность. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save)(Stream) | Сохраняет полученный PDF-документ в поток. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save_1)(string) | Сохраняет результирующий PDF-документ в файл. |

### Смотрите также

* interface [IFacade](../ifacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
