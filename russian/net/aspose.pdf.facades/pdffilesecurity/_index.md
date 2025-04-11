---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfFileSecurity. Представляет шифрование или расшифровку Pdf файла с использованием пароля владельца или пользователя, изменяя настройки безопасности и пароль
type: docs
weight: 4550
url: /ru/net/aspose.pdf.facades/pdffilesecurity/
---
## Класс PdfFileSecurity

Представляет шифрование или расшифровку Pdf файла с использованием пароля владельца или пользователя, изменяя настройки безопасности и пароль.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Инициализирует объект PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Инициализирует новый объект `PdfFileSecurity` на основе *документа*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Возвращает исключение, которое было выброшено последней операцией. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Инициализирует фасад. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Изменяет пароль пользователя и пароль владельца по паролю владельца, сохраняет оригинальные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца равен null или пустой. Вызывает исключение, если процесс завершился неудачно. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Изменяет пароль пользователя и пароль по паролю владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца равен null или пустой. Вызывает исключение, если процесс завершился неудачно. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Изменяет пароль пользователя и пароль по паролю владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) являются недопустимыми, и соответствующее исключение будет вызвано, если комплект столкнется с этой комбинацией. Вызывает исключение, если процесс завершился неудачно. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Закрывает фасад. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Расшифровывает зашифрованный документ Pdf по паролю владельца. Если у документа нет пароля владельца, разрешается использовать пароль пользователя. Вызывает исключение, если процесс завершился неудачно. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Шифрует файл Pdf с использованием пароля пользователя и пароля владельца и устанавливает привилегии доступа к документу. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если входной пароль владельца равен null или пустой. Вызывает исключение, если процесс завершился неудачно. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Шифрует файл Pdf с использованием пароля пользователя и пароля владельца и устанавливает привилегии доступа к документу. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если входной пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) являются недопустимыми, и соответствующее исключение будет вызвано, если комплект столкнется с этой комбинацией. Вызывает исключение, если процесс завершился неудачно. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Сохраняет документ PDF в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Сохраняет документ PDF в указанный файл. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Устанавливает безопасность файла Pdf с пустыми паролями пользователя/владельца. Пароль владельца будет добавлен случайной строкой. Вызывает исключение, если процесс завершился неудачно. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Устанавливает безопасность файла Pdf с оригинальным паролем. Вызывает исключение, если процесс завершился неудачно. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Изменяет пароль пользователя и пароль владельца по паролю владельца, сохраняет оригинальные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца равен null или пустой. Не вызывает исключение, если процесс завершился неудачно. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Изменяет пароль пользователя и пароль по паролю владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца равен null или пустой. Не вызывает исключение, если процесс завершился неудачно. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Изменяет пароль пользователя и пароль по паролю владельца, позволяет сбросить безопасность документа Pdf. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если новый пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) являются недопустимыми, и соответствующее исключение будет вызвано, если комплект столкнется с этой комбинацией. Не вызывает исключение, если процесс завершился неудачно. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Расшифровывает зашифрованный документ Pdf по паролю владельца. Если у документа нет пароля владельца, разрешается использовать пароль пользователя. Не вызывает исключение, если процесс завершился неудачно. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Шифрует файл Pdf с использованием пароля пользователя и пароля владельца и устанавливает привилегии доступа к документу. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменен случайной строкой, если входной пароль владельца равен null или пустой. Не вызывает исключение, если процесс завершился неудачно. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Устанавливает безопасность файла Pdf с оригинальным паролем. Не вызывает исключение, если процесс завершился неудачно. |

### См. также

* класс [SaveableFacade](../saveablefacade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)