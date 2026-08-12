---
title: "Класс Aspose::Pdf::PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::PdfSaveOptions. Параметры сохранения для экспорта в формат Pdf в C++."
type: docs
weight: 15200
url: /ru/cpp/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class


Параметры сохранения для экспорта в формат [Pdf](../).

```cpp
class PdfSaveOptions : public Aspose::Pdf::SaveOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_DefaultFontName](./get_defaultfontname/)() const | Имя шрифта, используемое по умолчанию для шрифтов, отсутствующих на компьютере. Когда PDF‑документ, сохраняемый в PDF, содержит шрифты, которые недоступны в самом документе и на устройстве, API заменяет эти шрифты шрифтом по умолчанию (если шрифт с [DefaultFontName](../) найден на устройстве). |
| [get_TempPath](./get_temppath/)() const | Путь к временным файлам. |
| [PdfSaveOptions](./pdfsaveoptions/)() | Конструктор. |
| [set_DefaultFontName](./set_defaultfontname/)(const System::String\&) | Имя шрифта, используемое по умолчанию для шрифтов, отсутствующих на компьютере. Когда PDF‑документ, сохраняемый в PDF, содержит шрифты, которые недоступны в самом документе и на устройстве, API заменяет эти шрифты шрифтом по умолчанию (если шрифт с [DefaultFontName](../) найден на устройстве). |
| [set_TempPath](./set_temppath/)(const System::String\&) | Путь к временным файлам. |
## См. также

* Class [SaveOptions](../saveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
