---
title: PdfFileInfo
second_title: Aspose.PDF для справочника API .NET
description: Представляет класс для доступа к метаинформации документа PDF.
type: docs
weight: 2530
url: /ru/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

Представляет класс для доступа к метаинформации документа PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileInfo](pdffileinfo#constructor)() | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo со значениями по умолчанию. |
| [PdfFileInfo](pdffileinfo#constructor_1)(Document) | Инициализирует новый[`PdfFileInfo`](../pdffileinfo)объект на основе*document*. |
| [PdfFileInfo](pdffileinfo#constructor_2)(Stream) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_4)(string) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_3)(Stream, string) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo#constructor_5)(string, string) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author) { get; set; } | Получает или задает информацию об авторе документа PDF. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate) { get; set; } | Получает или задает информацию о дате создания PDF-документа. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator) { get; set; } | Получает или задает информацию о создателе документа PDF. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection) { get; } | Возвращает true, если текущий входной файл является файлом «Портфолио», содержащим коллекцию PDF-файлов. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword) { get; } | Возвращает true, если для изменения разрешений или свойств безопасности документа требуется пароль. Обратите внимание, что это свойство можно прочитать, только если в конструкторе[`PdfFileInfo`](../pdffileinfo)был указан правильный пароль. В случае, если PasswordType имеет значение Inaccessible (означает, что был предоставлен неверный пароль), чтение этого свойства завершится ошибкой[`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword) { get; } | Возвращает true, если для открытия защищенного паролем PDF-документа требуется пароль. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header) { get; set; } | Получает или устанавливает пользовательскую информацию документа PDF. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted) { get; } | Проверяет, зашифрован ли PDF-документ. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile) { get; } | Проверяет, является ли исходный ввод допустимым файлом PDF. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords) { get; set; } | Получает или задает информацию о ключевых словах документа PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate) { get; set; } | Получает или задает информацию о дате ModDate документа PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages) { get; } | Получает количество страниц документа. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype) { get; } | Возвращает тип пароля, который был передан для создания экземпляра PdfFileInfo. См. возможные значения в[`PasswordType`](./passwordtype). Обратите внимание, что pdf-документ можно открыть как с использованием пароля пользователя (или открытия), так и пароля владельца (или прав доступа, редактирования). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer) { get; } | Получает информацию о производителе документа PDF. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject) { get; set; } | Получает или задает информацию о теме документа PDF. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title) { get; set; } | Получает или задает информацию о заголовке документа PDF. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation) { get; set; } | Использует строгие правила проверки с помощью свойства[`IsPdfFile`](./ispdffile). |

## Методы

| Имя | Описание |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf#bindpdf)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Инициализирует фасад. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo)() | Очищает всю метаинформацию документа PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close)() | Деинициализирует экземпляр. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege)() | Получает настройки привилегий для документа PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo)(string) | Получает настроенную информацию о документе PDF с именем свойства. Если нет свойства, соответствующего имени, будет возвращена пустая строка. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight)(int) | Получает высоту указанной страницы. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation)(int) | Получает поворот указанной страницы. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth)(int) | Получает ширину указанной страницы. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset)(int) | Получает горизонтальное смещение указанной области отображения страницы. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset)(int) | Получает вертикальное смещение указанной области отображения страницы. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion)() | Получает информацию о версии документа PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save)(Stream) | Сохраняет документ PDF в указанный файл. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save#save_1)(string) | Сохраняет документ PDF в указанный файл. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo#savenewinfo_1)(string) | Сохранить обновленный PDF-документ в указанный файл. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp)(string) | Изменяет свойства, указанные явно, путем установки информации о файле, другие свойства остаются. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo)(string, string) | Устанавливает пользовательскую информацию PDF-документа. |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
