---
title: PdfFileSecurity
second_title: Aspose.PDF для справочника API .NET
description: Представляет собой шифрование или дешифрование файла Pdf с использованием пароля владельца или пользователя изменение настроек безопасности и пароля.
type: docs
weight: 2560
url: /ru/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Представляет собой шифрование или дешифрование файла Pdf с использованием пароля владельца или пользователя, изменение настроек безопасности и пароля.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity#constructor)() | Инициализировать объект PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity#constructor_1)(Document) | Инициализирует новый[`PdfFileSecurity`](../pdffilesecurity)объект на основе*document*. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception) { get; } | Возвращает исключение, сгенерированное последней операцией. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_1)(Stream) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_2)(string) | Инициализирует фасад. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword)(string, string, string) | Меняет пароль пользователя и владельца на пароль владельца, сохраняет исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца нулевой или пустой. Выдает исключение, если процесс завершился неудачно. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца нулевой или пустой. Выдает исключение, если процесс завершился неудачно. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца нулевой или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) недействительны и соответствующее исключение будет вызвано, если набор встретит эту комбинацию. Выдает исключение, если процесс завершился неудачно. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close)() | Закрывает фасад. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile)(string) | Расшифровывает зашифрованный документ Pdf по паролю владельца. Если документ не имеет пароля владельца, можно использовать пароль пользователя. Выдает исключение, если процесс завершился неудачно. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile)(string, string, DocumentPrivilege, KeySize) | Шифрует Pdf-файл с помощью пароля пользователя и владельца и устанавливает права доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если введенный пароль владельца нулевой или пустой. Выдает исключение, если процесс завершился неудачно. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Шифрует Pdf-файл с помощью пароля пользователя и владельца и устанавливает права доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если введенный пароль владельца нулевой или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) недействительны и соответствующее исключение будет вызвано, если набор встретит эту комбинацию. Выдает исключение, если процесс завершился неудачно. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Сохраняет документ PDF в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Сохраняет документ PDF в указанный файл. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege)(DocumentPrivilege) | Устанавливает безопасность файла Pdf с пустыми паролями пользователя/владельца. Пароль владельца будет добавлен случайной строкой. Выдает исключение, если процесс завершился неудачно. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege_1)(string, string, DocumentPrivilege) | Устанавливает безопасность файла Pdf с исходным паролем. Выдает исключение, если процесс завершился неудачно. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword)(string, string, string) | Меняет пароль пользователя и владельца на пароль владельца, сохраняет исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен Не генерирует исключение в случае сбоя процесса. со случайной строкой, если пароль нового владельца нулевой или пустой. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца нулевой или пустой. Не генерирует исключение в случае сбоя процесса. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Изменяет пароль пользователя и пароль на пароль владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца нулевой или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) недействительны и соответствующее исключение будет вызвано, если набор встретит эту комбинацию. Не генерирует исключение в случае сбоя процесса. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile)(string) | Расшифровывает зашифрованный документ Pdf по паролю владельца. Если документ не имеет пароля владельца, можно использовать пароль пользователя. Не генерирует исключение в случае сбоя процесса. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile)(string, string, DocumentPrivilege, KeySize) | Шифрует Pdf-файл с помощью пароля пользователя и владельца и устанавливает права доступа к документу. Пароль пользователя и пароль владельца могут быть нулевыми или пустыми. Пароль владельца будет заменен случайной строкой, если введенный пароль владельца нулевой или пустой. Не генерирует исключение в случае сбоя процесса. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege)(string, string, DocumentPrivilege) | Устанавливает безопасность файла Pdf с исходным паролем. Не генерирует исключение в случае сбоя процесса. |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
