---
title: "Aspose::Pdf::Devices::TiffDevice::Process method"
linktitle: "Process"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::TiffDevice::Process method. Преобразует определённые страницы документа в TIFF и сохраняет их в выходном потоке в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.devices/tiffdevice/process/
---
## TiffDevice::Process(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) method


Преобразует определённые страницы документа в TIFF и сохраняет их в выходном потоке.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(System::SharedPtr<Aspose::Pdf::Document> document, int32_t fromPage, int32_t toPage, System::SharedPtr<System::IO::Stream> output) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | System::SharedPtr\<Aspose::Pdf::Document\> | Документ для конвертации. |
| fromPage | int32_t | Определяет номер страницы, с которой начнётся конвертация. |
| toPage | int32_t | Определяет номер страницы, на которой завершится конвертация. |
| output | System::SharedPtr\<System::IO::Stream\> | Выходной поток с изображением TIFF. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## TiffDevice::Process(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) method


Выполняет некоторую операцию над заданной страницей, например, преобразует страницу в графическое изображение.

```cpp
void Aspose::Pdf::Devices::TiffDevice::Process(System::SharedPtr<Page> page, System::SharedPtr<System::IO::Stream> output) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | System::SharedPtr\<Page\> | Страница для обработки. |
| output | System::SharedPtr\<System::IO::Stream\> | Этот поток содержит результаты обработки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [TiffDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
