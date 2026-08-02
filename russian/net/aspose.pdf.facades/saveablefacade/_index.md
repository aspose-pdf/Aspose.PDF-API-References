---
title: "Класс SaveableFacade"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.SaveableFacade. Базовый класс для всех сохраняемых фасадов"
type: docs
weight: 4820
url: /ru/net/aspose.pdf.facades/saveablefacade/
---
## SaveableFacade class

Базовый класс для всех сохраняемых фасадов.

```csharp
public abstract class SaveableFacade : Facade, ISaveableFacade
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Освобождает Aspose.Pdf.Document, связанный с фасадом. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save)(Stream) | Сохраняет PDF‑документ в указанный поток. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/#save_1)(string) | Сохраняет PDF‑документ в указанный файл. |

### См. также

* class [Facade](../facade/)
* interface [ISaveableFacade](../isaveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


