---
title: "Aspose::Pdf::Comparison::IFileOutputGenerator class"
linktitle: "IFileOutputGenerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::IFileOutputGenerator class. Представляет интерфейс для создания вывода в файл различий между текстами в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf.comparison/ifileoutputgenerator/
---
## IFileOutputGenerator class


Представляет интерфейс для генерации вывода в файл различий между текстами.

```cpp
class IFileOutputGenerator : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| virtual [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
