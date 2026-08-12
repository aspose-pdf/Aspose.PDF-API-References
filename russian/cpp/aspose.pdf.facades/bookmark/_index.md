---
title: "Aspose::Pdf::Facades::Bookmark class"
linktitle: "Bookmark"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::Bookmark class. Представляет закладку в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.facades/bookmark/
---
## Bookmark class


Представляет закладку.

```cpp
class Bookmark : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [Bookmark](./bookmark/)() | Инициализирует новый экземпляр класса [Bookmark](./). |
| [get_Action](./get_action/)() const | Получает действие, связанное с закладкой. Если [PageNumber](../../aspose.pdf/pagenumber/) представлен, действие не может быть указано. Тип действия включает: "GoTo", "GoToR", "Launch", "Named". |
| [get_BoldFlag](./get_boldflag/)() const | Получает флаг полужирного начертания заголовка закладки. |
| [get_ChildItem](./get_childitem/)() | Получает дочерние элементы закладки. |
| [get_ChildItems](./get_childitems/)() const | Получает дочерние элементы закладки. |
| [get_Destination](./get_destination/)() const | Получает страницу назначения закладки. Требуется, если действие установлено как string.Empty. |
| [get_ItalicFlag](./get_italicflag/)() const | Получает флаг курсивного начертания заголовка закладки. |
| [get_Level](./get_level/)() const | Получает уровень иерархии закладки. |
| [get_Open](./get_open/)() const | Получает состояние закладки (открыта, закрыта). |
| [get_PageDisplay](./get_pagedisplay/)() const | Получает тип отображения страницы назначения закладки. |
| [get_PageDisplay_Bottom](./get_pagedisplay_bottom/)() const | Получает нижнюю координату отображения страницы. |
| [get_PageDisplay_Left](./get_pagedisplay_left/)() const | Получает левую координату отображения страницы. |
| [get_PageDisplay_Right](./get_pagedisplay_right/)() const | Получает правую координату отображения страницы. |
| [get_PageDisplay_Top](./get_pagedisplay_top/)() const | Получает верхнюю координату отображения страницы. |
| [get_PageDisplay_Zoom](./get_pagedisplay_zoom/)() const | Получает коэффициент масштабирования отображения страницы. |
| [get_PageNumber](./get_pagenumber/)() const | Получает номер целевой страницы закладки. |
| [get_RemoteFile](./get_remotefile/)() const | Получает файл (путь), необходимый для действия "GoToR" закладки. |
| [get_Title](./get_title/)() const | Получает заголовок закладки. |
| [get_TitleColor](./get_titlecolor/)() const | Получает цвет заголовка закладки. |
| [set_Action](./set_action/)(const System::String\&) | Устанавливает действие, связанное с закладкой. Если [PageNumber](../../aspose.pdf/pagenumber/) представлен, действие не может быть указано. Тип действия включает: "GoTo", "GoToR", "Launch", "Named". |
| [set_BoldFlag](./set_boldflag/)(bool) | Устанавливает флаг полужирного начертания заголовка закладки. |
| [set_ChildItem](./set_childitem/)(const System::SharedPtr\<Bookmarks\>\&) | Устанавливает дочерние элементы закладки. |
| [set_ChildItems](./set_childitems/)(const System::SharedPtr\<Bookmarks\>\&) | Устанавливает дочерние элементы закладки. |
| [set_Destination](./set_destination/)(const System::String\&) | Устанавливает целевую страницу закладки. Требуется, если действие установлено как string.Empty. |
| [set_ItalicFlag](./set_italicflag/)(bool) | Устанавливает флаг курсивного начертания заголовка закладки. |
| [set_Level](./set_level/)(int32_t) | Устанавливает уровень иерархии закладки. |
| [set_Open](./set_open/)(bool) | Устанавливает состояние закладки (открыта, закрыта). |
| [set_PageDisplay](./set_pagedisplay/)(const System::String\&) | Устанавливает тип отображения целевой страницы закладки. |
| [set_PageDisplay_Bottom](./set_pagedisplay_bottom/)(int32_t) | Устанавливает нижнюю координату отображения страницы. |
| [set_PageDisplay_Left](./set_pagedisplay_left/)(int32_t) | Устанавливает левую координату отображения страницы. |
| [set_PageDisplay_Right](./set_pagedisplay_right/)(int32_t) | Устанавливает правую координату отображения страницы. |
| [set_PageDisplay_Top](./set_pagedisplay_top/)(int32_t) | Устанавливает верхнюю координату отображения страницы. |
| [set_PageDisplay_Zoom](./set_pagedisplay_zoom/)(int32_t) | Устанавливает коэффициент масштабирования отображения страницы. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Устанавливает номер целевой страницы закладки. |
| [set_RemoteFile](./set_remotefile/)(const System::String\&) | Устанавливает файл (путь), необходимый для действия "GoToR" закладки. |
| [set_Title](./set_title/)(const System::String\&) | Устанавливает заголовок закладки. |
| [set_TitleColor](./set_titlecolor/)(System::Drawing::Color) | Устанавливает цвет заголовка закладки. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
