---
title: "Aspose::Pdf::ImagePlacementAbsorber class"
linktitle: "ImagePlacementAbsorber"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::ImagePlacementAbsorber class. Представляет объект‑поглотитель объектов размещения изображений. Выполняет поиск использований изображений и предоставляет доступ к результатам поиска через коллекцию ImagePlacementAbsorber::ImagePlacements в C++."
type: docs
weight: 8100
url: /ru/cpp/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class


Представляет объект‑поглотитель объектов размещения изображений. Выполняет поиск использований изображений и предоставляет доступ к результатам поиска через коллекцию [ImagePlacementAbsorber::ImagePlacements](../).

```cpp
class ImagePlacementAbsorber : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_ImagePlacements](./get_imageplacements/)() const | Получает коллекцию вхождений размещения изображений, представленных объектами [ImagePlacement](../imageplacement/). |
| [get_IsReadOnlyMode](./get_isreadonlymode/)() const | Получает/устанавливает режим только для чтения коллекции операций разбора. Это может помочь избежать исключений нехватки памяти. |
| [ImagePlacementAbsorber](./imageplacementabsorber/)() | Инициализирует новый экземпляр объекта [ImagePlacementAbsorber](./). |
| [set_IsReadOnlyMode](./set_isreadonlymode/)(bool) | Получает/устанавливает режим только для чтения коллекции операций разбора. Это может помочь избежать исключений нехватки памяти. |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Выполняет поиск на указанной странице. |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Выполняет поиск в указанном документе. |
## Примечания


Объект [ImagePlacementAbsorber](./) в основном используется в сценарии поиска изображений. После завершения поиска вхождения представлены объектами [ImagePlacement](../imageplacement/), которые содержатся в коллекции [ImagePlacementAbsorber::ImagePlacements](../). Объект [ImagePlacement](../imageplacement/) предоставляет доступ к свойствам размещения изображения: размеры, разрешение и т.д. Положительное вращение [Image](../image/) происходит против часовой стрелки, для страницы — по часовой стрелке. Здесь нам нужно представить угол вращения изображения, поэтому мы вычитаем угол страницы из угла изображения.
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
