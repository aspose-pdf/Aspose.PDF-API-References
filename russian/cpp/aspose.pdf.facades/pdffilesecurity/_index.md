---
title: "класс Aspose::Pdf::Facades::PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Facades::PdfFileSecurity. Представляет шифрование или дешифрование PDF‑файла с паролем владельца или пользователя, изменение настроек безопасности и пароля в C++."
type: docs
weight: 2400
url: /ru/cpp/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class


Представляет шифрование или дешифрование [Pdf](../../aspose.pdf/) файла с паролем владельца или пользователя, изменение настроек безопасности и пароля.

```cpp
class PdfFileSecurity : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Инициализирует фасад. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Инициализирует фасад. |
| [ChangePassword](./changepassword/)(const System::String\&, const System::String\&, const System::String\&) | Изменяет пароль пользователя и пароль владельца, используя пароль владельца, сохраняет исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Выбрасывает исключение, если процесс завершился неудачей. |
| [ChangePassword](./changepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Изменяет пароль пользователя и пароль, используя пароль владельца, позволяет сбросить безопасность [Pdf](../../aspose.pdf/) документа. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Выбрасывает исключение, если процесс завершился неудачей. |
| [ChangePassword](./changepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) | Изменяет пароль пользователя и пароль, используя пароль владельца, позволяет сбросить безопасность [Pdf](../../aspose.pdf/) документа. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений [KeySize](../keysize/) и [Algorithm](../algorithm/). Однако комбинации ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) и ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) недействительны, и соответствующее исключение будет вызвано, если набор обнаружит эту комбинацию. Выбрасывает исключение, если процесс завершился неудачей. |
| [Close](./close/)() override | Закрывает фасад. |
| [get_AllowExceptions](./get_allowexceptions/)() | Если это значение установлено в true, при ошибке операции будет выброшено исключение. В противном случае метод возвращает false при неудаче, и последнее исключение можно проверить с помощью свойства LastException. |
| [get_LastException](./get_lastexception/)() const | Возвращает исключение, которое было выброшено последней операцией. |
| [MfDecryptFile](./mfdecryptfile/)(const System::String\&) | Дешифрует зашифрованный [Pdf](../../aspose.pdf/) документ с помощью пароля владельца. Если у документа нет пароля владельца, допускается использование пароля пользователя. Выбрасывает исключение, если процесс завершился неудачей. |
| [MfEncryptFile](./mfencryptfile/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Шифрует файл [Pdf](../../aspose.pdf/) с паролем пользователя и паролем владельца и задаёт привилегии доступа документа. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца равен null или пустой. Выбрасывает исключение, если процесс завершился неудачей. |
| [MfEncryptFile](./mfencryptfile/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) | Шифрует файл [Pdf](../../aspose.pdf/) с паролем пользователя и паролем владельца и задаёт привилегии доступа документа. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений [KeySize](../keysize/) и [Algorithm](../algorithm/). Однако комбинации ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) и ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) недействительны, и соответствующее исключение будет вызвано, если набор обнаружит эту комбинацию. Выбрасывает исключение, если процесс завершился неудачей. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Инициализировать объект [PdfFileSecurity](./) с входным и выходным потоком. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::String\&, const System::String\&) | Инициализирует объект [PdfFileSecurity](./) с входным и выходным файлом. |
| [PdfFileSecurity](./pdffilesecurity/)() | Инициализировать объект [PdfFileSecurity](./). |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Инициализирует новый объект [PdfFileSecurity](./) на основе *документа*. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Инициализирует новый объект [PdfFileSecurity](./) на основе *документа*. |
| [PdfFileSecurity](./pdffilesecurity/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Инициализирует новый объект [PdfFileSecurity](./) на основе *документа*. |
| [set_AllowExceptions](./set_allowexceptions/)(bool) | Если это значение установлено в true, при ошибке операции будет выброшено исключение. В противном случае метод возвращает false при неудаче, и последнее исключение можно проверить с помощью свойства LastException. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Устанавливает входной файл. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает входной поток. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Устанавливает выходной файл. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает выходной поток. |
| [SetPrivilege](./setprivilege/)(const System::SharedPtr\<DocumentPrivilege\>\&) | Устанавливает безопасность файла [Pdf](../../aspose.pdf/) с пустыми паролями пользователя/владельца. Пароль владельца будет заменён случайной строкой. Выбрасывает исключение, если процесс завершился неудачей. |
| [SetPrivilege](./setprivilege/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&) | Устанавливает безопасность файла [Pdf](../../aspose.pdf/) с оригинальным паролем. Выбрасывает исключение, если процесс завершился неудачей. |
| [TryChangePassword](./trychangepassword/)(const System::String\&, const System::String\&, const System::String\&) | Изменяет пароль пользователя и пароль владельца, используя пароль владельца, сохраняет исходные настройки безопасности. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Не выбрасывает исключение, если процесс завершился неудачей. |
| [TryChangePassword](./trychangepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Изменяет пароль пользователя и пароль, используя пароль владельца, позволяет сбросить безопасность [Pdf](../../aspose.pdf/) документа. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Не выбрасывает исключение, если процесс завершился неудачей. |
| [TryChangePassword](./trychangepassword/)(const System::String\&, const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize, Algorithm) | Изменяет пароль пользователя и пароль, используя пароль владельца, позволяет сбросить безопасность [Pdf](../../aspose.pdf/) документа. Новый пароль пользователя и новый пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если новый пароль владельца равен null или пустой. Существует 6 возможных комбинаций значений [KeySize](../keysize/) и [Algorithm](../algorithm/). Однако комбинации ([KeySize.x40](../keysize/), [Algorithm.AES](../algorithm/)) и ([KeySize.x256](../keysize/), [Algorithm.RC4](../algorithm/)) недействительны, и соответствующее исключение будет вызвано, если набор обнаружит эту комбинацию. Не выбрасывает исключение, если процесс завершился неудачей. |
| [TryDecryptFile](./trydecryptfile/)(const System::String\&) | Дешифрует зашифрованный [Pdf](../../aspose.pdf/) документ с помощью пароля владельца. Если у документа нет пароля владельца, допускается использование пароля пользователя. Не выбрасывает исключение, если процесс завершился неудачей. |
| [TryEncryptFile](./tryencryptfile/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&, KeySize) | Шифрует файл [Pdf](../../aspose.pdf/) с паролем пользователя и паролем владельца и задаёт привилегии доступа документа. Пароль пользователя и пароль владельца могут быть null или пустыми. Пароль владельца будет заменён случайной строкой, если входной пароль владельца равен null или пустой. Не выбрасывает исключение, если процесс завершился неудачей. |
| [TrySetPrivilege](./trysetprivilege/)(const System::String\&, const System::String\&, const System::SharedPtr\<DocumentPrivilege\>\&) | Устанавливает безопасность файла [Pdf](../../aspose.pdf/) с оригинальным паролем. Не генерирует исключение, если процесс завершился неудачей. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
