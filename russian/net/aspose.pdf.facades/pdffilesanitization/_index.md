---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfFileSanitization. Представляет API для санитарной обработки и восстановления. Используйте его, если вы не можете создать/открыть документы другим способом
type: docs
weight: 4540
url: /ru/net/aspose.pdf.facades/pdffilesanitization/
---
## Класс PdfFileSanitization

Представляет API для санитарной обработки и восстановления. Используйте его, если вы не можете создать/открыть документы другим способом.

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | После сохранения файла вы можете проверить, что было сделано с файлом. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Позволяет генерировать новый xref и трейлер для документа. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Позволяет удалить данные после данных pdf |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Позволяет удалить данные перед данными pdf. |

## Методы

| Имя | Описание |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Инициализирует фасад. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Привязывает поток Pdf для санитарной обработки. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Привязывает файл Pdf для санитарной обработки. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Закрывает фасад. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Уничтожает фасад. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Удаляет старый xref с трейлером и создает новый xref с трейлером. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Восстанавливает документ. Используйте свойства для настройки. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Сохраняет результат PDF в поток. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Сохраняет результат PDF в файл. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Удаляет данные после последнего %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Удаляет данные перед %PDF. |

### См. также

* класс [SaveableFacade](../saveablefacade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)