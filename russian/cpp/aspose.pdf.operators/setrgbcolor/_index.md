---
title: "Класс Aspose::Pdf::Operators::SetRGBColor"
linktitle: "SetRGBColor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Operators::SetRGBColor. Класс, представляющий оператор rg (устанавливает RGB‑цвет для не‑обводящих операторов) в C++."
type: docs
weight: 6800
url: /ru/cpp/aspose.pdf.operators/setrgbcolor/
---
## SetRGBColor class


Класс, представляющий оператор rg (устанавливает цвет RGB для операторов без обводки).

```cpp
class SetRGBColor : public Aspose::Pdf::Operators::SetColorOperator
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Принимает объект посетителя для обработки оператора. |
| [get_B](./get_b/)() const | Получает синий компонент. |
| [get_G](./get_g/)() const | Получает зеленый компонент. |
| [get_R](./get_r/)() const | Получает красный компонент. |
| [getColor](./getcolor/)() override | Возвращает цвет, указанный оператором. |
| [set_B](./set_b/)(double) | Устанавливает синий компонент. |
| [set_G](./set_g/)(double) | Устанавливает зеленый компонент. |
| [set_R](./set_r/)(double) | Устанавливает красный компонент. |
| [SetRGBColor](./setrgbcolor/)(double, double, double) | Инициализирует оператор. |
| [SetRGBColor](./setrgbcolor/)(System::Drawing::Color) | Инициализирует оператор с цветом. |
| [ToString](./tostring/)() const override | Возвращает текстовое представление оператора. |
## См. также

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
