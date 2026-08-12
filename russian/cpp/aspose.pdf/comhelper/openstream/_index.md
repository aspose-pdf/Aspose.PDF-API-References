---
title: "Метод Aspose::Pdf::ComHelper::OpenStream"
linktitle: "OpenStream"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::ComHelper::OpenStream. Инициализирует и возвращает новый экземпляр Document из входного потока в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf/comhelper/openstream/
---
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&) method


Инициализирует и возвращает новый экземпляр [Document](../../document/) из *input* потока.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Поток с PDF‑документом. |

### ReturnValue

[Document](../../document/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, bool) method


Инициализирует и возвращает новый экземпляр [Document](../../document/) из *input* потока.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, bool isManagedStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Поток с PDF‑документом. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; иначе — нет. |

### ReturnValue

[Document](../../document/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) method


Откройте и верните существующий документ из потока, предоставив необходимые преобразования для получения PDF‑документа.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток для преобразования в PDF‑документ. |
| опции | const System::SharedPtr\<LoadOptions\>\& | Представляет свойства для преобразования *input* в PDF‑документ. |

### ReturnValue

[Document](../../document/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Инициализирует и возвращает новый экземпляр [Document](../../document/) из *input* потока.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Объект входного потока, соответствующий PDF защищён паролем. |
| password | const System::String\& | Пароль пользователя или владельца. |

### ReturnValue

[Document](../../document/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## ComHelper::OpenStream(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) method


Инициализирует и возвращает новый экземпляр [Document](../../document/) из *input* потока.

```cpp
System::SharedPtr<Document> Aspose::Pdf::ComHelper::OpenStream(const System::SharedPtr<System::IO::Stream> &input, const System::String &password, bool isManagedStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Поток с PDF‑документом. |
| password | const System::String\& | Пароль пользователя или владельца. |
| isManagedStream | bool | Если установлено в **true**, внутренний поток закрывается перед выходом; иначе — нет. |

### ReturnValue

[Document](../../document/) object

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [ComHelper](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
