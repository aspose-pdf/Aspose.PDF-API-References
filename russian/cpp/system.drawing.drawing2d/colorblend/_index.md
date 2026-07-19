---
title: "System::Drawing::Drawing2D::ColorBlend class"
linktitle: "ColorBlend"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Drawing2D::ColorBlend class. Содержит массивы цветов и позиций, используемые для интерполяции смешивания цветов в многокрасном градиенте. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.drawing.drawing2d/colorblend/
---
## ColorBlend class


Содержит массивы цветов и позиций, используемых для интерполяции смешивания цветов в многокрасочном градиенте. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ColorBlend : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [ColorBlend](./colorblend/)() | Создаёт новый экземпляр класса [ColorBlend](./). |
| [ColorBlend](./colorblend/)(int) | Создаёт новый экземпляр класса [Blend](../blend/). |
| [get_Colors](./get_colors/)() | Возвращает массив цветов, используемых в соответствующих позициях вдоль градиента. |
| [get_Positions](./get_positions/)() | Возвращает массив позиций смешения вдоль градиента. |
| [set_Colors](./set_colors/)(const ArrayPtr\<Color\>\&) | Устанавливает массив цветов, используемых в соответствующих позициях вдоль градиента. |
| [set_Positions](./set_positions/)(const ArrayPtr\<float\>\&) | Устанавливает массив позиций смешения вдоль градиента. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
