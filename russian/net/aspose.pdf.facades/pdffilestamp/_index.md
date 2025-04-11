---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfFileStamp. Класс для добавления штампов, водяных знаков или фона к PDF-файлам
type: docs
weight: 4570
url: /ru/net/aspose.pdf.facades/pdffilestamp/
---
## Класс PdfFileStamp

Класс для добавления штампов (водяных знаков или фона) к PDF-файлам.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Конструктор PdfFileStamp. Входной файл и выходной файл могут быть указаны через соответствующие свойства. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Инициализирует новый объект `PdfFileStamp` на основе *документа*. |

## Свойства

| Название | Описание |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Устанавливает формат PDF-файла. Результирующий файл будет сохранен в указанном формате файла. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без конвертации. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Сохраняет безопасность, если true. (Эта функция будет реализована в следующих версиях). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Получает или устанавливает стиль нумерации страниц. Возможные значения: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Получает или устанавливает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить размер результирующего файла, но может привести к более медленному выполнению и большим требованиям к памяти. Значение по умолчанию: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Получает высоту первой страницы во входном файле. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Получает или устанавливает поворот номера страницы. Поворот в градусах. Значение по умолчанию - 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Получает ширину первой страницы во входном файле. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | Идентификатор штампа следующего добавленного штампа (включая заголовки/колонтитулы страниц/номера страниц). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Получает или устанавливает начальный номер для первой страницы во входном файле. Следующие страницы будут нумероваться, начиная с этого значения. Например, если StartingNumber установлен на 100, страницы документа будут иметь номера 100, 101, 102... |

## Методы

| Название | Описание |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Добавляет нижний колонтитул на страницы документа. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Добавляет изображение в качестве нижнего колонтитула на страницы документа. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Добавляет нижний колонтитул на страницы документа. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Добавляет изображение в качестве нижнего колонтитула на страницы. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Добавляет верхний колонтитул на страницу. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Добавляет изображение в качестве верхнего колонтитула на страницах. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Добавляет изображение в качестве верхнего колонтитула на страницы файла. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Добавляет верхний колонтитул на страницы файла. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Добавляет изображение в верхней части страницы. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Добавляет изображение в качестве верхнего колонтитула на страницы. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Добавляет номер страницы на страницу. Номер страницы может содержать знак #, который будет заменен на номер страницы. Номер страницы размещается внизу страницы по центру. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Добавляет номер страницы в файл. Текст номера страницы может содержать знак #, который будет заменен на номер страницы. Номер страницы размещается внизу страницы по центру. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Добавляет номер страницы на страницы. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Добавляет номер страницы на страницы. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Добавляет номер страницы в указанной позиции на странице. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Добавляет номер страницы в указанной позиции на странице. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Добавляет номер страницы на страницы документа. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Добавляет номер страницы на страницы документа. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Добавляет штамп в файл. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Закрывает открытые файлы и сохраняет изменения. Внимание. Если входные или выходные потоки указаны, они не закрываются методом Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Сохраняет документ в указанный поток. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Сохраняет результат в указанный файл. |

## Поля

| Название | Описание |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Позиция внизу слева. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Позиция внизу по центру. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Позиция внизу справа. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Позиция слева. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Позиция справа. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Позиция вверху слева. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Позиция вверху по центру. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Позиция вверху справа. |

### См. также

* класс [SaveableFacade](../saveablefacade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)