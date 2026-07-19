---
title: "Класс Aspose::Pdf::Vector::GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Vector::GraphicsAbsorber. Представляет объект‑поглотитель графических элементов. Выполняет поиск графики и предоставляет доступ к результатам поиска через коллекцию GraphicsAbsorber::Elements в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf.vector/graphicsabsorber/
---
## GraphicsAbsorber class


Представляет объект‑поглотитель графических элементов. Выполняет поиск графики и предоставляет доступ к результатам поиска через коллекцию [GraphicsAbsorber::Elements](../).

```cpp
class GraphicsAbsorber : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые классом [GraphicsAbsorber](./). |
| [get_Elements](./get_elements/)() const | Получает коллекцию найденных вхождений, представленных объектами [GraphicElement](../graphicelement/). |
| [GraphicsAbsorber](./graphicsabsorber/)() |  |
|  | [ResumeUpdate](./resumeupdate/)() | Возобновить обновление для [Page::Contents](../) и всех [XForm::Contents](../). Было сделано для повышения производительности, см. также |
[OperatorCollection::ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/)


. |
|  | [SuppressUpdate](./suppressupdate/)() | Подавить обновление для [Page::Contents](../) и всех [XForm::Contents](../). Было сделано для повышения производительности, см. также |
[OperatorCollection::SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)


. |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Выполняет поиск на указанной странице. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
