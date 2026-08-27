---
title: "Класс PdfFileSanitization"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Facades.PdfFileSanitization класс. Представляет API очистки и восстановления. Используйте его, если вы не можете создавать/открывать документы иным способом"
type: docs
weight: 4660
url: /ru/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

Представляет API очистки и восстановления. Используйте его, если вы не можете создать/открыть документы иным способом.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | После сохранения файла вы можете проверить, что было сделано с файлом. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Позволяет сгенерировать новый xref и трейлер для документа. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Позволяет удалить данные после pdf-данных |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Позволяет удалить данные перед pdf-данными. |

## Методы

| Имя | Описание |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Привязывает поток Pdf для очистки. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Привязывает файл Pdf для очистки. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Закрывает фасад. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Удаляет старый xref с трейлером и создает новый xref с трейлером. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Восстанавливает документ. Используйте свойства для настройки. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Сохраняет полученный PDF в поток. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Сохраняет полученный PDF в файл. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Удаляет данные после последнего %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Удаляет данные перед %PDF. |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


