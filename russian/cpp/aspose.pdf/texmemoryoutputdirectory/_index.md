---
title: "Aspose::Pdf::TeXMemoryOutputDirectory class"
linktitle: "TeXMemoryOutputDirectory"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::TeXMemoryOutputDirectory class. Реализует получение выходного потока из памяти. Вы можете использовать его, например, когда вы don''t хотите, чтобы сопутствующий вывод (например, файл журнала) записывался на диск, но you''d like to read it afterwards from memory in C++."
type: docs
weight: 18200
url: /ru/cpp/aspose.pdf/texmemoryoutputdirectory/
---
## TeXMemoryOutputDirectory class


Реализует получение выходного потока из памяти. Вы можете использовать его, например, когда не хотите, чтобы сопутствующий вывод (например, файл журнала) записывался на диск, но хотите прочитать его позже из памяти.

```cpp
class TeXMemoryOutputDirectory : public Aspose::Pdf::ITeXOutputDirectory
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Освобождает экземпляр. |
| [GetFile](./getfile/)(System::String, System::String\&, bool) override | Возвращает поток для чтения. |
| [GetOutputFile](./getoutputfile/)(System::String, System::String\&) override | Возвращает поток для записи. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/)() | Создаёт новый экземпляр. |
## См. также

* Class [ITeXOutputDirectory](../itexoutputdirectory/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
