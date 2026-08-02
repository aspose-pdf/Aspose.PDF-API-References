---
title: "Класс PdfFileSecurity"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.PdfFileSecurity. Представляет шифрование или дешифрование PDF‑файла с помощью пароля владельца или пользователя, изменяя настройки безопасности и пароль."
type: docs
weight: 4670
url: /ru/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

Представляет шифрование или дешифрование PDF‑файла с паролем владельца или пользователя, изменение настроек безопасности и пароля.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | Инициализировать объект PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | Инициализирует новый объект `PdfFileSecurity` на основе *документ*. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | Возвращает исключение, которое было выброшено последней операцией. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | Инициализирует фасад. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | Изменяет пароль пользователя и пароль владельца с помощью пароля владельца, сохраняет исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Выбрасывает исключение, если процесс завершился неудачей. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Изменяет пароль пользователя и пароль с помощью пароля владельца, позволяет сбросить безопасность PDF‑документа. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Выбрасывает исключение, если процесс завершился неудачей. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Изменяет пароль пользователя и пароль с помощью пароля владельца, позволяет сбросить безопасность PDF‑документа. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) являются недействительными, и соответствующее исключение будет вызвано, если набор столкнётся с этой комбинацией. Выбрасывает исключение, если процесс завершился неудачей. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | Закрывает фасад. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | Расшифровывает зашифрованный PDF‑документ с помощью пароля владельца. Если у документа нет пароля владельца, допускается использование пароля пользователя. Выбрасывает исключение, если процесс завершился неудачей. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | Шифрует PDF‑файл с паролем пользователя и паролем владельца и устанавливает привилегии доступа документа. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца равен null или пустой. Выбрасывает исключение, если процесс завершился неудачей. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | Шифрует PDF‑файл с паролем пользователя и паролем владельца и устанавливает привилегии доступа документа. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) являются недействительными, и соответствующее исключение будет вызвано, если набор столкнётся с этой комбинацией. Выбрасывает исключение, если процесс завершился неудачей. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Сохраняет PDF‑документ в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Сохраняет PDF‑документ в указанный файл. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | Устанавливает безопасность PDF‑файла с пустыми паролями пользователя/владельца. Пароль владельца будет заменён случайной строкой. Выбрасывает исключение, если процесс завершился неудачей. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | Устанавливает безопасность PDF‑файла с оригинальным паролем. Выбрасывает исключение, если процесс завершился неудачей. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | Изменяет пароль пользователя и пароль владельца с помощью пароля владельца, сохраняет исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть null и пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Не выбрасывает исключение, если процесс завершился неудачей. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | Изменяет пароль пользователя и пароль с помощью пароля владельца, позволяет сбросить безопасность PDF‑документа. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Не выбрасывает исключение, если процесс завершился неудачей. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | Изменяет пользовательский пароль и пароль владельца, позволяет сбросить безопасность PDF‑документа. Новый пользовательский пароль и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца null или пустой. Существует 6 возможных комбинаций значений KeySize и Algorithm. Однако (KeySize.x40, Algorithm.AES) и (KeySize.x256, Algorithm.RC4) недействительны, и соответствующее исключение будет вызвано, если набор обнаружит эту комбинацию. Не бросает исключение при неудаче процесса. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | Расшифровывает зашифрованный PDF‑документ с помощью пароля владельца. Если у документа нет пароля владельца, допускается использование пользовательского пароля. Не бросает исключение при неудаче процесса. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | Шифрует PDF‑файл с пользовательским паролем и паролем владельца и задаёт привилегии доступа документа. Пользовательский пароль и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца null или пустой. Не бросает исключение при неудаче процесса. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | Устанавливает безопасность PDF‑файла с оригинальным паролем. Не бросает исключение при неудаче процесса. |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


