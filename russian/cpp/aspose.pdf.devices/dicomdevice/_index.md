---
title: "Aspose::Pdf::Devices::DicomDevice класс"
linktitle: "DicomDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::DicomDevice класс. Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в формат Dicom на C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class


Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в формат Dicom.

```cpp
class DicomDevice : public Aspose::Pdf::Devices::ImageDevice
```

## Методы

| Метод | Описание |
| --- | --- |
| [DicomDevice](./dicomdevice/)() | Инициализирует новый экземпляр класса [DicomDevice](./) с разрешением по умолчанию. |
| [DicomDevice](./dicomdevice/)(const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [DicomDevice](./). |
| [DicomDevice](./dicomdevice/)(const System::SharedPtr\<PageSize\>\&) | Инициализирует новый экземпляр класса [DicomDevice](./) с указанным размером страницы, с разрешением по умолчанию (=150). |
| [DicomDevice](./dicomdevice/)(int32_t, int32_t) | Инициализирует новый экземпляр класса [DicomDevice](./) с указанными размерами изображения, с разрешением по умолчанию (=150). |
| [DicomDevice](./dicomdevice/)(const System::SharedPtr\<PageSize\>\&, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [DicomDevice](./) с указанным размером страницы и разрешением. |
| [DicomDevice](./dicomdevice/)(int32_t, int32_t, const System::SharedPtr\<Aspose::Pdf::Devices::Resolution\>\&) | Инициализирует новый экземпляр класса [DicomDevice](./) с указанными размерами изображения и разрешением. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Преобразует страницу в Dicom и сохраняет её в выходном потоке. |
## См. также

* Class [ImageDevice](../imagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
