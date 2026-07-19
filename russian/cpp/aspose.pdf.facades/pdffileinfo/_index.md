---
title: "Aspose::Pdf::Facades::PdfFileInfo класс"
linktitle: "PdfFileInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileInfo класс. Представляет класс для доступа к метаинформации PDF‑документа на C++."
type: docs
weight: 2100
url: /ru/cpp/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class


Представляет класс для доступа к метаинформации PDF‑документа.

```cpp
class PdfFileInfo : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Инициализирует фасад. |
| [ClearInfo](./clearinfo/)() | Очищает всю метаинформацию PDF‑документа. |
| [Close](./close/)() override | Деинициализирует экземпляр. |
| [get_Author](./get_author/)() | Получает информацию об авторе PDF‑документа. |
| [get_CreationDate](./get_creationdate/)() | Получает информацию о дате создания PDF‑документа. |
| [get_Creator](./get_creator/)() | Получает информацию о создателе PDF‑документа. |
| [get_HasCollection](./get_hascollection/)() | Возвращает true, если текущий входной файл является файлом 'Portfolio', содержащим коллекцию PDF‑файлов. |
| [get_HasEditPassword](./get_haseditpassword/)() | Возвращает true, если для изменения прав или свойства безопасности документа требуется пароль. Обратите внимание, что это свойство можно прочитать только при наличии действительного пароля, переданного в конструктор [PdfFileInfo](./). Если [PasswordType](../../aspose.pdf/passwordtype/) имеет значение Inaccessible (что означает, что был предоставлен неверный пароль), чтение этого свойства завершится ошибкой [InvalidPasswordException](../../aspose.pdf/invalidpasswordexception/). |
| [get_HasOpenPassword](./get_hasopenpassword/)() | Возвращает true, если для открытия защищённого паролем PDF‑документа требуется пароль. |
| [get_Header](./get_header/)() const | Получает пользовательскую информацию PDF‑документа. |
| [get_InputFile](./get_inputfile/)() const | Получает входной файл. |
| [get_InputStream](./get_inputstream/)() const | Получает входной поток. |
| [get_IsEncrypted](./get_isencrypted/)() | Проверяет, зашифрован ли PDF‑документ. |
| [get_IsPdfFile](./get_ispdffile/)() | Проверяет, является ли исходный ввод действительным PDF‑файлом. |
| [get_Keywords](./get_keywords/)() | Получает информацию о ключевых словах PDF‑документа. |
| [get_ModDate](./get_moddate/)() | Получает информацию о дате модификации (ModDate) PDF‑документа. |
| [get_NumberOfPages](./get_numberofpages/)() | Получает количество страниц документа. |
| [get_PasswordType](./get_passwordtype/)() | Возвращает тип пароля, который был передан при создании экземпляра [PdfFileInfo](./). См. возможные значения в [PasswordType](../../aspose.pdf/passwordtype/). Обратите внимание, что PDF‑документ может быть открыт как с пользовательским (или открывающим) паролем, так и с паролем владельца (или паролем прав, редактирования). |
| [get_Producer](./get_producer/)() | Получает информацию о производителе PDF‑документа. |
| [get_Subject](./get_subject/)() | Получает информацию о предмете PDF‑документа. |
| [get_Title](./get_title/)() | Получает информацию о заголовке PDF‑документа. |
| [get_UseStrictValidation](./get_usestrictvalidation/)() const | Использует строгие правила проверки с помощью свойства [IsPdfFile](../). |
| [GetDocumentPrivilege](./getdocumentprivilege/)() | Получает настройки привилегий PDF‑документа. |
| [GetMetaInfo](./getmetainfo/)(const System::String\&) | Получает пользовательскую информацию PDF‑документа по имени свойства. Если свойство с таким именем не найдено, будет возвращена пустая строка. |
| [GetPageHeight](./getpageheight/)(int32_t) | Получает высоту указанной страницы. |
| [GetPageRotation](./getpagerotation/)(int32_t) | Получает поворот указанной страницы. |
| [GetPageWidth](./getpagewidth/)(int32_t) | Получает ширину указанной страницы. |
| [GetPageXOffset](./getpagexoffset/)(int32_t) | Получает горизонтальное смещение области отображения указанной страницы. |
| [GetPageYOffset](./getpageyoffset/)(int32_t) | Получает вертикальное смещение указанной области отображения страницы. |
| [GetPdfVersion](./getpdfversion/)() | Получает информацию о версии PDF‑документа. |
| [PdfFileInfo](./pdffileinfo/)() | Создаёт новый экземпляр класса [Aspose.Pdf.Facades.PdfFileInfo](./) с значениями по умолчанию. |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<System::IO::Stream\>\&) | Создаёт новый экземпляр класса [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Создаёт новый экземпляр класса [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Создаёт новый экземпляр класса [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::String\&) | Создаёт новый экземпляр класса [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::String\&, const System::String\&) | Создаёт новый экземпляр класса [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Создаёт новый экземпляр класса [Aspose.Pdf.Facades.PdfFileInfo](./). |
| [PdfFileInfo](./pdffileinfo/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfFileInfo](./) на основе *document*. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Сохраняет PDF‑документ в указанный файл. |
| [Save](./save/)(System::String) override | Сохраняет PDF‑документ в указанный файл. |
| [SaveNewInfo](./savenewinfo/)(const System::SharedPtr\<System::IO::Stream\>\&) | Сохраняет обновлённый PDF‑документ в указанный поток. |
| [SaveNewInfo](./savenewinfo/)(const System::String\&) | Сохраняет обновлённый PDF‑документ в указанный файл. |
| [SaveNewInfoWithXmp](./savenewinfowithxmp/)(const System::String\&) | Изменяет явно указанные свойства, задавая информацию о файле; остальные свойства остаются без изменений. |
| [set_Author](./set_author/)(const System::String\&) | Устанавливает информацию об авторе PDF‑документа. |
| [set_CreationDate](./set_creationdate/)(const System::String\&) | Устанавливает информацию о дате создания PDF‑документа. |
| [set_Creator](./set_creator/)(const System::String\&) | Устанавливает информацию о создателе PDF‑документа. |
| [set_Header](./set_header/)(const System::SharedPtr\<System::Collections::Generic::Dictionary\<System::String, System::String\>\>\&) | Устанавливает пользовательскую информацию PDF‑документа. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Устанавливает входной файл. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает входной поток. |
| [set_Keywords](./set_keywords/)(const System::String\&) | Устанавливает информацию о ключевых словах PDF‑документа. |
| [set_ModDate](./set_moddate/)(const System::String\&) | Устанавливает информацию о дате изменения (ModDate) PDF‑документа. |
| [set_Subject](./set_subject/)(const System::String\&) | Устанавливает информацию о предмете PDF‑документа. |
| [set_Title](./set_title/)(const System::String\&) | Устанавливает информацию о заголовке PDF‑документа. |
| [set_UseStrictValidation](./set_usestrictvalidation/)(bool) | Использует строгие правила проверки с помощью свойства [IsPdfFile](../). |
| [SetMetaInfo](./setmetainfo/)(const System::String\&, const System::String\&) | Устанавливает пользовательскую информацию PDF‑документа. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
