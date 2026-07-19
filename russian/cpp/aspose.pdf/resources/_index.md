---
title: "Aspose::Pdf::Resources class"
linktitle: "Resources"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Resources class. Класс, представляющий ресурсы страницы в C++."
type: docs
weight: 16500
url: /ru/cpp/aspose.pdf/resources/
---
## Resources class


Класс, представляющий ресурсы страницы.

```cpp
class Resources : public Aspose::Pdf::ISupportsMemoryCleanup
```

## Nested classes

* Class [ExtGStateValue](./extgstatevalue/)
## Методы

| Метод | Описание |
| --- | --- |
| [cpp_set_xfrom_weak](./cpp_set_xfrom_weak/)(const System::SharedPtr\<XForm\>\&) |  |
| [FreeMemory](./freememory/)() override | Очищает кэшированные данные, освобождает память и т.д. |
| [get_Fonts](./get_fonts/)() | Получает коллекцию ресурсов [Fonts](../). |
| [get_Forms](./get_forms/)() | Получает коллекцию форм [Forms](../../aspose.pdf.forms/). |
| [get_Images](./get_images/)() | Получает коллекцию изображений [Images](../). |
| [GetExtGStates](./getextgstates/)() | Получает все ExGStates из ресурсов. |
| [GetFonts](./getfonts/)(bool) | Возвращает коллекцию шрифтов. Если ресурсы не содержат запись шрифтов, она будет создана в зависимости от флага CreateIfAbsent. |
## См. также

* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
