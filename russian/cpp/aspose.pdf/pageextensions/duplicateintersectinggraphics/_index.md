---
title: "Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics метод"
linktitle: "DuplicateIntersectingGraphics"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics метод. Находит все векторные графические элементы, которые пересекаются с указанным регионом, и создает их копии со смещением от оригинальных позиций в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf/pageextensions/duplicateintersectinggraphics/
---
## PageExtensions::DuplicateIntersectingGraphics method


Находит все векторные графические элементы, пересекающие указанную область, и создаёт их копии со смещением от оригинальных позиций.

```cpp
static void Aspose::Pdf::PageExtensions::DuplicateIntersectingGraphics(const System::SharedPtr<Page> &page, const System::SharedPtr<Rectangle> &region, double deltaX, double deltaY)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | const System::SharedPtr\<Page\>\& | Страница, на которой ищутся графические элементы и в которую они копируются. |
| регион | const System::SharedPtr\<Rectangle\>\& | Прямоугольная область для поиска пересекающихся элементов. |
| deltaX | double | Смещение вдоль оси X для скопированных элементов. |
| deltaY | double | Смещение вдоль оси Y для скопированных элементов. |
## Примечания



Этот метод работает только с векторной графикой (линии, фигуры, кривые Безье и т.д.). Растровые изображения и другие типы элементов не обрабатываются. Каждый скопированный элемент будет смещён на указанные значения dx и dy относительно его исходного положения. Исходные элементы остаются без изменений.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../page/)
* Class [Rectangle](../../rectangle/)
* Class [PageExtensions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
