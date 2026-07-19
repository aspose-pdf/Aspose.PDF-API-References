---
title: "Метод Aspose::Pdf::Devices::DocumentDevice::Process"
linktitle: "Process"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Devices::DocumentDevice::Process. Обрабатывает весь документ и сохраняет результаты в поток в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.devices/documentdevice/process/
---
## DocumentDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Обрабатывает весь документ и сохраняет результаты в поток.

```cpp
void Aspose::Pdf::Devices::DocumentDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::SharedPtr<System::IO::Stream> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | const System::SharedPtr\<Aspose::Pdf::Document\>\& | Документ для обработки. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Определяет поток, в котором хранятся результаты обработки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) method


Обрабатывает весь документ и сохраняет результаты в файл.

```cpp
void Aspose::Pdf::Devices::DocumentDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, const System::String &outputFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | const System::SharedPtr\<Aspose::Pdf::Document\>\& | Документ для обработки. |
| outputFileName | const System::String\& | Определяет файл, в котором хранятся результаты обработки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(const System::SharedPtr\<Aspose::Pdf::Document\>\&, int32_t, int32_t, const System::String\&) method


Обрабатывает определённые страницы документа и сохраняет результаты в файл.

```cpp
void Aspose::Pdf::Devices::DocumentDevice::Process(const System::SharedPtr<Aspose::Pdf::Document> &document, int32_t fromPage, int32_t toPage, const System::String &outputFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | const System::SharedPtr\<Aspose::Pdf::Document\>\& | Документ для обработки. |
| fromPage | int32_t | Первая страница, с которой начинается обработка. |
| toPage | int32_t | Последняя страница обработки. |
| outputFileName | const System::String\& | Определяет файл, в котором хранятся результаты обработки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## DocumentDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Каждое устройство представляет собой некоторую операцию над документом, например, мы можем преобразовать PDF‑документ в другой формат.

```cpp
virtual void Aspose::Pdf::Devices::DocumentDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, int32_t fromPage, int32_t toPage, System::SharedPtr<System::IO::Stream> output)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | System::SharedPtr\<Aspose::Pdf::Document\> | Документ для обработки. |
| fromPage | int32_t | Определяет страницу, с которой начинается обработка. |
| toPage | int32_t | Определяет последнюю страницу для обработки. |
| output | System::SharedPtr\<System::IO::Stream\> | Определяет поток, в котором хранятся результаты обработки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [DocumentDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
