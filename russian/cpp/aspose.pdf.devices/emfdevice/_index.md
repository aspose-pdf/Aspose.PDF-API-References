---
title: "Aspose::Pdf::Devices::EmfDevice класс"
linktitle: "EmfDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::EmfDevice класс. Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в формат emf в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.devices/emfdevice/
---
## EmfDevice class


Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в формат emf.

```cpp
class EmfDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Методы

| Метод | Описание |
| --- | --- |
| [EmfDevice](./emfdevice/)() | Инициализирует новый экземпляр класса [EmfDevice](./) с разрешением растрового изображения по умолчанию, записываемого в emf. |
| [EmfDevice](./emfdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [EmfDevice](./). |
| [EmfDevice](./emfdevice/)(int32_t, int32_t) | Инициализирует новый экземпляр класса [EmfDevice](./) с указанными размерами изображения и разрешением растрового изображения по умолчанию, записываемого в emf (=150). |
| [EmfDevice](./emfdevice/)(const System::SharedPtr\<PageSize\>\&) | Инициализирует новый экземпляр класса [EmfDevice](./) с указанным размером страницы и разрешением растрового изображения по умолчанию, записываемого в emf (=150). |
| [EmfDevice](./emfdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [JpegDevice](../jpegdevice/) с указанными размерами изображения и разрешением растрового изображения, записываемого в emf. |
| [EmfDevice](./emfdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [JpegDevice](../jpegdevice/) с указанным размером страницы и разрешением растрового изображения, записываемого в emf. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Преобразует страницу в emf и сохраняет её в выходном потоке. |
## См. также

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
