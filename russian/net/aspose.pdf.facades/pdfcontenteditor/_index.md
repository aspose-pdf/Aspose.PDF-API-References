---
title: "Класс PdfContentEditor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.PdfContentEditor. Представляет класс для редактирования содержимого PDF‑файлов."
type: docs
weight: 4550
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

Представляет класс для редактирования содержимого PDF‑файла.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor/#constructor)() | Конструктор объекта PdfContentEditor. |
| [PdfContentEditor](pdfcontenteditor/#constructor_1)(Document) | Инициализирует новый объект `PdfContentEditor` на основе *document*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy/) { get; set; } | Набор параметров для операции замены текста |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions/) { get; set; } | Получает или задает параметры редактирования текста. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions/) { get; set; } | Получает или задает параметры замены текста. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions/) { get; set; } | Получает или задает параметры поиска текста. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/)(string, string) | Добавляет дополнительное действие для события документа. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment_1)(string, string) | Добавляет вложение документа без аннотации. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment)(Stream, string, string) | Добавляет вложение документа без аннотации. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_1)(Stream) | Привязывает поток PDF для редактирования. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_2)(string) | Привязывает PDF‑файл для редактирования. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/)(int) | Изменяет предпочтения просмотра. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close/)() | Закрывает открытый документ. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink)(Rectangle, string, int) | Создаёт ссылку для запуска приложения в PDF‑документе. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_1)(Rectangle, string, int, Color) | Создаёт ссылку для запуска приложения в PDF‑документе. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | Создаёт ссылку для запуска приложения в PDF‑документе. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/)(string, Color, bool, bool, string, string, string) | Создаёт закладку с указанным действием. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret/)(int, Rectangle, Rectangle, string, string, Color) | Создаёт аннотацию‑каретку. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/)(Rectangle, int, Color, Enum[]) | Создаёт ссылку на пользовательские действия в PDF‑документе. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_2)(Rectangle, string, string, int, string) | Создаёт аннотацию‑вложение файла. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment)(Rectangle, string, Stream, string, int, string) | Создаёт аннотацию‑вложение файла. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_3)(Rectangle, string, string, int, string, double) | Создаёт аннотацию‑вложение файла. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Создаёт аннотацию‑вложение файла. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext/)(Rectangle, string, int) | Создаёт аннотацию свободного текста в PDF‑документе |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/)(string, Rectangle, int, Color) | Создаёт ссылку на JavaScript в PDF‑документе. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline/)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Создаёт линейную аннотацию. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink)(Rectangle, int, int) | Создаёт локальную ссылку в PDF‑документе. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_1)(Rectangle, int, int, Color) | Создаёт локальную ссылку в PDF‑документе. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | Создаёт локальную ссылку в PDF‑документе. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup/)(Rectangle, string, int, int, Color) | Создаёт разметочную аннотацию в PDF‑документе. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie/)(Rectangle, string, int) | Создаёт аннотации Movie. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink)(Rectangle, string, int, int) | Создаёт ссылку на страницу другого PDF‑документа. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Создаёт ссылку на страницу другого PDF‑документа. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Создаёт ссылку на страницу другого PDF‑документа. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon/)(LineInfo, int, Rectangle, string) | Создаёт полигональную аннотацию. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline/)(LineInfo, int, Rectangle, string) | Создаёт полилинейную аннотацию. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup/)(Rectangle, string, bool, int) | Создаёт всплывающую аннотацию в PDF‑документе. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp)(int, Rectangle, string, Color, Stream) | Создаёт аннотацию‑штамп. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_1)(int, Rectangle, string, Color, string) | Создаёт аннотацию‑штамп. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_2)(int, Rectangle, string, string, Color) | Создаёт аннотацию‑штамп. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound/)(Rectangle, string, string, int, string) | Создаёт звуковые аннотации. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle/)(Rectangle, string, Color, bool, int, int) | Создаёт аннотацию квадрат‑круг. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext/)(Rectangle, string, string, bool, string, int) | Создаёт текстовую аннотацию в PDF‑документе |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink)(Rectangle, string, int) | Создаёт веб‑ссылку в PDF‑документе. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_1)(Rectangle, string, int, Color) | Создаёт веб‑ссылку в PDF‑документе. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_2)(Rectangle, string, int, Color, Enum[]) | Создаёт веб‑ссылку в PDF‑документе. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments/)() | Удаляет все вложения в PDF‑документе. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage)() | Удаляет все изображения из PDF‑документа. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage_1)(int, int[]) | Удаляет указанные изображения на указанной странице. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp/)(int, int[]) | Удаляет несколько штампов на указанной странице по индексам штампов. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid)(int) | Удалить штамп по ID со всех страниц документа. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid_1)(int, int) | Удаляет штамп на указанной странице по ID штампа. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids_1)(int[]) | Удаляет штампы с указанными ID со всех страниц документа. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids)(int, int[]) | Удаляет штампы на указанной странице по нескольким ID штампов. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve/)(LineInfo, int, Rectangle, string) | Создает аннотацию кривой. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink/)() | Извлекает коллекцию экземпляров Link, содержащихся в PDF‑документе. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps/)(int) | Возвращает массив штампов на странице. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference/)() | Возвращает предпочтение просмотра. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid/)(int, int) | Скрывает штамп. После скрытия видимость штампа может быть восстановлена методом ShowStampById. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp/)(int, int, double, double) | Изменяет позицию штампа на странице. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid/)(int, int, double, double) | Изменяет позицию штампа на странице. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/)() | Удаляет действие открытия из документа. Эта операция полезна при объединении нескольких документов, использующих явное действие 'GoTo' при запуске. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage/)(int, int, string) | Заменяет указанное изображение на указанной странице PDF‑документа другим изображением. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_2)(string, string) | Заменяет текст в PDF‑файле. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext)(string, int, string) | Заменяет текст в PDF‑файле на указанной странице. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_4)(string, string, int) | Заменяет текст в PDF‑файле и задает размер шрифта. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_3)(string, string, TextState) | Заменяет текст в PDF‑файле, используя указанный объект [`TextState`](../../aspose.pdf.text/textstate/). |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_1)(string, int, string, TextState) | Заменяет текст в PDF‑файле на указанной странице. Объект [`TextState`](../../aspose.pdf.text/textstate/) (семейство шрифтов, цвет) может быть указан для заменяемого текста. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Сохраняет PDF‑документ в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Сохраняет PDF‑документ в указанный файл. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid/)(int, int) | Отображает штамп, который был скрыт методом HiddenStampById. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose/) | Тип события документа. Закрывает документ. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen/) | Тип события документа. Открывает документ. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted/) | Тип события документа. Выполняет действие после печати. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved/) | Тип события документа. Выполняет действие после сохранения. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint/) | Тип события документа. Выполняет действие перед печатью. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave/) | Тип события документа. Выполняет действие перед сохранением. |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


