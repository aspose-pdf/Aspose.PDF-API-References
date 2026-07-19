---
title: "System::Drawing::Drawing2D::AdjustableArrowCap class"
linktitle: "AdjustableArrowCap"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Drawing2D::AdjustableArrowCap class. Представляет регулируемую стрелку в виде заглавия линии. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 100
url: /ru/cpp/system.drawing.drawing2d/adjustablearrowcap/
---
## AdjustableArrowCap class


Представляет регулируемую стрелку в виде заглавия линии. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class AdjustableArrowCap : public System::Drawing::Drawing2D::CustomLineCap
```

## Методы

| Метод | Описание |
| --- | --- |
| [AdjustableArrowCap](./adjustablearrowcap/)(float, float, bool) | Создаёт новый экземпляр [AdjustableArrowCap](./) с указанными шириной и высотой. |
| [get_Filled](./get_filled/)() const | Возвращает значение, указывающее, заполнена ли стрелка, представляемая текущим объектом. |
| [get_Height](./get_height/)() const | Возвращает высоту стрелки, представляемой текущим объектом. |
| [get_MiddleInset](./get_middleinset/)() const | Устанавливает расстояние между линией и заголовком, представляемыми текущим объектом. |
| [get_Width](./get_width/)() const | Возвращает ширину стрелки, представляемой текущим объектом. |
| [set_Filled](./set_filled/)(bool) | Устанавливает значение, определяющее, заполнена ли стрелка, представляемая текущим объектом. |
| [set_Height](./set_height/)(float) | Устанавливает высоту стрелки, представляемой текущим объектом. |
| [set_MiddleInset](./set_middleinset/)(float) | Устанавливает расстояние между линией и заголовком, представляемыми текущим объектом. |
| [set_Width](./set_width/)(float) | Устанавливает ширину стрелки, представляемой текущим объектом. |
## См. также

* Class [CustomLineCap](../customlinecap/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
