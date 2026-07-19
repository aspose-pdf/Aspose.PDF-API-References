---
title: "Aspose::Pdf::Document::SendTo метод"
linktitle: "SendTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Document::SendTo метод. Отправляет весь документ на устройство документа для обработки в C++."
type: docs
weight: 8500
url: /ru/cpp/aspose.pdf/document/sendto/
---
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Отправляет весь документ на устройство документа для обработки.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, const System::SharedPtr<System::IO::Stream> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) устройство, которое используется для обработки документа. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Поток вывода содержит результаты обработки документа с заданным устройством. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::String\&) method


Отправляет весь документ на устройство документа для обработки.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, const System::String &outputFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) устройство, которое используется для обработки документа. |
| outputFileName | const System::String\& | Имя выходного файла с результатами обработки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Отправляет определённые страницы документа на устройство документа для обработки.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, int32_t fromPage, int32_t toPage, const System::SharedPtr<System::IO::Stream> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) устройство, которое используется для обработки документа. |
| fromPage | int32_t | Первая страница для обработки. |
| toPage | int32_t | Последняя страница для обработки. |
| output | const System::SharedPtr\<System::IO::Stream\>\& | Поток вывода содержит результаты обработки страниц документа с заданным устройством. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [Stream](../../../system.io/stream/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Document::SendTo(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::String\&) method


Отправляет весь документ на устройство документа для обработки.

```cpp
void Aspose::Pdf::Document::SendTo(const System::SharedPtr<Devices::DocumentDevice> &device, int32_t fromPage, int32_t toPage, const System::String &outputFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| device | const System::SharedPtr\<Devices::DocumentDevice\>\& | [Document](../) устройство, которое используется для обработки документа. |
| fromPage | int32_t | Первая страница для обработки. |
| toPage | int32_t | Последняя страница для обработки. |
| outputFileName | const System::String\& | Имя выходного файла с результатами обработки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DocumentDevice](../../../aspose.pdf.devices/documentdevice/)
* Class [String](../../../system/string/)
* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
