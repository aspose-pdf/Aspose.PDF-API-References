---
title: PdfPageEditor
second_title: Aspose.PDF для справочника API .NET
description: Представляет класс для редактирования страницы файла PDF включая поворот страницы масштабирование страницы перемещение позиции и изменение размера страницы.
type: docs
weight: 2600
url: /ru/net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Представляет класс для редактирования страницы файла PDF, включая поворот страницы, масштабирование страницы, перемещение позиции и изменение размера страницы.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfPageEditor](pdfpageeditor#constructor)() | Конструктор класса PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor#constructor_1)(Document) | Конструктор класса PdfPageEditor. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration) { get; set; } | Получает или задает продолжительность отображения страниц. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Получает фасад документа, над которым работает. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание исходного содержимого PDF на странице результатов, по умолчанию — AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations) { get; set; } | Хеш-таблица содержит номер страницы и степень поворота, ключ представляет номер страницы, значение ключа представляет поворот в градусах. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize) { get; set; } | Получает или задает размер страницы выходного файла. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages) { get; set; } | Получает или задает номера редактируемых страниц. По умолчанию каждая страница будет редактироваться. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation) { get; set; } | Получает или задает поворот страниц, поворот должен быть 0, 90, 180 или 270. Значение по умолчанию:0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration) { get; set; } | Получает или задает продолжительность эффекта перехода. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype) { get; set; } | Получает или задает стиль перехода, используемый при переходе на эту страницу с другой во время презентации. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype) { get; set; } | Получает или задает вертикальное выравнивание исходного содержимого PDF на странице результатов, по умолчанию — VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom) { get; set; } | Получить или установить коэффициент масштабирования. Значение 1,0 соответствует 100%. Значение по умолчанию — 1,0.  В следующем примере показано, как изменить масштаб страниц документа. &lt;code&gt; Редактор PdfPageEditor = new PdfPageEditor(); editor.BindPdf("sample.pdf"); editor.Zoom = 0.5f; &lt;/code&gt; |

## Методы

| Имя | Описание |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges)() | Применить изменения, сделанные на страницах документа. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Инициализирует фасад. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Инициализирует фасад. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Удаляет Aspose.Pdf.Document, связанный с фасадом. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Удаляет фасад. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize)(int, string) | Возвращает размер указанного блока в документе. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation)(int) | Возвращает поворот указанной страницы. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages)() | Возвращает общее количество страниц. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize)(int) | Возвращает размер указанной страницы. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition)(float, float) | Перемещает начало координат из (0, 0) в назначенную точку. Исходная точка слева внизу, единица измерения - точка (1 дюйм = 72 точки). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save)(Stream) | Сохраняет измененный документ в поток. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save#save_1)(string) | Сохраняет измененный документ в файл. |

## Поля

| Имя | Описание |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh) | Вертикальные жалюзи |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv) | Вертикальные жалюзи |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe) | Стирание снизу-вверх |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter) | Диагональный блеск |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve) | Старая страница растворяется |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox) | Внутренний ящик |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter) | Лево-правый блеск |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe) | Стирание влево-вправо |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox) | Внешний ящик |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe) | Вытеснение вправо-влево |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin) | IN Горизонтальное разделение |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout) | Из горизонтального разделения |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin) | В вертикальном разделении |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout) | Выход из вертикального разделения |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter) | Блеск сверху и снизу |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe) | Стирание сверху вниз |

### Смотрите также

* class [SaveableFacade](../saveablefacade)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
