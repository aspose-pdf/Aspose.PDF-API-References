---
title: "Метод Aspose::Pdf::Devices::PageDevice::Process"
linktitle: "Process"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::PageDevice::Process method. Выполняет некоторую операцию над заданной страницей и сохраняет результаты в файл в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.devices/pagedevice/process/
---
## PageDevice::Process(const System::SharedPtr\<Page\>\&, const System::String\&) method


Выполняет некоторую операцию над заданной страницей и сохраняет результаты в файл.

```cpp
void Aspose::Pdf::Devices::PageDevice::Process(const System::SharedPtr<Page> &page, const System::String &outputFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Page\>\& | Страница для обработки. |
| outputFileName | const System::String\& | Этот файл содержит результаты обработки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
## PageDevice::Process(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) method


Выполняет некоторую операцию над заданной страницей, например, преобразует страницу в графическое изображение.

```cpp
virtual void Aspose::Pdf::Devices::PageDevice::Process(System::SharedPtr<Page> page, System::SharedPtr<System::IO::Stream> output)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | System::SharedPtr\<Page\> | Страница для обработки. |
| output | System::SharedPtr\<System::IO::Stream\> | Этот поток содержит результаты обработки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [PageDevice](../)
* Namespace [Aspose::Pdf::Devices](../../)
* Library [Aspose.PDF for C++](../../../)
