---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfFileInfo. Представляет класс для доступа к метаинформации PDF-документа
type: docs
weight: 4520
url: /ru/net/aspose.pdf.facades/pdffileinfo/
---
## Класс PdfFileInfo

Представляет класс для доступа к метаинформации PDF-документа.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo с значениями по умолчанию. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Инициализирует новый объект `PdfFileInfo` на основе *документа*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Получает или задает информацию об авторе PDF-документа. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Получает или задает информацию о дате создания PDF-документа. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Получает или задает информацию о создателе PDF-документа. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Возвращает true, если текущий входной файл является файлом 'Портфолио', содержащим коллекцию PDF-файлов. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Возвращает true, если для изменения разрешений или свойств безопасности документа требуется пароль. Обратите внимание, что это свойство можно читать только в том случае, если действительный пароль был предоставлен в конструкторе `PdfFileInfo`. Если PasswordType недоступен (означает, что был предоставлен недействительный пароль), чтение этого свойства завершится неудачей с [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Возвращает true, если для открытия защищенного паролем PDF-документа требуется пароль. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Получает или задает пользовательскую информацию о PDF-документе. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Проверяет, зашифрован ли PDF-документ. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Проверяет, является ли исходный входной файл действительным PDF-файлом. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Получает или задает информацию о ключевых словах PDF-документа. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Получает или задает информацию о дате изменения PDF-документа. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Получает количество страниц документа. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Возвращает тип пароля, который был передан для создания экземпляра PdfFileInfo. Смотрите возможные значения в [`PasswordType`](./passwordtype/). Обратите внимание, что PDF-документ может быть открыт как с помощью пароля пользователя (или открытого), так и с помощью пароля владельца (или разрешений, редактирования). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Получает информацию о производителе PDF-документа. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Получает или задает информацию о предмете PDF-документа. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Получает или задает информацию о заголовке PDF-документа. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Использует строгие правила валидации с помощью свойства [`IsPdfFile`](./ispdffile/). |

## Методы

| Имя | Описание |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Очищает всю метаинформацию PDF-документа. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Деинициализирует экземпляр. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Получает настройки привилегий PDF-документа. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Получает пользовательскую информацию о PDF-документе с именем свойства. Если нет свойства, соответствующего имени, будет возвращена пустая строка. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Получает высоту указанной страницы. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Получает ориентацию указанной страницы. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Получает ширину указанной страницы. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Получает горизонтальный сдвиг области отображения указанной страницы. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Получает вертикальный сдвиг области отображения указанной страницы. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Получает информацию о версии PDF-документа. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Сохраняет PDF-документ в указанный файл. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Сохраняет PDF-документ в указанный файл. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Сохраняет обновленный PDF-документ в указанный файл. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Изменяет свойства, указанные явно, устанавливая информацию о файле, другие свойства остаются. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Устанавливает пользовательскую информацию о PDF-документе. |

### См. также

* класс [SaveableFacade](../saveablefacade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)