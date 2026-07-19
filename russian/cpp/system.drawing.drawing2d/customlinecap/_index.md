---
title: "System::Drawing::Drawing2D::CustomLineCap класс"
linktitle: "CustomLineCap"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Drawing::Drawing2D::CustomLineCap класс. Представляет пользовательский line cap. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.drawing.drawing2d/customlinecap/
---
## CustomLineCap class


Представляет пользовательский line cap. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CustomLineCap : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Clone](./clone/)() | Возвращает копию текущего объекта. |
| [CustomLineCap](./customlinecap/)(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) | Создаёт новый экземпляр класса [CustomLineCap](./), представляющего пользовательский line cap с указанными свойствами. |
| [Dispose](./dispose/)() | Освобождает все ресурсы операционной системы, полученные текущим объектом. |
| [get_BaseCap](./get_basecap/)() const | Возвращает базовый line cap, из которого создан этот пользовательский cap. |
| [get_BaseInset](./get_baseinset/)() const | Возвращает расстояние между линией и cap. |
| [get_StrokeJoin](./get_strokejoin/)() const | Возвращает значение [LineJoin](../linejoin/), определяющее, как соединяются линии этого пользовательского cap. |
| [get_WidthScale](./get_widthscale/)() const | Возвращает масштаб этого пользовательского cap. |
| [GetStrokeCaps](./getstrokecaps/)(LineCap\&, LineCap\&) | Получает начальные и конечные line caps пользовательского cap, представленного текущим объектом. |
| [set_BaseCap](./set_basecap/)(LineCap) | Устанавливает значение базового line cap для этого пользовательского cap. |
| [set_BaseInset](./set_baseinset/)(float) | Устанавливает расстояние между линией и cap. |
| [set_StrokeJoin](./set_strokejoin/)(LineJoin) | Устанавливает значение [LineJoin](../linejoin/), определяющее, как соединяются линии этого пользовательского cap. |
| [set_WidthScale](./set_widthscale/)(float) | Устанавливает значение масштаба этого пользовательского cap. |
| [SetStrokeCaps](./setstrokecaps/)(LineCap, LineCap) | Устанавливает начальные и конечные line caps пользовательского cap, представленного текущим объектом. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
