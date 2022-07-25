---
title: PdfFileStamp
second_title: Aspose.PDF для справочника API .NET
description: Класс для добавления штампов водяных знаков или фона в файлы PDF.
type: docs
weight: 2580
url: /ru/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Класс для добавления штампов (водяных знаков или фона) в файлы PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileStamp](pdffilestamp#constructor)() | Конструктор PdfFileStamp. Входной и выходной файлы могут быть указаны через соответствующие свойства. |
| [PdfFileStamp](pdffilestamp#constructor_1)(Document) | Инициализирует новый[`PdfFileStamp`](../pdffilestamp) объект на базе*document* . |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname) { get; set; } | Получает или задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition) { get; set; } | Получает или задает способ хранения содержимого при сохранении результата операции в объекте HttpResponse. Возможное значение: встроенный / вложение. По умолчанию: встроенный. |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto) { set; } | Устанавливает формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, то файл будет сохранен в формате PDF по умолчанию без преобразования. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity) { get; set; } | Сохраняет безопасность, если true. (Эта функция будет реализована в следующих версиях). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle) { get; set; } | Получает или задает стиль нумерации страниц. Возможные значения: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize) { get; set; } | Получает или устанавливает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить результирующий размер файла, но может привести к замедлению выполнения и увеличению требований к памяти. Значение по умолчанию: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight) { get; } | Получает высоту первой страницы исходного файла. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation) { get; set; } | Получает или задает чередование номеров страниц. Вращение в градусах. По умолчанию 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth) { get; } | Получает ширину первой страницы во входном файле. |
| [Response](../../aspose.pdf.facades/pdffilestamp/response) { get; set; } | Получает или задает объект Response, в котором будет храниться результат операции. |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions) { get; set; } | Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: PdfSaveOptions. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid) { get; set; } | Идентификатор штампа следующего добавленного штампа (включая заголовки страниц/гудок/номера страниц). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber) { get; set; } | Получает или задает начальный номер первой страницы во входном файле. Следующие страницы будут нумероваться, начиная с этого значения. Например, если для StartingNumber установлено значение 100, страницы документа будут иметь номера 100, 101, 102... |

## Методы

| Имя | Описание |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter)(FormattedText, float) | Добавляет нижний колонтитул на страницы документа. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_2)(Stream, float) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_4)(string, float) | Добавляет изображение в качестве нижнего колонтитула на страницы документа. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_1)(FormattedText, float, float, float) | Добавляет нижний колонтитул на страницы документа. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_3)(Stream, float, float, float) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter#addfooter_5)(string, float, float, float) | Добавляет изображение в качестве нижнего колонтитула страниц. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader)(FormattedText, float) | Добавляет заголовок на страницу. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_2)(Stream, float) | Добавляет изображение в качестве заголовка на страницы. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_4)(string, float) | Добавляет изображение в качестве заголовка к страницам файла. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_1)(FormattedText, float, float, float) | Добавляет заголовок к страницам файла. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_3)(Stream, float, float, float) | Добавляет изображение вверху страницы. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader#addheader_5)(string, float, float, float) | Добавляет изображение в качестве заголовка на страницы. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber)(FormattedText) | Добавляет номер страницы к странице. Номер страницы может содержать знак #, который будет заменен номером страницы. Номер страницы помещается внизу страницы по центру по горизонтали. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_4)(string) | Добавить номер страницы в файл. Текст номера страницы может содержать знак #, который будет заменен номером страницы. Номер страницы размещается внизу страницы по центру горизонтально. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_1)(FormattedText, int) | Добавляет номер страницы к страницам. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_5)(string, int) | Добавляет номер страницы к страницам. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_3)(FormattedText, float, float) | Добавляет номер страницы в указанную позицию на странице. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_7)(string, float, float) | Добавляет номер страницы в указанную позицию на странице. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_2)(FormattedText, int, float, float, float, float) | Добавляет номер страницы к страницам документа. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber#addpagenumber_6)(string, int, float, float, float, float) | Добавляет номер страницы к страницам документа. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp)(Stamp) | Добавляет штамп к файлу. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Инициализирует фасад. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close)() | Закрывает открытые файлы и сохраняет изменения. Предупреждение. Если указаны входные или выходные потоки, они не закрываются методом Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save)(Stream) | Сохраняет документ в указанный поток. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save#save_1)(string) | Сохраняет результат в указанный файл. |

## Поля

| Имя | Описание |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft) | Нижнее левое положение. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle) | Нижнее среднее положение. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright) | Нижнее правое положение. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft) | Левая позиция. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright) | Правильное положение. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft) | Верхняя позиция. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle) | Верхнее среднее положение. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright) | Правое верхнее положение. |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
