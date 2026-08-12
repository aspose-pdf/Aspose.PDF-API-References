---
title: "Aspose::Pdf::XImage::TrySetAlternativeText метод"
linktitle: "TrySetAlternativeText"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::XImage::TrySetAlternativeText метод. Устанавливает альтернативный текст для XImage на странице в C++."
type: docs
weight: 1900
url: /ru/cpp/aspose.pdf/ximage/trysetalternativetext/
---
## XImage::TrySetAlternativeText method


Устанавливает альтернативный текст для [XImage](../) на странице.

```cpp
bool Aspose::Pdf::XImage::TrySetAlternativeText(const System::String &alternativeText, const System::SharedPtr<Aspose::Pdf::Page> &page)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| alternativeText | const System::String\& | Альтернативный текст, который необходимо указать. |
| page | const System::SharedPtr\<Aspose::Pdf::Page\>\& | [Page](../../page/) где расположен [XImage](../). |

### ReturnValue

True если alternativeText для [XImage](../) установлен. False если alternativeText для [XImage](../) не установлен.
## Примечания



Метод возвращает false в следующих случаях:* [XImage](../) не найден на указанной странице.
* The [XImage](../) appears multiple times on the page with different structural elements, making it ambiguous which instance should receive the alternative text.


## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [XImage](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
