---
title: "Aspose::Pdf::DocumentFactory::CreateDocument метод"
linktitle: "CreateDocument"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::DocumentFactory::CreateDocument метод. Создать пустой документ в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf/documentfactory/createdocument/
---
## DocumentFactory::CreateDocument() method


Создать пустой документ.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument()
```


### ReturnValue

Документ создан.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&) method


Загрузить документ из потока.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток. |

### ReturnValue

Документ создан.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) method


Создать документ.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input, const System::SharedPtr<LoadOptions> &options)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Входной поток. |
| options | const System::SharedPtr\<LoadOptions\>\& | [Document](../../document/) параметры загрузки. |

### ReturnValue

Документ создан.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [LoadOptions](../../loadoptions/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Загрузить защищённый паролем документ из потока.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::SharedPtr<System::IO::Stream> &input, const System::String &password)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const System::SharedPtr\<System::IO::Stream\>\& | Поток источника. |
| password | const System::String\& | Пароль для доступа к документу. |

### ReturnValue

Документ создан.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentFactory::CreateDocument(const System::String\&) method


Загрузить документ из файла.

```cpp
System::SharedPtr<Document> Aspose::Pdf::DocumentFactory::CreateDocument(const System::String &fileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | const System::String\& | Имя PDF‑файла. |

### ReturnValue

Документ создан.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../document/)
* Class [String](../../../system/string/)
* Class [DocumentFactory](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
