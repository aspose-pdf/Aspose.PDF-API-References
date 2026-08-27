---
title: "Класс PdfFileSignature"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.PdfFileSignature. Представляет класс для подписания PDF‑файла с помощью сертификата"
type: docs
weight: 4680
url: /ru/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Представляет класс для подписи PDF‑файла сертификатом.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Конструктор класса PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Инициализирует новый объект `PdfFileSignature` на основе *document*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Возвращает флаг, определяющий, сертифицирован ли документ. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Возвращает флаг включённого LTV. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Устанавливает или получает графическое представление подписи. Значение свойства представляет имя файла изображения. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Устанавливает или получает графическое представление подписи. Значение свойства представляет поток изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Привязывает поток Pdf для редактирования. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Привязывает файл Pdf для редактирования. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Сертифицируйте документ с помощью MDP‑подписи, размещённой в уже существующем поле подписи. Перед подписанием поле подписи должно быть пустым, то есть не должно содержать словарь подписи. Таким образом, PDF‑документ уже содержит поле подписи, вам не нужно указывать место для нанесения подписи; соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Сертифицируйте документ с помощью MDP‑подписи. Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Закрывает фасад. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Проверяет, имеет ли PDF цифровую подпись. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Проверяет, имеет ли PDF права использования. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Проверяет, охватывает ли подпись весь документ. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Извлекает единственный сертификат X.509 подписи в виде потока. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Извлекает изображение подписи. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Возвращает значение прав доступа сертифицированного документа по типу MDP‑подписи. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Получает имена всех пустых полей подписи. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Получает контактную информацию подписи. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Получает дату и время подписи. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Получает место подписи. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Получает причину подписи. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Получает ревизию подписи. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Получает имена всех непустых подписей. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Получает информацию обо всех алгоритмах подписей, присутствующих в PDF‑документе. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Получает имя лица или организации, подписывающих PDF‑документ. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Получает общую ревизию. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Удаляет подпись по её имени. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Удаляет подпись по её имени. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Удаляет все подписи. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Удаляет запись прав использования. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Сохраняет полученный PDF в поток. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Сохраняет полученный PDF в файл. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Устанавливает файл сертификата и пароль для процедуры подписи. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Подписывает документ подписью указанного типа, размещённой в уже существующем поле подписи. Перед подписью поле подписи должно быть пустым, то есть не должно содержать словарь подписи. Таким образом, PDF‑документ уже содержит поле подписи, вам не нужно указывать место для нанесения подписи, соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName). Такие данные, как причина подписи, контакт и место, должны быть предоставлены соответствующими свойствами объекта Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Подписывает документ подписью указанного типа. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Подписывает документ подписью указанного типа, размещённой в уже существующем поле подписи. Перед подписью поле подписи должно быть пустым, то есть не должно содержать словарь подписи. Таким образом, PDF‑документ уже содержит поле подписи, вам не нужно указывать место для нанесения подписи, соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Создаёт подпись в PDF‑документе. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Подписывает документ подписью указанного типа. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Подписывает документ подписью указанного типа, размещённой в уже существующем поле подписи. Перед подписью PDF‑документ уже должен иметь поле подписи, соответствующая страница и прямоугольник берутся из поля подписи, найденного по имени подписи (см. параметр SigName). |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | Извлекает единственный сертификат X.509 подписи в виде потока. |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | Извлекает единственный сертификат X.509 подписи. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Проверяет действительность подписи. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | Проверяет действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Проверяет действительность подписи. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | Проверяет действительность подписи. Проверка выполняется с использованием внешнего сертификата открытого ключа. |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


