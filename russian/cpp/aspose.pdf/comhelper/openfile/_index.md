---
title: "Метод Aspose::Pdf::ComHelper::OpenFile"
linktitle: "OpenFile"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::ComHelper::OpenFile метод. Просто создайте и верните Document, используя имя файла. То же, что и Document(Stream) в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/comhelper/openfile/
---
## ComHelper::OpenFile(const System::String\&) method


Просто создайте и верните [Document](../../document/) используя *filename*. То же, что и [Document(Stream)](../).

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла pdf‑документа. |

### ReturnValue

[Document](../../document/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) method


Откройте существующий документ из файла, предоставив необходимые параметры преобразования для получения PDF‑документа.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::SharedPtr<LoadOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Входной файл для преобразования в pdf‑документ. |
| опции | const System::SharedPtr\<LoadOptions\>\& | Представляет свойства для преобразования *filename* в pdf‑документ. |

### ReturnValue

[Document](../../document/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::String\&) method


Инициализируйте и верните новый экземпляр класса [Document](../../document/) для работы с зашифрованным документом.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла [Document](../../document/). |
| password | const System::String\& | Пароль пользователя или владельца. |

### ReturnValue

[Document](../../document/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenFile(const System::String\&, const System::String\&, bool) method


Инициализируйте новый экземпляр класса [Document](../../document/) для работы с зашифрованным документом.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenFile(const System::String &filename, const System::String &password, bool isManagedStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const System::String\& | Имя файла [Document](../../document/). |
| password | const System::String\& | Пароль пользователя или владельца. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; иначе — нет. |

### ReturnValue

[Document](../../document/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
