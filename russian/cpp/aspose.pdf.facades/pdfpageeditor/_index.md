---
title: "Класс Aspose::Pdf::Facades::PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Facades::PdfPageEditor. Представляет класс для редактирования страниц PDF‑файла, включая вращение страницы, масштабирование страницы, перемещение позиции и изменение размера страницы в C++."
type: docs
weight: 2800
url: /ru/cpp/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class


Представляет класс для редактирования страниц PDF‑файла, включая вращение, масштабирование, перемещение и изменение размера страницы.

```cpp
class PdfPageEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Методы

| Метод | Описание |
| --- | --- |
| [ApplyChanges](./applychanges/)() | Применить изменения, внесённые в страницы документа. |
| [get_DisplayDuration](./get_displayduration/)() | Получает длительность отображения страниц. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() | Получает горизонтальное выравнивание оригинального PDF‑контента на результирующей странице, по умолчанию AlignmentType.Left. |
| [get_PageRotations](./get_pagerotations/)() | Хеш‑таблица содержит номер страницы и степень вращения, ключ представляет номер страницы, значение ключа представляет вращение в градусах. |
| [get_PageSize](./get_pagesize/)() | Получает размер страницы выходного файла. |
| [get_ProcessPages](./get_processpages/)() | Получает номера страниц, подлежащих редактированию. По умолчанию будет редактироваться каждая страница. |
| [get_Rotation](./get_rotation/)() | Получает вращение страниц, вращение должно быть 0, 90, 180 или 270. Значение по умолчанию — 0. |
| [get_TransitionDuration](./get_transitionduration/)() | Получает длительность эффекта перехода. |
| [get_TransitionType](./get_transitiontype/)() | Получает стиль перехода, используемый при переходе к этой странице из другой во время презентации. |
| [get_VerticalAlignmentType](./get_verticalalignmenttype/)() | Получает или задаёт вертикальное выравнивание оригинального PDF‑контента на результирующей странице, по умолчанию VerticalAlignmentType.Bottom. |
| [get_Zoom](./get_zoom/)() | Получает или задаёт коэффициент масштабирования. Значение 1.0 соответствует 100 %. Значение по умолчанию — 1.0. |
| [GetPageBoxSize](./getpageboxsize/)(int32_t, const System::String\&) | Возвращает размер указанного блока в документе. |
| [GetPageRotation](./getpagerotation/)(int32_t) | Возвращает вращение указанной страницы. |
| [GetPages](./getpages/)() | Возвращает общее количество страниц. |
| [GetPageSize](./getpagesize/)(int32_t) | Возвращает размер страницы указанной страницы. |
| [MovePosition](./moveposition/)(float, float) | Перемещает начало координат из (0, 0) в указанную точку. Начало координат находится в левом нижнем углу, единица измерения — пункт (1 дюйм = 72 пункта). |
| [PdfPageEditor](./pdfpageeditor/)() | Конструктор класса [PdfPageEditor](./). |
| [PdfPageEditor](./pdfpageeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Конструктор класса [PdfPageEditor](./). |
| [Save](./save/)(System::String) override | Сохраняет изменённый документ в файл. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Сохраняет изменённый документ в поток. |
| [set_DisplayDuration](./set_displayduration/)(int32_t) | Устанавливает длительность отображения страниц. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Устанавливает горизонтальное выравнивание оригинального PDF‑контента на результирующей странице, по умолчанию AlignmentType.Left. |
| [set_PageRotations](./set_pagerotations/)(const System::SharedPtr\<System::Collections::Generic::Dictionary\<int32_t, int32_t\>\>\&) | Хеш‑таблица содержит номер страницы и степень вращения, ключ представляет номер страницы, значение ключа представляет вращение в градусах. |
| [set_PageSize](./set_pagesize/)(const System::SharedPtr\<Aspose::Pdf::PageSize\>\&) | Устанавливает размер страницы выходного файла. |
| [set_ProcessPages](./set_processpages/)(const System::ArrayPtr\<int32_t\>\&) | Устанавливает номера страниц для редактирования. По умолчанию каждая страница будет редактироваться. |
| [set_Rotation](./set_rotation/)(int32_t) | Устанавливает вращение страниц, вращение должно быть 0, 90, 180 или 270. Значение по умолчанию — 0. |
| [set_TransitionDuration](./set_transitionduration/)(int32_t) | Устанавливает длительность эффекта перехода. |
| [set_TransitionType](./set_transitiontype/)(int32_t) | Устанавливает стиль перехода, используемый при переходе к этой странице с другой во время презентации. |
| [set_VerticalAlignmentType](./set_verticalalignmenttype/)(Aspose::Pdf::VerticalAlignment) | Получает или задаёт вертикальное выравнивание оригинального PDF‑контента на результирующей странице, по умолчанию VerticalAlignmentType.Bottom. |
| [set_Zoom](./set_zoom/)(float) | Получает или задаёт коэффициент масштабирования. Значение 1.0 соответствует 100 %. Значение по умолчанию — 1.0. |
## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [BLINDH](./blindh/) | Вертикальные жалюзи. |
| static constexpr [BLINDV](./blindv/) | Вертикальные жалюзи. |
| static constexpr [BTWIPE](./btwipe/) | Стирание снизу вверх. |
| static constexpr [DGLITTER](./dglitter/) | Диагональная блестка. |
| static constexpr [DISSOLVE](./dissolve/) | Старая страница растворяется. |
| static constexpr [INBOX](./inbox/) | Внутренний квадрат. |
| static constexpr [LRGLITTER](./lrglitter/) | Блестка слева‑направо. |
| static constexpr [LRWIPE](./lrwipe/) | Стирание слева направо. |
| static constexpr [OUTBOX](./outbox/) | Исходящий квадрат. |
| static constexpr [RLWIPE](./rlwipe/) | Стирание справа налево. |
| static constexpr [SPLITHIN](./splithin/) | Внутреннее горизонтальное разделение. |
| static constexpr [SPLITHOUT](./splithout/) | Исходящее горизонтальное разделение. |
| static constexpr [SPLITVIN](./splitvin/) | Внутреннее вертикальное разделение. |
| static constexpr [SPLITVOUT](./splitvout/) | Исходящее вертикальное разделение. |
| static constexpr [TBGLITTER](./tbglitter/) | Блестка сверху вниз. |
| static constexpr [TBWIPE](./tbwipe/) | Стирание сверху вниз. |
## См. также

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
