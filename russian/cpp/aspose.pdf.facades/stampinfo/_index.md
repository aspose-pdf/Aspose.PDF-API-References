---
title: "Aspose::Pdf::Facades::StampInfo класс"
linktitle: "StampInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::StampInfo класс. Класс, представляющий информацию о штампе в C++."
type: docs
weight: 3600
url: /ru/cpp/aspose.pdf.facades/stampinfo/
---
## StampInfo class


Класс, представляющий информацию о штампе.

```cpp
class StampInfo : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Form](./get_form/)() const | Получает [XForm](../../aspose.pdf/xform/) штампа. |
| [get_Image](./get_image/)() const | Получает изображение штампа. Может быть null, если штамп не содержит изображений (например, для текстового штампа). |
| [get_IndexOnPage](./get_indexonpage/)() const | Получает индекс штампа на странице. |
| [get_Rectangle](./get_rectangle/)() const | Получает прямоугольник, в котором размещён штамп. |
| [get_StampId](./get_stampid/)() const | Получает идентификатор штампа. |
| [get_StampType](./get_stamptype/)() const | Получает тип штампа (изображение / форма). |
| [get_Text](./get_text/)() | Получает текст в штампе. |
| [get_Visible](./get_visible/)() const | Получает видимость штампа. Если false, то штамп скрыт (с помощью HideStampById). Скрытый штамп может быть восстановлен с помощью ShowStampById. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
