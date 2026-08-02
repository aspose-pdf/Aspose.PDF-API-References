---
title: "Класс PdfPageEditor"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.PdfPageEditor. Представляет класс для редактирования страниц PDF‑файлов, включая вращение страниц, масштабирование, перемещение позиции и изменение размера страницы."
type: docs
weight: 4710
url: /ru/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Представляет класс для редактирования Page PDF‑файла, включая вращение Page, масштабирование Page, перемещение и изменение размера Page.

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
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Получает или задаёт длительность отображения страниц. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Получает document, с которым работает фасад. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Получает или задаёт горизонтальное выравнивание оригинального содержимого PDF на результирующей странице, по умолчанию AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Хеш-таблица содержит номер страницы и степень вращения; ключ представляет номер страницы, значение ключа — угол вращения в градусах. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Получает или задаёт размер страницы выходного файла. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Получает или задаёт номера страниц для редактирования. По умолчанию редактируются все страницы. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Получает или задает поворот страниц, поворот должен быть 0, 90, 180 или 270. Значение по умолчанию — 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Получает или задает длительность эффекта перехода. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Получает или задает стиль перехода, используемый при переходе к этой странице с другой во время презентации. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Получает или задает вертикальное выравнивание оригинального PDF‑контента на результирующей странице, значение по умолчанию — VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Получает или задает коэффициент масштабирования. Значение 1.0 соответствует 100 %. Значение по умолчанию — 1.0. Ниже приведён пример, демонстрирующий, как изменить масштаб страниц Document. |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Применить изменения, внесённые в страницы Document. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Инициализирует фасад. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Освобождает Aspose.Pdf.Document, связанный с фасадом. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Освобождает фасад. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Возвращает размер указанного блока в Document. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Возвращает поворот указанной страницы. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Возвращает общее количество страниц. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Возвращает размер указанной страницы. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Перемещает начало координат из (0, 0) в указанную точку. Начало координат находится в левом нижнем углу, единица измерения — пункт (1 дюйм = 72 пункта). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Сохраняет изменённый Document в поток. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Сохраняет изменённый Document в файл. |

## Поля

| Имя | Описание |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Вертикальные жалюзи |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Вертикальные жалюзи |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Стирание снизу вверх |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Диагональный блеск |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | Старая страница растворяется |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Внутренний квадрат |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Блеск слева направо |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Стирание слева направо |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Внешний квадрат |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Стирание справа налево |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | Внутреннее горизонтальное разделение |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Внешнее горизонтальное разделение |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | В вертикальном разрезе |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Внешний вертикальный разрез |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Сверху‑вниз блестки |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Сверху‑вниз стирание |

### См. также

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


