---
title: "Конструктор Aspose::Pdf::Document::Document"
linktitle: "Document"
second_title: "Справочник API Aspose.PDF для C++"
description: "Конструктор Aspose::Pdf::Document::Document. Инициализирует пустой документ в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/document/document/
---
## Document::Document() constructor


Инициализирует пустой документ.

```cpp
Aspose::Pdf::Document::Document()
```

## См. также

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&) constructor


Инициализировать новый экземпляр [Document](../) из *входного* потока.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Поток с PDF‑документом. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, bool) constructor


Инициализировать новый экземпляр [Document](../) из *входного* потока.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, bool isManagedStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Поток с PDF‑документом. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; иначе — нет. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) constructor


Открывает существующий документ из потока, предоставляя необходимые параметры конвертации для получения PDF‑документа.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток для преобразования в PDF‑документ. |
| опции | const System::SharedPtr\<LoadOptions\>\& | Представляет свойства для преобразования *input* в PDF‑документ. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) constructor


Инициализировать новый экземпляр [Document](../) из *входного* потока.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Объект входного потока, соответствующий PDF защищён паролем. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Параметры шифрования сертификата. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) constructor


Инициализировать новый экземпляр [Document](../) из *входного* потока.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions, bool isManagedStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Поток с PDF‑документом. |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Параметры шифрования сертификата. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; в противном случае — нет. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) constructor


Инициализировать новый экземпляр [Document](../) из *входного* потока.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Объект входного потока, соответствующий PDF защищён паролем. |
| password | const System::String\& | Пароль пользователя или владельца. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) constructor


Инициализировать новый экземпляр [Document](../) из *входного* потока.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Поток с PDF‑документом. |
| password | const System::String\& | Пароль пользователя или владельца. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; в противном случае — нет. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Инициализировать новый экземпляр [Document](../) из *входного* потока.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Поток с PDF‑документом. |
| password | const System::String\& | Пароль пользователя или владельца. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; в противном случае — нет. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Пользовательский обработчик безопасности. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Инициализировать новый экземпляр [Document](../) из *входного* потока.

```cpp
Aspose::Pdf::Document::Document(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Объект входного потока, соответствующий PDF защищён паролем. |
| password | const System::String\& | Пароль пользователя или владельца. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Пользовательский обработчик безопасности. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&) constructor


Просто инициализировать [Document](../) с помощью *filename*. То же самое, что и [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(const System::String &filename)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла pdf‑документа. |

## См. также

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, bool) constructor


Просто инициализировать [Document](../) с помощью *filename*. То же самое, что и [Document(Stream)](../).

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, bool isManagedStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла pdf‑документа. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; в противном случае — нет. |

## См. также

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) constructor


Открывает существующий документ из файла, предоставляя необходимые параметры конвертации для получения PDF‑документа.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<LoadOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Входной файл для преобразования в pdf‑документ. |
| опции | const System::SharedPtr\<LoadOptions\>\& | Представляет свойства для преобразования *filename* в pdf‑документ. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LoadOptions](../../loadoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) constructor


Инициализирует новый экземпляр класса [Document](../) для работы с зашифрованным документом.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла [Document](../). |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Параметры шифрования сертификата. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) constructor


Инициализирует новый экземпляр класса [Document](../) для работы с зашифрованным документом.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::SharedPtr<Security::CertificateEncryptionOptions> &certOptions, bool isManagedStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла [Document](../). |
| certOptions | const System::SharedPtr\<Security::CertificateEncryptionOptions\>\& | Параметры шифрования сертификата. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; иначе — нет. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&) constructor


Инициализирует новый экземпляр класса [Document](../) для работы с зашифрованным документом.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла [Document](../). |
| password | const System::String\& | Пароль пользователя или владельца. |

## См. также

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, bool) constructor


Инициализирует новый экземпляр класса [Document](../) для работы с зашифрованным документом.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, bool isManagedStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла [Document](../). |
| password | const System::String\& | Пароль пользователя или владельца. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; иначе — нет. |

## См. также

* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Инициализирует новый экземпляр класса [Document](../) для работы с зашифрованным документом.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, bool isManagedStream, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла [Document](../). |
| password | const System::String\& | Пароль пользователя или владельца. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; иначе — нет. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Пользовательский обработчик безопасности. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) constructor


Инициализирует новый экземпляр класса [Document](../) для работы с зашифрованным документом.

```cpp
Aspose::Pdf::Document::Document(const System::String &filename, const System::String &password, const System::SharedPtr<Security::ICustomSecurityHandler> &customSecurityHandler)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла [Document](../). |
| password | const System::String\& | Пароль пользователя или владельца. |
| customSecurityHandler | const System::SharedPtr\<Security::ICustomSecurityHandler\>\& | Пользовательский обработчик безопасности. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::Document(PdfVersion) constructor


Инициализирует пустой документ по версии.

```cpp
Aspose::Pdf::Document::Document(PdfVersion version)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| версия | PdfVersion | Версия PDF. |

## См. также

* Enum [PdfVersion](../../pdfversion/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
