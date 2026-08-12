---
title: "Aspose::Pdf::Facades::PdfProducer class"
linktitle: "PdfProducer"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfProducer class. Представляет класс для создания PDF из других форматов на C++."
type: docs
weight: 3000
url: /ru/cpp/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class


Представляет класс для создания PDF из других форматов.

```cpp
class PdfProducer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [Produce](./produce/)(const System::SharedPtr\<System::IO::Stream\>\&, ImportFormat, const System::SharedPtr\<System::IO::Stream\>\&) | Создаёт поток PDF, используя указанный формат импорта. |
| static [Produce](./produce/)(System::String, ImportFormat, const System::SharedPtr\<System::IO::Stream\>\&) | Создаёт поток PDF, используя указанный формат импорта. |
| static [Produce](./produce/)(const System::SharedPtr\<System::IO::Stream\>\&, ImportFormat, System::String) | Создаёт файл PDF, используя указанный формат импорта. |
| static [Produce](./produce/)(System::String, ImportFormat, System::String) | Создаёт файл PDF, используя указанный формат импорта. |
| static [Produce](./produce/)(const System::String\&, const System::SharedPtr\<ImportOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Создаёт поток PDF, используя указанную опцию импорта. |
| static [Produce](./produce/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<ImportOptions\>\&, const System::String\&) | Создаёт файл PDF, используя указанную опцию импорта. |
| static [Produce](./produce/)(const System::String\&, const System::SharedPtr\<ImportOptions\>\&, const System::String\&) | Создаёт файл PDF, используя указанную опцию импорта. |
| static [Produce](./produce/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<ImportOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Создаёт файл PDF, используя указанную опцию импорта. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
