---
title: "Aspose::Pdf::Facades::PdfFileSanitization класс"
linktitle: "PdfFileSanitization"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileSanitization класс. Представляет API очистки и восстановления. Используйте его, если вы не можете создать/открыть документы иным способом в C++."
type: docs
weight: 2300
url: /ru/cpp/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class


Представляет API очистки и восстановления. Используйте его, если вы не можете создать/открыть документы иным способом.

```cpp
class PdfFileSanitization : public Aspose::Pdf::Facades::SaveableFacade,
                            public Aspose::Pdf::Sanitization::IRecovery
```

## Методы

| Метод | Описание |
| --- | --- |
| [BindPdf](./bindpdf/)(System::String) override | Привязывает файл [Pdf](../../aspose.pdf/) для очистки. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Привязывает поток [Pdf](../../aspose.pdf/) для очистки. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Инициализирует фасад. |
| [Close](./close/)() override | Закрывает фасад. |
| [get_Log](./get_log/)() override | После сохранения файла вы можете проверить, что было сделано с файлом. |
| [get_UseRebuildXrefAndTrailer](./get_userebuildxrefandtrailer/)() const | Позволяет сгенерировать новый xref и трейлер для документа. |
| [get_UseTrimBottom](./get_usetrimbottom/)() const | Позволяет удалить данные после данных PDF. |
| [get_UseTrimTop](./get_usetrimtop/)() const | Позволяет удалить данные перед данными PDF. |
| [PdfFileSanitization](./pdffilesanitization/)() | Инициализирует новый экземпляр. |
| [RebuildXrefAndTrailer](./rebuildxrefandtrailer/)() | Удаляет старый xref с трейлером и создает новый xref с трейлером. |
| [Recover](./recover/)() override | Восстанавливает документ. Используйте свойства для настройки. |
| [Save](./save/)(System::String) override | Сохраняет полученный PDF в файл. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Сохраняет полученный PDF в поток. |
| [set_UseRebuildXrefAndTrailer](./set_userebuildxrefandtrailer/)(bool) | Позволяет сгенерировать новый xref и трейлер для документа. |
| [set_UseTrimBottom](./set_usetrimbottom/)(bool) | Позволяет удалить данные после данных PDF. |
| [set_UseTrimTop](./set_usetrimtop/)(bool) | Позволяет удалить данные перед данными PDF. |
| [TrimBottom](./trimbottom/)() override | Удаляет данные после последнего %EOF. |
| [TrimTop](./trimtop/)() override | Удаляет данные перед PDF. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Class [IRecovery](../../aspose.pdf.sanitization/irecovery/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
