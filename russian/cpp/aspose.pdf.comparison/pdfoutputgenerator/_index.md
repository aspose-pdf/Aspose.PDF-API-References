---
title: "Aspose::Pdf::Comparison::PdfOutputGenerator класс"
linktitle: "PdfOutputGenerator"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::PdfOutputGenerator class. Представляет класс для создания PDF‑представления различий текстов в C++."
type: docs
weight: 1300
url: /ru/cpp/aspose.pdf.comparison/pdfoutputgenerator/
---
## PdfOutputGenerator class


Представляет класс для генерации PDF‑представления различий текстов.

```cpp
class PdfOutputGenerator : public Aspose::Pdf::Comparison::IFileOutputGenerator,
                           public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Методы

| Метод | Описание |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [PdfOutputGenerator](./pdfoutputgenerator/)() | Создаёт экземпляр класса [PdfOutputGenerator](./). |
| [PdfOutputGenerator](./pdfoutputgenerator/)(const System::SharedPtr\<PageInfo\>\&) | Создаёт экземпляр класса [PdfOutputGenerator](./). |
| [PdfOutputGenerator](./pdfoutputgenerator/)(const System::SharedPtr\<OutputTextStyle\>\&) | Создаёт экземпляр класса [PdfOutputGenerator](./). |
| [PdfOutputGenerator](./pdfoutputgenerator/)(const System::SharedPtr\<OutputTextStyle\>\&, const System::SharedPtr\<PageInfo\>\&) | Создаёт экземпляр класса [PdfOutputGenerator](./). |
## См. также

* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
