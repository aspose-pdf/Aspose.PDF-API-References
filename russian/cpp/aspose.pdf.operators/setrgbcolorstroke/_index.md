---
title: "Aspose::Pdf::Operators::SetRGBColorStroke класс"
linktitle: "SetRGBColorStroke"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Operators::SetRGBColorStroke класс. Класс, представляющий оператор RG (устанавливает RGB‑цвет для операторов обводки) в C++."
type: docs
weight: 6900
url: /ru/cpp/aspose.pdf.operators/setrgbcolorstroke/
---
## SetRGBColorStroke class


Класс, представляющий оператор RG (устанавливает цвет RGB для операторов с обводкой).

```cpp
class SetRGBColorStroke : public Aspose::Pdf::Operators::SetColorOperator
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
| [SetRGBColorStroke](./setrgbcolorstroke/)(double, double, double) | Инициализирует оператор. |
| [SetRGBColorStroke](./setrgbcolorstroke/)(System::Drawing::Color) | Инициализирует оператор с цветом. |
| [ToString](./tostring/)() const override | Возвращает текстовое представление оператора. |
## См. также

* Class [SetColorOperator](../setcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
