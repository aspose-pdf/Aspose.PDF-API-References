---
title: "класс Aspose::Pdf::Security::UnsignedContentAbsorber::UnsignedContent"
linktitle: "UnsignedContent"
second_title: "Справочник API Aspose.PDF для C++"
description: "класс Aspose::Pdf::Security::UnsignedContentAbsorber::UnsignedContent. Инкапсулирует элементы неподписанного содержимого, извлечённые из PDF‑документа. Этот класс предоставляет доступ к страницам, полям форм, XForms и аннотациям, которые являются частью неподписанного содержимого в документе в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.security/unsignedcontentabsorber/unsignedcontent/
---
## UnsignedContent class


Инкапсулирует элементы неподписанного содержимого, извлечённые из PDF‑документа. Этот класс предоставляет доступ к страницам, полям форм, XForms и аннотациям, которые являются частью неподписанного содержимого в документе.

```cpp
class UnsignedContent : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Annotations](./get_annotations/)() const | Получает словарь изменённых аннотаций, которые могли быть изменены или добавлены. |
| [get_Forms](./get_forms/)() const | Получает поля форм, которые были инкрементно изменены или добавлены. |
| [get_Pages](./get_pages/)() const | Получает список страниц, содержимое которых неподписано или было инкрементно изменено. |
| [get_XForms](./get_xforms/)() const | Получает словарь изменённых объектов [XForm](../../../aspose.pdf/xform/), которые могли измениться, хотя сама страница не изменилась (не входит в список Pages). |
## См. также

* Class [Object](../../../system/object/)
* Class [UnsignedContentAbsorber](../)
* Namespace [Aspose::Pdf::Security](../../)
* Library [Aspose.PDF for C++](../../../)
