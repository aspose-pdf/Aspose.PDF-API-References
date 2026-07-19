---
title: "Aspose::Pdf::Facades::PdfContentEditor class"
linktitle: "PdfContentEditor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor class. Представляет класс для редактирования содержимого PDF‑файла на C++."
type: docs
weight: 1700
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class


Представляет класс для редактирования содержимого PDF‑файла.

```cpp
class PdfContentEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddDocumentAdditionalAction](./adddocumentadditionalaction/)(const System::String\&, const System::String\&) | Добавляет дополнительное действие для события документа. |
| [AddDocumentAttachment](./adddocumentattachment/)(const System::String\&, const System::String\&) | Добавляет вложение документа без аннотации. |
| [AddDocumentAttachment](./adddocumentattachment/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::String\&) | Добавляет вложение документа без аннотации. |
| [BindPdf](./bindpdf/)(System::String) override | Привязывает PDF‑файл для редактирования. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Привязывает поток PDF для редактирования. |
| [ChangeViewerPreference](./changeviewerpreference/)(int32_t) | Изменяет предпочтения просмотра. |
| [Close](./close/)() override | Закрывает открытый документ. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Создаёт ссылку для запуска приложения в PDF‑документе. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) | Создаёт ссылку для запуска приложения в PDF‑документе. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Создаёт ссылку для запуска приложения в PDF‑документе. |
| [CreateBookmarksAction](./createbookmarksaction/)(const System::String\&, System::Drawing::Color, bool, bool, const System::String\&, const System::String\&, const System::String\&) | Создаёт закладку с указанным действием. |
| [CreateCaret](./createcaret/)(int32_t, System::Drawing::Rectangle, System::Drawing::Rectangle, const System::String\&, const System::String\&, System::Drawing::Color) | Создаёт аннотацию каретки. |
| [CreateCustomActionLink](./createcustomactionlink/)(System::Drawing::Rectangle, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Создаёт ссылку на пользовательские действия в PDF‑документе. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&) | Создаёт аннотацию вложения файла. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&, double) | Создаёт аннотацию вложения файла. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&) | Создаёт аннотацию вложения файла. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&, double) | Создаёт аннотацию вложения файла. |
| [CreateFreeText](./createfreetext/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Создаёт аннотацию свободного текста в PDF‑документе. |
| [CreateJavaScriptLink](./createjavascriptlink/)(const System::String\&, System::Drawing::Rectangle, int32_t, System::Drawing::Color) | Создаёт ссылку на JavaScript в PDF‑документе. |
| [CreateLine](./createline/)(System::Drawing::Rectangle, const System::String\&, float, float, float, float, int32_t, int32_t, System::Drawing::Color, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<System::String\>\&) | Создаёт линейную аннотацию. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Создаёт локальную ссылку в PDF‑документе. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color) | Создаёт локальную ссылку в PDF‑документе. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t) | Создаёт локальную ссылку в PDF‑документе. |
| [CreateMarkup](./createmarkup/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color) | Создаёт разметочную аннотацию в PDF‑документе. |
| [CreateMovie](./createmovie/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Создаёт Movie [Annotations](../../aspose.pdf.annotations/). |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Создаёт ссылку на страницу другого PDF‑документа. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color) | Создаёт ссылку на страницу другого PDF‑документа. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t) | Создаёт ссылку на страницу другого PDF‑документа. |
| [CreatePolygon](./createpolygon/)(const System::SharedPtr\<LineInfo\>\&, int32_t, System::Drawing::Rectangle, const System::String\&) | Создаёт полигональную аннотацию. |
| [CreatePolyLine](./createpolyline/)(const System::SharedPtr\<LineInfo\>\&, int32_t, System::Drawing::Rectangle, const System::String\&) | Создаёт полилинейную аннотацию. |
| [CreatePopup](./createpopup/)(System::Drawing::Rectangle, const System::String\&, bool, int32_t) | Создаёт всплывающую аннотацию в PDF‑документе. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, const System::String\&, const System::String\&, System::Drawing::Color) | Создаёт аннотацию штампа. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::String\&) | Создаёт аннотацию штампа. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::SharedPtr\<System::IO::Stream\>\&) | Создаёт аннотацию штампа. |
| [CreateSound](./createsound/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&) | Создаёт Sound [Annotations](../../aspose.pdf.annotations/). |
| [CreateSquareCircle](./createsquarecircle/)(System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, bool, int32_t, int32_t) | Создает аннотацию квадрат‑круг. |
| [CreateText](./createtext/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, bool, const System::String\&, int32_t) | Создает текстовую аннотацию в PDF‑документе. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Создает веб‑ссылку в PDF‑документе. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) | Создает веб‑ссылку в PDF‑документе. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Создает веб‑ссылку в PDF‑документе. |
| [DeleteAttachments](./deleteattachments/)() | Удаляет все вложения в PDF‑документе. |
| [DeleteImage](./deleteimage/)(int32_t, const System::ArrayPtr\<int32_t\>\&) | Удаляет указанные изображения на указанной странице. |
| [DeleteImage](./deleteimage/)() | Удаляет все изображения из PDF‑документа. |
| [DeleteStamp](./deletestamp/)(int32_t, const System::ArrayPtr\<int32_t\>\&) | Удаляет несколько штампов на указанной странице по индексам штампов. |
| [DeleteStampById](./deletestampbyid/)(int32_t, int32_t) | Удаляет штамп на указанной странице по ID штампа. |
| [DeleteStampById](./deletestampbyid/)(int32_t) | Удаляет штамп по ID со всех страниц документа. |
| [DeleteStampByIds](./deletestampbyids/)(const System::ArrayPtr\<int32_t\>\&) | Удаляет штампы с указанными ID со всех страниц документа. |
| [DeleteStampByIds](./deletestampbyids/)(int32_t, const System::ArrayPtr\<int32_t\>\&) | Удаляет штампы на указанной странице по нескольким ID штампов. |
| [DrawCurve](./drawcurve/)(const System::SharedPtr\<LineInfo\>\&, int32_t, System::Drawing::Rectangle, const System::String\&) | Создает аннотацию кривой. |
| [ExtractLink](./extractlink/)() | Извлекает коллекцию экземпляров Link, содержащихся в PDF‑документе. |
| [get_ReplaceTextStrategy](./get_replacetextstrategy/)() const | Набор параметров для операции замены текста. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Получает параметры редактирования текста. |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Получает параметры замены текста. |
| [get_TextSearchOptions](./get_textsearchoptions/)() const | Получает параметры поиска текста. |
| [GetStamps](./getstamps/)(int32_t) | Возвращает массив штампов на странице. |
| [GetViewerPreference](./getviewerpreference/)() | Возвращает предпочтение просмотра. |
| [HideStampById](./hidestampbyid/)(int32_t, int32_t) | Скрывает штамп. После скрытия видимость штампа может быть восстановлена методом ShowStampById. |
| [MoveStamp](./movestamp/)(int32_t, int32_t, double, double) | Изменяет позицию штампа на странице. |
| [MoveStampById](./movestampbyid/)(int32_t, int32_t, double, double) | Изменяет позицию штампа на странице. |
| [PdfContentEditor](./pdfcontenteditor/)() | Конструктор объекта [PdfContentEditor](./). |
| [PdfContentEditor](./pdfcontenteditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfContentEditor](./) на основе *document*. |
| [RemoveDocumentOpenAction](./removedocumentopenaction/)() | Удаляет действие открытия из документа. Эта операция полезна при объединении нескольких документов, использующих явное действие 'GoTo' при запуске. |
| [ReplaceImage](./replaceimage/)(int32_t, int32_t, const System::String\&) | Заменяет указанное изображение на указанной странице PDF‑документа другим изображением. |
| [ReplaceText](./replacetext/)(const System::String\&, int32_t, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) | Заменяет текст в PDF‑файле на указанной странице. Объект [TextState](../) (семейство шрифтов, цвет) может быть указан для заменяемого текста. |
| [ReplaceText](./replacetext/)(const System::String\&, const System::String\&) | Заменяет текст в PDF‑файле. |
| [ReplaceText](./replacetext/)(const System::String\&, int32_t, const System::String\&) | Заменяет текст в PDF‑файле на указанной странице. |
| [ReplaceText](./replacetext/)(const System::String\&, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) | Заменяет текст в PDF‑файле, используя указанный объект [TextState](../). |
| [ReplaceText](./replacetext/)(const System::String\&, const System::String\&, int32_t) | Заменяет текст в PDF‑файле и задаёт размер шрифта. |
| [set_ReplaceTextStrategy](./set_replacetextstrategy/)(const System::SharedPtr\<Aspose::Pdf::Facades::ReplaceTextStrategy\>\&) | Набор параметров для операции замены текста. |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Устанавливает параметры редактирования текста. |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>\&) | Устанавливает параметры замены текста. |
| [set_TextSearchOptions](./set_textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Устанавливает параметры поиска текста. |
| [ShowStampById](./showstampbyid/)(int32_t, int32_t) | Отображает штамп, скрытый с помощью HiddenStampById. |
## Поля

| Поле | Описание |
| --- | --- |
| static [DocumentClose](./documentclose/) | Тип события документа. Закрывает документ. |
| static [DocumentOpen](./documentopen/) | Тип события документа. Открывает документ. |
| static [DocumentPrinted](./documentprinted/) | Тип события документа. Выполняет действие после печати. |
| static [DocumentSaved](./documentsaved/) | Тип события документа. Выполняет действие после сохранения. |
| static [DocumentWillPrint](./documentwillprint/) | Тип события документа. Выполняет действие перед печатью. |
| static [DocumentWillSave](./documentwillsave/) | Тип события документа. Выполняет действие перед сохранением. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
