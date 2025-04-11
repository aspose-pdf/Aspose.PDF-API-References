---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfPageEditor. Представляет класс для редактирования страниц PDF файлов, включая поворот страниц, изменение масштаба, перемещение позиции и изменение размера страниц.
type: docs
weight: 4590
url: /ru/net/aspose.pdf.facades/pdfpageeditor/
---
## Класс PdfPageEditor

Представляет класс для редактирования страниц PDF файла, включая поворот страниц, изменение масштаба, перемещение позиции и изменение размера страниц.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Конструктор класса PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Конструктор класса PdfPageEditor. |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Получает или задает длительность отображения страниц. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает фасад документа, с которым работает. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание оригинального содержимого PDF на результирующей странице, по умолчанию AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Хеш-таблица, содержащая номер страницы и угол поворота, ключ представляет номер страницы, значение ключа представляет угол поворота в градусах. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Получает или задает размер страницы выходного файла. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Получает или задает номера страниц для редактирования. По умолчанию редактируется каждая страница. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Получает или задает угол поворота страниц, угол поворота должен быть 0, 90, 180 или 270. Значение по умолчанию 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Получает или задает длительность эффекта перехода. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Получает или задает стиль перехода, который будет использоваться при переходе на эту страницу из другой во время презентации. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Получает или задает вертикальное выравнивание оригинального содержимого PDF на результирующей странице, по умолчанию VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Получает или задает коэффициент масштабирования. Значение 1.0 соответствует 100%. Значение по умолчанию 1.0. Следующий пример демонстрирует, как изменить масштаб страниц документа. |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Применяет изменения, внесенные в страницы документа. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Освобождает Aspose.Pdf.Document, связанный с фасадом. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Возвращает размер указанного бокса в документе. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Возвращает угол поворота указанной страницы. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Возвращает общее количество страниц. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Возвращает размер страницы указанной страницы. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Перемещает начало координат из (0, 0) в указанную точку. Начало координат находится в левом нижнем углу, единица измерения - пункт (1 дюйм = 72 пункта). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Сохраняет измененный документ в поток. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Сохраняет измененный документ в файл. |

## Поля

| Имя | Описание |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Вертикальные жалюзи |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Вертикальные жалюзи |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Стирание снизу вверх |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Диагональное мерцание |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | Старая страница растворяется |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Внутренний бокс |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Мерцание слева направо |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Стирание слева направо |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Внешний бокс |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Стирание справа налево |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | Внутреннее горизонтальное деление |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Внешнее горизонтальное деление |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | Внутреннее вертикальное деление |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Внешнее вертикальное деление |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Мерцание сверху вниз |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Стирание сверху вниз |

### См. также

* класс [SaveableFacade](../saveablefacade/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)