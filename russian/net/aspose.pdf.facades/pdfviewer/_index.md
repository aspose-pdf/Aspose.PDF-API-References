---
title: "Класс PdfViewer"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Facades.PdfViewer class. Класс, представляющий возможность просмотра или печати PDF."
type: docs
weight: 4750
url: /ru/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

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
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Получает или задает значение типа bool, указывающее, будет ли файл печататься с оптимизированным размером. Если false, печать страницы без масштабирования. Если true, печать страницы с масштабированием для соответствия печатной области. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Получает или задает значение типа bool, указывающее, будет ли файл печататься с автоматическим вращением. |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Получает или задает значение AutoRotateMode, указывающее направление вращения. |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Получает или задает режим отображения формы. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Получает или задает значение, указывающее горизонтальное выравнивание. |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Получает количество страниц текущего PDF‑файла. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Получает или задает пароль входного документа. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Получает или задает значение типа bool, указывающее, печатается ли страница в градациях серого. По умолчанию false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Задает или получает режим печати PdfViewer в виде изображения. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Получает или задает имя документа в очереди принтера при печати. Значение по умолчанию — имя файла. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Получает или задает значение типа bool, указывающее, выводить ли диалог номера страницы при печати. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Получает результат печати. Если успешно — null; в противном случае объект исключения. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Получает или задает разрешение при просмотре и печати. Чем выше разрешение, тем медленнее скорость. Значение по умолчанию — 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Получает или задает значение с плавающей запятой, указывающее коэффициент масштабирования. Значение по умолчанию — 1,0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Получает/задает использование конвертации страницы pdf в промежуточный png‑файл при печати в файловом режиме. Используйте это, когда важен размер выходного файла. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Получает или задает значение, указывающее вертикальное выравнивание. |

## Методы

| Имя | Описание |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Инициализирует фасад. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Инициализирует фасад. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Инициализирует фасад. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Закрывает фасад. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Получить страницы текущего pdf файла. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Декодирует страницу одного Pdf файла. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Освобождает ресурсы фасада. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Получает настройки страницы по умолчанию. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Получает настройки принтера по умолчанию. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Печатает Pdf документ, используя принтер по умолчанию. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Печатает Pdf документ с настройками принтера. Размер выходной страницы будет соответствовать размеру первой страницы документа. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Печатает Pdf документ с настройками. Если размер документа не соответствует размеру страницы, он будет расширен до размера страницы. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Печатает Pdf документ с диалогом настройки. Выберите принтер с помощью диалога. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Открывает и печатает большой Pdf поток. Если ваш Pdf файл содержит сотни страниц или более, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Открывает и печатает большой Pdf файл. Если ваш Pdf файл содержит сотни страниц или более, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Открывает и печатает большой Pdf поток с указанными настройками принтера. Если ваш Pdf файл содержит сотни страниц или более, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Открывает и печатает большой Pdf файл с указанными настройками принтера. Если ваш Pdf файл содержит сотни страниц или более, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Открывает и печатает большой Pdf поток с указанными настройками страницы и принтера. Если ваш Pdf файл содержит сотни страниц или более, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Открывает и печатает большой Pdf файл с указанными настройками страницы и принтера. Если ваш Pdf файл содержит сотни страниц или более, или его размер превышает 3 МБ, рекомендуется использовать этот метод для повышения производительности. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Сохраняет полученный PDF документ в поток. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Сохраняет полученный PDF документ в файл. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments)(params Document[]) | Печатает несколько PDF документов, используя принтер по умолчанию и настройки страницы. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_7)(params Stream[]) | Печатает несколько PDF документов из предоставленных потоков, используя принтер по умолчанию и настройки страницы. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_8)(params string[]) | Печатает несколько PDF документов, используя принтер по умолчанию и настройки страницы. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_1)(PrinterSettings, params Document[]) | Печатает несколько PDF документов, используя указанные настройки принтера. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_5)(PrinterSettings, params Stream[]) | Печатает несколько PDF‑документов из предоставленных потоков, используя указанные настройки принтера. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_6)(PrinterSettings, params string[]) | Печатает несколько PDF документов, используя указанные настройки принтера. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_2)(PrinterSettings, PageSettings, params Document[]) | Печатает несколько PDF‑документов, используя указанные настройки принтера и страницы. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_3)(PrinterSettings, PageSettings, params Stream[]) | Печатает несколько PDF‑документов из предоставленных потоков, используя указанные настройки принтера и страницы. |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_4)(PrinterSettings, PageSettings, params string[]) | Печатает несколько PDF‑документов, используя указанные настройки принтера и страницы. |

## События

| Имя | Описание |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Происходит до начала печати и позволяет предоставить пользовательские обработчики печати вместо стандартного. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | Происходит, когда печать страницы завершается в PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Добавляет/удаляет подписку на событие печати последней страницы. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Добавляет/удаляет подписку на событие печати последней страницы. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Происходит перед началом печати страницы. |

### См. также

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


