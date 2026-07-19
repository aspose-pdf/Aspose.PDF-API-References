---
title: "Класс Aspose::Pdf::Devices::PageDevice"
linktitle: "PageDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Devices::PageDevice. Абстрактный класс для всех устройств, используемых для обработки определённой страницы PDF‑документа в C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.pdf.devices/pagedevice/
---
## PageDevice class


Абстрактный класс для всех устройств, который используется для обработки определённой страницы PDF‑документа.

```cpp
class PageDevice : public Aspose::Pdf::Devices::Device
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) | Выполняет некоторую операцию над заданной страницей, например, преобразует страницу в графическое изображение. |
| [Process](./process/)(const System::SharedPtr\<Page\>\&, const System::String\&) | Выполняет некоторую операцию над заданной страницей и сохраняет результаты в файл. |
## См. также

* Class [Device](../device/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
