---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfFileSignature. Представляет класс для подписи pdf файла с сертификатом
type: docs
weight: 4560
url: /ru/net/aspose.pdf.facades/pdffilesignature/
---
## Класс PdfFileSignature

Представляет класс для подписи pdf файла с сертификатом.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Конструктор класса PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Инициализирует новый объект `PdfFileSignature` на основе *документа*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Получает флаг, определяющий, сертифицирован ли документ или нет. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Получает флаг, указывающий, включен ли LTV. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Устанавливает или получает графический вид для подписи. Значение свойства представляет собой имя файла изображения. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Устанавливает или получает графический вид для подписи. Значение свойства представляет собой поток изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Привязывает поток Pdf для редактирования. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Привязывает файл Pdf для редактирования. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Сертифицирует документ с помощью MDP подписи, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, pdf документ уже имеет поле подписи, вы не должны указывать место для печати подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Сертифицирует документ с помощью MDP подписи. Такие данные, как причина подписи, контакт и местоположение, должны быть предоставлены соответствующими свойствами объекта подписи sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Закрывает фасад. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Проверяет, имеет ли pdf цифровую подпись или нет. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Проверяет, имеет ли pdf права на использование или нет. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Проверяет, охватывает ли подпись весь документ. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Уничтожает фасад. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Извлекает единственный X.509 сертификат подписи в виде потока. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Извлекает изображение подписи. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Возвращает значение прав доступа сертифицированного документа по типу MDP подписи. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Получает имена всех пустых полей подписи. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Получает контактную информацию подписи. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Получает дату и время подписи. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Получает местоположение подписи. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Получает причину подписи. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Получает ревизию подписи. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Получает имена всех непустых подписей. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Извлекает информацию обо всех алгоритмах подписей, присутствующих в PDF документе. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Получает имя лица или организации, подписывающего pdf документ. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Получает общую ревизию. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Удаляет подпись по имени подписи. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Удаляет подпись по имени подписи. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Удаляет все подписи. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Удаляет запись прав на использование. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Сохраняет результат PDF в поток. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Сохраняет результат PDF в файл. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Устанавливает файл сертификата и пароль для процедуры подписи. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Подписывает документ с помощью данного типа подписи, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, pdf документ уже имеет поле подписи, вы не должны указывать место для печати подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName). Такие данные, как причина подписи, контакт и местоположение, должны быть предоставлены соответствующими свойствами объекта подписи sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Подписывает документ с помощью данного типа подписи. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Подписывает документ с помощью данного типа подписи, которая размещена в уже представленном поле подписи. Перед подписанием поле подписи должно быть пустым, т.е. поле не должно содержать словарь подписи. Таким образом, pdf документ уже имеет поле подписи, вы не должны указывать место для печати подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Делает подпись на pdf документе. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Подписывает документ с помощью данного типа подписи. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Подписывает документ с помощью данного типа подписи, которая размещена в уже представленном поле подписи. Перед подписанием pdf документ должен уже иметь поле подписи, соответствующая страница и прямоугольник берутся из поля подписи, которое находится по имени подписи (см. параметр SigName). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Проверяет действительность подписи. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Проверяет действительность подписи. |

### См. также

* класс [SaveableFacade](../saveablefacade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)