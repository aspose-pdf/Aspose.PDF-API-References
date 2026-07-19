---
title: "System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2 конструктор"
linktitle: "X509Certificate2"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2 конструктор. Создаёт пустой X509Certificate2 в C++."
type: docs
weight: 100
url: /ru/cpp/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() constructor


Создаёт пустой [X509Certificate2](../).

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## См. также

* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const ByteArrayPtr\& | Последовательность байтов, представляющая закодированный сертификат. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const ByteArrayPtr\& | Последовательность байтов, представляющая закодированный сертификат (публичная часть). |
| private_key | const ByteArrayPtr\& | Последовательность байтов, представляющая закрытый ключ. |
| key_storage_flags | X509KeyStorageFlags | Флаги, указывающие, как хранить ключ. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const ByteArrayPtr\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const SecureStringPtr\& | Пароль сертификата. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const ByteArrayPtr\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const SecureStringPtr\& | Пароль сертификата. |
| key_storage_flags | X509KeyStorageFlags | Флаги, указывающие, как хранить ключ. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const ByteArrayPtr\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const String\& | Пароль сертификата. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| raw_data | const ByteArrayPtr\& | Последовательность байтов, представляющая закодированный сертификат. |
| password | const String\& | Пароль сертификата. |
| key_storage_flags | X509KeyStorageFlags | Флаги, указывающие, как хранить ключ. |

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| cert | const SharedPtr\<X509Certificate\>\& | Объект [X509Certificate](../../x509certificate/). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate](../../x509certificate/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const String\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const String\& | Файл, из которого загружается сертификат. |

## См. также

* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const String\& | Файл, из которого загружается сертификат. |
| password | const SecureStringPtr\& | Пароль сертификата. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const String\& | Файл, из которого загружается сертификат. |
| password | const SecureStringPtr\& | Пароль сертификата. |
| key_storage_flags | X509KeyStorageFlags | Флаги, указывающие, как хранить ключ. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const String\&, const String\&) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const String\& | Файл, из которого загружается сертификат. |
| password | const String\& | Пароль сертификата. |

## См. также

* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) constructor


Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const String\& | Файл, из которого загружается сертификат. |
| password | const String\& | Пароль сертификата. |
| key_storage_flags | X509KeyStorageFlags | Флаги, указывающие, как хранить ключ. |

## См. также

* Class [String](../../../system/string/)
* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.PDF for C++](../../../)
