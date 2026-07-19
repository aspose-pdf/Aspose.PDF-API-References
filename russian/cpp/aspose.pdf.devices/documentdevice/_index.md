---
title: "Класс Aspose::Pdf::Devices::DocumentDevice"
linktitle: "DocumentDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Devices::DocumentDevice. Абстрактный класс для всех устройств, используемых для обработки всего PDF‑документа в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.devices/documentdevice/
---
## DocumentDevice class


Абстрактный класс для всех устройств, который используется для обработки всего PDF‑документа.

```cpp
class DocumentDevice : public Aspose::Pdf::Devices::PageDevice
```

## Методы

| Метод | Описание |
| --- | --- |
| [DocumentDevice](./documentdevice/)() |  |
| virtual [Process](./process/)(System::SharedPtr\<Aspose::Pdf::Document\>, int32_t, int32_t, System::SharedPtr\<System::IO::Stream\>) | Каждое устройство представляет собой некоторую операцию над документом, например, мы можем преобразовать PDF‑документ в другой формат. |
| [Process](./process/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Обрабатывает весь документ и сохраняет результаты в поток. |
| [Process](./process/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Обрабатывает весь документ и сохраняет результаты в файл. |
| [Process](./process/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, int32_t, int32_t, const System::String\&) | Обрабатывает определённые страницы документа и сохраняет результаты в файл. |
## См. также

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
