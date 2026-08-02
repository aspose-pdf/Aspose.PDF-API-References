---
title: "Класс PdfFileInfo"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Facades.PdfFileInfo class. Представляет класс для доступа к метаинформации PDF‑документа."
type: docs
weight: 4640
url: /ru/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

Представляет класс для доступа к метаинформации PDF Document.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo со значениями по умолчанию. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Инициализирует новый объект `PdfFileInfo` на основе *документа*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_6)(string, string) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(Stream, string, ICustomSecurityHandler) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_7)(string, string, ICustomSecurityHandler) | Инициализирует новый экземпляр класса Aspose.Pdf.Facades.PdfFileInfo. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Получает или задает информацию об авторе PDF‑документа. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Получает или задает информацию о дате создания PDF‑документа. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Получает или задает информацию о создателе PDF‑документа. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Возвращает true, если текущий входной файл является файлом 'Portfolio', содержащим коллекцию PDF‑файлов. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Возвращает true, если требуется пароль для изменения прав доступа или свойства безопасности документа. Обратите внимание, что это свойство можно прочитать только если в конструкторе `PdfFileInfo` был предоставлен действительный пароль. В случае, когда PasswordType имеет значение Inaccessible (это означает, что был предоставлен недействительный пароль), чтение этого свойства завершится ошибкой [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Возвращает true, если требуется пароль для открытия защищённого паролем pdf‑документа. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Получает или задает пользовательскую информацию PDF‑документа. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Проверяет, зашифрован ли PDF‑документ. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Проверяет, является ли исходный ввод действительным PDF‑файлом. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Получает или задает информацию о ключевых словах PDF‑документа. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Получает или задает информацию о дате ModDate PDF‑документа. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Получает количество страниц документа. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Возвращает тип пароля, который был передан при создании экземпляра PdfFileInfo. Смотрите возможные значения в [`PasswordType`](./passwordtype/). Обратите внимание, что pdf‑документ может быть открыт как с пользовательским (или открывающим) паролем, так и с паролем владельца (или паролем прав доступа, редактирования). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Получает информацию о производителе PDF‑документа. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Получает или задает информацию о предмете PDF‑документа. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Получает или задает информацию о заголовке PDF‑документа. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Использует строгие правила проверки через свойство [`IsPdfFile`](./ispdffile/). |

## Методы

| Имя | Описание |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Очищает всю мета‑информацию PDF Document. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Деинициализирует экземпляр. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Получает настройки привилегий PDF Document. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Получает пользовательскую информацию PDF Document по имени свойства. Если нет свойства, соответствующего имени, будет возвращена пустая строка. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Получает высоту указанной Page. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Получает вращение указанной Page. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Получает ширину указанной Page. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Получает горизонтальное смещение области отображения указанной Page. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Получает вертикальное смещение области отображения указанной Page. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Получает информацию о версии PDF Document. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Сохраняет PDF‑документ в указанный файл. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Сохраняет PDF‑документ в указанный файл. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Сохраняет обновлённый PDF Document в указанный файл. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Изменяет явно указанные свойства, задавая информацию о файле, остальные свойства остаются без изменений. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Устанавливает пользовательскую информацию PDF Document. |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


