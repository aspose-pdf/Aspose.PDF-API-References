---
title: PdfFileSignature
second_title: Aspose.PDF для справочника API .NET
description: Представляет класс для подписи PDF-файла сертификатом.
type: docs
weight: 2570
url: /ru/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Представляет класс для подписи PDF-файла сертификатом.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileSignature](pdffilesignature#constructor)() | Конструктор класса PdfFileSignature. |
| [PdfFileSignature](pdffilesignature#constructor_1)(Document) | Инициализирует новый[`PdfFileSignature`](../pdffilesignature)объект на основе*document*. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified) { get; } | Получает флаг, определяющий, сертифицирован документ или нет. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled) { get; } | Получает флаг включения LTV. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance) { get; set; } | Задает или получает графический вид подписи. Значение свойства представляет имя файла изображения. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream) { get; set; } | Задает или получает графический вид подписи. Значение свойства представляет поток изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_1)(Stream) | Связывает поток Pdf для редактирования. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_2)(string) | Связывает файл Pdf для редактирования. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify_1)(string, DocMDPSignature) | Заверить документ подписью MDP, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, в pdf документе уже есть поле для подписи, место для проставления подписи указывать не нужно, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр сигнаме). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Заверить документ подписью MDP. Такие данные, как причина подписи, контакт и местонахождение, должны быть предоставлены соответствующими свойствами объекта Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close)() | Закрывает фасад. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature)() | Проверяет, есть ли у pdf цифровая подпись или нет. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights)() | Проверяет, есть ли у pdf права на использование или нет. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument)(string) | Проверяет, охватывает ли подпись весь документ. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate)(string) | Извлекает единственный сертификат X.509 подписи в виде потока. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage)(string) | Извлекает изображение подписи. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions)() | Возвращает значение прав доступа сертифицированного документа по типу подписи MDP. |
| [GetBlankSignNames](../../aspose.pdf.facades/pdffilesignature/getblanksignnames)() | Получает имена всех пустых полей подписи. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo)(string) | Получает контактную информацию подписи. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime)(string) | Получает дату и время подписи. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation)(string) | Получает расположение подписи. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason)(string) | Получает причину подписи. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision)(string) | Получает версию подписи. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername)(string) | Получает имя человека или организации, подписавших PDF-документ. |
| [GetSignNames](../../aspose.pdf.facades/pdffilesignature/getsignnames)(bool) | Получает имена всех непустых подписей. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision)() | Получает полную версию. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature)(string) | Удалить подпись по имени подписи. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature_1)(string, bool) | Удаляет подпись по имени подписи. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights)() | Удаляет запись прав использования. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_1)(Stream) | Сохраняет результат PDF в поток. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_2)(string) | Сохраняет результат PDF в файл. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate)(string, string) | Установить файл сертификата и пароль для процедуры подписи. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_4)(string, Signature) | Подпишите документ подписью данного типа, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, в pdf документе уже есть поле для подписи, место для проставления подписи указывать не нужно, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName). Такие данные, как причина подписи, контакт и местонахождение, должны быть предоставлены соответствующими свойствами объекта Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign)(int, bool, Rectangle, Signature) | Подпишите документ с заданным типом подписи. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_5)(string, string, string, string, Signature) | Подпишите документ подписью данного типа, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, в pdf документе уже есть поле для подписи, место для проставления подписи указывать не нужно, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_1)(int, string, string, string, bool, Rectangle) | Сделать подпись в pdf документе. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Подпишите документ с заданным типом подписи. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Подпишите документ подписью данного типа, которая размещена в уже представленном поле подписи. Перед подписанием в pdf-документе уже должно быть поле для подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature)(string) | Проверяет действительность подписи. |
| [VerifySigned](../../aspose.pdf.facades/pdffilesignature/verifysigned)(string) | Проверяет действительность подписи. |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
