---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfViewer. Представляет класс для просмотра или печати pdf
type: docs
weight: 4630
url: /ru/net/aspose.pdf.facades/pdfviewer/
---
## Класс PdfViewer

Представляет класс для просмотра или печати pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Инициализирует новый объект `PdfViewer`. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Инициализирует новый объект `PdfViewer`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Получает или задает значение типа bool, которое указывает, будет ли файл напечатан с оптимизированным размером. Если false, печатать страницу без масштабирования. Если true, печатать страницу с масштабированием, чтобы она соответствовала печатной области. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Получает или задает значение типа bool, которое указывает, будет ли файл напечатан с автоматическим поворотом. |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Получает или задает значение AutoRotateMode, которое указывает направление поворота. |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Получает или задает режим представления формы. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Получает или задает значение, которое указывает горизонтальное выравнивание. |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Получает количество страниц текущего Pdf файла. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Получает или задает пароль для входного документа. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Получает или задает значение типа bool, которое указывает, будет ли страница напечатана в градациях серого. По умолчанию false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Устанавливает или получает режим для PdfViewer, чтобы печатать как изображение. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Получает или задает имя документа в очереди печати, когда документ печатается. Значение по умолчанию - имя файла. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Получает или задает значение типа bool, которое указывает, следует ли выводить диалог номера страницы при печати. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Получает результат задания печати. Если успешно, то null; в противном случае объект исключения. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Получает или задает разрешение при просмотре и печати. Чем выше разрешение, тем медленнее скорость. Значение по умолчанию - 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Получает или задает значение с плавающей точкой, которое указывает коэффициент масштабирования. Значение по умолчанию - 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Получает/задает использование преобразования страницы pdf в промежуточный png файл во время печати в файловом режиме. Используйте это, когда размер выходного файла важен. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Получает или задает значение, которое указывает вертикальное выравнивание. |

## Методы

| Имя | Описание |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Инициализирует фасад. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Инициализирует фасад. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Инициализирует фасад. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Закрывает фасад. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Получает страницы текущего pdf файла. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Декодирует страницу одного Pdf файла. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Освобождает ресурсы фасада. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Получает настройки страницы по умолчанию. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Получает настройки принтера по умолчанию. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Печатает Pdf документ с использованием принтера по умолчанию. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Печатает Pdf документ с настройками принтера. Размер выходной страницы будет соответствовать размеру первой страницы документа. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Печатает Pdf документ с настройками. Если размер документа не соответствует размеру страницы, он будет увеличен, чтобы соответствовать размеру страницы. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Печатает Pdf документ с диалогом настройки. Выберите принтер с помощью диалога. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Открывает и печатает большой поток Pdf. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, этот метод рекомендуется для достижения лучшей производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Открывает и печатает большой Pdf файл. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, этот метод рекомендуется для достижения лучшей производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Открывает и печатает большой поток Pdf с указанными настройками принтера. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, этот метод рекомендуется для достижения лучшей производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Открывает и печатает большой Pdf файл с указанными настройками принтера. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, этот метод рекомендуется для достижения лучшей производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Открывает и печатает большой поток Pdf с указанными настройками страницы и принтера. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, этот метод рекомендуется для достижения лучшей производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Открывает и печатает большой Pdf файл с указанными настройками страницы и принтера. Если ваш Pdf файл содержит сотни страниц или больше, или его размер превышает 3 МБ, этот метод рекомендуется для достижения лучшей производительности. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Сохраняет результирующий PDF документ в поток. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Сохраняет результирующий PDF документ в файл. |

## События

| Имя | Описание |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Происходит перед началом печати и позволяет предоставить пользовательские обработчики печати вместо стандартного. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | Происходит, когда печать страницы заканчивается в PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Добавляет/удаляет подписку на событие печати последней страницы. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Добавляет/удаляет подписку на событие печати последней страницы. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Происходит перед началом печати страницы. |

### См. также

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)