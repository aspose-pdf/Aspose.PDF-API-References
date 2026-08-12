---
title: "Aspose::Pdf::Operators::SetColorStroke класс"
linktitle: "SetColorStroke"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Operators::SetColorStroke класс. Класс, представляющий оператор SC, устанавливающий цвет для обводки в C++."
type: docs
weight: 5700
url: /ru/cpp/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class


Класс, представляющий оператор SC (устанавливает цвет для операторов обводки).

```cpp
class SetColorStroke : public Aspose::Pdf::Operators::BasicSetColorOperator
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(const System::SharedPtr\<IOperatorSelector\>\&) override | Принимает объект посетителя для обработки оператора. |
| [get_B](./get_b/)() | Получает синий компонент. |
| [get_C](./get_c/)() | Получает циановый компонент. |
| [get_G](./get_g/)() | Получает зеленый компонент. |
| [get_K](./get_k/)() | Получает черный компонент. |
| [get_M](./get_m/)() | Получает пурпурный компонент. |
| [get_R](./get_r/)() | Получает красный компонент. |
| [get_Y](./get_y/)() | Получает желтый компонент. |
| [getColor](./getcolor/)() override | Возвращает цвет, указанный оператором. |
| [set_B](./set_b/)(double) | Устанавливает синий компонент. |
| [set_C](./set_c/)(double) | Устанавливает циановый компонент. |
| [set_G](./set_g/)(double) | Устанавливает зеленый компонент. |
| [set_K](./set_k/)(double) | Устанавливает черный компонент. |
| [set_M](./set_m/)(double) | Устанавливает пурпурный компонент. |
| [set_R](./set_r/)(double) | Устанавливает красный компонент. |
| [set_Y](./set_y/)(double) | Устанавливает желтый компонент. |
| [SetColorStroke](./setcolorstroke/)() | Инициализирует оператор. |
| [SetColorStroke](./setcolorstroke/)(double) | Установить цвет для операторов обводки для пространств цветов DeviceGray, CalGray и Indexed. |
| [SetColorStroke](./setcolorstroke/)(double, double, double) | Установить цвет для оператора обводки для пространств цветов DeviceRGB, CalRGB и Lab. |
| [SetColorStroke](./setcolorstroke/)(const System::ArrayPtr\<double\>\&) | Конструктор, позволяющий установить компоненты цвета. |
| [SetColorStroke](./setcolorstroke/)(double, double, double, double) | Установить цвет для оператора обводки для цветового пространства CMYK. |
## См. также

* Class [BasicSetColorOperator](../basicsetcoloroperator/)
* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
