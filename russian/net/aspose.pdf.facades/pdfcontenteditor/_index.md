---
title: PdfContentEditor
second_title: Aspose.PDF для справочника API .NET
description: Представляет класс для редактирования содержимого файла PDF.
type: docs
weight: 2440
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

Представляет класс для редактирования содержимого файла PDF.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor#constructor)() | Конструктор объекта PdfContentEditor. |
| [PdfContentEditor](pdfcontenteditor#constructor_1)(Document) | Инициализирует новый[`PdfContentEditor`](../pdfcontenteditor) объект на базе*document* . |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy) { get; set; } | Набор параметров для операции замены текста |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions) { get; set; } | Получает или задает параметры редактирования текста. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions) { get; set; } | Получает или задает параметры замены текста. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions) { get; set; } | Получает или задает параметры текстового поиска. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction)(string, string) | Добавляет дополнительное действие для события документа. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment_1)(string, string) | Добавляет вложение к документу без аннотации. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment)(Stream, string, string) | Добавляет вложение к документу без аннотации. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_1)(Stream) | Связывает поток PDF для редактирования. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_2)(string) | Связывает файл PDF для редактирования. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference)(int) | Изменяет настройки просмотра. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close)() | Закрывает открытый документ. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink)(Rectangle, string, int) | Создает ссылку для запуска приложения в документе PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_1)(Rectangle, string, int, Color) | Создает ссылку для запуска приложения в документе PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | Создает ссылку для запуска приложения в документе PDF. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction)(string, Color, bool, bool, string, string, string) | Создает закладку с указанным действием. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret)(int, Rectangle, Rectangle, string, string, Color) | Создает аннотацию курсора. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink)(Rectangle, int, Color, Enum[]) | Создает ссылку на дополнительные действия в документе PDF. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_2)(Rectangle, string, string, int, string) | Создает аннотацию вложенного файла. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment)(Rectangle, string, Stream, string, int, string) | Создает аннотацию вложенного файла. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_3)(Rectangle, string, string, int, string, double) | Создает аннотацию вложенного файла. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Создает аннотацию вложенного файла. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext)(Rectangle, string, int) | Создает аннотацию произвольного текста в документе PDF |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink)(string, Rectangle, int, Color) | Создает ссылку на JavaScript в документе PDF. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Создает аннотацию строки. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink)(Rectangle, int, int) | Создает локальную ссылку в документе PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_1)(Rectangle, int, int, Color) | Создает локальную ссылку в документе PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | Создает локальную ссылку в документе PDF. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup)(Rectangle, string, int, int, Color) | Создает аннотацию разметки в документе PDF. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie)(Rectangle, string, int) | Создает аннотации к фильмам. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink)(Rectangle, string, int, int) | Создает ссылку на другую страницу документа PDF. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Создает ссылку на другую страницу документа PDF. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Создает ссылку на другую страницу документа PDF. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon)(LineInfo, int, Rectangle, string) | Создает полигональную аннотацию. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline)(LineInfo, int, Rectangle, string) | Создает полилинейную аннотацию. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup)(Rectangle, string, bool, int) | Создает всплывающую аннотацию в документе PDF. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp)(int, Rectangle, string, Color, Stream) | Создает аннотацию в виде штампа. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_1)(int, Rectangle, string, Color, string) | Создает аннотацию в виде штампа. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_2)(int, Rectangle, string, string, Color) | Создает аннотацию в виде штампа. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound)(Rectangle, string, string, int, string) | Создает звуковые аннотации. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle)(Rectangle, string, Color, bool, int, int) | Создает аннотацию квадрат-круг. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext)(Rectangle, string, string, bool, string, int) | Создает текстовую аннотацию в документе PDF |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink)(Rectangle, string, int) | Создает веб-ссылку в документе PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_1)(Rectangle, string, int, Color) | Создает веб-ссылку в документе PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_2)(Rectangle, string, int, Color, Enum[]) | Создает веб-ссылку в документе PDF. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments)() | Удаляет все вложения в документе PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage)() | Удаляет все изображения из документа PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage_1)(int, int[]) | Удаляет указанные изображения на указанной странице. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp)(int, int[]) | Удаляет несколько штампов на указанной странице по индексам штампов. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid)(int) | Удалить штамп по ID со всех страниц документа. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid_1)(int, int) | Удаляет штамп на указанной странице по идентификатору штампа. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids_1)(int[]) | Удаляет штампы с указанными идентификаторами со всех страниц документа. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids)(int, int[]) | Удаляет штампы на указанной странице по нескольким идентификаторам штампов. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve)(LineInfo, int, Rectangle, string) | Создает аннотацию кривой. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink)() | Извлекает коллекцию экземпляров ссылок, содержащихся в документе PDF. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps)(int) | Возвращает массив штампов на странице. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference)() | Возвращает настройки просмотра. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid)(int, int) | Скрывает штамп. После скрытия видимость штампа можно восстановить с помощью метода ShowStampById. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp)(int, int, double, double) | Изменяет положение штампа на странице. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid)(int, int, double, double) | Изменяет положение штампа на странице. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction)() | Удаляет открытое действие из документа. Эта операция полезна при объединении нескольких документов, использующих явное действие «Перейти» при запуске. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage)(int, int, string) | Заменяет указанное изображение на указанной странице документа PDF другим изображением. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_2)(string, string) | Заменяет текст в файле PDF. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext)(string, int, string) | Заменяет текст в файле PDF на указанной странице. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_4)(string, string, int) | Заменяет текст в файле PDF и устанавливает размер шрифта. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_3)(string, string, TextState) | Заменяет текст в файле PDF, используя указанный[`TextState`](../../aspose.pdf.text/textstate) объект. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_1)(string, int, string, TextState) | Заменяет текст в файле PDF на указанной странице.[`TextState`](../../aspose.pdf.text/textstate) объект (семейство шрифтов, цвет) может быть указан для заменяемого текста. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Сохраняет документ PDF в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Сохраняет документ PDF в указанный файл. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid)(int, int) | Показывает штамп, который был скрыт HiddenStampById. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose) | Тип события документа. Закрывает документ. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen) | Тип события документа. Открывает документ. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted) | Тип события документа. Выполнить действие после печати. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved) | Тип события документа. Выполнить действие после сохранения. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint) | Тип события документа. Выполнить действие перед печатью. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave) | Тип события документа. Выполнить действие перед сохранением. |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
